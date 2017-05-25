# Cordova-Camera-Example
Another Code Sample for using the Cordova Camera Plugin with File Transfer
This respository was created because when I needed to come up with a script for my mobile app using the Camera plugin, many of the code examples/samples I found were either out-of-date, lacked functionality (being plain-jane samples), and/or didn't do what I needed.  There are lots of examples out there. This is just one more.  My goal is to help some other novice developer get over the same hump I had to get over, but faster.

So far, I've only tested this with iOS.

Plugins: 
	https://github.com/apache/cordova-plugin-camera
	https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-file-transfer/ 
  
  I'm using PhoneGap Build, so my config.xml file contains
  
```  <plugin name="cordova-plugin-camera" />
	<feature name="Camera">
    	<param name="ios-package" value="CDVCamera" />
	</feature>```
  
 ``` <gap:plugin name="cordova-plugin-file-transfer" source="npm"/>```
  
  See inline comments index.html for further information.
