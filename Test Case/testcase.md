# Test Case Template for Papa John's Website

This repository contains a collection of test cases for the **Papa John's** website, including the **Login functionality** and other related features.

## Test Case Template Overview

The following format is used to document test cases in this repository:

| **Project Name**   | Papa John's                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Module Name**    | Login Page                                                                   |
| **Created By**     | [Nitish Kumar Yadav]                                                                  |
| **Created Date**   | [10 March 2025]                                                                       |
| **Peer Review By** | [Peer's Name]                                                                |
| **Peer Reviewed Date** | [Date]                                                                   |

### Test Case Structure

1. **Scenario TID:** A unique identifier for the test scenario.
2. **Scenario Description:** A brief description of the scenario being tested.
3. **Test Case ID:** Unique identifier for the test case.
4. **Pre Condition:** Any conditions that need to be satisfied before executing the test case.
5. **Steps to Execute:** Detailed steps to reproduce the test case.
6. **Expected Result:** The expected outcome of the test case.
7. **Actual Result:** The actual outcome observed after execution.
8. **Status:** Whether the test case passed or failed.
9. **Executed QA Name:** The name of the tester who executed the test case.
10. **Misc (Comments):** Additional comments or observations.

---

## Example Test Case: Login Functionality

| **Scenario TID** | **Scenario Description**        | **Test Case ID** | **Pre Condition**                           | **Steps to Execute**                                                                                                                                                                                                                                                                      | **Expected Result**                                                                                         | **Actual Result**                                 | **Status** | **Executed QA Name** | **Misc (Comments)** |
|------------------|----------------------------------|------------------|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------|------------|----------------------|----------------------|
| 1                | Login Scenario with Valid User  | TC001            | 1. Papa John's Website is loaded. <br> 2. The user must have valid credentials (username and password).  | 1. Navigate to the Papa John's website (https://www.papajohns.com). <br> 2. Click on the **Login** button located at the top right corner. <br> 3. Enter the valid **username** `testuser@example.com`. <br> 4. Enter the valid **password** `ValidPassword123`. <br> 5. Click the **Login** button. | Login should work with valid credentials and user should be redirected to the homepage with their account info displayed. | Login is working with valid credentials. User is redirected to homepage. | Pass       | [QA Name]            | -                    |
| 2                | Login Scenario with Invalid User | TC002            | 1. Papa John's Website is loaded. <br> 2. The user must have invalid credentials (username and password). | 1. Navigate to the Papa John's website (https://www.papajohns.com). <br> 2. Click on the **Login** button located at the top right corner. <br> 3. Enter the invalid **username** `invaliduser@example.com`. <br> 4. Enter the invalid **password** `InvalidPassword123`. <br> 5. Click the **Login** button. | An error message should be displayed indicating invalid credentials. The user should not be logged in.       | Login failed, error message "Invalid credentials" displayed.     | Pass       | [QA Name]            | -                    |

---

## How to Add New Test Cases

1. **Follow the Test Case Template** provided above to create new test cases for additional functionality on the Papa John's website.
2. Ensure each test case has clear preconditions, steps to execute, and both expected and actual results for tracking.
3. Add your name and the peer reviewer details in the corresponding fields for transparency and traceability.

---

## Test Deliverables

- **Test Cases:** A detailed list of all test cases executed for the project.
- **Test Reports:** Documenting the outcome of all test cases executed.
- **Defect Logs:** If any bugs or issues were found, they will be logged and tracked for resolution.

