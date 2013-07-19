This repo is forked from mgryszko.
His Presentation URL: http://www.slideshare.net/mgryszko/android-tdd-ci

I'll use this as my playground to do TDD in Android.

Android Maven Project
=====================

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

I removed licence.txt from the jars. and I did <code>mvn install:install-file</code> to install those three jars in my local.

Chirp Server on Grails
======================

And I just notice that it uses Grails for the server. So, you need to install Grails (1.3.7) if you want to run it.
I'm running on windows so I don't use its <code>chirp-server.sh</code>.
I just set GRAILS_HOME to where I copy grails-1.3.7 distribution and run <code>chirp-server.bat</code>

Note
====

I'm still in progress of understanding what this Android project does. :D

So, feel free to give me feedback or suggest better solutions.


