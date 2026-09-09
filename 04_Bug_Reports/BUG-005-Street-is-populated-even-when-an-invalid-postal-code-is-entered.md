# Street is populated even when an invalid postal code is entered

## ID
BUG-005-REG-ST-005

## Environment
- OS: Windows 10
- Browser: Google Chrome 152
- Application: Customer Registration

## Severity
High

## Priority
High

## Preconditions
1. Registration page is opened.
2. Country is selected.
3. A valid House Number is entered.
4. An invalid Postal Code is entered.

## Steps to Reproduce
1. Open the registration page.
2. Select a country.
3. Enter an invalid postal code (e.g. 18-555).
4. Enter a valid house number.
5. Verify the value populated in the Street field.

## Actual Result
The Street field is populated automatically despite the invalid postal code.

Example:
Postal Code: 18-555
Expected: No street should be populated.
Actual: Morelowa

## Expected Result
The Street field should remain empty until a valid postal code is entered.
A validation error should be displayed.

## Attachments
Screenshot
