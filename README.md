### Automated Testing for OrangeHRM: A Project Showcase

Hello! This README file is a polished showcase of your automated testing project using **TestRigor** and **OrangeHRM**. This can be a great addition to your Software Quality Assurance (SQA) intern portfolio.

---

### 🌟 Project Summary

This project demonstrates my proficiency in automated testing using **TestRigor**, a cutting-edge, AI-powered no-code automation tool. The goal was to build and execute a suite of test cases to validate the key functionalities of the **OrangeHRM** system.

My work covers a comprehensive range of testing scenarios, including positive and negative test cases, all written in plain English. The use of a no-code tool highlights a modern approach to QA, focusing on efficiency, speed, and maintainability.

---

### 🛠️ Tools and Technologies

* **TestRigor:** An AI-powered, no-code automation tool that allows test creation using simple, human-readable language. Its ability to identify elements by their visual text rather than complex locators significantly reduces test maintenance.
* **OrangeHRM:** An open-source Human Resources Management (HRM) system used as the application under test.

---

### ✨ Key Project Features

#### ✅ **Positive Testing (Pass Functions)**

These test cases prove that the system works as expected under normal conditions.

* **`Check Claim Function`:** Ensures the user can successfully access the "Claim" module.
* **`Check My Info Function`:** Verifies the user can navigate to and view their personal information page.
* **`Check PIM and Time Functions`:** Confirms the proper functionality and display of the Personal Information Management (PIM) and Time Management modules.

#### ❌ **Negative Testing (Fail Functions)**

These tests are crucial for validating the system's robustness and security. They are designed to fail, demonstrating that the system handles invalid or unexpected inputs gracefully.

* **`Check wrong Password with Dashboard Function`:** A fundamental security test. This case intentionally uses incorrect login credentials to confirm that the system correctly blocks access and prevents the user from reaching the dashboard.
* **`Check Most Recent Photo` and `Check Student Record`:** These tests were designed to fail, as a way to prove that the system does not display these specific features or elements under the tested conditions. This highlights a key skill in anticipating system behavior.

---

#### 🌐 **Leveraging Global Variables**

To showcase best practices in automation, this project uses global variables for key data like the username and password.

* **Efficiency:** By storing credentials as variables (e.g., `username`, `password`), I've created a test suite that is easy to manage. If the login credentials change, a single update to the variable is all that's needed, saving valuable time and reducing maintenance effort.
* **Reusability:** This method promotes code reusability, a core principle in software development. The login process becomes a reusable component that can be called by any test case, making the entire test suite more scalable and organized.

This project is a strong reflection of my ability to apply practical QA principles to real-world applications using modern, efficient tools. It demonstrates a solid foundation in both manual and automated testing methodologies, making me a valuable candidate for a Software Quality Assurance role.
