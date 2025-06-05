# Reservation Form Test Cases

This folder contains manual test cases for the reservation form on the Simply33Food website.

## Scope

The tests are focused specifically on the reservation form component of the site, as accessed via laptop (PC). The purpose is to verify form functionality, validation rules, input boundaries, localization, and expected behavior under both positive and negative scenarios.

## Test Environment

- **Operating System**: Windows 11 (Full HD resolution – 1920x1080)  
- **Browser**: Google Chrome  
- **Browser Version**: 137.0.7151.57 (Official Build, 64-bit)  
- **Device Type**: Laptop  
- **Connection**: Wi-Fi 6 (802.11ax)
- **Test Date**: June 2025  

## Covered Scenarios

- Submitting valid reservation data  
- Validation of required fields  
- Email and phone number format validation  
- Logical boundary cases (0, -1, 60 guests, past dates, closed hours)  
- Confirmation message and email delivery  
- Security-related inputs (planned)  

## Structure

Each test case is written in its own `.md` file using a consistent, readable format and includes:
- Pre-conditions  
- Steps  
- Expected Results  
- Execution metadata  

## Notes

- The tests assume that no server-side changes (like disabling email notifications) interfere with execution.
- Business rules (e.g. maximum allowed guests) are interpreted based on observed system behavior unless officially documented.

---

**Author**: Petro Shutiak  
**Date Created**: 4.6.2025  
