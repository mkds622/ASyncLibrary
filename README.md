# ASyncLibrary
Image Loading Library for Asynchronous downloading, caching and rendering Images and Bitmaps from Internet using HTTP requests. 

Features:<br />
-Uses LRU cache for caching(with configurable max capacity).<br />
-Asynchronous loading.<br />
-Easy to Integrate into Android apps.<br />
      Step 1: On Android Studio, select File -> New -> Import Module and import the Library as module.<br />
      Step 2: In App level build.gradle file, add<br />
                compile project("ASynchLoaderLibrary")<br />
                    and build project.<br />
      Step 3: Change the ImageView in which the Images are to be loaded to PhotoView (Custom ImageView created in library).<br />
      Step 4: Use Library using the command:<br />
                  ASyncLibrary.with(***Context***).load(***URL_String***).into(***Target_PhotoView***);<br />
