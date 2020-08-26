# rn-maps-review

<p align="center">
  <a href="https://dribbble.com/patgrivet">
        <img src="https://static.dribbble.com/users/187497/screenshots/1402091/city-dribbble.gif" alt="City 
by Brent Clouse" width="380" height="280">
  </a>
  <br><i>© <a href="https://dribbble.com/brentclouse"> Brent Clouse </a></i>
  <h3 align="center">rn-maps-review</h3>
  <p align="center">
    <a href="https://github.com/othneildrew/Best-README-Template">Run examples</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Contribue</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Tested libraries](#tested-maps-libraries)
- [Run examples](#run-examples)
- [Screenshots](#screenshots)
- [Features availability](#components-availability)
- [Benchmarking](#Benchmarking)
- [Contributing](#contributing)
  <!-- ABOUT THE PROJECT -->

## About The Project

React Native maps review aim to help you finding the best maps library for your next react native project, by giving you a detailed benchmark about the most popular and available libraries, their best use cases, their limits, as well as their performance.
You will find all the needed information in this page, also you can clone the project and see how these libraries works in real life by running the samples under the "packages" folder.

### Tested libraries

Below is a list of the tested map libraries in this project :

- [react-native-maps](https://github.com/react-native-community/react-native-maps) : React Native Map components for iOS + Android
- [react-native-mapbox-gl](https://github.com/react-native-mapbox-gl/maps) : An unofficial React Native library for building maps with the Mapbox Maps SDK for iOS and Mapbox Maps SDK for Android

## Run examples

The example apps are creates as packages under this project, and we are using [Lerna](https://github.com/lerna/lerna) to manage these packages.
So if you want to test one of these apps, you can use this command :
```
npx lerna --socpe=<PackageName> yarn start 
```
expamle :
```
// To run the react-native-maps example app 
npx lerna --scope=Maps yarn start
```
## Screenshots
- React Native Maps 
 <div> <img src="https://camo.githubusercontent.com/32d70397b08fb63aa1eb6cad31983958036b060d/687474703a2f2f692e67697068792e636f6d2f336f3655426f50534c6c494b5132647637712e676966" alt="react native maps" height="450"/> <img src="https://camo.githubusercontent.com/3ec3eaaa8f44a0f79694b59fa3ecf8774b371cb9/687474703a2f2f692e67697068792e636f6d2f7854373758576a7145437664676a78396f412e676966" 
 alt="react native maps" height="450"
 /> </div>
- React Native MapBox GL <img src="https://miro.medium.com/max/596/0*z83LdxEoS0eMa9X2.png" alt="react native paper" height="450" />

## Features availability

Before choosing your map library you may want to know what features support each library, so you can choose the one that fits your project the most.

| Features | react-native-maps | react-native-mapbox-gl | 
| -------------- | :-----------: | -----: |
| Offline | <img src="https://image.flaticon.com/icons/svg/1828/1828665.svg" height="25"  alt="Cross icon made by FlatIcon.com" /> | <img src="https://image.flaticon.com/icons/svg/1828/1828644.svg" height="25" alt="check mark icon made by FlatIcon.com" />| 
custom markers | <img src="https://image.flaticon.com/icons/svg/1828/1828644.svg" height="25" alt="check mark icon made by FlatIcon.com" /> | <img src="https://image.flaticon.com/icons/svg/1828/1828644.svg" height="25" alt="check mark icon made by FlatIcon.com" /> | 
