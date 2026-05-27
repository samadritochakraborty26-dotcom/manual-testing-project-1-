# Learning Guide: Manual Testing With SauceDemo

## Step 1: Understand The Application

Open SauceDemo and explore it like a real customer:

- Can you log in?
- Can you view products?
- Can you sort products?
- Can you add products to the cart?
- Can you checkout?
- What happens when required fields are blank?

## Step 2: Think Like A Tester

For every feature, ask:

- What should happen when the user does the correct thing?
- What should happen when the user makes a mistake?
- What fields are mandatory?
- What messages should appear?
- Can the user recover from errors?
- Does the UI show correct data after each action?

## Step 3: Write Test Cases

A good manual test case includes:

- Test case ID
- Requirement ID
- Scenario
- Preconditions
- Test steps
- Test data
- Expected result
- Actual result
- Status
- Priority

## Step 4: Execute Tests

Run each test case exactly as written. If the actual behavior matches the expected result, mark it as Pass. If it does not, mark it as Fail and create a bug report.

## Step 5: Report Bugs Clearly

A good bug report includes:

- Bug ID
- Summary
- Environment
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Status
- Screenshot or evidence, if available

## Step 6: Use RTM

The Requirement Traceability Matrix proves that each requirement has test coverage. Every requirement should connect to one or more test cases.

## Practice Checklist

- Execute all smoke test cases.
- Execute all functional test cases.
- Log at least three sample bugs.
- Update RTM status.
- Write a short final test summary.

## Mini Glossary

- SDLC: Software Development Life Cycle, the full process of building software.
- STLC: Software Testing Life Cycle, the testing process from planning to closure.
- Test Case: A documented condition to verify application behavior.
- Defect: A mismatch between expected and actual behavior.
- Severity: Business or technical impact of a defect.
- Priority: Urgency of fixing a defect.
- Regression Testing: Testing existing features after changes.
- Smoke Testing: Quick testing to verify that critical features are working.
