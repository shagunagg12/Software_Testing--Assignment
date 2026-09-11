# Software Testing & QA Assessment

A comprehensive QA assessment for a **Task Management Application**, focused on identifying functional, negative, boundary, security, persistence, and error-handling risks before production release.

## 📌 Overview

This assessment covers testing for a task management system with:

* User Registration & Login
* Task Creation, Viewing, Editing & Deletion
* Authentication & Authorization
* Database Persistence
* Input Validation & Error Handling
* Security & User Data Isolation

## 🧪 Testing Coverage

The assessment includes:

* **20 Test Scenarios**
* **Detailed Registration Test Cases**
* **Login Test Cases**
* **Task CRUD Test Cases**
* **Negative & Boundary Testing**
* **Security Testing**
* **Database & Persistence Testing**
* **End-to-End Testing**
* **Test Prioritization**
* **Entry & Exit Criteria**
* **Regression Testing**

## 🔐 Security Testing

Key security risks assessed include:

* Unauthorized access to protected tasks
* Cross-user task manipulation
* Session invalidation after logout
* XSS and SQL injection risks
* Password security
* Brute-force / repeated login attempts
* Exposure of sensitive technical errors

## 🐞 Bug Risk Assessment

Potential production risks were identified and categorized by severity, including:

* Duplicate user registration
* Unauthorized task access
* Cross-user data manipulation
* CRUD persistence failures
* XSS vulnerabilities
* Excessive input handling
* Session/cache issues
* Server or database failure handling

> **Note:** The potential bugs listed in the assessment are risk areas and were **not executed/verified against a live application**.

## 📊 Test Prioritization

Testing is prioritized as:

* **P0 – Critical:** Authentication, authorization, user isolation, CRUD persistence
* **P1 – High:** Input validation, sessions, logout, error handling
* **P2 – Medium:** Boundary values, special characters, empty states
* **P3 – Low:** Cosmetic and minor UI inconsistencies

## 🎯 QA Strategy

The proposed testing strategy follows:

**Smoke → Functional → Negative → Boundary → Security → Database → Regression**

The primary release focus is ensuring that authentication, authorization, CRUD operations, data persistence, and user-data isolation are reliable before production release.

## 📄 Assessment Document

The complete QA assessment is available in this repository:

**`Software_Tester_QA_Assignment.docx`**

## 👩‍💻 Author

**Shagun Aggarwal**

Computer Science | Software Development & QA
