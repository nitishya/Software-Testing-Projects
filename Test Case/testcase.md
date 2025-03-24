# Test Cases for Papa John's Website

This repository contains a list of test cases for the **Papa John's** website. The test cases cover various functionalities such as login, product selection, checkout, and more.

## Test Case Template

Each test case is documented in the following format:

| **Project Name**   | Papa John's                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Module Name**    | Login Page                                                                   |
| **Created By**     | [Nitish]                                                                  |
| **Created Date**   | [Date]                                                                       |
| **Peer Review By** | [Peer's Name]                                                                |
| **Peer Reviewed Date** | [Date]                                                                   |

---

## Test Case List

| **Scenario TID** | **Scenario Description**        | **Test Case ID** | **Pre Condition**                           | **Steps to Execute**                                                                                                                                                                                                                                                                      | **Expected Result**                                                                                         | **Actual Result**                                 | **Status** | **Executed QA Name** | **Misc (Comments)** |
|------------------|----------------------------------|------------------|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------|------------|----------------------|----------------------|
| 1                | Login Scenario with Valid User  | TC001            | 1. Papa John's Website is loaded. <br> 2. The user must have valid credentials (username and password).  | 1. Navigate to the Papa John's website (https://www.papajohns.com). <br> 2. Click on the **Login** button located at the top right corner. <br> 3. Enter the valid **username** `testuser@example.com`. <br> 4. Enter the valid **password** `ValidPassword123`. <br> 5. Click the **Login** button. | Login should work with valid credentials and user should be redirected to the homepage with their account info displayed. | Login is working with valid credentials. User is redirected to homepage. | Pass       | [QA Name]            | -                    |
| 2                | Login Scenario with Invalid User | TC002            | 1. Papa John's Website is loaded. <br> 2. The user must have invalid credentials (username and password). | 1. Navigate to the Papa John's website (https://www.papajohns.com). <br> 2. Click on the **Login** button located at the top right corner. <br> 3. Enter the invalid **username** `invaliduser@example.com`. <br> 4. Enter the invalid **password** `InvalidPassword123`. <br> 5. Click the **Login** button. | An error message should be displayed indicating invalid credentials. The user should not be logged in.       | Login failed, error message "Invalid credentials" displayed.     | Pass       | [QA Name]            | -                    |
| 3                | Password Reset Scenario          | TC003            | 1. Papa John's Website is loaded. <br> 2. User must have access to email for password reset.  | 1. Navigate to the Papa John's website (https://www.papajohns.com). <br> 2. Click on the **Login** button located at the top right corner. <br> 3. Click on **Forgot Password**. <br> 4. Enter the registered email address `testuser@example.com`. <br> 5. Click **Reset Password**. | User should receive an email with password reset instructions.                                               | Email received with reset instructions.                 | Pass       | [QA Name]            | -                    |
| 4                | Product Search Functionality     | TC004            | 1. Papa John's Website is loaded. <br> 2. User is on the homepage.  | 1. Navigate to the Papa John's homepage (https://www.papajohns.com). <br> 2. In the search bar, enter a valid product name, e.g., "Pepperoni Pizza". <br> 3. Click on the **Search** button. | Search results should display products related to the search term entered.                                  | Results show Pepperoni Pizza in search results.         | Pass       | [QA Name]            | -                    |
| 5                | Add Product to Cart              | TC005            | 1. Papa John's Website is loaded. <br> 2. User has selected a product to add to the cart.  | 1. Navigate to the product page for "Pepperoni Pizza". <br> 2. Click **Add to Cart** button. <br> 3. Verify that the cart icon is updated with the correct number of items. | Product should be added to the cart and the cart icon should reflect the added item.                         | Product added to the cart and cart icon updated.        | Pass       | [QA Name]            | -                    |
| 6                | Checkout Scenario                | TC006            | 1. User has added a product to the cart. <br> 2. User is logged in.  | 1. Navigate to the shopping cart. <br> 2. Click **Proceed to Checkout**. <br> 3. Enter shipping and payment details. <br> 4. Click **Place Order**. | Order should be placed successfully, and the user should see an order confirmation page.                     | Order placed successfully. Confirmation page displayed. | Pass       | [QA Name]            | -                    |
| 7                | Logout Functionality             | TC007            | 1. User is logged in on the Papa John's website.  | 1. Click on the **Account** button located at the top right corner. <br> 2. Click **Logout**. | User should be logged out and redirected to the homepage.                                                      | User logged out and redirected to homepage.           | Pass       | [QA Name]            | -                    |

---

## How to Add More Test Cases

1. **Identify the new functionality** that needs to be tested (e.g., mobile responsiveness, payment methods, product details).
2. **Create test cases** for that functionality, following the **Test Case Template**.
3. Ensure that **test data** is valid, and steps are **easy to understand**.
4. After execution, update the **Actual Result** and **Status**.

---

## Test Deliverables

- **Test Case Documents**: Contains all the test cases and their results.
- **Defect Logs**: Includes any bugs or issues found during testing.
- **Test Reports**: Final report of the test results.

---

## Test Tools

- **Selenium**: Used for automating cross-browser testing.
- **JIRA**: Used for bug tracking and defect reporting.
- **TestRail**: Used for test management and documentation.

---

Feel free to modify or extend this README file as per your project requirements.
