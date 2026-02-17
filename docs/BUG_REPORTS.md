# Bug Reports – Sample Defects (Portfolio)

> Note: These defects are written as realistic examples for portfolio demonstration.

---

## BUG-001 – Login button remains disabled after correcting invalid email

**Status:** Open  
**Severity:** Medium  
**Priority:** High  
**Component:** Login UI / Validation  
**Environment:** Windows 11, Chrome (latest)

### Preconditions
- User is on the login page.

### Steps to Reproduce
1. Enter an invalid email format (e.g., `test@`)
2. Enter any password
3. Observe that the **Login** button is disabled (expected)
4. Correct the email to a valid format (e.g., `test@test.com`)

### Expected Result
- The **Login** button becomes enabled after the email format is corrected.

### Actual Result
- The **Login** button remains disabled until the page is refreshed.

### Evidence
- Screenshot/Video: (add later)

### Notes
- Possible issue with client-side validation state not updating.

---

## BUG-002 – Password field allows leading/trailing spaces and causes unexpected login failure

**Status:** Open  
**Severity:** Low  
**Priority:** Medium  
**Component:** Authentication / Input handling  
**Environment:** Windows 11, Chrome (latest)

### Preconditions
- A valid user exists.

### Steps to Reproduce
1. Open login page
2. Enter valid username/email
3. Enter valid password with spaces (e.g., `  correctPassword  `)
4. Click **Login**

### Expected Result
- Leading/trail

