# TC-005 — Registration with a password containing invalid characters

## ID

TC-005

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
| Postal Code | 01-793 |
| House Number | 42 |
| Street | Test Street |
| City | Warsaw |
| State | Mazowieckie |
| Phone | 48794322832 |
| Email Address | qatest001@gmail.com |
| Password | A^tim8KD*Y |

## Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Fill in all required fields with valid data. Enter a password containing invalid characters (`A^tim8KD*Y`). | Data is entered successfully. |
| 2 | Click the **Register** button. | Registration is not completed. A validation message is displayed. |

## Postconditions

No new user account is created.

## Status

Passed

## Notes

Validation message:

> Password can not include invalid characters.
