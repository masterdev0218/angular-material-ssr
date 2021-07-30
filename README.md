# Angular Material SSR

* Angular app to deploy to Firebase functions with Server Side Rendering
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/angular-material-ssr?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/angular-material-ssr?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/angular-material-ssr?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/angular-material-ssr?style=plastic)

## :page_facing_up: Table of contents

* [Angular Material SSR](#angular-material-ssr)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Firebase functions used to serve Node.js SSR app
* Dist folder contains functions folder with browser and server SSR code.
* Functions folder contains a copy of dependencies from the src package.json file

## :camera: Screenshots

* ![Frontend screenshot](./img/home.png)

## :signal_strength: Technologies

* [Angular v12](https://angular.io/)
* [Angular Universal v12](https://angular.io/guide/universal) added for Server Side Rendering (SSR)
* [RxJS v6](http://reactivex.io/)
* [Express v4](https://www.npmjs.com/package/express) Node.js framework

## :floppy_disk: Setup

* `npm i` to install dependencies
* `npm prune` to remove unused npm modules
* `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
* `ng update` to update Angular

* Run `npm run dev:ssr` to see SSR app on a dev server
* Run `npm run build:ssr` to build SSR project. The browser & server build folders will be stored in the `dist/functions` directory.
* cd `dist/function` then run `firebase emulators:start` for Firebase emulator
* Add `defer` to `dist/functions/browser/index.html` to make loading of styles asynchronous, e.g. `<link rel="stylesheet" href="styles.d6d9df648b6debafe22a.css" defer>`
* From command prompt cd `/dist/functions' then run `npm run deploy` to deploy app to firebase functions & hosting

## :computer: Code Examples

* tba

```typescript
tba
```

## :cool: Features

* Excellent Lighthouse score

## :clipboard: Status & To-Do List

* Status: Working. Perfect Lighthouse score
* To-Do: Try material on Lighthouse score. Add PWA. Use to create an actual app with content. Update sitemap & robots.txt

## :clap: Inspiration

* [Codeible: Server Side Rendering with Angular, Angular Universal, & Firebase 2021](https://www.youtube.com/watch?v=k7pLxaKkHYs)

## :file_folder: License

* N/A

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com