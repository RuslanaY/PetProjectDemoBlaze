# DemoBlaze — QA Pet Project

This repository contains my QA pet project based on the demo e-commerce web application DemoBlaze. I worked on this project as a realistic simulation of manual QA work, not just a learning exercise. My focus was on understanding the application, choosing the most important areas to test, creating clear test documentation, and reporting issues in a way that would be useful for a real team. This project shows my testing mindset, not only my technical skills.

## Why I created this project
I created this project to practice manual testing of a web application, work with e-commerce functionality that is common in many real projects, and show that I can analyze product behavior, decide what should be tested first, create practical and easy-to-understand test documentation, and report bugs clearly and in a structured way.

## What I tested
DemoBlaze is a demo e-commerce application, so I focused on core user and business flows.

### Web UI
I tested user registration, login and logout; product catalog and category switching; product details page; adding and removing products from the cart; total price calculation; checkout flow (Place Order); contact form functionality; and session behavior such as page refresh and guest-to-logged-in user flow. I did not try to test everything. Instead, I focused on the functionality that is most important for users and business logic.

### API
API testing was used as supporting testing for UI. I checked catalog-related API requests, authentication requests, and basic cart-related API logic. The goal was to make sure backend responses are stable and that UI issues are not hiding API problems.

## How I approached testing
I used a practical and flexible approach. I used a UI checklist for smoke testing and quick validation, UI test cases for key user scenarios where step-by-step checks are important, API test cases for main endpoints, and bug reports for all found issues. This approach helps to quickly understand if the application works in general, avoid unnecessary documentation, and reuse tests during regression testing.

## Documentation and repository structure
The repository contains the main QA artifacts:

docs/
Test Design Overview
Requirements
Web UI Test Checklist
UI Test Cases
API Test Cases
Bug Reports

postman/
collections

newman/
reports

sql/
SQL scripts / test data structure

## Bug reporting
Each issue was reported with clear steps to reproduce, expected and actual results, environment details, and severity and priority. I focused on writing bug reports in a clear and practical way so developers can easily understand and reproduce the problem.

## What this project demonstrates
This project shows that I understand e-commerce application logic, can plan testing instead of testing randomly, know when a checklist is enough and when detailed test cases are needed, can work with both UI and API testing, and create clear and structured QA documentation.

## Author
Ruslana Yakymiv  
Manual QA Engineer
