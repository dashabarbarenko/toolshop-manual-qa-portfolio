# Street, City and State are populated after entering an invalid house number

## ID
BUG-008-REG-ADDRESS-001

## Environment
- OS: Windows 10
- Browser: Google Chrome 152
- Application: Customer Registration

## Severity
Medium

## Priority
High

## Preconditions
1. The registration page is opened.
2. A country is selected.
3. A valid postal code is entered.
4. An invalid house number is entered.

## Steps to Reproduce
1. Open the registration page.
2. Select a country.
3. Enter a valid postal code.
4. Enter an invalid house number (e.g. R2221777777777777).
5. Verify the values populated in the Street, City and State fields.

## Actual Result
The Street, City and State fields are populated automatically despite the invalid house number.

Example:
House Number: R2221777777777777

Street: Klonowa
City: Ostróda
State: podlaskie

## Expected Result
The Street, City and State fields should not be populated when the house number is invalid.
A validation error should be displayed.

## Attachments
Screenshot
