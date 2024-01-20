# Geofencing in Android

This project is fork of https://github.com/wadjaafar/android-geofencing with
following minor modifications.

1. Compiles with latest Android Studio.
1. Fixed a few compilation issues (supports SDK version 34)
1. Formatting.

## Prerequisite

- Generate your Google Map API key and add to
  `app/src/debug/res/values/google_maps_api.xml` file. I have added a test API
  key which may or may not work.

## App

A geofence is a virtual boundary around a physical location. Geofences are
monitored, and when an authorized mobile device enters or exits the geofence, an
alert is sent.

Using Google Geofencing API, this app allows you to create a geofence with a
certain radius and send notifications when the device enters or exit the
geofence or dwelling inside the geofence.

1. To add a geofence and test it, simply long press on the map.

## Screens

![Entering geofence](demo.png)
