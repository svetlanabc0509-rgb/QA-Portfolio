 # Login Test Cases

## TC-01: Successful login with valid credentials
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Enter valid email
2. Enter valid password
3. Click "Login" button

Expected Result:
- User is successfully logged in
- User is redirected to the dashboard


## TC-02: Login with invalid password
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Enter valid email
2. Enter invalid password
3. Click "Login" button

Expected Result:
- Error message is displayed
- User is not logged in
## TC-03: Login with empty email field
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Leave email field empty
2. Enter valid password
3. Click "Login" button

Expected Result:
- Error message is displayed for email field
- User is not logged in
## TC-04: Login with empty password field
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Enter valid email
2. Leave password field empty
3. Click "Login" button

Expected Result:
- Error message is displayed for password field
- User is not logged in
## TC-05: Login with empty email and password fields
Preconditions:
- Login page is opened

Steps:
1. Leave email field empty
2. Leave password field empty
3. Click "Login" button

Expected Result:
- Validation error messages are displayed
- User is not logged in
