React Native for Web with Expo
==============================

I found it to be a bit less straightforward than expected to get React Native for Web working with Expo, mostly due to version conflicts. I figured I may as well create a boilerplate project to ease the setup process. This project is based off of [React Native for Web - Example App](https://github.com/ndbroadbent/react-native-web-webpack)

## Getting Started

* Install dependencies: `npm install`
* Load for apps: `npm start` (expo)
* Load for web: `npm run web` (webpack)

You can run both expo and webpack simultaneously in different processes, and both will hot-reload your changes. Go ahead and customize `app.js` to try it out!

## Publishing to Expo

When you've got something cooking and you want to share it, you can publish to Expo:

`npm run exp publish`
