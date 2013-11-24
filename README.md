# Ensemble

Ensemble is a set of [samples](http://www.oracle.com/technetwork/java/javafx/samples/index.html) for JavaFX 2. Unfortunately, it is only available as a NetBeans project, and through an Ant build.

This project is a port of Ensemble to Maven so that IntelliJ IDEA and Eclipse users can also play with JavaFX.

## Fix classpath issue

JavaFX is included in the JRE but on the classpath. Run the following to fix it:

    sudo mvn com.zenjava:javafx-maven-plugin:2.0:fix-classpath

