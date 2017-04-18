
phonegap-plugin-pwa
------------------------

# API Support

:white_check_mark: Supported natively
:ballot_box_with_check: Supported with plugin
:x: Not Supported

## Native Behaviours

| API                  | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Local Notifications](http://www.w3.org/TR/notifications/)  |         |     | :white_check_mark:        | | [#16](https://github.com/phonegap/phonegap-plugin-pwa/issues/16) |
| [Push Messages](https://w3c.github.io/push-api/)        |         |     | :white_check_mark: | [phonegap-plugin-push](https://github.com/phonegap/phonegap-plugin-push) | [#3](https://github.com/phonegap/phonegap-plugin-pwa/issues/3) |
| [Foreground Detection](https://w3c.github.io/page-visibility/) | :white_check_mark: |     | :white_check_mark: | | |
| [Permissions](https://w3c.github.io/permissions/) | :x: | :x: | :white_check_mark: | | [#17](https://github.com/phonegap/phonegap-plugin-pwa/issues/17) |

## Surroundings

| API                  | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Bluetooth](https://webbluetoothcg.github.io/web-bluetooth/) | :x: | :x: | :white_check_mark: | | [#6](https://github.com/phonegap/phonegap-plugin-pwa/issues/6) |
| [NFC](https://w3c.github.io/web-nfc/) | :x: | :x: | :x: | | |
| [Proximity Sensors](https://w3c.github.io/proximity/) | :x: | :x: | :x: | | |
| [Ambient Light](https://w3c.github.io/ambient-light/) | :x: | :x: | :x: | | |

## Device Features

| API                  | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Network Type & Speed](http://wicg.github.io/netinfo/) | :white_check_mark: | :white_check_mark: | :x: | [cordova-plugin-network-information](https://github.com/apache/cordova-plugin-network-information) | |
| [Online State](https://html.spec.whatwg.org/multipage/browsers.html#browser-state) | :white_check_mark: | :white_check_mark: | :white_check_mark: | | |
| [Vibration](https://w3c.github.io/vibration/) | :white_check_mark: | :ballot_box_with_check: | :white_check_mark: | [cordova-plugin-vibration](https://github.com/apache/cordova-plugin-vibration) | |
| [Battery Status](https://dvcs.w3.org/hg/dap/raw-file/default/battery/Overview.html)       | :x: | :x: | :white_check_mark: | [cordova-plugin-battery-status](https://github.com/apache/cordova-plugin-battery-status)  | [#8](https://github.com/phonegap/phonegap-plugin-pwa/issues/8) |

## Seamless Experience

| API                      | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Offline Mode (i.e. ServiceWorkers)](https://www.w3.org/TR/service-workers/)             |         |     | :white_check_mark: | [phonegap-plugin-service-worker](https://github.com/phonegap/phonegap-plugin-service-worker) | [#7](https://github.com/phonegap/phonegap-plugin-pwa/issues/7) |
| [Home Screen Installation](https://w3c.github.io/manifest/) | :white_check_mark: | :white_check_mark: | :white_check_mark: | | |
| [Background Sync](https://wicg.github.io/BackgroundSync/spec/) | :x: | :x: | :white_check_mark: | [cordova-plugin-service-worker-background-sync](https://github.com/MobileChromeApps/cordova-plugin-service-worker-background-sync) | [#18](https://github.com/phonegap/phonegap-plugin-pwa/issues/18) |
| [Inter-app Communication](https://www.w3.org/TR/web-intents/)  | :x: | :x: | :x: | | |

## Camera & Microphone

| API                      | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Audio & Video Capture](https://whatwebcando.today/camera-microphone.html)    |         |     | :white_check_mark: | | |
| [Advanced Camera Controls](https://w3c.github.io/mediacapture-image/) |         |     | :white_check_mark: | | |
| [Recording Media](https://w3c.github.io/mediacapture-record/MediaRecorder.html)          |         |     | :white_check_mark: | | |
| [Real-time Communication](https://w3c.github.io/webrtc-pc/)  |         |     | :white_check_mark: | | |

## Screen & Output

| API                       | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Fullscreen](https://fullscreen.spec.whatwg.org/)                |         |     | :white_check_mark: | | |
| [Screen Orientation & Lock](https://w3c.github.io/screen-orientation/) | :ballot_box_with_check: | :ballot_box_with_check: | :white_check_mark: |
| [Wake Lock](https://w3c.github.io/wake-lock/)                 |         |     | :x:     | | |
| [Presentation Features](https://w3c.github.io/presentation-api/)     |         |     | :white_check_mark: | | |

## Input

| API                      | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Touch Gestures](https://w3c.github.io/touch-events/)           |         |     | :white_check_mark: | | |
| [Speech Recognition](https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html#speechreco-section)       |         |     | :white_check_mark: | | |
| [Copy & Paste](https://w3c.github.io/clipboard-apis/)             |         |     | :white_check_mark: | | |
| [Pointing Device](https://www.w3.org/TR/mediaqueries-4/#mf-interaction)          |         |     | :white_check_mark: | | |

## Location & Position

| API                      | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Geolocation](https://www.w3.org/TR/geolocation-API/)              |         |     | :white_check_mark: | | |
| [Geofencing](https://w3c.github.io/geofencing-api/)               |         |     | :x:     | | |
| [Device Orientation](https://w3c.github.io/deviceorientation/spec-source-orientation.html)       |         |     | :white_check_mark: | | |
| [Device Motion](https://w3c.github.io/deviceorientation/spec-source-orientation.html#devicemotion)            |         |     | :white_check_mark: | | |

## Operating System

| API                      | Android | iOS | Browser | Plugin | Issue |
| -------------------- | ------- | --- | ------- | ------ | ----- |
| [Offline Storage](https://html.spec.whatwg.org/multipage/webstorage.html)          | :white_check_mark: | :white_check_mark: | :white_check_mark: | | |
| [File Access](https://w3c.github.io/FileAPI/)              |         |     | :white_check_mark: | | |
| Contacts                 |         |     | :x:     | | |
| [Storage Quotas](https://w3c.github.io/quota-api/)           |         |     | :white_check_mark: | | |
