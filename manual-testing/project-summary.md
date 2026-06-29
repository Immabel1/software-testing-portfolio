# Project Summary

## Project

Employee Management System

## Objective

To perform manual testing on the Employee Management System by validating authentication, employee management, input validation, boundary values, and business workflows.

## Testing Types Used

* Functional Testing
* Boundary Value Analysis
* Input Validation
* Exploratory Testing

## Test Execution Summary

* Total Test Cases: 25
* Passed: 21
* Failed: 4

## Defects Found

* Session remains active after logout.
* Employee below minimum age can be created.
* Employee above maximum age can be created.
* Name field accepts fewer characters than required.
* Dashboard fails to load after multiple failed login attempts until the page is refreshed.

## Outcome

The application's main functionality works as expected, but several validation and session management issues were identified and documented through detailed bug reports.

