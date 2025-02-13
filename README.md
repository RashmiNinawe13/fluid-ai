# fluid-ai
📝 Introduction

This project focuses on testing the functionality and performance of a chatbot using RestAssured for API testing and Selenium for UI testing. The goal was to validate chatbot responses, handle different input cases, and ensure optimal response times. The project followed a structured testing approach with detailed documentation and execution.

🔍 Project Type

Automation Testing using RestAssured & SeleniumThe testing included writing test scripts for API and UI validation.

📁 Directory Structure

Test Plan: Document outlining the scope, approach, and strategy for testing.

RTM (Requirements Traceability Matrix): Mapping of requirements to test scripts to ensure full coverage.

Test Scenarios: High-level scenarios based on chatbot interactions.

Test Scripts: API and UI scripts written for chatbot validation.

Bug Report: Detailed document of identified issues and their resolutions.

Summary: Overview of the testing performed on the chatbot.

Mind Map: Visual representation of the testing flow and approach.

🎯 Features Tested

API Testing

Validation of chatbot responses for different inputs.

Handling of malformed and empty requests.

Response time verification.

UI Testing

Automating chatbot interactions on the web UI.

Validating text inputs and response visibility.

Checking responsiveness on different screen sizes.

Performance Testing

Ensuring API response times are within acceptable limits.

Load testing with multiple user interactions.

Error Handling

Validation of incorrect API requests.

Ensuring proper error messages are displayed.

🛠️ Design Decisions and Assumptions

Focused primarily on API and UI testing.

Assumed chatbot should provide responses within 2 seconds.

Used RestAssured & Selenium for reliable automation.

📊 Testing Artifacts

1. Test Plan

Defined the objectives, tools, and testing timelines.

2. RTM

Ensured traceability between requirements and test scripts.

3. Test Scenarios

Created scenarios for API validation, UI interactions, and performance testing.

4. Test Scripts

API tests written using RestAssured.

UI tests automated using Selenium.

5. Bug Report

Highlighted issues with severity and resolution steps.

6. Mind Map

Visualized the testing process and key focus areas.

🐞 Key Bugs Identified

Critical: Chatbot API fails to respond correctly to special character inputs.

Major: UI does not display chatbot responses consistently.

Minor: Response time occasionally exceeds 2 seconds under heavy load.

🚀 Installation & Getting Started

Prerequisites

Java installed on your system.

Maven installed.

Cypress or Selenium installed for UI testing.

Install dependencies using:

mvn clean install

🖋️ Summary

This project validated the chatbot’s API and UI functionality using RestAssured & Selenium. Through detailed test scripts and documentation, we ensured that all major chatbot functionalities were tested and optimized.

💻 Technology Stack

Automation Tool: RestAssured (API), Selenium (UI)

Documentation Tools: MS Word, Google Sheets

Testing Platforms: Postman, JMeter, Browser-based testing

🏆 Acknowledgments

I would like to express my gratitude to Masai School and my instructors for their guidance and support throughout this project.

