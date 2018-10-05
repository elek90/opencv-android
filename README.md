# OpenCV-Android
OpenCV for Android ready to be included

## Usage
```
implementation 'com.github.elek90:opencv-android:x.x.x'
```

## Creating a new version
Download the OpenCV Android pack from the [releases page](https://opencv.org/releases.html) and extract it.

 * Copy all java files into the Android project
 * Move the `org.opencv.engine.OpenCVEngineInterface` from the java folder to the aidl folder
 * Copy all `.so` files from the `native/libs` to the jniLibs folder 

## Publish new version
Push a tag for a new version to [Jitpack](https://jitpack.io/#elek90/opencv-android)
```
git tag -a 1.0.0 -m "Release 1.0.0"
git push --tags
```

# Credits
All credit goes to the OpenCV team