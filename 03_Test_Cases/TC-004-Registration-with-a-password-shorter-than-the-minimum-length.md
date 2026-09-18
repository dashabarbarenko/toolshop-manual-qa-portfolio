# TC-004 — Registration with a password shorter than the minimum length

## ID

TC-004

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
| City | Warszawa |
| State | Mazowieckie |
| Phone | 48794322832 |
| Email Address | qatest001@gmail.com |
| Password | 12345 |

## Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Fill in all required fields with valid data. Enter a 5-character password (`12345`). | Data is entered successfully. |
| 2 | Click the **Register** button. | Registration is not completed. An appropriate validation message is displayed. |

## Postconditions

No new user account is created.

## Status

Failed

## Notes

Actual Result:

The application displays the message:

> Password must be minimal 6 characters long.

However, the password requirements displayed on the page state that the password must contain **at least 8 characters**.

Related Bug Report:

- BUG-009
