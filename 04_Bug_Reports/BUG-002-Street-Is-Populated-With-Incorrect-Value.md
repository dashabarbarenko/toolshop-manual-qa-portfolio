# Street is populated with incorrect value after entering valid address

## ID
BUG-002-REG-ST-001

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
2. Country, Postal Code and House Number are entered.
3. The entered address exists.

## Steps to Reproduce
1. Open the registration page.
2. Select a country.
3. Enter a valid postal code.
4. Enter a valid house number.
5. Verify the value populated in the Street field.

## Actual Result
The Street field is populated automatically, but the displayed street name is incorrect.

Example:

Expected street: Żoliborz

Displayed street: Klonowa

## Expected Result
The Street field is populated automatically with the correct street name corresponding to the entered address.

## Attachment
Screenshot
