# Bug Report 005

## Title

Application fails to load the dashboard after multiple failed login attempts until the page is refreshed.

### Bug ID

BUG-005

### Module

Authentication

### Severity

High

### Priority

High

### Environment

Employee Management System

### Type

Exploratory Testing

### Preconditions

* User account exists with valid credentials.

### Steps to Reproduce

1. Open the login page.
2. Enter an incorrect password four consecutive times.
3. Enter the correct email address and password.
4. Click **Login**.

### Expected Result

The user should be authenticated successfully and redirected to the dashboard.

### Actual Result

The dashboard does not load even though the credentials are correct. Refreshing the page and logging in again allows access.

### Frequency

Consistently reproducible.

### Impact

Users with valid credentials may be unable to log in after several failed attempts, leading to confusion and a poor user experience.

### Suggested Investigation

Review the authentication flow to determine whether a temporary client-side or server-side lockout state is not being cleared after successful authentication.

### Status

Open

## Test Type

Exploratory Testing

## Tested By

Immabel

## Date Reported

29 June 2026
