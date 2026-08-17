# Test Data

## Project

SauceDemo - Manual Testing

## Application

SauceDemo

## Test Environment

- Operating System: Windows
- Browser: Firefox
- Testing Type: Manual Testing

---

## 1. Login Test Data

### Valid Credentials

Username:
`standard_user`

Password:
`[Use the password provided by the application]`

Expected:
Successful login and access to the Products page.

---

### Invalid Username

Username:
`invalid_user`

Password:
`[Valid password]`

Expected:
An appropriate error message is displayed.

---

### Invalid Password

Username:
`standard_user`

Password:
`wrong_password`

Expected:
An appropriate error message is displayed.

---

### Empty Username

Username:
``
 
Password:
`[Valid password]`

Expected:
A validation/error message is displayed.

---

### Empty Password

Username:
`standard_user`

Password:
``

Expected:
A validation/error message is displayed.

---

## 2. Product Test Data

Products will be selected from the products available in the application.

Example:

- Product: Sauce Labs Backpack
- Product: Sauce Labs Bike Light

---

## 3. Checkout Test Data

### Valid Customer Information

First Name:
`Fatima`

Last Name:
`Zahra`

Postal Code:
`14000`

Expected:
The user can continue to the checkout overview.

---

### Invalid / Missing Customer Information

Test cases will include:

- Empty First Name
- Empty Last Name
- Empty Postal Code
- Missing required fields

---

## 4. Notes

Test data will be updated during the execution phase if additional
scenarios or edge cases are identified.