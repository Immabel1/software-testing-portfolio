# Bug Report 004

## Title

Name field accepts fewer characters than the minimum required length.

### Bug ID

BUG-004

### Module

Employee Management

### Severity

Low

### Priority

Medium

### Environment

Employee Management System

### Preconditions

* Admin is logged in.

### Steps to Reproduce

1. Navigate to **Create Employee**.
2. Enter a name shorter than the minimum required length.
3. Complete all remaining required fields.
4. Submit the form.

### Expected Result

The application should display a validation error.

### Actual Result

The form accepts the value and creates the employee.

### Impact

Invalid employee names may be stored in the database.

### Status

Open

## Tested By

Immabel

## Date Reported

29 June 2026
