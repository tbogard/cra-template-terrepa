# cra-template-ts-electron-react-eslint-prettier-airbnb

An All-in-one template to create Electron applications with Create React App. The template includes:
- TypeScript 4.1.13
- React 17
- Recoil
- ESLint & Prettier with AirBnB Settings
- Support for SASS/SCSS files
- Electron 11 with electron-forge operations to build and develop executable files

# Requirements
- Node.js 12.16.3 or greater
- npm 6.14.4 or greater
- yarn 1.22.10 or greater

## Installation
Use create-react-app and run the provided template:
```
$ npx create-react-app my_new_app --template cra-template-ts-electron-react-eslint-prettier-airbnb
```
## Developing with Electron
To start developing use `yarn start` so it will execute the compilation of the electron main process and the development server from create-react-app. after the build is complete, electron-forge will load the application on the browser.

Important Note: **After installation, the postinstall script will run the default project and it might take a while since electron-forge needs to initialize all the electron framework in your project.**

After the application starts, you are free to close the electron window and start to develop your application.
