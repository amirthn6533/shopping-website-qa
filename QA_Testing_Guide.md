# Manual QA Testing Guide

Welcome to the QA testing guide for the Shopping Website project!  
This document is designed to help you (or any team member) perform manual QA testing effectively.

---

## 1. What is QA Testing?

Quality Assurance (QA) testing ensures that the website works as expected and delivers a positive user experience. Manual QA involves a tester using the website just like a real user, following test cases, and reporting any bugs or issues found.

---

## 2. How to Perform Manual QA Testing

1. **Review Test Cases:**  
   Start by reading the provided test cases (`ShoppingWebsite_TestCases.md`).

2. **Set Up the Environment:**  
   - Prepare browsers (e.g., Chrome, Firefox).
   - Make sure the website is accessible and, if needed, login credentials are ready.

3. **Execute Each Test Case:**  
   - Follow each step exactly as written.
   - Observe the website’s behavior.
   - Compare actual results with expected ones.
   - Record the outcome (pass/fail).

4. **Document Issues:**  
   - If something doesn’t work as expected, document the steps to reproduce, actual vs. expected results, and any error messages.

---

## 3. How to Report Bugs

When you find a bug, report it clearly:

- **Title:** A short, descriptive summary.
- **Steps to Reproduce:** Numbered steps so anyone can follow and see the bug.
- **Expected Result:** What should have happened.
- **Actual Result:** What actually happened.
- **Screenshots:** Attach images if possible.
- **Environment:** Browser, OS, and device info.

**Example:**
```
Title: Unable to add product to cart

Steps to Reproduce:
1. Login as a valid user
2. Browse to a product page
3. Click 'Add to Cart'

Expected Result: Product should be added to cart.
Actual Result: Nothing happens, and no error message is shown.

Screenshot: [attach image]
Environment: Chrome 116, Windows 11
```

---

## 4. Tips & Best Practices

- Test on multiple browsers and devices.
- Log out and repeat some scenarios as a guest user.
- Try invalid inputs and edge cases.
- Keep communication clear and respectful.
- Always retest bugs after fixes.

---

**Happy Testing!**