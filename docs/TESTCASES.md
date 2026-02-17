# Test Cases – Login Functionality

## Test Case TC-001

Title: Verify login with valid credentials

Precondition:
User is registered

Steps:
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click login button

Expected Result:
User is logged in successfully and redirected to dashboard

Actual Result:
User is logged in successfully

Status:
Pass

---

## Test Case TC-002

Title: Verify login with invalid password

Precondition:
User exists

Steps:
1. Open login page
2. Enter valid username
3. Enter invalid password
4. Click login button

Expected Result:
Error message is displayed

Actual Result:
Error message displayed

Status:
Pass

---

## Test Case TC-003

Title: Verify login with empty fields

Precondition:
Login page open

Steps:
1. Leave username empty
2. Leave password empty
3. Click login button

Expected Result:
Validation error displayed

Actual Result:
Validation error displayed

Status:
Pass

---

## Test Case TC-004

Title: Verify logout functionality

Precondition:
User is logged in

Steps:
1. Click logout button

Expected Result:
User is logged out and redirected to login page

Actual Result:
User logged out successfully

Status:
Pass

