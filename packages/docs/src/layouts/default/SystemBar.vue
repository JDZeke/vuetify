<template>
  <v-system-bar
    v-if="hasPromotion"
    color="#000C19"
    app
    dark
    height="76"
  >
    <a
      class="cm-banner"
      href="https://vueschool.io/sales/blackfriday?friend=vuetify"
      rel="noopener"
      target="_blank"
      @click="onClick"
    />

    <v-btn
      fab
      small
      absolute
      right
      @click="onClose"
    >
      <v-icon class="mr-0">$clear</v-icon>
    </v-btn>
  </v-system-bar>
</template>

<script>
  // Utilities
  import { differenceInHours } from 'date-fns'
  import { get, sync } from 'vuex-pathify'

  export default {
    name: 'DefaultSystemBar',

    computed: {
      last: sync('user/last@promotion'),
      name: get('route/name'),
      hasPromotion () {
        const now = Date.now()

        return (
          differenceInHours(now, Number(this.last)) > 1
        )
      },
    },

    methods: {
      onClick () {
        this.$gtag.event('click', {
          event_category: 'vuetify-banner',
          event_label: 'vue-school-cyber-monday-2021',
          value: this.name.toLowerCase(),
        })
      },
      onClose () {
        this.last = Date.now()
      },
    },
  }
</script>

<style lang="sass">
  .cm-banner
    background-position: center
    background-repeat: no-repeat
    background-size: contain
    bottom: 0
    display: block
    height: inherit
    left: 0
    overflow: hidden
    position: absolute
    right: 0
    text-indent: 100%
    top: 0
    white-space: nowrap

  .cm-banner
    background-image: url(https://cdn.vuetifyjs.com/docs/images/promotions/vs-cyber-monday-2021/vs-cyber-monday-2021-mobile.png)

    @media (min-width: 660px)
      background-image: url(https://cdn.vuetifyjs.com/docs/images/promotions/vs-cyber-monday-2021/vs-cyber-monday-2021-tablet.png)

    @media (min-width: 992px)
      background-image: url(https://cdn.vuetifyjs.com/docs/images/promotions/vs-cyber-monday-2021/vs-cyber-monday-2021-desktop.png)
</style>
