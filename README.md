# 06 Tutorial: MySql and Spring
## Connect mysql and Spring Boot Applications with each other

1. Create a [new application](https://github.com/Dat17i/03_hello_spring/blob/master/README.md) using the Spring Boot Initializer.

When choosing the dependencies you should now also add the **SQL -> MySql** dependency.    
So you will now have these 3: 
 
* Web -> Web
* Template Engines -> Thymeleaf
* **SQL -> MySql**
  

This will add the folowing dependency to you pom.xml file

````   
  <dependency>
	<groupId>mysql</groupId>
	<artifactId>mysql-connector-java</artifactId>
	<scope>runtime</scope>
  </dependency>
````
If you have an existing application without the mysql dependency added from the beginning, you can always write this directly into the pom.xml file. 



