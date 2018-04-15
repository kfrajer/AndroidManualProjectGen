SUMMARY
=========================

[1] Folder structure
[2] Gradle files
[3] Gradle setup
[4] Files generated in the first run


REFERENCE: 
C:\Users\C\Documents\Processing\CMsketches\Android-code\Android1stSample\android_gradle_exp
C:\Users\C\Desktop\moreDocuments\mySandBox\Android\AndroidDevSamples\ActivitySceneTransitionBasic

---------------------------------------------------------------------------

[1] Folder structure

:\Users\C\Desktop\moreDocuments\mySandBox\Android\AndroidSpace\AndroidManualProjectGen>doskey /history
mkdir DualActivityDemo
mkdir DualActivityDemo\Application
mkdir DualActivityDemo\Application\src
mkdir DualActivityDemo\Application\src\main
mkdir DualActivityDemo\Application\src\main\java
mkdir DualActivityDemo\Application\src\main\res
mkdir DualActivityDemo\Application\src\main\res\layout
mkdir DualActivityDemo\Application\src\main\res\values
mkdir DualActivityDemo\Application\src\main\java\com
mkdir DualActivityDemo\Application\src\main\java\com\ads
mkdir DualActivityDemo\Application\src\main\java\com\ads\android
mkdir DualActivityDemo\Application\src\main\java\com\ads\android\demoDualActivity


Package name for this demo: com.ads.android.demoDualActivity

To consider checking next link based on happycoding manifest example: 
http://www.tothenew.com/blog/introduction-to-mipmap-drawables-in-android/ 


It seems we need in DualActivityDemo folder: 
[*] gradle: A folder than contains two files: gradle\wrapper\gradle-wrapper.jar AND gradle\wrapper\gradle-wrapper.properties
[*] build.gradle: [P3] Specific instructions specific to P3.Android: google, jcenter [AS] EMPTY
[*] gradle.properties  [P3] single liner (?) [AS] NO_FILE
[*] gradlew
[*] gradlew.bat
[*] local.properties: [P3] Indicates Android sdk path [AS] NO_FILE
[*] settings.gradle: Single liner --> include ':{folder_name_source_files}'. In this case --> include ':Application'
[*] Any license file


It seems we need in DualActivityDemo\Application folder: 
[*] build.gradle
[*] proguard-rules.pro [P3] Rules strict for this project [AS] NO_FILE
[*] libs: A folder that contains external jar resources like Processing's core.jar file

C:\Users\C\Desktop\moreDocuments\mySandBox\Android\AndroidSpace\AndroidManualProjectGen>tree /f
C:.
│   README.txt
│
└───DualActivityDemo
    └───Application
        └───src
            └───main
                │   AndroidManifest.xml
                │
                ├───java
                │   └───com
                │       └───ads
                │           └───android
                │               └───demoDualActivity
                │                       ClickedScreenActivity.java
                │                       MainActivity2018.java
                │
                └───res
                    ├───layout
                    │       activity_clicked_screen.xml
                    │       activity_main.xml
                    │
                    └───values
                            base-strings.xml