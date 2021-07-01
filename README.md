# java-avanzado
Advanced Java SE Course

# Java SE Object Oriented
OOP Course Java SE

## Table of contents

* [General info](#general-info) 
* [Technologies](#technologies) 
* [Setup](#setup)
<!-- * [Concepts](#concepts) -->

## General info

On this course I learned more about abstract and annonymous classes. Also, that we can have nested classes, useful for some logics (such as Album -> Song, where song is only used in Album). 

We reviewed interfaces and abstract classes, seen in the previous course, and implemented examples on our project.

Another thing I learned was how to manage exceptions and errors using try-catch and try-with-resources. We also saw how to work with a database and implement CRUD actions using JDBC API.

The last things we saw on the course was functional interfaces and how to use lambda functions in out proyect. These functions have a short life, however they are very useful and help to minimize the code. We used some in our proyect alongside stream and filter methods.


[JavaDoc](https://lourdesnrdz.github.io/java-avanzado/JavaDoc/index.html)

## Technologies

On this course I used the following development technologies:
 <!-- - Visual Studio Code -->
 - Git
 - Github
 - IntelliJ IDEA 2021 1.2
 - OpenJDK 11

## Setup

The setup for this project was made on a Windows 10 OS.

### IntelliJ IDEA

1. Go to [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)
2. Download the Community version (Free, built on open source)

### OpenJDK
For this course we used 2 versions of OpenJDK.

1. Go to [https://adoptopenjdk.net/](https://adoptopenjdk.net/)
2. Download the following versions:
    - OpenJDK 8
    - OpenJDK 11

### XAMPP and MySQL Connector
We needed a phpmyadmin server for the proyect. To access this we installed XAMPP, following:
1. Go to [https://www.apachefriends.org/es/index.html](https://www.apachefriends.org/es/index.html) 
2. Once installes open XAMPP and start the MySQL server and Apache Web Server.
3. One both services are inicialized, go to [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)
4. Add a User Account named **amazonviewer**
5. Import the following [database](https://drive.google.com/file/d/1uneLZrRZ0y1ASOUkVzzw7qRQwrS0Ui-d/view?usp=sharing)
6. After this download the [MySQL Connector](https://dev.mysql.com/downloads/connector/j/5.1.html)