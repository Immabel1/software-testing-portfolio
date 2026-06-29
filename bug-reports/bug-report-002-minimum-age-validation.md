# Bug Report 002

## Title

System allows creation of employees below the minimum age requirement.

### Bug ID

BUG-002

### Module

Employee Management

### Severity

Medium

### Priority

Medium

### Environment

Employee Management System

### Preconditions

* Admin is logged in.

### Steps to Reproduce

1. Navigate to **Create Employee**.
2. Enter an age below the minimum allowed value (e.g., 15).
3. Complete the remaining required fields.
4. Submit the form.

### Expected Result

The application should reject the submission and display a validation message indicating the minimum age requirement.

### Actual Result

The employee record is created successfully.

### Impact

Business rules regarding minimum employee age are not enforced.

### Status

Open

## Tested By

Immabel

## Date Reported

29 June 2026
