# Bug Report 003

## Title

System allows creation of employees above the maximum age limit.

### Bug ID

BUG-003

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
2. Enter an age above the maximum allowed value.
3. Complete all required fields.
4. Submit the form.

### Expected Result

The application should reject the submission and display a validation message.

### Actual Result

The employee record is successfully created.

### Impact

Invalid employee records can be stored in the system.

### Status

Open

## Tested By

Immabel

## Date Reported

29 June 2026
