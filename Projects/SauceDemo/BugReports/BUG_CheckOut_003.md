Bug ID: BUG-003

From: TC_CheckOut_007.md

Title: Checkout form accepts invalid customer names consisting only of space characters

Severity: Medium

Priority: Medium

Steps:

  1. Login to SauceDemo
  2. Add any product to cart
  3. Proceed to Checkout
  4. Enter "  " into First Name
  5. Enter "  " into Last Name
  6. Enter "  " into Postal Code
  7. Complete checkout


Actual Result: Order is successfully processed.

Expected Result: System should reject names consisting only of punctuation characters and display a validation message.
