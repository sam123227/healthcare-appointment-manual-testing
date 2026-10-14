# Manual Test Cases — Healthcare Appointment System

## Project Overview
Manual testing of a healthcare appointment web application, focusing on booking, input validation, appointment management, persistence, and dark-mode usability.

## Test Environment
- Application: Healthcare Appointment System
- Testing type: Manual functional and UI testing
- Test cases: 8

## Test Execution Results

| Test Case ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-001 | Book appointment with valid information | Appointment is booked and appears in My Appointments | Appointment booked and displayed successfully | PASS |
| TC-002 | Submit booking with an empty patient name | Booking is prevented and validation is displayed | Validation message displayed; appointment not booked | PASS |
| TC-003 | Submit booking with an invalid patient name | Invalid name is rejected | Validation message displayed; appointment not booked | PASS |
| TC-004 | Delete an appointment | Selected appointment is removed | Appointment deleted successfully | PASS |
| TC-005 | Refresh after booking an appointment | Appointment remains displayed | Appointment remained displayed after refresh | PASS |
| TC-006 | Book the same doctor for the same date and time twice | Duplicate booking is prevented | Second appointment was accepted | FAIL |
| TC-007 | Check text readability when switching themes | Text remains readable in both themes | Smaller descriptive text had low contrast in dark mode | FAIL |
| TC-008 | Check appointment form readability in dark mode | Fields, labels, placeholders, and values remain readable | Several form elements and their text were difficult to read | FAIL |

## Summary
- Total test cases: 8
- Passed: 5
- Failed: 3

## Notes
Failed test cases indicate behavior that needs further investigation. Results reflect the observed behavior during this test execution.
