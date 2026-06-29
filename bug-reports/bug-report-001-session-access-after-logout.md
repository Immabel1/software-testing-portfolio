# Bug Report 001

## Title

User can access protected pages after logging out using the browser Back button.

### Bug ID

BUG-001

### Module

Authentication

### Severity

High

### Priority

High

### Environment

Employee Management System

### Preconditions

* User is logged into the application.

### Steps to Reproduce

1. Log in with valid credentials.
2. Navigate to the dashboard.
3. Click **Logout**.
4. After returning to the login page, click the browser's **Back** button.

### Expected Result

The application should redirect the user to the login page or display an unauthorized access message.

### Actual Result

The dashboard remains accessible after logout.

### Impact

Users may gain unauthorized access to protected pages after ending their session.

### Status

Open
## Tested By

Immabel

## Date Reported

29 June 2026
