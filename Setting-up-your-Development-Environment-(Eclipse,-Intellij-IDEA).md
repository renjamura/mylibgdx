Libgdx projects use [Gradle](http://www.gradle.org/) to manage dependencies, the build process, and IDE integation. This allows you to develop your app with whatever development environment you prefer. Best of all: your team mates can use a different dev environment while working on the same project! Just don't commit your IDE specific files to your source control. The `.gitignore` file contained in libgdx projects will take care of that if you use Git.

### Setting up Eclipse 
To develop your application via Eclipse, you need to install the following pieces of software.

  * [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
  * [Eclipse](http://www.eclipse.org/downloads/), the "Eclipse IDE for Java Developers" is usually sufficient.
  * [Android SDK](http://developer.android.com/sdk/installing.html), you only need the SDK, not the ADT bundle, which includes Eclipse. Install all platforms via the SDK Manager!
  * [Android Development Tools for Eclipse], aka ADT Plugin. Use this update site: https://dl-ssl.google.com/android/eclipse/
  * [Eclipse Integration Gradle](https://github.com/spring-projects/eclipse-integration-gradle/), use this update site: http://dist.springsource.com/release/TOOLS/gradle

To additionally target iOS

  * A Mac, iOS Development does not work on Windows/Linux thanks to Apple.
  * The latest XCode, which you can get from the Mac OS X App Store for free
  * [RoboVM](http://www.robovm.com/docs#robovm-for-eclipse), simply install the Eclipse plugin. Make sure to update the plugin frequently!

Once all of these tools are installed, proceed to [Project Setup](https://github.com/libgdx/libgdx/wiki/Project-setup%2C-running-%26-debugging)

### Setting up Gradle
To develop your application via Eclipse, you need to install the following pieces of software.

  * [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
  * [Intellij IDEA 13+](http://www.jetbrains.com/idea/download/), the Community edition is sufficient
  * [Android SDK](http://developer.android.com/sdk/installing.html), you only need the SDK, not the ADT bundle, which includes Eclipse. Install all platforms via the SDK Manager!

To additionally target iOS

  * A Mac, iOS Development does not work on Windows/Linux thanks to Apple.
  * The latest XCode, which you can get from the Mac OS X App Store for free

Once all of these tools are installed, proceed to [Project Setup](https://github.com/libgdx/libgdx/wiki/Project-setup%2C-running-%26-debugging)