# Quickstart Chrome Extension Template with NPM

Base template for quickly creating working extensions.

This repo was build for beginners to Chrome Extension development and veteran
developers who don't create new extensions often but need to create one fast.

- Good for people with little Chrome experience as there are examples
  of common tasks with explanations.

- Good for quick development since the descriptions will remind you how things
  work. See `Speed tips` for even faster development.

**TODO: Global search and action for "TODO".**

## Icons

Generate favicon and icons at https://favicon.io.

Use https://imageresizer.com/resize for 128x128.

## Used technologies

- [Node Package Manager](https://www.npmjs.com) for ability to import
  dependencies.
- [React framework](https://react.dev) for some logic in Chrome Extension
  toolbar popup panel.
- [Material UI](https://mui.com) for modern UI styling.
- `@fontsource` fonts.

## Speed tips

- Program in the browser console instead of `npm run build` for each change

## Getting started with development

1. Install dependencies.

   ```bash
   npm install
   ```

1. Make code changes.

1. Build package.

   This project uses npm with the Chrome Extension.

   To build and further upload, sideload, or distribute the extension, run
   `npm run build` which will create a `build` directory which should be pointed
   to when loading into a Chromium type browser.

   As compared to a conventional Chrome Extension, the `manifest.json`,
   `background.js` script, etc. are found in the `public` directory.

   The contents of React app are found in the `src` directory.

1. Sideload on local Chrome or Chromium based browser. A `build` directory which
   should be pointed to when loading into a Chromium type browser.

   https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked

1. Look at errors in different consoles depending on the script.

   https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#logs

1. Deploy to Chrome Extension Marketplace.

   Make sure you have an developer account with required application info.

   Turn the contents of the `build` directory into a ZIP file. Upload the ZIP
   file to the Chrome Extension Marketplace.

## Typescript

At the current time, Chrome Extensions do not support Typescript.
