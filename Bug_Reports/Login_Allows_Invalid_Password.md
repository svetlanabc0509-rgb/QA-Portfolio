# Bug: Login is possible with invalid password

## Summary
User can successfully log in using an invalid password.

## Environment
- Environment: Test
- Browser: Chrome
- OS: Windows 10

## Preconditions
- User is registered
- Login page is opened

## Steps to Reproduce
1. Enter a valid email
2. Enter an invalid password
3. Click the "Login" button

## Actual Result
User is successfully logged in.

## Expected Result
An error message is displayed and the user is not logged in.

## Severity
Critical

## Priority
High

## Related Test Case
TC-02: Login with invalid password
