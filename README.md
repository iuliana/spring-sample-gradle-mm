spring-sample-gradle-mm
=======================

This is the gradle version of the spring-sample project. It is a gradle multi-module project.
It has two modules: dao and web. Configurations for the modules is very simple as the dependencies are all defined in the 
misc, hibernate and spring arrays in the build.gradle file.


Steps to run:

1.Install Java 8 and set JAVA_HOME environment variable

2.Install Gradle 2.x.x and set GRADLE_HOME environment variable (I use a standalone Gradle local instance to build all my projects, I do not like the Gradle wrapper very much.

3.Install Tomcat 8

4.Download and install an IDE (I recommend Intellij Idea)

5.Run "gradle war"

6.In web/build/libs you will find your war: web-1.0.war. Deploy this war on your Tomcat installation (by copying it under CATALINA_HOME/webapps or use your editor to deploy it by creating a Tomcat Launcher.

8. Go to http://localhost:8080/sample and test it.

7.Start adding your own stuff.

Enjoy!