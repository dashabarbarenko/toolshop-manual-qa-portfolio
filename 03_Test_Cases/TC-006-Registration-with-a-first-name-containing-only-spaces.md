# TC-006 — Registration with a first name containing only spaces

## ID

TC-006

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
| First Name | `         ` (10 spaces) |
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
| Password | Test123! |

## Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Fill in all required fields with valid data. Enter only spaces in the **First Name** field. | Data is entered successfully. |
| 2 | Click the **Register** button. | Registration is not completed. A validation message is displayed for the **First Name** field. |

## Postconditions

No new user account is created.

## Status

Passed
