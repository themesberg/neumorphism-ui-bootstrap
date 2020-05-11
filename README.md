# [Neumorphism UI](https://demo.themesberg.com/neumorphism-ui/) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fthemesberg.com%2Fproduct%2Fui-kits%2Fneumorphism-ui&via=themesberg&text=Start%20developing%20neumorphic%20interfaces%20with%20Neumorphism%20UI%20PRO&hashtags=neumorphism%2Cneomorphism%2Cbootstrap)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/themesberg/neumorphism-ui.svg?maxAge=2592000)](https://github.com/themesberg/neumorphism-ui/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/themesberg/neumorphism-ui.svg?maxAge=2592000)](https://github.com/themesberg/neumorphism-ui/issues?q=is%3Aissue+is%3Aclosed)

<a href="https://demo.themesberg.com/neumorphism-ui/">
 <img src="https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/neumorphism-ui-preview.gif" alt="Neumorphism UI Preview"/>
 </a>

Start developing neumorphic web applications and pages using Neumorphism UI which makes use of the neumorphic design trend. It features over 200 individual components and 5 example pages.

## Neumorphic components

All components are perfectly in compliance with the neumorphism design trend making use of the specific shadow and coloring attributes. Neumorphism UI also comes with the shadow inset style add-on.

Check out [all components here](https://demo.themesberg.com/neumorphism-ui/html/components/all.html).

## Example pages

Neumorphism UI comes with 13 example pages including an about, pricing, contact, log in and register pages. You can use these example pages to quickly set up a working website in no time.

## Full documentation

Each component, plugin and the general workflow is well documented. Check out the [online documentation for Neumorphism UI](https://themesberg.com/docs/neumorphism-ui/getting-started/quick-start/).

## Workflow

This product is built using the following widely used technologies:

- Most popular CSS Framework Bootstrap
- Productive workflow tool Gulp
- Awesome CSS preprocessor Sass

## Table of Contents

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

## Demo

| Components | About | Contact |
| --- | --- | --- |
| [![Components](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/all-components.jpg)](https://demo.themesberg.com/neumorphism-ui/html/components/all.html) | [![About page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/about.jpg)](https://demo.themesberg.com/neumorphism-ui/html/pages/about.html) | [![Contact page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/contact.jpg)](https://demo.themesberg.com/neumorphism-ui/html/pages/contact.html)

| Login | Register | Documentation |
| --- | --- | --- |
| [![Login page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/login.jpg)](https://demo.themesberg.com/neumorphism-ui/html/pages/sign-in.html) | [![Register page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/register.jpg)](https://demo.themesberg.com/neumorphism-ui/html/pages/sign-up.html) | [![Documentation](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui/github/docs.jpg)](https://themesberg.com/docs/neumorphism-ui/getting-started/quick-start/)

-   [Live Preview](https://demo.themesberg.com/neumorphism-ui/)
-   [Details](https://themesberg.com/product/ui-kits/neumorphism-ui?ref=github-neumorphism)

## Quick start

1. Download from [Themesberg](https://themesberg.com/product/ui-kits/neumorphism-ui?ref=github-neumorphism)
2. Download the project's zip
3. Make sure you have Node locally installed.
4. Download Gulp Command Line Interface to be able to use gulp in your Terminal.

```
npm install gulp-cli -g
```

5. After installing Gulp, run npm install in the main `neumorphism/` folder to download all the project dependencies. You'll find them in the `node_modules/` folder.

```
npm install
```

6. Run gulp in the `neumorphism/` folder to serve the project files using BrowserSync. Running gulp will compile the theme and open `/index.html` in your main browser.

```
gulp
```

While the gulp command is running, files in the `assets/scss/`, `assets/js/` and `components/` folders will be monitored for changes. Files from the `assets/scss/` folder will generate injected CSS.

Hit `CTRL+C` to terminate the gulp command. This will stop the local server from running.

## Theme without Sass, Gulp or Npm

If you'd like to get a version of our theme without Sass, Gulp or Npm, we've got you covered. Run the following command:

```
gulp build:dev
```

This will generate a folder `html&css` which will have unminified CSS, Html and Javascript.

## Minified version

If you'd like to compile the code and get a minified version of the HTML and CSS just run the following Gulp command:

```
gulp build:dist
```

This will generate a folder `dist` which will have minified CSS, Html and Javascript.

## Documentation

The documentation for Neumorphism UI is hosted on our [website](https://themesberg.com/docs/neumorphism-ui/getting-started/overview).

## File Structure

Within the download you'll find the following directories and files:

```
Neumorphism UI
.
├── README.md
├── gulpfile.js
├── neumorphism-ui.zip
├── package-lock.json
├── package.json
└── src
    ├── assets
    │   ├── img
    │   │   ├── blog
    │   │   ├── brand
    │   │   ├── carousel
    │   │   ├── checker_logo.png
    │   │   ├── clients
    │   │   ├── favicon
    │   │   ├── illustrations
    │   │   ├── macbook-mockup.png
    │   │   ├── megamenu-image.jpg
    │   │   ├── presentation
    │   │   ├── presentation-mockup.png
    │   │   ├── presentation-sections
    │   │   ├── sections
    │   │   ├── shop
    │   │   ├── signature.svg
    │   │   ├── team
    │   │   ├── themesberg.svg
    │   │   └── wavelogo.svg
    │   └── js
    │       └── neumorphism.js
    ├── html
    │   ├── components
    │   │   ├── accordions.html
    │   │   ├── alerts.html
    │   │   ├── all.html
    │   │   ├── badges.html
    │   │   ├── bootstrap-carousels.html
    │   │   ├── breadcrumbs.html
    │   │   ├── buttons.html
    │   │   ├── cards.html
    │   │   ├── forms.html
    │   │   ├── modals.html
    │   │   ├── navs.html
    │   │   ├── pagination.html
    │   │   ├── popovers.html
    │   │   ├── progress-bars.html
    │   │   ├── steps.html
    │   │   ├── tables.html
    │   │   ├── tabs.html
    │   │   ├── toasts.html
    │   │   ├── tooltips.html
    │   │   ├── typography.html
    │   │   └── widgets.html
    │   ├── pages
    │   │   ├── about.html
    │   │   ├── contact.html
    │   │   ├── pricing.html
    │   │   ├── sign-in.html
    │   │   └── sign-up.html
    ├── index.html
    ├── partials
    │   ├── _analytics.html
    │   ├── _footer.html
    │   ├── _head.html
    │   ├── _navigation.html
    │   ├── _pages-preview.html
    │   ├── _pricing.html
    │   ├── _scripts.html
    │   └── components
    │       ├── _accordions.html
    │       ├── _alerts.html
    │       ├── _badges.html
    │       ├── _bootstrap-carousels.html
    │       ├── _breadcrumbs.html
    │       ├── _buttons.html
    │       ├── _cards.html
    │       ├── _forms.html
    │       ├── _modals.html
    │       ├── _navs.html
    │       ├── _pagination.html
    │       ├── _popovers.html
    │       ├── _progress-bars.html
    │       ├── _steps.html
    │       ├── _tables.html
    │       ├── _tabs.html
    │       ├── _toasts.html
    │       ├── _tooltips.html
    │       ├── _typography.html
    └── scss
        ├── bootstrap
        │   ├── _alert.scss
        │   ├── _badge.scss
        │   ├── _breadcrumb.scss
        │   ├── _button-group.scss
        │   ├── _buttons.scss
        │   ├── _card.scss
        │   ├── _carousel.scss
        │   ├── _close.scss
        │   ├── _code.scss
        │   ├── _custom-forms.scss
        │   ├── _dropdown.scss
        │   ├── _forms.scss
        │   ├── _functions.scss
        │   ├── _grid.scss
        │   ├── _images.scss
        │   ├── _input-group.scss
        │   ├── _jumbotron.scss
        │   ├── _list-group.scss
        │   ├── _media.scss
        │   ├── _mixins.scss
        │   ├── _modal.scss
        │   ├── _nav.scss
        │   ├── _navbar.scss
        │   ├── _pagination.scss
        │   ├── _popover.scss
        │   ├── _print.scss
        │   ├── _progress.scss
        │   ├── _reboot.scss
        │   ├── _root.scss
        │   ├── _spinners.scss
        │   ├── _tables.scss
        │   ├── _toasts.scss
        │   ├── _tooltip.scss
        │   ├── _transitions.scss
        │   ├── _type.scss
        │   ├── _utilities.scss
        │   ├── _variables.scss
        │   ├── bootstrap-grid.scss
        │   ├── bootstrap-reboot.scss
        │   ├── bootstrap.scss
        │   ├── mixins
        │   ├── utilities
        │   └── vendor
        ├── neumorphism
        │   ├── _components.scss
        │   ├── _functions.scss
        │   ├── _layout.scss
        │   ├── _mixins.scss
        │   ├── _reboot.scss
        │   ├── _utilities.scss
        │   ├── _variables.scss
        │   ├── _vendor.scss
        │   ├── components
        │   ├── layout
        │   ├── mixins
        │   ├── utilities
        │   └── vendor
        └── neumorphism.scss
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources
- Demo: <https://demo.themesberg.com/neumorphism-ui/>
- Download Page: <https://themesberg.com/product/ui-kits/neumorphism-ui>
- Documentation: <https://themesberg.com/docs/neumorphism-ui/getting-started/quick-start>
- Themesberg EULA: <https://themesberg.com/licensing>
- Support: <https://themesberg.com/contact>
- Issues: [Github Issues Page](https://github.com/themesberg/neumorphism-ui/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for Neumorphism UI. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of Neumorphism UI. Check the CHANGELOG on our [website](https://themesberg.com/product/ui-kits/neumorphism-ui?ref=github-neumorphism).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://themesberg.com/contact?ref=github-neumorphism) instead of opening an issue.

## Licensing

- Copyright 2020 Themesberg (Crafty Dwarf LLC) (https://themesberg.com)
- MIT License (https://themesberg.com/licensing#mit)

## Useful Links

- [More themes](https://themesberg.com/themes?ref=github-neumorphism) from Themesberg
- [Free themes](https://themesberg.com/products/free-themes?ref=github-neumorphism) from Themesberg
- [Affiliate Program](https://themesberg.com/affiliate?ref=github-neumorphism)

##### Social Media

Twitter: <https://twitter.com/themesberg>

Facebook: <https://www.facebook.com/themesberg/>

Dribbble: <https://dribbble.com/themesberg>

Instagram: <https://www.instagram.com/themesberg/>
