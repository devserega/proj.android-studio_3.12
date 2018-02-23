ABOUT 
-----------------------

This is fixed Android Studio project template for COCOS2D-X-3.12.

Edited files:
* proj.android-studio\app\jni\Andorid.mk
* proj.android-studio\app\build.gradle
* proj.android-studio\build.gradle
* proj.android-studio\gradle\wrapper\gradle-wrapper.jar
* proj.android-studio\gradle\wrapper\gradle-wrapper.properties

Prerequisites software for success building and running 
--------------------------------------------------------

* Android Studio 3.1
* Cocos2d-x-3.12
* Android NDK r12b (x64)

Guide
--------------------------------------------------------
1) Replace original folder 'templates/cpp-template-default/proj.android-studio' with same from this archive.

2) Create new project via cocos console. Example: $ cocos new MyGame -p com.your_company.mygame -l cpp -d projects

2) During first opening 'proj.android-studio' in Android Studio 3.1 you should manually set path to Android NDK. You can do that by opening 'File/Project Structures' and setting path to 'Android NDK location' filled. For testing purpose i used android-ndk-r12b (64 bit OS version).