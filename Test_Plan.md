# Test Plan: E-Commerce QA Test Suite

## 1. Objective

The objective of this test plan is to verify the main user workflows of an e-commerce demo website, including login, signup, product search, filters, cart, and checkout.

## 2. Scope

### In Scope

- Login with valid and invalid credentials
- Signup requirement review
- Product search requirement review
- Product sorting and filtering
- Add and remove products from cart
- Checkout information entry
- Order completion
- Basic smoke and regression coverage

### Out of Scope

- Payment gateway integration
- Email verification
- Backend database validation
- Security penetration testing
- Performance testing beyond basic observation
- Mobile app testing

## 3. Test Approach

Testing will be performed manually using functional testing techniques. Test cases will cover positive, negative, boundary, and UI validation scenarios. Smoke testing will verify that critical flows work before deeper testing. Regression testing will be used after defects are fixed or when changes are made.

## 4. Test Environment

- Browser: Chrome, Edge, or Firefox
- Operating system: Windows
- Site: https://www.saucedemo.com/
- Network: Stable internet connection

## 5. Entry Criteria

- Test environment is available.
- Website is accessible.
- Test data is available.
- Test cases are reviewed and ready.

## 6. Exit Criteria

- All planned test cases are executed.
- All critical and high severity defects are reported.
- Test results are updated.
- RTM shows requirement coverage.

## 7. Roles And Responsibilities

- Tester: Write and execute test cases, report defects, update RTM.
- Developer: Fix reported defects.
- Test Lead or Reviewer: Review test cases, defects, and final test summary.

## 8. Test Types

- Smoke testing: Verify critical flows such as login, cart, and checkout.
- Functional testing: Verify each feature against expected behavior.
- Regression testing: Re-run important test cases after fixes or changes.
- Negative testing: Validate behavior for invalid inputs and missing required fields.

## 9. Risks

- Demo website behavior may not match a full e-commerce application.
- Signup and search features may be unavailable.
- Some issues may be intentional demo behavior.

## 10. Defect Lifecycle

New -> Assigned -> Open -> Fixed -> Retest -> Verified -> Closed

Alternative outcomes:

- Reopened
- Duplicate
- Not a Bug
- Deferred

## 11. Test Deliverables

- Test plan
- Test case sheet
- Bug report sheet
- RTM sheet
- Test execution summary
