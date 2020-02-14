
# react-native-webview-fullscreen

![platforms](https://img.shields.io/badge/platforms-Android-brightgreen.svg?style=flat-square&colorB=191A17)
[![npm](https://img.shields.io/npm/v/rn-webview-fullscreen.svg?style=flat-square)](https://www.npmjs.com/package/react-native-webview-fullscreen)
[![npm](https://img.shields.io/npm/dm/rn-webview-fullscreen.svg?style=flat-square&colorB=007ec6)](https://www.npmjs.com/package/react-native-webview-fullscreen)
[![github issues](https://img.shields.io/github/issues/umuttaymaz/rn-webview-fullscreen.svg?style=flat-square)](https://github.com/trabricks/react-native-webview-fullscreen/issues)
[![github closed issues](https://img.shields.io/github/issues-closed/umuttaymaz/rn-webview-fullscreen.svg?style=flat-square&colorB=44cc11)](https://github.com/trabricks/react-native-webview-fullscreen/issues?q=is%3Aissue+is%3Aclosed)

Android HTML5 fullscreen support for react-native-webview


## Getting started

`$ npm install react-native-webview react-native-webview-fullscreen --save`


### Mostly automatic installation ( <= 0.59 )

```
$ react-native link react-native-webview
$ react-native link rn-webview-fullscreen
```

## Usage
```javascript
import WebView from 'rn-webview-fullscreen';

<Webview
  style={{ flex: 1, }}
  source={{ uri: 'https://youtube.com' }} />

```
