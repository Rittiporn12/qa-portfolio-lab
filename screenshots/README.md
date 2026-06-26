# Screenshots

This folder contains testing evidence screenshots from the demo login page.

Screenshots are used to support test cases, bug reports, and testing summary documentation.

## Screenshot List

| File Name                    | Description                                                                  | Related Document |
| ---------------------------- | ---------------------------------------------------------------------------- | ---------------- |
| `login-page.png`             | Default login page before testing                                            | Test Cases       |
| `valid-login.png`            | Evidence for successful login with valid credentials                         | `TC-LOGIN-001`   |
| `empty-email-validation.png` | Evidence for empty email validation                                          | `TC-LOGIN-003`   |
| `invalid-email-format.png`   | Evidence for invalid email format validation                                 | `TC-LOGIN-005`   |
| `bug-example.png`            | Evidence for `BUG-LOGIN-001`, showing incorrect password validation behavior | Bug Report       |

## Current Bug Evidence

The main bug evidence is:

```txt
bug-example.png
```

This screenshot shows that when the password field is empty, the system displays:

```txt
Invalid email or password.
```

However, the expected result should be:

```txt
Password is required.
```

## Usage

Screenshots can be referenced in Markdown documents using relative paths.

Example:

```md
![Bug Evidence](../screenshots/bug-example.png)
```

## Notes

Do not include sensitive user data, real passwords, private tokens, API keys, or customer information in screenshots.

All screenshots should be used only for testing evidence and documentation.
