# React Native PoC

## Requirements

* Setup react native project with android and ios support
* Document how to setup local development environment
* Incorporate two views with a routing using between the views
* View 1: show current Wifi info and Cellular connection info
* View 2: show ping time to an dns host and a download speed for http://ipv4.download.thinkbroadband.com/5MB.zip
* Both views to preserve ios/andorid status bar, i.e. don't take over the entire mobile screen
* No hard-coded values: use json configuration files
* Strict separation between javascript code in modules and react views to be able to re-use javascript from other views
* Unit tests for javascript modules
* Package the application for ios and for android
* Document how to distribute application for testing purposes in user user-friendly fashion, e.g.: https://www.installrapp.com/ or a similar service, low cost or free
* Document how to publish application to Andorid and iOS app stores for release to consumers
* Use markdown format for all documentation
* App must support background tasks on iOS and on Android


## Acceptance Criteria

* Can clone the repository
* Follow documentation to setup local development environment
* Able to run unit tests
* Unit tests cover all javascript functionality
* Able to distribute new version for testing purposes
* Able to publish app to Google & iOS app stores
* Sound coding practices: separation of concerns, test-ability, modern javascript, no hard-coded values

## How to contribute

* Fork this repository
* Commit changes to your own repository
* Submit your work by creating a pull request from your repository to this repository


## Setting up Developing Enviroment

* [Setting up Develping environment](https://facebook.github.io/react-native/docs/getting-started)
* A possible error on MacOS:
```
xcrun: error: unable to find utility "instruments", not a developer tool or in PATH
```
* [Resolution](http://www.seanbehan.com/how-to-fix-xcrun-error-unable-to-find-utility-instruments-not-a-developer-tool-or-in-path/) is to launch XCode and agree to the terms first. Then go to Preferences > Locations and you'll see a select tag for Command Line Tools. Click this select box and choose the version of XCode installed


## Runing iOS/Android locally

* Go to project directory (on terminal for mac, gitbash or cmd for windows).     
* npm install or yarn install        
* To build Android: react-native run-android   
* To build iOS: react-native run-ios
