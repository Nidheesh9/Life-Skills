# Spring Framework
The Spring Framework is a lightweight Java framework widely used for building scalable, maintainable enterprise applications. It offers a comprehensive programming and configuration model for Java-based development.

A key element of Spring is infrastructural support at the application level: Spring focuses on the "plumbing" of enterprise applications so that teams can focus on application-level business logic, without unnecessary ties to specific deployment environments.

# MVC Architecture
MVC (Model-View-Controller) architecture is a universal pattern in which an application is divided into three parts that handle specific responsibilities. This pattern is commonly used to create organized and easy-to-maintain code. Here’s a closer look at each component:

![MVC architecture diagram](./MVC-Architecture.webp)

* **Model:** It is worth stating that the Model stands as the data layer for the application. It is directly involved in managing the data as well as the control of the application’s logic and rules.
* **View:** The View is in the presentation tier. It plays a role of presenting the information given by the Model to the user and transferring the user commands to the Controller. The View is used to display the data to the user in a readable and manageable way using the interface created by the Controller.
* **Controller:** The Controller CE works in the middle between the Model and the View. It takes the input from the View, sometimes modifies it with the help of the Model, and sends it back to the View. the results back to the View.

# References

* https://www.geeksforgeeks.org/advance-java/introduction-to-spring-framework/
* https://spring.io/projects/spring-framework
* https://www.geeksforgeeks.org/system-design/mvc-architecture-system-design/