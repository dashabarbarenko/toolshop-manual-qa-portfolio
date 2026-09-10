# City is populated even when an invalid postal code is entered

## ID
BUG-006-REG-CITY-004

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
2. A country is selected.
3. An invalid postal code is entered.
4. A valid house number is entered.

## Steps to Reproduce
1. Open the registration page.
2. Select a country.
3. Enter an invalid postal code (e.g. 18-555).
4. Enter a valid house number.
5. Verify the value populated in the City field.

## Actual Result
The City field is populated automatically despite the invalid postal code.

Example:
Postal Code: 18-555
Expected: No city should be populated.
Actual: Szczecinek

## Expected Result
The City field should not be populated when the postal code is invalid.
A validation error should be displayed.

## Attachments
Screenshot
