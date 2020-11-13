# Angular Electron Seed Barebones

This project is a super barebones angular project with electron. It is a regular Angular 11 starter app (CSS styling) whit electron.
You can package it with electron builder and github action for automated builds (Linux, Windows, Mac) are included.

![Website Build](https://github.com/Mrgove10/angular-electron-minimal/workflows/Website%20Build/badge.svg)
![Application Build](https://github.com/Mrgove10/angular-electron-minimal/workflows/Application%20Build/badge.svg)

<p align="center">
  <img src="https://angular.io/assets/images/logos/angular/angular.png">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Electron_Software_Framework_Logo.svg/250px-Electron_Software_Framework_Logo.svg.png">
</p>

The stack :

- Angular 11 ([link](https://angular.io/))
- Electron 10 ([link](https://www.electronjs.org/))
- Electron Builder 22.9 ([link](https://www.electron.build/))

- [Angular Electron Seed Barebones](#angular-electron-seed-barebones)
  - [Developpement](#developpement)
    - [Website](#website)
    - [Application](#application)
  - [Building for production](#building-for-production)
    - [Website](#website-1)
    - [Application](#application-1)

## Developpement

When possible you whould be developping in website mode. You will get hot reload and faster compiles times.
Warning : if you clone this repo and then push on github, the build actions will be activated.

### Website

You can test and developpe your app as a website with ```$ npm run start``` then navigating to http://localhost:4200/

To do a test build you can run ```$ npm run build```

### Application

To test in electron ```$ npm run electron```

## Building for production

### Website

If you want to export your app as a website you sure can !

You can run ```$ npm run build:prod``` to do that, it will be exported to `/dist`

### Application

To build for the current platform you can run ```$ npm run electron:build```
To build for every platform you can run ```$ npm run electron:build:all```

the output app should be in the `/release` directory
