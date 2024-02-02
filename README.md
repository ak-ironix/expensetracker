# Expense Tracking

A simple web application which allows users to manage and track their expenses. 


## Features

 1. Perform operations such as adding, updating, and deleting expenses.
 2. Display expense summaries in a tabular format, along with a total amount spent overview.
 3. Filter expenses based on criteria such as year, month, and expense type.
 4. Implement pagination for improved navigation through expense records.
 5. Personalize expense categories according to your preferences.
 6. Enable users to download expense data in CSV format.
 7. Ensure a responsive design for optimal user experience across different devices.

## Technologies Used

- Java 17.0
- Spring Boot 3
- Spring Data JPA (for data access)
- Thymeleaf (for server-side templating)
- MySQL (as the database)
- Maven (for build and dependency management)
- HTML, CSS, Bootstrap
- Server is Tomcat, built-in server of Spring Boot.

## Getting Started

1. Clone the repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Make sure you have MySQL installed on your machine
4. Create a MySQL database named `expensetracker` or update the database configuration in `src/main/resources/application.properties` with your own database settings.
6. Build and run the application using Maven via `mvn spring-boot:run` command or via IDE.
7. Access the app in your browser at `http://localhost:9191`. You can change the serverport in application.properties file.



