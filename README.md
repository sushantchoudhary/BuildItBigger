# Gradle for Android and Java Project

In this project, we are creating an app with multiple flavors that uses
multiple libraries and Google Cloud Endpoints. The finished app will consist
of four modules. A Java library that provides jokes, a Google Cloud Endpoints
(GCE) project that serves those jokes, an Android Library containing an
activity for displaying jokes, and an Android app that fetches jokes from the
GCE module and passes them to the Android Library for display.

### Product Flavors
1. freeDebug : Shows interstitial Ad 
2. prodDebug : No Ads

### Gradle Task 
#### Start app engine 
./gradlew appengineStart 

#### Stop app engine 
./gradlew appengineStop 


#### To start local GCE , run Android test and stop server
./gradlew androidTest 

### Android UI Test
MainActivityUITest.java
