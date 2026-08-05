# Bug Report

| Bug ID | Title | Module | Severity | Priority | Status |
|--------|-------|--------|----------|----------|--------|
| BUG-001 | Shopping cart badge is not updated after removing all products *(Sample Bug)* | Cart | Medium | High | Open |

## Bug Description

Summary:
The shopping cart badge remains visible after removing all products from the cart.

Preconditions:
- User is logged in.
- At least one product is added to the cart.

Steps to Reproduce:
1. Login to SauceDemo.
2. Add one product to the cart.
3. Open the cart.
4. Remove the product.

Expected Result:
The shopping cart badge should disappear when the cart becomes empty.

Actual Result:
The shopping cart badge remains visible.

Environment:
- Browser: Google Chrome
- OS: Windows 11

Reported By:
Saad Kamal Shalan
