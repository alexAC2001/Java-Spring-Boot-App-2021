# Java Spring Boot Web Application

This was a project I created at Grand Canyon University in fall of 2021. It is a website called Albums4You, where users can view a list of albums, each with their own songs. All albums can be edited, deleted, and new ones can be created. Albums are stored and managed in MongoDB.  

![image](https://user-images.githubusercontent.com/62003762/147712792-b3b653ec-4c2d-422b-8aa5-9312a5c7eb17.png)

# Frameworks

I learned the following frameworks when creating this project:

•	Spring Boot

• Spring MVC

• Spring Core

• Spring Data JDBC

• Spring Data MongoDB

• Spring Security

# Spring Security Configuration

Here is a simple method from the Security Config file. The file is needed to support Spring Security to secure the entire web application. This method auto wires an instance of AuthenticationManagerBuilder, enabling Web Security. A password is encrypted using BCrpytPasswordEncoder from the Spring Security framework. The password is authenticated with the userDetailsService and the passwordEncoder.

![image](https://user-images.githubusercontent.com/62003762/147713104-4773bd0d-2c34-4f5b-9083-124981b3e399.png)

The user must input a password that exists in MongoDB. The password must also be correctly linked with the username. In MongoDB, the password is encrypted to provide further security

![image](https://user-images.githubusercontent.com/62003762/147713528-38332abb-2ef0-498b-ba81-6a767fcf053c.png)


# Dependency Injection



****
