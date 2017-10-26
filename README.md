# FaceRecogonition
Google APIs library version 11.4.2 sync problem:
"SDK Version Support in 11.2

When you upgrade your app’s Play services dependencies to 11.2.0 or later, your app’s build.gradle must also be updated to specify a compileSdkVersion of at least 26 (Android O). This does not change the way your app runs. You will not be required to update targetSdkVersion. If you update compileSdkVersion to 26, you may receive an error in your build with the following message referring to the Android support library:

This support library should should not use a different version (25) than the compileSdkVersion (26).
This error can be resolved by upgrading your support library dependencies to at least version 26.0.0."
From-Google API
