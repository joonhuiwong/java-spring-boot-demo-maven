# Spring Boot Basics

This is the project of myself following along the video tutorial explained in: https://www.youtube.com/watch?v=vtPkZShrvXQ

The tutorial teaches you (in rough order, updated as I go along with the lesson):
- The structure of a Spring Boot application (using REST API in particular)
- How to use Spring Initializer to kickstart a Spring Boot project.
    - We just started with Spring Web, which has embedded Tomcat server.
    - This allows us to import the project in IntelliJ Community Edition, which has Spring Boot and Tomcat support locked behind the Ultimate Edition paywall.
    - For learning purposes, we will stick to free solutions until we are at least adept enough to make cost-efficient use of the paid features.
- How to create a simple REST API:
    - Model, Dao, API, Service. Recurring concepts similar to other stuff we may have learnt like RoomDatabase & Retrofit2, but the terms Service and Controller were new for me at least (in this context).
  
- How to create a JAR using Maven

----

Notes:
- Had to also add `spring-boot-starter-validation` to pom.xml dependency as it's no longer included in the web starter.
- Seems like the error messages are different than the demo.
- The video is from 2019, a lot of things have changed. So I'll go do another tutorial guide with more up to date information.