# Framework7 Vuejs Webpack Cordova App Template

A full-featured Framework7 Vue with Webpack setup with hot-reload & css extraction. Based on [Vue Webpack Boilerplate](https://github.com/vuejs-templates/webpack)

## Usage

### 1. Create a new app from this template
```
$ cordova create hello com.example.hello HelloWorld --template https://github.com/asperduti/framework7-vuejs-cordova-webpack
```

### 2. Install dependencies

Go to the app folder and run:
```
npm install
```

This will download latest version of Framework7, Framework7-Vue, Vue, Webpack

### 3. Run the app

The template is prepared to load the cordova.js

```
npm run dev
```
App will be opened in browser at `http://localhost:8080/`

### 3. Run the app on mobile (Android or iOs)

```
npm run cordova-run-android
```

### 4. Build app for production

```
npm run build
```

## One command install

```
cordova create hello com.example.hello HelloWorld --template https://github.com/asperduti/framework7-vuejs-cordova-webpack &&
cd hello &&
npm install &&
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
