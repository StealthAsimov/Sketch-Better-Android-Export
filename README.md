sketch-android-kit
==================

Sketch.app Plugin for Exporting Android Layouts

Now works for Sketch Version 3!

**Current Progress:**

* http://quick.as/wzx8cb2m - generate an android app in under 3 minutes
* http://quick.as/lw0di0mm - pixel density and generating layouts with images
* http://quick.as/x4zxhkyj - passing data to generated templates
* http://quick.as/wzx8c0mp - introduction

### quick note

This generates files to be used in an android application using gradle.
It also generates the source files to be used using the great AndroidAnnotations plugin.

Everything is generated dynamically at the moment, except for a few version numbers in the build.gradle file.  I'm planning on adding a few modals to deal with those as well.

As always, feel free to fork this and use it to create your own ideas and application skeletons for iOS/web/etc.

Cheers
=======
Sketch-Better-Android-Export
============================

A plugin for Sketch to export layers for Android. Supports transparency, 1x and 2x base sizes, and has been tested against Sketch 3.2.

TIP: If everything is exporting as a solid rectangle, you probably need to select the artboard and UNCHECK "Include in Export" (in reference to the background color).
