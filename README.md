# Phoenix Airline PVT <img src="https://github.com/lakshithaonline/Phoenix-Airline-MVP-Project/blob/main/phoenix-colorful-logo-vector_557569-218%20copywwww%20copy.png"  width="100" height="45" style="padding-left: 20px;">

<a href="https://github.com/harismuneer"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=lakshithaonline&style=flat-square" width="125"/></a>
[![Welcome](https://img.shields.io/badge/NSBM%20Green%20University-Welcome-brightgreen)](#)

Web-based fully responsive Flight Booking System for Phoenix Airline based on the Model View Controller (MVC) Architecture made using Java Servlets and Java Server Pages. Moreover, authentication and authorization for users are implemented using GlassFish Roles. The web application is also secured against SQL Injection and Cross-Site Scripting attacks.



Phoenix Airline PVT is an airline with a small online flight booking system.  So the application has ticket booking and many more facilities,


# Technologies Used

* **Frontend**: HTML, CSS, JavaScript, Jquery, Bootstrap, Java Server Pages (JSPs)
* **Backend**: Java Servlets, Java Models, mySQL (Database)
* **Security Features**: SQL Injection, Cross-Site Scripting (XSS), Glassfish roles


# Roles

* Public Customer 
* Airline Staff
* Airline Admin 

# Workflow (Functionalities)

Phoenix-Airline is a multifunctional web application that customers can use to book a flight and search & find flights without booking a ticket. 

Following are the steps of work flow:

1. Airline Admin will add & can approve the airline management staff.
2. There are two types of staff categories:

   Staff members need to register on the system using the staff registration form, and Staff can log in using a registered    email password after the admin approves and selects the staff grade. 
      * Grade one Staff (G1)
          - G1 Staff can view, update and delete user information & flight section, and booking section 
      * Grade two Staff (G2)
          - G2 Staff can view information and only add new flight details
3. Public users can't enter the system without registration on the system, so the user needs to register and log in using the registered user name and email. 

4. After login into the system public user can book a ticket for a flight, and without booking user can search or find flight details like arrival and departure date/time and user can view the reserved ticket list in the profile section and also can update profile details & contact the airline management to clarify anything about Phoenix-Airline
   
5. Ticket Booking procedure 
   The user needs to select the type (compulsory)
      * Return trip
      * One Way
      
   The airline system has three flight ticket categories 
      * Economical 
      * Business
      * First Class

   A single per user can book flight tickets for up to 10 people. 
      * 18+ Adult 
      * 17- Chilled 

6. Find Flight procedere 
   user can find the booked flights or without booking user can view flight details and find. There is two types for find      flight
      * Find flight using Tikect ID
      * Find flight selecting From/To


# Interface - Public user

* Login & Registrations 
* Home Page - user's Dashboard 
* Book a flight
* Flight Status
* Profile

# Interface - Staff

* Login & Registrations 
* Staff Dashboard
* User Account
* flights

# Interface - Admin

* Login & Registrations 
* Admin Dashboard
* User Account

# How to run

1- Install these:

* Java SE Development Kit 8 (JDK 8)
* After installing JDK 8, install NetBeans IDE with all the features including GlassFish Server.

2. Download and unzip the project and open it in Netbeans





