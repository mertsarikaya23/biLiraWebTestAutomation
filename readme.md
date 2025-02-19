# biLira Web Automation Project
## Overview

This project is a mobile test automation framework built using the following technologies:
- **Java**
- **Maven**
- **Gauge**
- **Selenium**
- **Log4j**
- **Gauge Reporter**

The framework is designed to automate testing for mobile applications, with support for Android platforms.

## Technologies Used

- **Java**: The main programming language for the automation scripts.
- **Maven**: For project build management and dependency management.
- **Gauge**: For behavior-driven development (BDD), allowing test scenarios to be written in a natural language.
- **Selenium**: Used for automating web applications.
- **log4j.properties**: Configuration file for Log4j logging.
- **Gauge Reporter**: For logging the test execution flow.

### Explanation of Key Directories and Files

- **src/test/java**: Contains application-specific code. Typically, this is not used heavily in test automation projects.
- **src/test/java/base**: File containing Appium Driver installations.
- **src/test/java/step**: Step definitions that map scenarios to actual Java methods.
- **src/test/java/pages**: Implements the Page Object Model (POM) to represent the screens in the mobile app.
- **src/test/java/utils**: Helper classes with utility methods, such as handling wait conditions, file operations, etc.
- **log4j.properties**: Configuration file for Log4j logging.
- **src/test/resources/elementValues**: Elements are in JSON file. Such as id,xpath and css.

Test Result Report SS:
![Ekran Resmi 2025-02-19 13.09.30.png](Ekran%20Resmi%202025-02-19%2013.09.30.png)