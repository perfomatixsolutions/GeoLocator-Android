[![Android Arsenal]( https://img.shields.io/badge/Android%20Arsenal-GeoLocator--Android-green.svg?style=flat )]( https://android-arsenal.com/details/1/7331 ) &nbsp; &nbsp;  [![](https://jitpack.io/v/AravindVijay7/GeoLocator-Android.svg)](https://jitpack.io/#AravindVijay7/GeoLocator-Android)


# GeoLocator-Android
 Using GeoLocator-Android you could easily get you GPS based location from Android Devices
 
 
 
 
# Gradle / Maven dependency
At the moment we do not have a publishing mechanism to a maven repository so the easiest way to add the library to your app is via a JitPack Dependency 

 # Add this to you project.gradle

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
 # Add this to your App.gradle
  
  	dependencies {
	       implementation 'com.github.AravindVijay7:GeoLocator-Android:2.0.0'
	}


# Usage


 ## Initialize GeoLocator:
 
   > GeoLocator geoLocator = new GeoLocator(getApplicationContext(),MainActivity.this);
   
     >or(Converting address to latitude and longitude)

   > GeoLocator geoLocator = new GeoLocator(getApplicationContext(),MainActivity.this,"Address String");

 ## get latitude and longitude by:
  
   > geoLocator.getLattitude()
   
   > geoLocator.getLongitude()

 ## get address by:

   > geoLocator.getAddress()
   
   
   ## License
   
	   Copyright (c) 2020 AravindVijay

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.   
