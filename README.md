# Framework7 Vuejs Webpack Cordova App Template

A full-featured Framework7 Vue with Webpack setup with hot-reload & css extraction. Based on [Vue Webpack Boilerplate](https://github.com/vuejs-templates/webpack)

# Getting Started

## Usage

### 1. Create a new app from this template
```
$ git clone https://github.com/asperduti/framework7-vuejs-cordova-webpack.git
```

### 2. Install dependencies

Go to the app folder and run:
```
$ cd framework7-vuejs-cordova-webpack
$ npm install
```

This will download latest version of Framework7, Framework7-Vue, Vue, Webpack

### 3. Run the app

The template is prepared to load the cordova.js for browsers. First you need to add the browser platform

```
$ cordova platform add browser
$ npm run dev
```
App will be opened in browser at `http://localhost:8080/`

### 3. Run the app on mobile (Android or iOs)

You need to add the android platform

```
$ cordova platform add android
$ npm run cordova-run-android
```

### 4.a Build browser app for production

```
npm run build
```

### 4.b Build android app for production

```
npm run cordova-build-android
```


## One command install

```
git clone https://github.com/asperduti/framework7-vuejs-cordova-webpack.git &&
cd framework7-vuejs-cordova-webpack &&
npm install &&
cordova platform add browser &&
npm run dev
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## Project Structure

* `src/assets` - folder with static assets (images)
* `src/components` - folder with custom `.vue` components
* `src/css` - put custom app CSS styles here. Don't forget to import them in `main.js`
* `src/pages` - app `.vue` pages
* `src/main.js` - main app file where you include/import all required libs and init app
* `src/routes.js` - app routes
* `src/app.vue` - main app structure/component

# Upgrading the Template

This template is always being improved by its users, so sometimes one may need to upgrade.
Ensure there's an upstream remote

If git remote -v doesn't have an upstream listed, you can do the following to add it:

```
$ git remote add upstream https://github.com/asperduti/framework7-vuejs-cordova-webpack.git
```
Pull in the latest changes
```
$ git pull upstream master
```
There may be merge conflicts, so be sure to fix the files that git lists if they occur. That's it!
