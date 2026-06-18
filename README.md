# My First Web App

A simple Java Servlet-based web application created to understand the fundamentals of web development using Jakarta Servlets. The application handles HTTP requests and returns a basic HTML response to the browser.

## Features

- Basic Servlet implementation using `GenericServlet`
- Handles client requests through the `service()` method
- Generates dynamic HTML response
- Maven-based project structure
- Deployable on Apache Tomcat

## Project Structure

```text
My-First-Web-App/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── Servlet.java
│       │
│       └── webapp/
│           ├── index.html
│           └── WEB-INF/
│
├── pom.xml
└── .gitignore
```

## Technologies Used

- Java
- Jakarta Servlet API
- Apache Tomcat
- HTML
- Maven

## How It Works

1. The user accesses the application through a web browser.
2. The request is sent to the Servlet.
3. The Servlet processes the request using the `service()` method.
4. An HTML response is generated and returned to the client.
5. The browser displays the response.

## Output

```html
Hello from Motilal Gupta!
```

## Prerequisites

- JDK 8 or later
- Apache Tomcat 10+
- Maven 3.x
- IntelliJ IDEA

## Running the Application

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the project in IntelliJ IDEA.

3. Configure Apache Tomcat.

4. Build and deploy the application.

5. Open your browser and visit:

```text
http://localhost:8080/MyFirstWebApp/
```

## Learning Objectives

- Understanding Servlet architecture
- Working with `GenericServlet`
- Handling HTTP requests and responses
- Generating dynamic web content
- Deploying Java web applications on Tomcat

## Author

**Motilal Gupta**
