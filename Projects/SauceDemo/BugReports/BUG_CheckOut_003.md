Bug ID: BUG-003

From: TC_CheckOut_007.md

Title: Checkout form accepts invalid customer names consisting only of space characters

Severity: Medium

Priority: Medium

Steps:

  1. Enter username: standard_user
  2. Enter password: secret_sauce
  3. Click Login
  4. Add any product to cart
  5. Proceed to Checkout
  6. Enter "  " into First Name
  7. Enter "  " into Last Name
  8. Enter "  " into Postal Code
  9. Complete checkout


Actual Result: Order is successfully processed.

Expected Result: System should reject names consisting only of punctuation characters and display a validation message.
