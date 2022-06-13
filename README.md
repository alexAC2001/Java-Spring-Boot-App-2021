# Java Spring Boot Web Application

This was a collaborative project created at Grand Canyon University in fall of 2021. It is a website called Albums4You, where users can view a list of albums, each with their own songs. All albums can be edited, deleted, and new ones can be created. Albums are stored and managed in MongoDB.  

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

Here is a simple example from my project where I performed Dependency Injection, or specifically constructor injection. in the AlbumDataService constructor, I injected albumsRepository as a parameter. It was then set equal to albumsRepository.

![image](https://user-images.githubusercontent.com/62003762/147713766-245cb8e3-c11d-4a7d-84e6-d8362f10996c.png)

# Diagrams

Creating diagrams for any application is important to plan on what the project will look like and how it will get accomplished.
****
Here is a Wireframe Design (User Interface Diagram) I created.

![image](https://user-images.githubusercontent.com/62003762/147714458-0a04a306-50a2-42ed-a75e-6e5e0ee50f0f.png)
****
Here is the Sitemap Diagram for the project.

![image](https://user-images.githubusercontent.com/62003762/147714618-2378846c-28cb-49f6-ae3c-517696dec19c.png)
****
Here is a snippet of the UML Class Diagram, showing the relationship between Business Services Layer and the Controllers.

![image](https://user-images.githubusercontent.com/62003762/147714733-5fb6537c-fa00-43ce-859d-9015ae3cd825.png)
****
Here is the ER Diagram.

![image](https://user-images.githubusercontent.com/62003762/147715031-af8a0054-3679-416e-b7d0-b3c645db6273.png)
****

# Test Cases

Test cases were created for this project to ensure the application performed as expected. Heres are examples of a test cases used for testing REST APIs, Spring Security and custom exceptions.

![JavaSpringBootTestCaseExamples](https://user-images.githubusercontent.com/62003762/173452802-3dbd4085-5aeb-480a-9de3-f54de89f45a9.png)

# Conclusion

Throughout the process of creating this project, I learned many new technologies, frameworks, and design patterns that helped me become proficient at creating Spring Boot applications Java as the main programming language, and HTML with CSS as the front-end languages. Spring Boot has become one of my favorite frameworks to work in.
