# Postal Code accepts invalid values

## ID
BUG-001-REG-PC-001

## Environment
- Windows 10
- Google Chrome 152
- Customer Registration

## Severity
High

## Priority
High

## Preconditions
1. Registration page is opened.
2. All required fields except Postal Code are filled with valid data.

## Steps to Reproduce
1. Enter letters into the Postal Code field.
2. Click Register.

## Actual Result
The application accepts the invalid postal code.
No validation error is displayed.

## Expected Result
A validation error is displayed.
Registration is not completed.

## Attachment
Screenshot
