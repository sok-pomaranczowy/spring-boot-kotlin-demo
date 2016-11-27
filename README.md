# Spring Boot Kotlin sample project

This is the source code for the a sample Spring Boot application developed with Kotlin and Spring Data JPA. 

You can launch the application with by running:

		$ ./gradlew bootRun

This project uses a [Kotlin based Gradle](https://blog.gradle.org/kotlin-meets-gradle) configuration.
Make sure you have at least IntelliJ IDEA 2016.2.5 and Kotlin plugin 1.1-M02 to have
`build.gradle.kts` auto-complete and validation working correctly. You may have to
configure the EAP update site in:
Tools -> Kotlin -> Configure Kotlin Plugin Updates -> Early Access Preview 1.1

This project is Apache 2.0 licensed.

My fork fiexed some problems that I had with running this application using gradle.
