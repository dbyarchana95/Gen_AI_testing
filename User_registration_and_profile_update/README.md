# Gen_AI_Testing
## Project Overview

This project demonstrates how Generative AI can be used to automatically create functional test cases from Agile user stories and acceptance criteria.
The generated output follows an XRAY + Jira compatible format, making it suitable for QA teams working with Jira test management integrations.

### User Story

As a new user, I want to register with email or phone so I can save my details for future purchases.

##### Acceptance Criteria
Registration form collects:
- Name
- Email or Phone
- Password

System sends:
- OTP verification for phone registration
- Email verification for email registration

#### Objective 
Generate functional test cases in:

- XRAY format
- Jira-compatible structure
- QA-ready documentation style
- Generated Functional Test Cases

## Test Coverage Summary

| Module | Scenario Covered | Status |
|---|---|---|
| User Registration | Registration with Email | ✅ Covered |
| User Registration | Registration with Phone Number | ✅ Covered |
| Field Validation | Mandatory Field Validation | ✅ Covered |
| Field Validation | Invalid Email Validation | ✅ Covered |
| Field Validation | Invalid Phone Validation | ✅ Covered |
| Password Validation | Strong Password Validation | ✅ Covered |
| Password Validation | Weak Password Validation | ✅ Covered |
| OTP Verification | Valid OTP Verification | ✅ Covered |
| OTP Verification | Invalid OTP Verification | ✅ Covered |
| OTP Verification | Expired OTP Validation | ✅ Covered |
| OTP Verification | Resend OTP Functionality | ✅ Covered |
| Duplicate User Validation | Existing Email Validation | ✅ Covered |
| Duplicate User Validation | Existing Phone Validation | ✅ Covered |
| Login Validation | Login After Successful Registration | ✅ Covered |
| Verification Validation | Login Restriction Before Verification | ✅ Covered |
| Email Verification | Verification Link Validation | ✅ Covered |
| Error Handling | OTP Service Failure Handling | ✅ Covered |

#### Features Covered
- Positive Registration Scenarios
- Negative Validation Scenarios
- OTP Verification
- Email Verification
- Duplicate User Validation
- Password Policy Validation
- Mandatory Field Validation
- Login Validation After Registration
- Error Handling Scenarios


##### The generated format supports:

- Jira Test Management
- Manual Test Execution
- Agile QA workflows
- Requirement Traceability
- Benefits of Using Generative AI for Test Case Creation
- Faster QA documentation
- Reduced manual effort
- Better requirement coverage
- Consistent formatting
- Improved productivity for QA teams

#### Sample Prompt Used
```
User story: As a new user, I want to register with email or phone so I can save my details for future purchases.

Acceptance criteria:
Registration form collects name, email/phone, password and sends OTP/email verification.

Create functional test cases in XRAY+Jira format.
```

#### Future Enhancements
- Generate API test cases
- Generate automation scripts
- Export to CSV/XLSX
- Jira API integration
- AI-powered requirement traceability
- Risk-based test generation
- QA Automation