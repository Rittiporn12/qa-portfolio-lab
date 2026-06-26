# Login Feature Test Cases

## Feature

Login

## Objective

To verify that users can log in successfully with valid credentials and that the system correctly handles invalid input.

---

## Test Case 1: Login with valid email and password

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-001 |
| Test Scenario | Verify that the user can login with a valid email and password |
| Preconditions | The user already has a registered account |
| Test Data | Email: user@example.com / Password: Password123 |
| Steps | 1. Open the login page<br>2. Enter a valid email<br>3. Enter a valid password<br>4. Click the Login button |
| Expected Result | The user should be redirected to the dashboard |
| Actual Result | The user is redirected to the dashboard |
| Status | Pass |

---

## Test Case 2: Login with invalid password

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-002 |
| Test Scenario | Verify that login fails when the password is incorrect |
| Preconditions | The user already has a registered account |
| Test Data | Email: user@example.com / Password: wrongpassword |
| Steps | 1. Open the login page<br>2. Enter a valid email<br>3. Enter an invalid password<br>4. Click the Login button |
| Expected Result | The system should show an error message |
| Actual Result | The system shows "Invalid email or password" |
| Status | Pass |

---

## Test Case 3: Login with empty email field

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-003 |
| Test Scenario | Verify validation when the email field is empty |
| Preconditions | The user is on the login page |
| Test Data | Email: empty / Password: Password123 |
| Steps | 1. Open the login page<br>2. Leave the email field empty<br>3. Enter a password<br>4. Click the Login button |
| Expected Result | The system should show "Email is required" |
| Actual Result | The system shows "Email is required" |
| Status | Pass |

---

## Test Case 4: Login with empty password field

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-004 |
| Test Scenario | Verify validation when the password field is empty |
| Preconditions | The user is on the login page |
| Test Data | Email: user@example.com / Password: empty |
| Steps | 1. Open the login page<br>2. Enter a valid email<br>3. Leave the password field empty<br>4. Click the Login button |
| Expected Result | The system should show "Password is required." |
| Actual Result | The system shows "Invalid email or password" instead of "Password is required." |
| Status | Fail |

---

## Test Case 5: Login with invalid email format

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-005 |
| Test Scenario | Verify validation when the email format is invalid |
| Preconditions | The user is on the login page |
| Test Data | Email: userexample.com / Password: Password123 |
| Steps | 1. Open the login page<br>2. Enter an invalid email format<br>3. Enter a password<br>4. Click the Login button |
| Expected Result | The system should show "Invalid email format" |
| Actual Result | The system shows "Invalid email format" |
| Status | Pass |