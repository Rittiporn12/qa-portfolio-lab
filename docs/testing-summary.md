# Testing Summary Report

## Project

QA Portfolio Lab

## Feature Tested

Login Feature

## Testing Type

- Manual Testing
- Functional Testing
- Negative Testing
- API Testing

## Summary

The login feature was tested using multiple test cases, including valid login, invalid password, empty fields, and invalid email format.

Most test cases passed successfully. However, one issue was found in the password field validation.

## Test Result Summary

| Total Test Cases | Passed | Failed | Blocked |
|---|---|---|---|
| 5 | 4 | 1 | 0 |

## Bugs Found

| Bug ID | Title | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-LOGIN-001 | Login form allows submission when password field is empty | Medium | High | Open |

## Failed Test Case

| Test Case ID | Scenario | Reason |
|---|---|---|
| TC-LOGIN-004 | Login with empty password field | No validation message is displayed |

## Retest Notes

The failed test case should be retested after the password validation issue is fixed.

Retest should confirm that:

- The password field shows a required validation message
- The form cannot be submitted when the password field is empty
- The error message is clear and easy to understand

## Regression Testing Notes

After the bug is fixed, regression testing should be performed on the following areas:

- Login with valid credentials
- Login with invalid password
- Empty email validation
- Empty password validation
- Invalid email format validation
- Error message display

## Conclusion

The login feature is mostly functional, but password field validation should be fixed before release.