# QA Portfolio – Pamela Bravin

## About Me

Aspiring Manual QA Tester with a professional background in Operations Management, Purchasing, and Supply Chain.

Currently developing expertise in Software Quality Assurance with a focus on:

- Manual Testing
- Functional Testing
- Exploratory Testing
- Test Case Design
- Bug Reporting
- User Acceptance Testing (UAT)
- Agile & Scrum

## Skills

- Manual Testing
- Test Case Design
- Bug Reporting
- Exploratory Testing
- Requirements Analysis
- User Acceptance Testing
- Agile Methodologies
- Scrum

## Tools

- GitHub
- Jira
- Postman
- Agile/Scrum

## Portfolio Projects

### Test Cases
Documentation of functional and non-functional test scenarios.

### Bug Reports
Examples of defect identification and reporting.

### Exploratory Testing
Structured exploratory testing sessions and findings.

## Contact

LinkedIn: www.linkedin.com/in/pamelabravin

GitHub: github.com/pamelabravin
## Test Cases

### Login Functionality Test Case

**Test ID:** TC-001

**Objective:** Verify that a registered user can log in successfully.

**Preconditions:**
- User account exists.

**Test Steps:**
1. Open login page.
2. Enter valid email.
3. Enter valid password.
4. Click Login.

**Expected Result:**
User is redirected to the dashboard.


## Bug Reports

### BUG-001

**Title:** Login button remains disabled after entering valid credentials.

**Severity:** High

**Priority:** High

**Steps to Reproduce:**
1. Open login page.
2. Enter valid credentials.
3. Observe login button.

**Expected Result:**
Login button becomes active.

**Actual Result:**
Login button remains disabled.


## Exploratory Testing

### Session 001

**Area Tested:** Login Page

**Duration:** 30 minutes

**Findings:**
- Checked form validation.
- Tested invalid credentials.
- Tested password visibility option.
- No critical defects found.
---

# Amazon Login Testing Project

## Project Overview

This project focuses on manual testing of Amazon's login functionality, including positive and negative test scenarios, bug reporting, and exploratory testing activities.

## Test Cases

### TC-AMZ-001 - Successful Login

**Objective:** Verify that a registered user can log in with valid credentials.

**Steps:**
1. Open Amazon login page.
2. Enter valid email.
3. Click Continue.
4. Enter valid password.
5. Click Sign In.

**Expected Result:**
User is successfully logged into the account.

---

### TC-AMZ-002 - Invalid Password

**Objective:** Verify system behavior when an incorrect password is entered.

**Steps:**
1. Open login page.
2. Enter valid email.
3. Enter invalid password.
4. Click Sign In.

**Expected Result:**
Error message is displayed.

---

### TC-AMZ-003 - Empty Email Field

**Objective:** Verify validation for empty email field.

**Steps:**
1. Open login page.
2. Leave email field empty.
3. Click Continue.

**Expected Result:**
Validation message appears.

---

### TC-AMZ-004 - Empty Password Field

**Expected Result:**
Validation message appears.

---

### TC-AMZ-005 - Password Visibility Toggle

**Expected Result:**
Password visibility changes correctly.

## Bug Reports

### BUG-AMZ-001

**Title:** Password field accepts leading spaces.

**Severity:** Medium

**Priority:** Medium

**Expected Result:**
Leading spaces should be trimmed.

**Actual Result:**
Spaces are accepted.

---

### BUG-AMZ-002

**Title:** Error message overlaps login form on small screens.

**Severity:** Low

**Priority:** Low

**Expected Result:**
Responsive layout maintained.

**Actual Result:**
UI overlap occurs.

## Exploratory Testing Session

### Session 001

**Area:** Login Page

**Duration:** 45 minutes

**Scope:**
- Email validation
- Password validation
- Error handling
- Responsive behavior

**Findings:**
- No critical issues identified.
- Minor UI inconsistencies observed on mobile devices.
---

# Netflix Sign-Up Testing Project

## Project Overview

This project focuses on manual testing of Netflix's account registration flow, validating user creation, form validations, error handling, and user experience.

## Test Cases

### TC-NFLX-001 - Successful Account Registration

Objective: Verify that a new user can successfully create an account.

Steps:

1. Open Netflix sign-up page.
2. Enter valid email.
3. Create valid password.
4. Select a subscription plan.
5. Complete registration.

Expected Result:

Account is successfully created.

---

### TC-NFLX-002 - Invalid Email Format

Objective: Verify validation for invalid email addresses.

Steps:

1. Open registration page.
2. Enter invalid email format.
3. Click Continue.

Expected Result:

Validation message is displayed.

---

### TC-NFLX-003 - Empty Required Fields

Objective: Verify mandatory field validation.

Steps:

1. Leave required fields blank.
2. Click Continue.

Expected Result:

Required field error messages appear.

---

## Bug Report

### BUG-NFLX-001

Title: Continue button remains enabled with invalid email format.

Severity: Medium

Priority: Medium

Steps to Reproduce:

1. Open registration page.
2. Enter invalid email.
3. Observe Continue button.

Expected Result:

Button remains disabled.

Actual Result:

Button remains enabled.

---

## Exploratory Testing Session

Area Tested: Registration Flow

Duration: 45 minutes

Findings:

- Tested multiple email formats.
- Verified password validation rules.
- Tested browser refresh behavior.
- No critical issues identified.
---

# E-commerce Checkout Testing Project

## Project Overview

This project focuses on manual testing of an e-commerce checkout process, validating cart functionality, payment flow, order confirmation, and error handling.

## Test Cases

### TC-ECOM-001 - Successful Checkout

Objective: Verify that a customer can complete a purchase successfully.

Steps:

1. Add product to cart.
2. Proceed to checkout.
3. Enter shipping information.
4. Select payment method.
5. Confirm order.

Expected Result:

Order is placed successfully and confirmation page is displayed.

---

### TC-ECOM-002 - Empty Shipping Address

Objective: Verify required field validation.

Steps:

1. Add product to cart.
2. Proceed to checkout.
3. Leave shipping address blank.
4. Click Continue.

Expected Result:

Validation message is displayed.

---

### TC-ECOM-003 - Invalid Credit Card Number

Objective: Verify payment validation.

Steps:

1. Proceed to payment step.
2. Enter invalid card number.
3. Submit payment.

Expected Result:

Error message is displayed and payment is rejected.

---

## Bug Report

### BUG-ECOM-001

Title: Order total does not update after removing item from cart.

Severity: High

Priority: High

Steps to Reproduce:

1. Add two products to cart.
2. Remove one product.
3. Observe order total.

Expected Result:

Order total updates correctly.

Actual Result:

Order total remains unchanged.

---

## Exploratory Testing Session

Area Tested: Checkout Process

Duration: 60 minutes

Findings:

- Tested cart updates.
- Verified coupon code validation.
- Tested payment error handling.
- Confirmed order confirmation workflow.
- No critical defects found.
