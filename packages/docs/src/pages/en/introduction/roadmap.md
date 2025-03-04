---
meta:
  title: The Vuetify roadmap
  description: The upcoming planned features and new functionality coming to Vuetify. New components, new directives, and much much more!.
  keywords: vuetify roadmap, future plans, new vuetify features
nav: Roadmap
related:
  - /introduction/long-term-support/
  - /introduction/support/
  - /getting-started/frequently-asked-questions/
---

# The Vuetify roadmap

Vuetify is always under development. We are constantly working towards improving the existing codebase, as well as adding new features and functionality that help make building applications even easier. Below is a tentative list of planned features. This is not an exhaustive list and is subject to change at any time without notice.

<promoted-ad slug="vuetify-github-sponsors" />

## In Development

The following releases are currently under development:

### v3.0 (Titan)

- **Target Release:** February 2022
- **Alpha:** [Live](https://next.vuetifyjs.com/)
- **Beta:** December 2021
- **Overview:**
  - Rebuilt for Vue 3 using the new [composition api](https://vue-composition-api-rfc.netlify.com/)
  - Global properties that allow you to make large overarching changes to your app
  - Improved SASS variable customization and extensibility with [Built-In Modules](https://sass-lang.com/documentation/modules)
  - New [Vue CLI presets](https://github.com/vuetifyjs/vue-cli-plugins) for generating pre-built starting projects
  - First party [Vite](https://vitejs.dev/) support for lightning fast development
  - Greatly improved TypeScript support
  - Better framework coverage with E2E testing using Cypress

Track our progress in the [Vuetify GitHub Issues](https://github.com/vuetifyjs/vuetify/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3ATask) or connect with the [Team](/about/meet-the-team/) on [Discord](https://community.vuetifyjs.com/).

## Long-term support (LTS)

<alert type="error">

  v1.5 reached end of life on **July 31st, 2020** and is no longer actively maintained. It is recommended to update to the latest stable version of Vuetify using our [Upgrade guide](/getting-started/upgrade-guide/).

</alert>

The following versions have continued maintenance for backwards compatible fixes, major bugs, and security vulnerabilities. More information is located on the [Long-term support](/introduction/long-term-support/) page.

### v2.7

- **Target Release:** TBD (probably March 2022)
- **Support until:** Approx. September 2023
- **Overview:**
  Backports and deprecations from v3.0.0

### v1.5

- **Released:** February 2019
- **Support until:** August 1st, 2020
- **Notes:** [v1.5 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.5.0)
- **Overview:**
  Added new component, `v-calendar`. Improved functionality of `v-sparkline` with new **bar** and **fill** properties. Improved `v-treeview` and prepared for LTS. Navigate to the [Long-term Support Page](/introduction/long-term-support) for more information on LTS.

---

<promoted-ad slug="vuetify-open-collective" />

## Released

The following are the already released **minor** and **major** version updates. Find more information on the [latest releases](https://github.com/vuetifyjs/vuetify/releases/latest) on GitHub.

### v2.6 (Horizon)

- **Released**: November 2021
- **Notes**: [v2.6 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.6.0)
- **Overview**:
  New [v-otp-input](/components/otp-input/) component, calendar event and scrolling improvements, minor features for other components.

### v2.5 (Avalon)

- **Released:** May 2021
- **Notes:** [v2.5 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.5.0)
- **Overview:**
  The v2.5 release adds a multitude of new functionality to [v-data-table](/components/data-tables/) and [v-text-field](/components/text-fields/), as well as bug fixes for the [click-outside](/directives/click-outside/) directive, [v-carousel](/components/carousels/) component, and more.
- **Objectives:**
  - Expand functionality of `v-data-table`
  - Quality of life improvements
  - General bug fixes

### v2.4 (Endurance)

- **Released:** December 2020
- **Notes:** [v2.4 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.4.0)
- **Overview:**
  The v2.4 release provides bug fixes, features and quality of life changes for Vuetify as we prepare for v3 Alpha. This release contains some new features that we are building into Vuetify 3 right now such as new slots for `v-carousel` and support for globally defined icon components.
- **Objectives:**
  - Add **plain** property for `v-btn`
  - Add new locales
    - Azerbaijani
    - Central Kurdish
  - Add typography css classes `text-pre` and `text-pre-wrap`
  - Add new slots for `v-carousel`
  - Support for a globally defined icon components
  - Improved accessibility in the `v-menu` component

---

### v2.3 (Liberator)

- **Released:** June 2020
- **Notes:** [v2.3 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.3.0)
- **Overview:**
  The v2.3 release was dropped earlier in the year to focus on v3 development but was revived when COVID-19 showed up. This release is packed full of quality of life changes, new features such as the `v-virtual-scroll` component, responsive typography css classes.
- **Objectives:**
  - Add new css helper classes for `text-decoration`, `border-radius`, `typography`, and more.
  - Add new `v-virtual-scroll` component
  - Improve *Date Pickers, Data Tables, and Calendars*
  - Harden framework in preparation for **LTS version**

---

### v2.2 (Tigris)

- **Released:** January 2020
- **Notes:** [v2.2 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.2.0)
- **Overview:**
  The introduction of Vuetify Presets. Will include the entire Material Design Studies collection and be _user customizable_. Will streamline the process for altering the default styles for the framework. Thousands of SASS variables will be added and a lookup tree for finding those variables will put into the documentation. For more information on Google's studies, please [navigate here](https://material.io/design/material-studies/about-our-material-studies.html).
- **Objectives:**
  - Add _thousands_ of new SASS variables
  - Create a new Vuetify Service for bootstrapping pre-configured framework options; **Preset**
  - Create presets for the official [Material Design Studies](https://material.io/design/material-studies/about-our-material-studies.html)
  - Add new features and improve code styling of `v-badge`
  - Add new features and improve code styling of `v-expansion-panels`
  - new `v-theme-provider` component

---

### v2.1 (Vanguard)

- **Released:** October 2019
- **Notes:** [v2.1 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.1.0)
- **Overview:**
  A maintenance cycle to work on bugs from the v2.0 release. This includes performance issues, incorrect or missing a11y, RTL, regressions and general fixes. This will allow the team to catch up on the backlog of tasks that have accumulated over the 8 month development cycle of the previous release.
- **Objectives:**
  - Add new components
    - `v-lazy`
    - `v-skeleton-loader`
  - Add new directives
    - `v-intersect`
    - `v-mutate`
  - Add lazy loading support for `v-img`

---

### v2.0 (Arcadia)

- **Released:** July 2019
- **Notes:** [v2.0 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v2.0.0)
- **Overview:**
  A complete rebuild of the framework core. Improving the layout and theme systems, platform integration, accessibility, RTL and performance. Update all components to the [Material Design 2](https://material.io/design/) specification. Add additional functionality to multiple existing components and setup v1.5 for [Long-term Support](/introduction/long-term-support).
- **Objectives:**
  - Add new components
    - `v-app-bar`
    - `v-banner`
    - `v-chip-group`
    - `v-color-picker`
    - `v-file-input`
    - `v-list-item-group`
    - `v-overlay`
    - `v-simple-table`
    - `v-slide-group`
  - Complete update to Material Design 2
  - Convert from Javascript to Typescript
  - Convert from Stylus to Sass
  - Convert from avoriaz to vue-test-utils

## Archived

The following releases are old and unsupported **minor** and **major** versions:

### v1.4

- **Released:** December 2018
- **Notes:** [v1.4 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.4.0)
- **Overview:**
  Added new components `v-sparkline` and abstracted `v-toolbar`'s functionality into multiple components for easier maintainability and testing. Rebuilt the entire documentation to make it easier for contributors and maintenance from the team.

---

### v1.3

- **Released:** December 2018
- **Notes:** [v1.3 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.3.0)
- **Overview:**
  Added new components, `v-treeview`, `v-timeline` and `v-item-group`. Unified the interfaces used in `v-tabs` and `v-carousel`. Improved the **vuetify-loader** to support effortless application tree-shaking of Vuetify components.

---

### v1.2

- **Released:** October 2018
- **Notes:** [v1.2 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.2.0)
- **Overview:**
  Added new components, `v-img`, `v-rating` and `v-hover`. Improved theme propagation system and expanded the functionality of the colors used with components such as HEX and RGBA. Als added numerous new locales.

---

### v1.1

- **Released:** July 2018
- **Notes:** [v1.1 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.1.0)
- **Overview:**
  A complete rebuild of all form functionality including all inputs and selection controls. Abstracted features from components like `v-select` into new implementations, `v-autocomplete`, `v-combobox` for more scoped functionality and easier testing. This release also marked the first official support of **RTL** languages.

---

### v1.0

- **Released:** February 2018
- **Notes:** [v1.0 Release](https://github.com/vuetifyjs/vuetify/releases/tag/v1.0.0)
- **Overview:**
  The official v1.0 release party. After 18 months and Kael's sanity, we rolled into our first **MAJOR** release. This included a multitude of brand new components, features and functionality.

---

### Alpha release

- **Released:** December 2016
- **Overview:**
  Vuetify is officially announced to the public. The framework initially shipped with 40 components and came in at a whopping 46kb.

<backmatter />
