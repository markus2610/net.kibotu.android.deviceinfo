Android Device Info [![Build Status](https://travis-ci.org/kibotu/net.kibotu.android.deviceinfo.svg?branch=develop)](https://travis-ci.org/kibotu/net.kibotu.android.deviceinfo) [![API](https://img.shields.io/badge/API-15%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=15) [![](https://jitpack.io/v/kibotu/net.kibotu.android.deviceinfo.svg)](https://jitpack.io/#kibotu/net.kibotu.android.deviceinfo) [![Licence](https://img.shields.io/badge/licence-Apache-blue.svg)](https://raw.githubusercontent.com/kibotu/net.kibotu.android.deviceinfo/develop/LICENSE)
================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

### Introduction

Library and app for showing tons of device information for your android device. 

### How to install
	
	repositories {
	    maven {
	        url "https://jitpack.io"
	    }
	}
		
	dependencies {
        compile 'com.github.kibotu:net.kibotu.android.deviceinfo:-SNAPSHOT'
    }
   

### How to build the lib:

    gradle clean lib:build

### Features

##### Build

    Build.getSystemAvailableFeatures()

##### Configuration
##### Cpu
##### Gpu
##### Memory
##### Battery
##### Display
##### Network
##### Sensor
##### Java
##### Geolocation
##### App
##### Misc


### Todo

* documentation how to access the data, currently it can be found at the demo app
* memory: add environment info
* display: finish display class info
* display: fix configuration info
* geolocation: add fusion, also gmaps
* option menu: re-add endpoints for github, twitter, fbook, find parse alternative server endpoint to store shared device data
* release new build to gplay

