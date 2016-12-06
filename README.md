## About
- This is simple example demonstrating how to integrate cordova plugin, cordova-plugin-googleplus, into ios application to authenticate user with google account. But similarly, you can get it done by following original docs at https://github.com/EddyVerbruggen/cordova-plugin-googleplus

## Prerequisites
- Android SDK
- Xcode

## Prepare development environment
- install cordova: npm install -g cordova

## Generate cordova app with cordova CLI
- https://cordova.apache.org/#getstarted

## Config package name
- Go into your config.xml and make sure that your package name (i.e. the app ID) is what you want it to be. ex: io.naustud.testgooglelogin

## Get your iOS REVERSED_CLIENT_ID
- Go to page https://developers.google.com/mobile/add?platform=ios&cntapi=signin
- Follow instruction screen to generate Googleservice-Info.plist

## Install cordova-plugin-googleplus
- run: `cordova plugin add cordova-plugin-googleplus --save --variable REVERSED_CLIENT_ID=myreversedclientid`
ex: cordova plugin add cordova-plugin-googleplus --save --variable REVERSED_CLIENT_ID=com.googleusercontent.apps.247459730726-5q22k6ork7238c93pu6k1qaoqtepahcg

## Reference Documents:
- Original document: https://github.com/EddyVerbruggen/cordova-plugin-googleplus

