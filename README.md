# [Vue Material Kit PRO](https://demos.creative-tim.com/vue-material-kit-pro) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Vue%20Material%20Kit%20Pro-%20Premium%20Vue%20Material%20Kit%20for%20Vue.js%20https%3A//www.creative-tim.com/product/vue-material-kit-pro%20%23vuejs%20%23kit%20%23pro%20%23vuejs%20%23vue-material%20%20%40creativetim)

![version](https://img.shields.io/badge/version-1.2.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-vue-material-kit-pro.svg)](https://github.com/creativetimofficial/ct-vue-material-kit-pro/issues?q=is%3Aopen+is%3Aissue) [![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-vue-material-kit-pro.svg?maxAge=259200)](https://github.com/creativetimofficial/ct-vue-material-kit-pro/issues?q=is%3Aissue+is%3Aclosed)

![Product Gif](https://s3.amazonaws.com/creativetim_bucket/products/139/original/opt_mkp_vue_thumbnail.jpg)


Vue Material Kit PRO is a beautiful resource built over [Vue Material](https://vuematerial.io/) and [Vue.js](https://vuejs.org/). It will help you get started developing kits in no time. Vue Material Kit PRO is the official Vuejs version of the Original [Material Kit PRO](https://www.creative-tim.com/product/material-kit-pro). Using the Kit is pretty simple but requires basic knowledge of Javascript, [Vue.js](https://vuejs.org/v2/guide/) and [Vue-Router](https://router.vuejs.org/en/).

## Getting Started
- Install Nodejs from [Nodejs Official Page](https://nodejs.org/en/)
- Open your terminal
- Navigate to the project
- Run `npm install` or `yarn install` if you use [Yarn](https://yarnpkg.com/en/)
- Run `npm run dev` or `yarn serve` to start a local development server
- A new tab will be opened in your browser

You can also run additional npm tasks such as
- `npm run build` to build your app for production
- `npm run lint` to run linting.

## Vue Material
Vue Material is developed exactly according to Material Design spec. Every component is hand crafted to bring you the best possible UI tools to your next great app. The development doesn't stop at the core components outlined in Google's spec. Through the support of community members and sponsors, additional components will be designed and made available for everyone to enjoy.


## Vue-cli

We used the latest 3.x [Vue CLI](https://github.com/vuejs/vue-cli) which aims to reduce project configuration
to as little as possible. Almost everything is inside `package.json` + some other related files such as
`.babel.config.js`, `.eslintrc.js` and `.postcss.config.js`


### Autoprefixer

Vue Material Kit PRO uses Autoprefixer (included in our build process) to automatically add vendor prefixes to some CSS properties at build time. Doing so saves us time and code by allowing us to write key parts of our CSS a single time while eliminating the need for vendor mixins.

### Webpack

Vue CLI 3 is powered by Webpack and it's great ecosystem. Under the hood, Vue CLI compiles .vue files into javascript and transforms them into something that is understood by the browser with the help of webpack. You can customize the webpack config quite easily with Vue CLI. For more info check their docs;

### Babel

Vue CLI uses Babel to convert new Javascript features to features that are understood by the browser. Note that there is `.browserlistrc` file in the project where you can specify what target browser you aim for. This way, babel knows what features to convert and what features to not convert. Having a modern browser support (e.g excluding Internet Explorer) will most likely result in a small javascript bundle.

### Eslint

Vue CLI comes along with eslint. You can configure it in the `.eslintrc.js` file. Eslint will provide warnings and errors and try to enforce best practices for the Javascript code. An important note is that you can fix warnings with `npm run lint --fix` command.

#### Special thanks
During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:
- [Vue Material](https://vuematerial.io/) for the wonderful framework


Let us know your thoughts below. And good luck with development!

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions


[<img src="https://s3.amazonaws.com/creativetim_bucket/github/html.png" width="60" height="60" />](https://www.creative-tim.com/product/material-kit-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/react.svg" width="60" height="60" />](https://www.creative-tim.com/product/material-kit-pro-react)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-kit-pro)


 Vue | React | HTML |
| --- | --- | --- |
| [![Vue Material Kit Pro](https://s3.amazonaws.com/creativetim_bucket/products/139/original/opt_mkp_vue_thumbnail.jpg)](https://www.creative-tim.com/product/vue-material-kit-pro) | [![Material Kit Pro React](https://s3.amazonaws.com/creativetim_bucket/products/89/original/opt_mkp_react_thumbnail.jpg)](https://www.creative-tim.com/product/material-kit-pro-react)  | [![Material Kit Pro HTML](https://s3.amazonaws.com/creativetim_bucket/products/46/original/opt_mkp_thumbnail.jpg)](https://www.creative-tim.com/product/material-kit-pro)

## Demo

- [Presentation page](https://demos.creative-tim.com/vue-material-kit-pro/#/presentation)
- [Sections pages](https://demos.creative-tim.com/vue-material-kit-pro/#/sections#headers)
- [Examples pages](https://demos.creative-tim.com/vue-material-kit-pro/#/about-us)

[View More](https://demos.creative-tim.com/vue-material-kit-pro).


## Quick start

Quick start options:

- Buy from [Creative Tim](https://www.creative-tim.com/product/vue-material-kit-pro)


## Documentation
The documentation for the Vue Material Kit Pro is hosted at our [website](https://demos.creative-tim.com/vue-material-kit-pro/documentation).


## File Structure

Within the download you'll find the following directories and files:

```
vue-material-kit-pro
├── README.md
├── babel.config.js
├── package.json
├── postcss.config.js
├── public
│   └── index.html
└── src
    ├── API_KEY.js
    ├── App.vue
    ├── assets
    │   ├── img
    │   │   ├── example-pages
    │   │   ├── examples
    │   │   ├── faces
    │   │   ├── section-components
    │   │   └── sections
    │   └── scss
    │       ├── material-kit
    │       │   ├── example-pages
    │       │   ├── mixins
    │       │   ├── plugins
    │       │   └── sections
    │       └── material-kit.scss
    ├── components
    │   ├── Badge.vue
    │   ├── Collapse.vue
    │   ├── Dropdown.vue
    │   ├── FileUpload.vue
    │   ├── InfoAreas.vue
    │   ├── Modal.vue
    │   ├── Pagination.vue
    │   ├── Parallax.vue
    │   ├── Slider.vue
    │   ├── Tabs.vue
    │   ├── cards
    │   │   ├── BlogCard.vue
    │   │   ├── FullBgCard.vue
    │   │   ├── LoginCard.vue
    │   │   ├── NavTabsCard.vue
    │   │   ├── PricingCard.vue
    │   │   ├── ProductCard.vue
    │   │   ├── ProfileCard.vue
    │   │   ├── RotatingCard.vue
    │   │   └── TestimonialCard.vue
    │   └── index.js
    ├── layout
    │   ├── MainFooter.vue
    │   ├── MainNavbar.vue
    │   └── MobileMenu.vue
    ├── main.js
    ├── plugins
    │   ├── basicMixins.js
    │   ├── globalComponents.js
    │   ├── globalDirectives.js
    │   ├── globalMixins.js
    │   └── material-kit.js
    ├── router.js
    └── views
        ├── Index.vue
        ├── Presentation.vue
        ├── Sections.vue
        ├── components
        │   ├── BasicElementsSection.vue
        │   ├── CardsSection.vue
        │   ├── CommentsSection.vue
        │   ├── FooterSection.vue
        │   ├── JavascriptComponentsSection.vue
        │   ├── NavPillsSection.vue
        │   ├── NavigationSection.vue
        │   ├── NotificationsSection.vue
        │   ├── PreFooterSection.vue
        │   ├── SmallNavigationSection.vue
        │   ├── TablesSection.vue
        │   ├── TabsSection.vue
        │   └── TypographyImagesSection.vue
        ├── examples
        │   ├── AboutUs.vue
        │   ├── BlogPost.vue
        │   ├── BlogPosts.vue
        │   ├── ContactUs.vue
        │   ├── Ecommerce.vue
        │   ├── Error.vue
        │   ├── Landing.vue
        │   ├── Login.vue
        │   ├── Pricing.vue
        │   ├── Product.vue
        │   ├── Profile.vue
        │   ├── Shopping.vue
        │   └── Signup.vue
        ├── presentation
        │   ├── Cards.vue
        │   ├── Components.vue
        │   ├── Content.vue
        │   ├── Examples.vue
        │   ├── Github.vue
        │   ├── Introduction.vue
        │   ├── Overview.vue
        │   ├── Pricing.vue
        │   └── Sections.vue
        └── sections
            ├── Blogs.vue
            ├── ContactUs.vue
            ├── Features.vue
            ├── Headers.vue
            ├── Pricing.vue
            ├── Projects.vue
            ├── Teams.vue
            └── Testimonials.vue
```


## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Resources
- [Live Preview](https://demos.creative-tim.com/vue-material-kit-pro)
- Buy Page: https://www.creative-tim.com/product/vue-material-kit-pro
- Documentation is [here](https://demos.creative-tim.com/vue-material-kit-pro/documentation)
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-vue-material-kit-pro/issues)
- Vue Material Kit - [demo](https://www.creative-tim.com/product/vue-material-kit?ref=github-mk-pro)
- For Front End Development - [Material Kit Pro ](https://www.creative-tim.com/product/material-kit-pro?ref=github-md-pro)

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Vue Material Kit PRO. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Vue Material Kit PRO. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2018 Creative Tim (https://www.creative-tim.com)
- Creative Tim [license](https://www.creative-tim.com/license)

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim

- [Vue products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
