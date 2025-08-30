# Manual QA Testing Guide

---

## Executive Summary

This guide outlines the standards and procedures for conducting manual Quality Assurance (QA) testing on the Shopping Website project. Its purpose is to ensure software quality, minimize defects, and deliver a seamless user experience. All QA team members and contributors are expected to adhere to these guidelines.

---

## Objectives

- To verify the Shopping Website meets business requirements and user expectations.
- To ensure all features function as intended across supported environments.
- To document, track, and communicate defects effectively for timely resolution.

---

## Manual QA Process

### 1. Review Test Artifacts

- Familiarize yourself with the project requirements and acceptance criteria.
- Reference the master test case document (`ShoppingWebsite_TestCases.md`) for detailed scenarios.

### 2. Prepare Test Environment

- Confirm access to test environments and necessary credentials.
- Test across supported browsers (e.g., Chrome, Firefox, Edge) and devices (desktop, mobile, tablet).
- Ensure test data is available and reset as necessary.

### 3. Execute Test Cases

- Follow each test case step-by-step.
- Record actual results and compare them against expected outcomes.
- Mark each test case as Pass/Fail.
- Note any deviations, errors, or unexpected behaviors.

### 4. Exploratory & Negative Testing

- Attempt scenarios outside standard test cases to uncover edge cases.
- Validate input validation, error handling, and security flows.
- Repeat critical scenarios as both authenticated and guest users.

### 5. Regression Testing

- Re-execute impacted test cases after bug fixes or new feature deployments.
- Confirm resolved issues no longer occur and no new defects are introduced.

---

## Bug Reporting Standards

When defects are identified, report using the template below for clarity and consistency:

**Bug Report Template**

| Field                | Description                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------|
| **Title**            | Clear, concise summary (e.g., “Add to Cart button unresponsive on mobile”)                  |
| **Environment**      | Browser, device, OS, app version (e.g., Chrome 116, Android 13, v1.0.3)                     |
| **Preconditions**    | State required before reproducing the issue (e.g., “User logged in; product in stock”)      |
| **Steps to Reproduce** | Numbered list of actions to replicate the issue                                             |
| **Expected Result**  | What should happen                                                                          |
| **Actual Result**    | What actually happens                                                                       |
| **Screenshots/Logs** | Visual or log attachments (if applicable)                                                   |
| **Severity/Priority**| (Optional) Indicate business impact (e.g., Critical, Major, Minor)                          |

**Example:**

```
Title: Checkout fails with error 500

Environment: Firefox 120, Windows 10

Preconditions:
- User logged in
- Cart contains at least one product

Steps to Reproduce:
1. Go to Cart page
2. Click 'Checkout'
3. Fill in valid shipping details
4. Click 'Place Order'

Expected Result: Order confirmation page appears, and order is created.
Actual Result: Error page is displayed (500 Server Error).

Screenshot: [attach file]
Severity: Critical
```

---

## Communication & Collaboration

- Use descriptive language in all reports and documentation.
- Tag relevant team members on critical or blocking defects.
- Participate in regular QA stand-ups or sync meetings.
- Always retest and update defect tickets after fixes.

---

## Glossary

- **QA (Quality Assurance):** Activities ensuring the product meets quality standards.
- **Test Case:** A set of actions and expected results to verify a feature/requirement.
- **Regression Testing:** Re-testing after updates to confirm unchanged areas still work.
- **Severity:** The impact level of a defect (Critical, Major, Minor, Trivial).
- **Priority:** The urgency with which a defect should be addressed.

---

## Best Practices

- Maintain test documentation up-to-date.
- Communicate blockers or risks early.
- Practice unbiased, user-centric testing.
- Respectful, constructive feedback is encouraged.

---

**For questions, improvements, or additional support, contact the QA Lead or open a discussion in the repository.**

---

**Happy Testing!**