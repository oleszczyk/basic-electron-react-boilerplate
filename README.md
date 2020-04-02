# Modern and Minimal Electron + React Starter Kit
_Electron, React, Webpack -- Modern and up-to-date, with a handful of quality of life features included_

Production builds babel-minify is used, and ES2015/ES6 transpilation is provided -- As modern node and chromium versions support 99%+ of the ES6 feature set, I feel those steps are unnecessary.

### To get started:
* Run `npm install`

##### Development
* Run `npm run dev` to start webpack-dev-server. Electron will launch automatically after compilation.

##### Production
* Run `npm run prod` to open application with production setup. Webpack will compile and output your bundle to `build/bundle.js`. This will also cause electron to load off of the `build/` build instead of looking for the webpack-dev-server instance. Electron will launch automatically after compilation.

##### Preparing installer package
* Run `npm run package` to create debian package (`*.deb`) installer from production build of the application. Package will be placed in `dist/installers/` directory.


