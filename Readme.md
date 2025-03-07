# Health Care Portal

## Description
The **Health Care Portal** is an integrated web-based platform that connects patients, doctors, and pharmacies to streamline healthcare delivery. It provides secure access to personal medical history and enables appointment scheduling. This project aims to improve patient outcomes, enhance efficiency, and modernize healthcare services by giving users greater control over their health information and access to care.

## Features
- Secure access to personal medical history
- Appointment scheduling for patients
- Medical record sharing between patients and doctors
- User authentication for patients, doctors, and admins
- Improved healthcare service management

## Technologies Used
### **Frontend (React Native)**
- **React Native CLI or Expo** – Framework for building mobile applications
- **Node.js** – Required for JavaScript runtime and npm package management
- **npm** – Package manager for installing dependencies
- **Visual Studio Code** – Code editor for writing React Native code

### **Backend (Java with Spring Boot)**
- **Spring Boot** – Framework for building Java-based enterprise applications
- **Maven or Gradle** – Build tools for managing Java projects
- **PostgreSQL JDBC Driver** – Enables Java applications to connect to PostgreSQL
- **Hibernate** – ORM framework for database interactions
- **Spring Data JPA** – Simplifies data access with JPA
- **Spring Security** – Manages authentication and authorization
- **JUnit & Mockito** – Testing frameworks for unit testing

### **Database (PostgreSQL)**
- **PostgreSQL Database** – Open-source relational database management system
- **pgAdmin** (Optional) – Graphical tool for managing PostgreSQL

## Installation & Setup
### **1. Set Up React Native Environment**
1. Install Node.js and npm from [Node.js official site](https://nodejs.org/en)
2. Create a React Native project:
   ```sh
   npx create-react-app my-react-app
   ```
3. Navigate to the project directory:
   ```sh
   cd my-react-app
   ```
4. Start the React app:
   ```sh
   npm start
   ```
5. Open a browser and go to `localhost:3000` to view the app.

### **2. Set Up Spring Boot Project in Eclipse IDE**
1. Install Eclipse IDE for Enterprise Java and Web Development
2. Create a Spring Boot project using [Spring Initializr](https://start.spring.io/)
3. Import the Spring Boot project into Eclipse:
   - Search for "Maven"
   - Choose **Existing Maven Project**
   - Click **Next**
   - Browse and select the extracted project folder
   - Click **Finish**

### **3. Set Up PostgreSQL Database Using pgAdmin**
1. Log in to PostgreSQL using **pgAdmin**
2. Right-click **Databases** and select **Create > Database**
3. Enter the database name and select an owner
4. Click **SQL** tab to view the SQL statement
5. Click **Save** to create the database
6. Alternatively, use SQL command:
   ```sql
   CREATE DATABASE healthcare_db;
   ```

## Conclusion
A healthcare portal is a valuable tool for managing healthcare efficiently. It enables users to securely access medical records, schedule appointments, and communicate with healthcare providers. Ensuring ease of use, security, and continuous updates can make the portal an essential asset in modern healthcare systems.
