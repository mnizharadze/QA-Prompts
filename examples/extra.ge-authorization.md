# Test Case Design Prompt

## Purpose
This prompt helps generate comprehensive test cases for the authorization feature on extra.ge.

## Prompt
You are a senior QA engineer.

Analyze the following feature description and generate detailed test cases for the authorization process on extra.ge.

The authorization options include:

- **Email login:** must verify correct email format  
- **Phone login:** must be a valid Georgian phone number  
- **Gmail login via OAuth**  
- **Facebook login via OAuth**

Focus on:

- **Positive scenarios:** valid inputs, successful logins  
- **Negative scenarios:** invalid email formats, incorrect phone numbers, failed OAuth flows  
- **Edge cases:** empty fields, special characters, input length limits  
- **Boundary conditions:** minimum and maximum allowed characters  
- **Functional flows:** main workflows, optional paths, and alternate flows  
- **Input validation:** format checks, mandatory vs optional fields  
- **Security considerations:** authentication, authorization, and session handling  
- **Error messages:** clear and consistent feedback to the user  
- **State changes:** system or data updates after login attempts  
- **Dependencies:** preconditions or external systems affecting login

Feature description:  
Users can authorize on extra.ge using multiple methods:

- **Email:** must be in a valid email format (e.g., user@example.com)  
- **Phone:** must be a valid Georgian phone number starting with `+995` followed by 9 digits, or starting with `5` followed by 8 digits  
- **Gmail and Facebook:** users can sign in using OAuth, handling success and failure cases

## Output format
| Test Case ID | Scenario | Preconditions | Steps | Expected Result |
