Bug ID:
BUG-002

From: TC_Card_006.md

Title:
Checkout form accepts invalid customer names consisting only of punctuation characters

Severity:
Medium

Priority:
Medium

Steps:
1. Login to SauceDemo
2. Add any product to cart
3. Proceed to Checkout
4. Enter "." into First Name
5. Enter "." into Last Name
6. Enter valid Postal Code
7. Complete checkout

Actual Result:
Order is successfully processed.

Expected Result:
System should reject names consisting only of punctuation characters and display a validation message.
