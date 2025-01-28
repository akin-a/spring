# Spring

## Before Spring?

- Java EE ([javaEEvsSE](https://github.com/akin-a/java/blob/main/fundamentals/JavaSEvsEE.md)) is what predominently used in enterprise world before Spring.
- Major components of Java EE
   - **Servlets & JavaServer Pages (JSP)** : powerful Java components that manage requests and responses in a web application
   - **JavaServer Faces (JSF)** : component-based UI framework that streamlines the creation of user interfaces for Java EE applications
   - **Enterprise JavaBeans (EJB)** : server-side component architecture used to encapsulate business logic of an application
   - **Java Persistence API (JPA)** : JPA simplifies the management of relational data through high-level Object-Relational Mapping (ORM) capabilities and Java Persistence Query Language.
   - **Java Message Service (JMS)** : provides a reliable, flexible service for exchanging data and events asynchronously
   - **Etc**
- In its early days (J2EE 1.4) programming model of enterprise edition of Java had a lot of flaws and deficiencies, but the most important ones were that it was tedious and verbose with a lot of boiler-plate code and tons of xml configurations.
- Spring was introduced as an alternative framework favoring convention-over-configuration principle. In other words, in Spring there were some **sensible defaults** that could be reconfigured if you need it.
-  Java EE 5 introduced significant changes adopting the same convention-over-configuration principle from Spring (dependency injection concepts introduced later in Java EE after spring's introduction)
-  Java EE is just a specification. To build a real world app you need an implementation and there are plenty of them today - Glassfish, JBoss, TomcatEE,etc.
-  But one area where Java EE still lacks behind Spring is comfortable testability. It is not easy to write unit tests for EJB.
