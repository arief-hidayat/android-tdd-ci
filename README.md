This repo is forked from mgryszko.
His Presentation URL: http://www.slideshare.net/mgryszko/android-tdd-ci

I'll use this as my playground to do TDD in Android.

Maven
=====

This is maven-based project. So, you'll have the following installed:

* JDK + Android SDK
* Maven
* Android SDK Deployer. https://github.com/mosabua/maven-android-sdk-deployer

I use Android SDK deployer to use android version that's not available in Maven repository.
Another things that need to be installed manually is the hamcrest.

What I did is that I download all three hamcrest jars from

 * http://mvnrepository.com/artifact/org.hamcrest/hamcrest-core
 * http://mvnrepository.com/artifact/org.hamcrest/hamcrest-library
 * http://mvnrepository.com/artifact/org.hamcrest/hamcrest-integration

I remove licence.txt from the jars. and I do <code>mvn install:install-file</code>

Note: that I'm still in progress of understanding what this Android project does. :P
So, feel free to give me feedback or suggest better solutions.


