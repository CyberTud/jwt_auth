# Getting Started

### What is this?

This is the repository for my homework on java unit testing from the Java Spring Advanced course.

### Homework requirements

* Create a Spring Boot project and design (code) an API for a Market (users have a cart, and add and remove products, 
  each user has an id, and also a Wishlist, no need to implement a login system; create all CRUD operations for Users, Cart and Wishlist, use H2 (in-memory) as a database)
* Create unit tests for it
* Please make sure to implement all those things, and meet the deadline
* Comments would be a nice addition 

Please make sure to have the extra endpoints:

* An endpoint where i can get all the carts from all the users, sorted by the total of the products (a product must 
have a name, price and a quantity)
* An endpoint where i can get all the users sorted by their number of orders (users will also have order history, 
  make sure to implement it)

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.6.6/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.6.6/maven-plugin/reference/html/#build-image)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/2.6.6/reference/htmlsingle/#boot-features-jpa-and-spring-data)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.6.6/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides

The following guides illustrate how to use some features concretely:

* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

