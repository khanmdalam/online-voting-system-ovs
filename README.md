# online-voting-system


# Application Features:

* User can vote the Candidate.
* Admin has the permission to see the vote details.


# Technology used in this Project:
(i) Thymeleaf,CSS : designing page layout.
(ii) Java : all the logic has been written in java.
(iii) MySQL: MySQL database has been used as database.
(iv) SpringSecurity: SpringSecurity has been used for authentication.
(v) Hibernate: Hibernate ORM is used.


# Software And Tools Required:
Java JDK 8+
Eclipse EE or Spring Tool Suite
MySQL

 # Steps To Import And Run The Project in Eclipse EE
In Eclipse or Spring Tool Suite

Click on File

Select Import

Select Projects from Git(with smart import) -> Next

Select Clone URI -> Next

In URI paste this url: https://github.com/khanmdalam/online-voting-system-ovs -> Next

Now in Local Destination

proceed -> Next

     Now only select VotingApp\MySpring_Boot_aa23v_VotingApp_Final
     -> Finish
If everything goes right Project will get successfully imported

Now wait for few seconds for getting things properly loaded

Now open Project > src/main/resources > open application.properties file, inside this file look for

spring.datasource.url=jdbc:mysql://localhost:3306/springbootnew?serverTimezone=UTC

here "springbootnew" is the name of the database.

so


# create database name "springbootnew" in MySQL.
or

(you can also create the database with different name in MySQL. but the created database name in MySQL should match the database name in url in application.properties file. so according to created database in MySQL set the database name in url in application.properties file.

Now save the changes.)
And Try to Run the Project

If you are using Spring Tool Suite
Right Click On Project > Run As > Spring Boot App


# Some Screenshots of this Project:


![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a1.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a2.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a3.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a4.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a5.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a6.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a7.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a8.png)
![image ait](https://github.com/khanmdalam/online-voting-system-ovs/blob/main/a9.png)

