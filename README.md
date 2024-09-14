Event Management System

Project Overview
Event Management System is a web-based platform designed to facilitate the management and participation in various events. It provides three distinct roles:

Organizers: Can create and manage events, venues, and resources.

Users: Can browse, book, and pay for events.

Admins: Oversee the system, managing users, venues, events, and bookings.

This system leverages Angular for the frontend and Node.js with Java Spring Boot for the backend, offering a responsive and secure experience for all users.

Features

Organizer Features:

Account Creation & Login: Organizers can securely register and log in
.
Manage Venues & Events: Add, update, and manage events and venues.

View Bookings: Check upcoming bookings and booking history.

Manage Resources: Add food items and equipment for events.

Notifications: Receive real-time updates about bookings and events.

Profile Management: Manage organizer's profile information.

User Features:

Account Creation & Login: Users can register and log in to the system.

Browse Venues & Events: Explore available venues and events.

Event Booking: Book events and venues, make payments, and receive booking confirmations.

Check Availability: Check the availability of venues and events before booking.

Booking History: View past bookings and their payment status.

Notifications: Receive real-time notifications related to bookings and events.

Profile Management: Manage personal details and account information.

Admin Features:

Manage Users: View and manage profiles of all organizers and users.

Manage Venues & Events: Admins oversee venues and events created by organizers.

View All Bookings: Access and manage booking records.

System Oversight: Full control over system operations to ensure smooth event management.

Project Architecture & Design


Frontend (Angular):
The frontend is developed using Angular, which provides:

Single Page Application (SPA): Fast and seamless user experience.
Component-based Architecture: Ensures code reusability and maintainability.
Routing: For smooth navigation between application sections.
Forms & Validation: Secure and error-free user input for account creation, bookings, and payments.
HTTP Client: For interacting with backend APIs and ensuring smooth communication.




Backend (Node.js & Spring Boot):
The backend is developed using a combination of Node.js and Java Spring Boot, ensuring:

API Endpoints: RESTful APIs to manage CRUD operations for events, venues, bookings, and notifications.
Authentication: JWT-based secure access for all roles (Organizers, Users, Admins).
Password Hashing: Using bcryptjs for password encryption to enhance security.
Database Design


MySQL Database: Stores data for users, events, venues, bookings, and notifications.
Sequelize ORM: Used for database operations in Node.js.



Spring Boot JPA: Integrates with MySQL to handle business logic and data operations.

Key Database Tables:
Users: Stores details for organizers, users, and admins.
Events: Stores event information, linked to venues and organizers.
Bookings: Manages event booking records with references to users and events.
Notifications: Stores real-time notifications sent to users and organizers.

Technologies Used

Frontend:
Angular: For developing a dynamic and interactive user interface.


Backend:
Node.js & Express.js: For managing event-related functionalities and API endpoints.
Spring Boot: Java-based framework to handle core business logic and backend operations.
Additional Tools:
Sequelize ORM: For MySQL database operations in Node.js.
JWT: Secure user authentication.
bcryptjs: Password encryption.
Postman: For testing backend API endpoints.
Core Functionalities
Event Management: Organizers can create, update, and delete events.
Booking System: Users can book events and venues, check availability, and view booking history.
Notifications: Real-time notifications for users and organizers.
Secure Authentication: JWT-based authentication for all users.
Profile Management: Manage user, organizer, and admin profiles.


Setup Instructions

Prerequisites
Node.js and npm installed
Java 11 or later installed for Spring Boot
MySQL database setup
Angular CLI installed
Steps to Run the Project
Backend (Node.js + Spring Boot)

Clone the repository:

Clone the repository:

git clone https://github.com/SRIDHARAN1819/EVENT-MANAGEMENT-SYSTEM.git

Navigate to the backend directories for both Node.js and Spring Boot.

For Node.js backend:

npm install

npm start

For Spring Boot backend:

cd backend-springboot


Build and run the application:
./mvnw spring-boot:run


Here is a sample README.md file that you can use for your Online Event Management System project on GitHub based on the problem statement you've provided:

Online Event Management System
Project Overview
The Online Event Management System is a web-based platform designed to facilitate the management and participation in various events. It provides three distinct roles:

Organizers: Can create and manage events, venues, and resources.
Users: Can browse, book, and pay for events.
Admins: Oversee the system, managing users, venues, events, and bookings.
This system leverages Angular for the frontend and Node.js with Java Spring Boot for the backend, offering a responsive and secure experience for all users.

Features
Organizer Features:
Account Creation & Login: Organizers can securely register and log in.
Manage Venues & Events: Add, update, and manage events and venues.
View Bookings: Check upcoming bookings and booking history.
Manage Resources: Add food items and equipment for events.
Notifications: Receive real-time updates about bookings and events.
Profile Management: Manage organizer's profile information.
User Features:
Account Creation & Login: Users can register and log in to the system.
Browse Venues & Events: Explore available venues and events.
Event Booking: Book events and venues, make payments, and receive booking confirmations.
Check Availability: Check the availability of venues and events before booking.
Booking History: View past bookings and their payment status.
Notifications: Receive real-time notifications related to bookings and events.
Profile Management: Manage personal details and account information.
Admin Features:
Manage Users: View and manage profiles of all organizers and users.
Manage Venues & Events: Admins oversee venues and events created by organizers.
View All Bookings: Access and manage booking records.
System Oversight: Full control over system operations to ensure smooth event management.
Project Architecture & Design
Frontend (Angular):
The frontend is developed using Angular, which provides:

Single Page Application (SPA): Fast and seamless user experience.
Component-based Architecture: Ensures code reusability and maintainability.
Routing: For smooth navigation between application sections.
Forms & Validation: Secure and error-free user input for account creation, bookings, and payments.
HTTP Client: For interacting with backend APIs and ensuring smooth communication.
Backend (Node.js & Spring Boot):
The backend is developed using a combination of Node.js and Java Spring Boot, ensuring:

API Endpoints: RESTful APIs to manage CRUD operations for events, venues, bookings, and notifications.
Authentication: JWT-based secure access for all roles (Organizers, Users, Admins).
Password Hashing: Using bcryptjs for password encryption to enhance security.
Database Design
MySQL Database: Stores data for users, events, venues, bookings, and notifications.
Sequelize ORM: Used for database operations in Node.js.
Spring Boot JPA: Integrates with MySQL to handle business logic and data operations.
Key Database Tables:
Users: Stores details for organizers, users, and admins.
Events: Stores event information, linked to venues and organizers.
Bookings: Manages event booking records with references to users and events.
Notifications: Stores real-time notifications sent to users and organizers.
Technologies Used
Frontend:
Angular: For developing a dynamic and interactive user interface.
Backend:
Node.js & Express.js: For managing event-related functionalities and API endpoints.
Spring Boot: Java-based framework to handle core business logic and backend operations.
Additional Tools:
Sequelize ORM: For MySQL database operations in Node.js.
JWT: Secure user authentication.
bcryptjs: Password encryption.
Postman: For testing backend API endpoints.
Core Functionalities
Event Management: Organizers can create, update, and delete events.
Booking System: Users can book events and venues, check availability, and view booking history.
Notifications: Real-time notifications for users and organizers.
Secure Authentication: JWT-based authentication for all users.
Profile Management: Manage user, organizer, and admin profiles.
Setup Instructions
Prerequisites
Node.js and npm installed
Java 11 or later installed for Spring Boot
MySQL database setup
Angular CLI installed
Steps to Run the Project
Backend (Node.js + Spring Boot)

For Node.js backend:

Install dependencies:
bash
Copy code
cd backend-nodejs
npm install
Set up the .env file for database and JWT configurations.
Start the server:
bash
Copy code
npm start
For Spring Boot backend:

Navigate to the Spring Boot project directory:
bash
Copy code
cd backend-springboot
Build and run the application:
bash
Copy code
./mvnw spring-boot:run


Frontend (Angular)
Navigate to the frontend directory:

npm install

ng serve

