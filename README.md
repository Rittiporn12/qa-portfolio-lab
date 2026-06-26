# QA Portfolio Lab

![QA](https://img.shields.io/badge/QA-Manual%20Testing-blue)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange)
![Markdown](https://img.shields.io/badge/Documentation-Markdown-lightgrey)

A software testing portfolio project that demonstrates manual testing, API testing, test case design, bug reporting, and testing documentation.

## Overview

This repository contains sample QA documents and testing workflows created to demonstrate my understanding of software testing practices.

The goal of this project is to show how I approach software quality, test planning, bug reporting, API testing, and documentation.

## What This Project Includes

- Manual Test Cases
- Bug Reports
- Test Plan
- API Testing with Postman
- Retest and Regression Testing Notes
- Testing Summary Report

## Tools Used

- Postman
- Browser DevTools
- Markdown
- Git
- GitHub
- Jira-style Bug Report Format

## Project Structure

```txt
qa-portfolio-lab/
├── README.md
├── .gitignore
├── demo-login/
│   └── index.html
├── test-cases/
│   └── login-test-case.md
├── bug-reports/
│   └── login-validation-bug.md
├── test-plan/
│   └── test-plan.md
├── postman/
│   └── user-api-testing.postman_collection.json
├── screenshots/
│   ├── README.md
│   ├── login-page.png
│   ├── valid-login.png
│   ├── empty-email-validation.png
│   ├── invalid-email-format.png
│   └── bug-example.png
└── docs/
    └── testing-summary.md
```

## Demo Application

This repository includes a simple demo login page located in `demo-login/index.html`.

The demo page is used as a sample application for manual testing practice. It intentionally contains a password validation issue so that the testing documents can demonstrate how to write test cases, bug reports, and testing summaries.

## Sample Testing Scenario

This project uses a sample Login feature as the main testing scenario.

The login feature includes the following test conditions:

- Valid email and valid password
- Invalid password
- Empty email field
- Empty password field
- Invalid email format
- API response validation
- Error message validation

## Test Result Overview

| Total Test Cases | Passed | Failed | Blocked |
|---|---|---|---|
| 5 | 4 | 1 | 0 |

One failed test case was found in password field validation and documented in the bug report.

## Testing Skills Demonstrated

- Writing clear test cases
- Identifying expected and actual results
- Writing bug reports with severity and priority
- Creating test plans
- Understanding retest and regression testing
- Documenting testing results
- Using Postman for API testing

## Quick Links

- [Live Demo Login Page](https://rittiporn12.github.io/qa-portfolio-lab/demo-login/)
- [Test Cases](./test-cases/login-test-case.md)
- [Bug Report](./bug-reports/login-validation-bug.md)
- [Test Plan](./test-plan/test-plan.md)
- [Postman Collection](./postman/user-api-testing.postman_collection.json)
- [Testing Summary](./docs/testing-summary.md)
- [Screenshots](./screenshots)

## Repository Sections

### Demo Application

The `demo-login` folder contains a simple login demo page used for manual testing practice. The page intentionally contains a password validation issue for QA documentation purposes.

### Test Cases

The `test-cases` folder contains manual test cases for the login feature.

### Bug Reports

The `bug-reports` folder contains Jira-style bug report examples.

### Test Plan

The `test-plan` folder contains the testing plan for the login feature.

### Postman Collection

The `postman` folder contains a sample Postman collection for API testing.

### Testing Summary

The `docs` folder contains the final testing summary report.

## How to Use This Repository

1. Open the test case document in `test-cases/login-test-case.md`
2. Review the failed test case `TC-LOGIN-004`
3. Open the bug report in `bug-reports/login-validation-bug.md`
4. Import the Postman collection from the `postman` folder
5. Review the final testing summary in `docs/testing-summary.md`

## Author

Created by Rittiporn Phungphai  
GitHub: [Rittiporn12](https://github.com/Rittiporn12)
