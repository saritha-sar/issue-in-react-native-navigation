Hello everyone pls check this issue...this happens when adding dependencies for the react native stack navigation....




error Failed to install the app. Make sure you have the Android development environment set up: https://facebook.github.io/react-native/docs/getting-started.html#android-development-environment. Run CLI with --verbose flag for more details.
Error: Command failed: gradlew.bat app:installDebug -PreactNativeDevServerPort=8081

FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring project ':react-native-community_masked-view'.
> Could not resolve all artifacts for configuration ':react-native-community_masked-view:classpath'.
   > Could not resolve com.android.tools.build:gradle:3.3.1.
     Required by:
         project :react-native-community_masked-view
      > Could not resolve com.android.tools.build:gradle:3.3.1.
         > Could not get resource 'https://dl.google.com/dl/android/maven2/com/android/tools/build/gradle/3.3.1/gradle-3.3.1.pom'.
            > Could not GET 'https://dl.google.com/dl/android/maven2/com/android/tools/build/gradle/3.3.1/gradle-3.3.1.pom'.
               > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
      > Could not resolve com.android.tools.build:gradle:3.3.1.
         > Could not get resource 'https://maven.google.com/com/android/tools/build/gradle/3.3.1/gradle-3.3.1.pom'.
            > Could not GET 'https://dl.google.com/dl/android/maven2/com/android/tools/build/gradle/3.3.1/gradle-3.3.1.pom'.
               > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 7s

    at checkExecSyncError (child_process.js:630:11)
    at execFileSync (child_process.js:648:15)
    at runOnAllDevices (D:\MTW-mobile\node_modules\@react-native-community\cli-platform-android\build\commands\runAndroid\runOnAllDevices.js:94:39)
    at buildAndRun (D:\MTW-mobile\node_modules\@react-native-community\cli-platform-android\build\commands\runAndroid\index.js:179:41)
    at D:\MTW-mobile\node_modules\@react-native-community\cli-platform-android\build\commands\runAndroid\index.js:133:12
    at processTicksAndRejections (internal/process/task_queues.js:97:5)
    at async Command.handleAction (D:\MTW-mobile\node_modules\react-native\node_modules\@react-native-community\cli\build\index.js:182:9)
