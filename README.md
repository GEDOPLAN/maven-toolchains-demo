# maven-toolchain-demo

This project demonstrates the use of different JDKs for building a maven project.

The pom.xml contains a property named java.version. It can be set to any JDK version string contained in
toolchains.xml (normally located in ~/.m2).
A sample file - sample-toolchains.xml - is provided here. Just copy it to your .m2 folder and rename it
into toolchains.xml.

A demonstration build can be started by the command "mvn compile". The compiler plugin will log the
JDK used.

More info can be found in:
* http://maven.apache.org/plugins/maven-toolchains-plugin/
* https://maven.apache.org/guides/mini/guide-using-toolchains.html 