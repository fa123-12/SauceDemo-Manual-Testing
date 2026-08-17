# SauceDemo - Manual Testing

## Project Status

🔄 **Continuously Improving**

The project is functional and manual testing is ongoing.

Additional test cases, scenarios, edge cases, and validation checks
are being added progressively to improve test coverage and strengthen
the overall test suite.

---

## Project Overview

This project focuses on the manual testing of the SauceDemo e-commerce
web application.

The objective is to practice and demonstrate a complete QA testing
workflow, including:

- Application exploration
- Requirement and feature analysis
- Test scenario identification
- Test case design
- Manual test execution
- Positive and negative testing
- Defect identification
- Bug reporting
- Retesting
- Regression testing
- Test reporting

---

## Application Under Test

**SauceDemo**

SauceDemo is a demo e-commerce web application used for practicing
software testing.

Main application features covered by this project:

- Login
- Products
- Product details
- Product sorting
- Shopping Cart
- Checkout
- Order completion
- Logout

---

## Testing Objectives

The main objectives of this project are to:

- Verify that the main application functionalities work as expected.
- Validate positive and negative scenarios.
- Verify the user interface.
- Identify unexpected application behavior.
- Document defects using structured bug reports.
- Retest defects after fixes.
- Perform regression testing.
- Increase test coverage by continuously adding new test cases.
- Document test execution results.

---

## Testing Types

The following testing types are applied:

### Functional Testing

Verify that application features work according to their expected
behavior.

### Smoke Testing

Perform a quick validation of the main application workflow to verify
that the application is stable enough for further testing.

### Regression Testing

Verify that existing functionality continues to work after changes
or fixes.

### Positive Testing

Verify application behavior using valid input and expected user flows.

### Negative Testing

Verify that the application correctly handles invalid, incomplete,
or unexpected input.

### UI Testing

Verify the visibility, positioning, alignment, labels, and usability
of interface elements.

### End-to-End Testing

Validate a complete user workflow from login through successful
purchase completion.

---

## Test Scope

### In Scope

#### Login

- Login with valid credentials
- Login with invalid username
- Login with invalid password
- Login with empty username
- Login with empty password
- Login with empty credentials
- Error message validation

#### Products

- Product display
- Product information
- Product details
- Product sorting
- Add product to cart

#### Shopping Cart

- Add product
- Add multiple products
- Remove product
- Remove products
- Verify cart contents
- Verify cart counter

#### Checkout

- Valid customer information
- Missing required information
- Checkout validation
- Order summary
- Order completion

#### Logout

- Successful logout
- Navigation after logout

---

## Out of Scope

Features that are not available in the application are not considered
functional requirements.

For example, a feature should not be reported as a functional defect
simply because it is not implemented in the application.

Additional observations or improvement suggestions may be documented
separately when appropriate.

---

## Test Environment

| Item | Value |
|---|---|
| Application | SauceDemo |
| Operating System | Windows |
| Browser | Firefox |
| Testing Type | Manual Testing |

---

## Test Artifacts

### Test Cases

Location:

`QA/Test-Cases.xlsx`

The Excel file contains:

- Test Case ID
- Module
- Test Scenario
- Preconditions
- Test Data
- Expected Result
- Actual Result
- Status
- Test Type
- Priority
- Severity
- Defect ID


---

### Test Data

Location:

`QA/Test-Data/Test-Data.md`

Contains the test data used during manual test execution.

---

### Test Execution Report

Location:

`QA/Test-Results/Test-Execution-Report.md`

Contains:

- Test execution summary
- Test results
- Defects
- Retesting results
- Regression testing results
- Testing conclusion

---

### Bug Reports

Location:

`QA/Bug-Reports/`

Each defect is documented using a structured bug report.

Bug reports contain:

- Bug ID
- Title
- Module
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Status
- Defect type
- Evidence

---

## Test Workflow

The project follows the following QA workflow:

Application Exploration
        ↓
Feature / Requirement Analysis
        ↓
Test Scenario Identification
        ↓
Test Case Design
        ↓
Test Execution
        ↓
PASS / FAIL
        ↓
Bug Report
        ↓
Bug Fix
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Execution Report
        ↓
Continuous Test Improvement

---

## Current Progress

| Activity | Status |
|---|---|
| Application exploration | ✅ Completed |
| Initial test case design | ✅ Completed |
| Login test cases | ✅ Completed |
| Products test cases | 🔄 Ongoing |
| Cart test cases | 🔄 Ongoing |
| Checkout test cases | 🔄 Ongoing |
| Test execution | 🔄 Ongoing |
| Bug reporting | 🔄 Ongoing |
| Retesting | 🔄 Ongoing |
| Regression testing | 🔄 Ongoing |
| Additional test cases | 🔄 Continuously Improving |
| Documentation | 🔄 Continuously Improving |

---

## Continuous Improvement

The test suite is continuously improved by:

- Adding new test cases.
- Adding edge cases.
- Adding negative scenarios.
- Increasing functional coverage.
- Improving test data.
- Adding UI validation scenarios.
- Adding regression scenarios.
- Improving defect documentation.
- Updating execution results.

---

## Tools

- SauceDemo
- Microsoft Excel
- Git
- GitHub
- Firefox

---

## Conclusion

This project demonstrates a practical manual testing workflow for
an e-commerce web application.

The project is continuously improved as new test cases, scenarios,
edge cases, defects, and validation activities are identified.

The final test execution report will be updated progressively as
additional test cases are executed.
