#Reading Class 11

1- What role do the @Controller classes play in a Spring MVC application?

- Handle HTTP requests

---

2- Explain to a non-technical friend what a GET request is.

- To browse internet , your web browser sends a special request to the server where that webpage is stored,That request is called a "GET request." It's one of the most common types of requests on the internet. When your browser sends a GET request, it's asking the server to send back a specific webpage or piece of information.

----
3- What annotation should be placed on your Spring Boot application class?

- @Controller annotation to identify the controller
- @GetMapping annotation ensures that HTTP requests are mapped.
- @SpringBootApplication annotation that adds :
  - @Configuration: Tags the class as a source of bean definitions for the application context.

   - @EnableAutoConfiguration: Tells Spring Boot to start adding beans based on classpath settings. 

  - @ComponentScan: Tells Spring to look for other components, configurations, and services. 

---

4- What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?

- displayVariable in Spring Controller
---

5- Explain the role of a @Controller class in a Spring MVC application.

- Request Handling,Model Preparation, View Resolution, Request-Response Flow, also HTTP Response.

---

6- What is a model attribute refered to in Thymeleaf?

- Pieces of data that can be accessed during the execution of views and  made available in the template from a controller