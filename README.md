
# Soar Inc. Assessment - Tausif Javed

Welcome! This repository is a showcase of my work for the Soar Inc. Software Testing Assessment. It includes exploratory testing, automation scripts, performance analysis, and test management. Each section highlights what I worked on, the tools I used, and the outcomes achieved.

## What’s Included?

### **Exploratory Testing**
I conducted in-depth exploratory testing on two applications to uncover bugs and usability issues:

- **OWASP Juice Shop**: Focused on identifying security vulnerabilities and functionality defects.
  - **Deliverable**: `OWASP Juice Shop - Bug Report.pdf` with a detailed list of discovered issues.

- **Wiki Mobile App**: Assessed this app to detect usability and functionality problems.
  - **Deliverable**: `Wiki Mobile App - Bug Report.pdf` documenting all findings.

### **Functional Testing**
This section contains automation scripts I developed for both web and mobile platforms. These scripts cover various workflows and edge cases.

#### **End-to-End Web Automation**
Using Selenium and Java, I automated several workflows for a web application. The project is structured using the Page Object Model (POM) for maintainability and reusability.

- **Tools**: Selenium, TestNG, Extent Reports
- **Tasks Covered**:
  - Pagination and item count verification.
  - Testing pop-ups and customer reviews on product pages.
  - Automating user registration, login, and shopping workflows.

#### **End-to-End Mobile Automation**
For mobile automation, I used Appium to interact with key features of the Wikipedia app, such as search and settings.

- **Tools**: Appium, TestNG, Java
- **Tasks Covered**:
  - Navigated and interacted with various sections of the app.
  - Performed searches and validated results.
  - Adjusted app settings and verified functionality.

### **Logical and Security Testing**
I analyzed a Flask-based application to identify logical errors and security vulnerabilities, focusing on the `/client_registeration` and `/client_login` endpoints.

- **Deliverable**: `Logical and Security Testing Report.pdf` with risk scores to prioritize issues.

### **Performance Testing**
I evaluated the performance of the Flask application and the Wikipedia app using Behave BDD and Apptim.

#### **Flask App Performance Testing**
- **Tasks**:
  - Load testing on `/client_register`.
  - Stress testing on `/client_login`.
  - BDD load testing with dynamic inputs.
- **Deliverables**:
  - `performance-testing-assessment.zip`: Includes scripts and configurations.
  - `report.html`, `report.json`: Detailed performance metrics.

#### **Wikipedia App Performance Testing**
- **Task**: Used Apptim to analyze the app’s responsiveness and overall performance.
- **Deliverable**: `E2EMobileAutomationPerformanceTest.pdf` with detailed results.

### **Test Management**
I created a comprehensive test plan and documented test cases based on user stories.

- **Deliverable**: `Test Management Document.pdf` with the test plan, test cases, and risk assessment.

## Tools Used
- **Exploratory Testing**: Manual testing.
- **Web Automation**: Selenium, TestNG, Extent Reports, Maven.
- **Mobile Automation**: Appium, TestNG, Maven.
- **Security Testing**: Manual vulnerability analysis.
- **Performance Testing**: Behave BDD, Apptim.
- **Test Management**: Risk-Based Testing (RBT).

## How to Run the Automation Scripts

### **Web Automation**
1. Navigate to the `Functional Test/E2EWebAutomationAssessment` directory.
2. Install dependencies using Maven:
   ```bash
   mvn clean install
   ```
3. Execute the tests with TestNG:
   ```bash
   mvn test
   ```
4. Find the reports in the `target` directory.

### **Mobile Automation**
1. Navigate to the `Functional Test/E2EMobileAutomationAssessment` directory.
2. Configure Appium settings in `config.properties`.
3. Run the tests:
   ```bash
   mvn test
   ```

### **Performance Testing**
1. Extract `performance-testing-assessment.zip`.
2. Execute Behave tests for the Flask app:
   ```bash
   behave
   ```
3. Review the performance reports in `report.html`.

## Extras
- **Screen Recordings**: Videos of key test executions are included.
- **Bug Reports**: Detailed documentation of exploratory and security testing findings.

## Questions?
Feel free to reach out via email: [tausifjaved@gmail.com].
