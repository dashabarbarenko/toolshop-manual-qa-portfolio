# Password minimum length is inconsistent with UI requirements

## ID
BUG-009-REG-PW-009

## Environment
- OS: Windows 10
- Browser: Google Chrome 152
- Application: Customer Registration

## Severity
High

## Priority
High

## Preconditions
1. The registration page is opened.
2. All required fields except Password are filled with valid data.

## Steps to Reproduce
1. Open the registration page.
2. Fill in all required fields with valid data.
3. Enter a password containing 7 valid characters (e.g. `14AD&r4`).
4. Click the **Register** button.

## Actual Result

Validation message is displayed:

"Password must be minimal 6 characters long."

However, the password requirements displayed on the page state that the password must contain **at least 8 characters**.

Example password:

14AD&r4 (7 characters)

## Expected Result

The minimum password length shown in the validation message should match the password requirement displayed in the UI.

## Attachments

Screenshot
