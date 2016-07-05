# aide-libgdx-example
Do you want ability to work in modern Android Studio and continue working from mobile device? Here it is. Using gradle in Android Studio and eclipse ant project files in AIDE

Note: this approach is obsolete. Modern AIDE support regular gradle structured projects. See  https://github.com/Deepscorn/libgdx-gradle-template

# How it works
You have regular gradle LibGdx project in Android Studio / IDEA on desktop. You run gradle task to generate eclipse ant project files (.project + .classpath). They are used instead of build.gradle in AIDE.

It's an example to article http://deepscorn.blogspot.ru/2016/07/building-and-running-android-studio.html
