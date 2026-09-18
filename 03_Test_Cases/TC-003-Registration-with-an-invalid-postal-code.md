# TC-003 — Registration with an invalid postal code

## ID

TC-003

## Module

Customer Registration

## Priority

High

## Preconditions

1. The registration page is opened.
2. The account with the test email does not exist.
3. Valid registration data is available.

## Test Data

| Field | Value |
|------|------|
| First Name | John |
| Last Name | Smith |
| Date of Birth | 1995-10-10 |
| Country | Poland |
| Postal Code | 18-555 |
| House Number | 42 |
| Street | *(auto-filled)* |
| City | *(auto-filled)* |
| State | *(auto-filled)* |
| Phone | 48794322832 |
| Email Address | qatest001@gmail.com |
| Password | na6-2Ns-KRE-6T9 |

## Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Fill in all required fields using valid data. Enter an invalid postal code (`18-555`). | Data is entered successfully. |
| 2 | Click the **Register** button. | Registration is not completed. A validation message is displayed. Street, City and State fields remain empty. |

## Postconditions

No new user account is created.

## Status

Failed
