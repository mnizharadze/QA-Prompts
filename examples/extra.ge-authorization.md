## Purpose
This prompt helps generate comprehensive test cases for the authorization feature on extra.ge.

## Prompt

You are a senior QA engineer.

Analyze the following feature description and generate detailed test cases for the authorization process on extra.ge.

The authorization options include:
- Email login (must verify correct email format)
- Phone login (must be a valid Georgian phone number)
- Gmail login via OAuth
- Facebook login via OAuth

Focus on:
- Positive scenarios (valid inputs, successful logins)
- Negative scenarios (invalid email formats, incorrect phone numbers, failed OAuth flows)
- Edge cases (empty fields, special characters, input length limits)
- Boundary conditions (minimum and maximum allowed characters)

Feature description:
Users can authorize on extra.ge using multiple methods:
- Email: must be in a valid email format (e.g., user@example.com)
- Phone: must be a valid Georgian phone number starting with +995, followed by 9 digits, or starting with 5 containing 9 digits
- Gmail and Facebook: users can sign in using OAuth, handling success and failure cases

Output format:
| Test Case ID | Scenario                        | Preconditions               | Steps                                  | Expected Result                                      |
|--------------|--------------------------------|----------------------------|---------------------------------------|-----------------------------------------------------|
