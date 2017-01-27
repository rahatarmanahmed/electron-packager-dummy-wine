# electron-packager-dummy-wine

This package is for when you want to use `electron-packager` to build a windows build of your app on a non-windows host environment, but you don't want to install wine. Adding this to your package.json will put a dummy wine in your node_modules/.bin (which is included in npm scripts PATH), which will do nothing.

## Caveats

- The icon will not be set
- The application metadata will not be changed from the Electron defaults

If these are important to you, then you will need Wine.
