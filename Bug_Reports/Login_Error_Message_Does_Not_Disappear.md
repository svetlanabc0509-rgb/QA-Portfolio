# Bug: Error message does not disappear after correcting input data

## Summary
Error message remains visible even after the user enters valid credentials.

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
4. Error message is displayed
5. Correct the password to a valid one

## Actual Result
Error message is still displayed after entering valid data.

## Expected Result
Error message disappears after entering valid credentials.

## Severity
Medium

## Priority
Medium

## Related Test Case
TC-02: Login with invalid password
