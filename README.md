# Spring Boot Application with JSP

This is a simple Spring Boot application that demonstrates how to use JSP (JavaServer Pages) for views.

## Overview
The application includes a HelloController that handles requests for the root path (/) and /hello. It uses a JSP view to display a personalized greeting message.
## Getting Started

### Prerequisites
- Java JDK 8 or higher
- Maven
### Installation
1. Clone the repository:
```bash
  git clone https://github.com/abhishekshah2905/spring-boot-jsp.git
```
2. Navigate to the project directory:
```bash
  cd bookmark-service
```
3. Build the project:
```bash
  mvn clean install
```
4. Deploy the WAR file to a Servlet container (e.g., Apache Tomcat).
5. Access the application at http://localhost:8080
### Usage
- The application includes a single HelloController that handles requests for the root path (/) and /hello.
- It uses a JSP view to display a personalized greeting message based on the name parameter.

### Configuration
- The application is configured to use JSP views located in the /WEB-INF/jsp/ directory.
- The view prefix is set to /WEB-INF/jsp/ and the suffix is set to .jsp in the application.properties file.
