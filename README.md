# From http://spring.io/guides/gs/gradle/

I changed all the urls to not use https or you will have an error running gradle.

For example:
http://stackoverflow.com/questions/29576871/cant-build-android-app-with-gradle

-from:

distributionUrl=https\://services.gradle.org/distributions/gradle-2.3-all.zip
-to:

distributionUrl=http://services.gradle.org/distributions/gradle-2.3-all.zip


## Gradlew
gradlew is for running the project without having gradle installed in your system.

