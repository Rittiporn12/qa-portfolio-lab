# Bug Report: Login Form Allows Empty Password

## Bug ID

BUG-LOGIN-001

## Title

Login form allows submission when the password field is empty

## Summary

The login form does not display the correct validation message when the password field is left empty. Instead of showing "Password is required.", the system shows a generic error message: "Invalid email or password."

## Severity

Medium

## Priority

High

## Environment

* OS: Windows 10
* Browser: Google Chrome
* Device: Desktop
* Test Type: Manual Testing

## Preconditions

The user is on the login page.

## Steps to Reproduce

1. Open the login page
2. Enter a valid email address
3. Leave the password field empty
4. Click the Login button

## Expected Result

The system should display a validation message:

```txt
Password is required.
```

## Actual Result

The system shows a generic error message:

```txt
Invalid email or password.
```

## Evidence

![Bug Evidence](../screenshots/bug-example.png)

## Severity Explanation

This is Medium severity because the issue affects form validation and user experience, but it does not completely block the entire login system.

## Priority Explanation

This is High priority because login validation is part of a core user flow and should be fixed before release.

## Suggested Fix

Add both client-side and server-side validation to prevent form submission when the password field is empty.

## Status

Open
