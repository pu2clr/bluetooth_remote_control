# Mobile Application based on Cordova environment

## Introduction 

The goal of this mobile application is improve the VFO control and visualization. 


## Compile and deploy this mobile application

Copy this folder to a local folder and follow the steps bellow

For Android, is recommended to install [Android Studio](http://developer.android.com/sdk/index.html) on your computer to compile and deploy this application. 

For iOS (iPhone or iPad), is recommended to install [Xcode](https://developer.apple.com/xcode/) on your Mac computer to compile and deploy this application.


## Cordova 

This applications was build using the [Apache Cordova](https://cordova.apache.org/docs/en/latest/guide/overview/index.html). 
[Apache Cordova](https://cordova.apache.org/docs/en/latest/guide/overview/index.html) is an open-source tool to develop cross-platform mobile application. Click [here](https://cordova.apache.org/docs/en/latest/guide/overview/index.html) to see more about Apache Cordova.

### Install Cordova

    Cordova runs on Node.js.  Please, before installing Cordova, you have to configure the [Node.js](https://nodejs.org/en/). 

    $ npm install cordova -g


### Install Platform and Plugin

    $ cordova platform add android
    $ cordova platform add ios
    $ cordova plugin add cordova-plugin-bluetooth-serial


### Build and Deploy

Compile and run the application


    $ cordova run --device android 

    or

    $ cordova run --device ios


### Arduino sketch 

The Arduino sketch have to use the [SoftwareSerial](https://github.com/PaulStoffregen/SoftwareSerial) library. You have to download and install this library on your Arduino enviroment.  

Downlod the proper Arduino Sketch to your Arduino Board.

### Pair your phone

You have to pair your smartphone with the HM10 or HC-05 Bluetooth Shield. The HC-05 Bluetooth shield does not work on iOS devices. 


## References

- [Bluetooth Serial Plugin for PhoneGap](https://github.com/digistump/Digispark_Cordova_BTShieldEcho/tree/master/plugins/com.megster.cordova.bluetoothserial)
- [Bluetooth Serial Plugin for PhoneGap](https://github.com/don/BluetoothSerial)
- [UI Plugin For Seven-Segment Indicator - sevenSeg.js](https://www.jqueryscript.net/demo/jQuery-jQuery-UI-Plugin-For-Seven-Segment-Indicator-sevenSeg-js/)
- 