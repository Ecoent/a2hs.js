<h1 align="center">📲 a2hs.js</h1>
<h4 align="center"><i>Add progressive web application (PWA) to Home Screen on iOS</i></h4>

<p align="center">
  <img width="640px" src="https://user-images.githubusercontent.com/11155743/57543776-fd47ba80-735d-11e9-8c7d-07b0f498b627.jpg" alt="iPhone X mockup a2hs.js"/>
</p>

<p align="center">
    <img src="https://badge.fury.io/js/a2hs.js.svg" alt="npm version"/>
    <img src="https://img.shields.io/badge/GZip_size-1.9_KB-green.svg?style=flat" alt="gzip"/>
    <img src="https://data.jsdelivr.com/v1/package/npm/a2hs.js/badge?style=rounded" alt="jsDelivr download"/>
    <img src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat" alt="code style: prettier"/>
    <img src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat" alt="license"/>
</p>

<p align="center">
    A useful modern JavaScript solution for adding (install) a <b>progressive web application</b> (PWA) to the <b>Home screen</b> of your <b>iOS</b> mobile device. Designed for the <b>latest 4 major versions</b> of iOS Safari 9.x-12.2+.
</p>

## Install

```bash
$ npm install --save a2hs.js
```

## Usage

There is two way to use `a2hs.js` in your JS bundle:

```js
// Import a2hs.js
import AddToHomeScreen from "a2hs.js";

// Init a2hs.js
new AddToHomeScreen({
    brandName: "Demo",
    fontFamily: "Tahoma, sans-serif",
    backgroundColor: "red",
    color: "white"
});
```
## Demo

<table border="0">
 <tr border="0">
   <td width="300px" border="0">
     <img width="100%" src="https://user-images.githubusercontent.com/11155743/57539303-e2bc1400-7352-11e9-951c-07bb63b4cb61.gif" alt="demo"/>
   </td>
   <td border="0">
     <img src="https://user-images.githubusercontent.com/3104648/28352004-a055292c-6c4b-11e7-9c6b-a94cdc2a5458.png" alt="PWA logo"/>
   </td>
 </tr>
</table>
