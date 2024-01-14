# Playwright Test Setup
## [Documentation](https://playwright.dev) 

The Playwright is a framework for Web Testing and Automation. It allows testing Chromium, Firefox, and Safari with a single API. The playwright is built to enable cross-browser web automation that is **ever-green**, **capable**, **reliable**, and **fast**.


## Installation

Playwright has its own test runner for end-to-end tests, we call it the Playwright Test.

### Using the init command

The easiest way to get started with the Playwright Test is to run the init command.

```Shell
# Run from your project's root directory
npm init playwright@latest
# Or create a new project
npm init playwright@latest new-project
```

This will create a configuration file, optionally add examples, a GitHub Action workflow, and a first test example.spec.ts. You can now jump directly to the writing assertions section.

### Manually

Add dependency and install browsers.

```Shell
npm i -D @playwright/test
# install supported browsers
npx playwright install
```

You can optionally install only selected browsers, see [install browsers](https://playwright.dev/docs/cli#install-browsers) for more details. Or you can install no browsers at all and use existing [browser channels](https://playwright.dev/docs/browsers).

* [Getting started](https://playwright.dev/docs/intro)
