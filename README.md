# ASyncLibrary
Image Loading Library for Asynchronous downloading, caching and rendering Images and Bitmaps from Internet using HTTP requests. 

Features:
-Uses LRU cache for caching(with configurable max capacity).
-Asynchronous loading.
-Easy to Integrate into Android apps.
      Step 1: On Android Studio, select File -> New -> Import Module and import the Library as module.
      Step 2: In App level build.gradle file, add
                compile project("ASynchLoaderLibrary")
                    and build project.
      Step 3: Change the ImageView in which the Images are to be loaded to PhotoView (Custom ImageView created in library).
      Step 4: Use Library using the command:
                  ASyncLibrary.with(***Context***).load(***URL_String***).into(***Target_PhotoView);
