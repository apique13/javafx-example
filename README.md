# javafx-example
Simple example of a JavaFX minimal application

# Requirements
You needs :
* Gradle in your PATH : set PATH=%PATH%;C:\Applications\gradle-8.10.2\bin  (Source : https://gradle.org/install/)
* Java with JavaFX (use a zulu with JavaFX JDK) : set JAVA_HOME=N:\dev\zulu17.54.21-ca-fx-jdk17.0.13-win_x64 (source https://www.azul.com/downloads/?version=java-17-lts&architecture=x86-64-bit&package=jdk-fx#zulu)
* Wix v3 installed : source https://wixtoolset.org/docs/wix3/  (they removed candle an light from last wix version)

# Run the test :
gradle run

# Make install package :
gradle jpackage
