# GrabCutDemo
---

An Android demonstration segments image using Grab-Cut algorithm.

**Notes:**
 1. You should download the [OpenCV4Android SDK][1] and import it to the project manully. Here is the guide on how to import the library: [OpenCV in Android Studio][2]
 2. A known issue is that this application cannot process images too big, or you will get a `std::bad_alloc` exception. I recommend using images that are no larger than 700*500.


  [1]: http://docs.opencv.org/doc/tutorials/introduction/android_binary_package/O4A_SDK.html
  [2]: http://stackoverflow.com/questions/27406303/opencv-in-android-studio
