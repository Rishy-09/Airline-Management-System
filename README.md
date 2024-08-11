# Airline Management System

## Table of Contents
- [Introduction & Overview](#introduction--overview)
- [Project Structure](#project-structure)
- [API Reference](#api-reference)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Deployment](#deployment)
- [Demo](#demo)
- [Documentation](#documentation)
- [Related Projects](#related-projects)
- [Acknowledgements](#acknowledgements)
- [Authors](#authors)
- [Badges](#badges)
- [Appendix](#appendix)

## Introduction & Overview
The Airline Management System is an advanced application designed to streamline and manage various operations within an airline company. It includes functionalities such as booking flights, managing customer data, and generating boarding passes. The application is built using Java Swing for a user-friendly graphical interface and integrates with a MySQL database for data persistence.

The system provides a comprehensive solution for airline management, allowing users to easily interact with and manage flight and customer information. The intuitive interface and backend connectivity ensure smooth operation and effective management of airline operations.

## Project Structure
The project consists of the following main folders and files:

### `airline.management.system`
- **AddCustomer**: Manages the addition of new customer information.
- **BoardingPass**: Generates and manages boarding passes.
- **BookFlight**: Handles flight booking processes.
- **Cancel**: Manages the cancellation of flight bookings.
- **FlightInfo**: Provides information about available flights.
- **Conn**: Connects the application to the MySQL database.
- **Home**: Serves as the main user interface.
- **JourneyDetails**: Displays details of the journey.
- **Login**: Manages user authentication and login.

### `Icons`
Contains various JPEG and PNG files used for the graphical interface of the application.

## API Reference
The project utilizes the following Java packages:
- `javax.swing.*`: For creating and managing the graphical user interface.
- `java.awt.*`: For various AWT components and functionalities.
- `java.awt.event.*`: For handling user events and interactions.

## Prerequisites
- **Java JDK 21**: Required for compiling and running the project.
- **MySQL Workbench**: For managing the database.
- **JAR Files**:
    - `rs2xml.jar`
    - `mysql-connector-java-8.0.28.jar`
    - `jcalendar-tz-1.3.3-4.jar`

## Installation

To set up the Airline Management System on your local machine, follow these steps:

1. **Clone the Repository**: Clone the repository to your local machine using Git:
   ```bash
   git clone https://github.com/Rishy-09/Airline-Management-System


**Navigate to the Project Directory**: Change to the project directory:
   ```bash
   cd Airline-Management-System
```
2. **Install Java Development Kit (JDK)**: Ensure that Java JDK 21 is installed on your machine. If not, download and install it from the [Oracle JDK Downloads](https://www.oracle.com/java/technologies/javase-downloads.html) page.


3. **Set Up MySQL Database**:
    - Install MySQL Workbench if it is not already installed.
    - Create a database for the project and configure the connection details in the `Conn` class.
    - Import any necessary SQL scripts into the database to set up tables and initial data.


4. **Add JAR Files**: Place the following JAR files in the `lib` directory of your project or include them in your project's classpath:
    - `rs2xml.jar`
    - `mysql-connector-java-8.0.28.jar`
    - `jcalendar-tz-1.3.3-4.jar`


5. **Open the Project in Your IDE**: Open the project in an Integrated Development Environment (IDE) such as IntelliJ IDEA.


6. **Build and Run the Project**:
    - Compile the project using your IDE’s build tools.
    - Run the main class to start the application.


7. **Verify Configuration**: Ensure that the application is correctly connected to the MySQL database and that all necessary resources are available.

For further configuration details, refer to the `Conn` class and the provided documentation in the Google Drive folder.

## Deployment

1. **Open the Project in Your IDE**: Open the project in an Integrated Development Environment (IDE) such as IntelliJ IDEA.


2. **Configure Database Connection**:
    - Ensure that the `Conn` class has the correct database connection details.
    - Verify that the MySQL server is running and accessible.


3. **Build the Project**:
    - Use your IDE’s build tools to compile the project.
    - Resolve any build issues that may arise during the compilation process.


4. **Run the Application**:
    - Execute the main class to start the application.
    - Ensure that all components, such as the graphical interface and database connectivity, are functioning as expected.

    
5. **Test the Application**:
    - Perform thorough testing of all features, including booking flights, managing customer information, and generating boarding passes.
    - Check for any errors or issues and address them as needed.


6. **Package for Distribution** (Optional):
    - If you need to distribute the application, package it into an executable JAR file or other deployment format as required.

## Demo

You can view a demonstration of the Airline Management System through the following [YouTube Playlist](https://youtube.com/playlist?list=PL_6klLfS1WqG2JM6fFFWGlhLJLCB5mr7T&si=eQnHffU4xi_z2uBc). The playlist includes videos that showcase various features and functionalities of the application.

## Documentation

Detailed documentation for the Airline Management System, including project files and descriptions, can be found in the Google Drive folder. This documentation includes:
- Setup and configuration instructions
- Database schema and SQL scripts
- Detailed descriptions of classes and their functionalities

Access the documentation here: [Google Drive Folder](https://drive.google.com/drive/folders/1wDw2Y1CtwwpTP85X1J3Kj2N2cWWDjAia)

## Related Projects

Here are some related projects that you might find interesting:
- **[Hotel Management System](https://github.com/Rishy-09/Hotel-Management-System)**: A Java project for managing hotel operations, including room bookings and customer management.
- **[University Management System](https://github.com/Rishy-09/University-Management-System)**: A Java project for managing university operations such as student records, teacher details, and examination schedules.
- **[Bank Management System](https://github.com/Rishy-09/Bank-Management-System)**: A Java project for handling various banking operations like deposits, withdrawals, and account management.

## Acknowledgements

Special thanks to [Kunal Tyagi](https://github.com/kunaltyagi9) for providing valuable insights and contributions to this project. Their support and guidance were instrumental in the development of the Airline Management System.

## Authors

- **Naman Chanana**: Lead Developer and Project Coordinator
- **Kunal Tyagi**: Contributor and Support

## Badges

![Java](https://img.shields.io/badge/Java-21-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0.28-orange)
![IntelliJ IDEA](https://img.shields.io/badge/IDE-IntelliJ_IDEA-green)

## Appendix

For additional information, refer to the following resources:
- **Google Drive Folder**: [Project Resources](https://drive.google.com/drive/folders/1wDw2Y1CtwwpTP85X1J3Kj2N2cWWDjAia) (includes icons, project files, and JAR files)
- **YouTube Playlist**: [Project Demo](https://youtube.com/playlist?list=PL_6klLfS1WqG2JM6fFFWGlhLJLCB5mr7T&si=eQnHffU4xi_z2uBc)
- **JDK Downloads**: [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- **MySQL Workbench**: [MySQL Workbench Download](https://dev.mysql.com/downloads/workbench/)

