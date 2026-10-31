# API Test Execution Report

## 1. Project Details
- **Project:** E-Commerce Product API Testing
- **Tool:** Postman
- **API:** DummyJSON
- **Test Date:** 31 October 2026

## 2. Test Execution Summary

| Description | Result |
|---|---|
| Total Test Cases | 8 |
| Total Assertions | 36 |
| Passed Assertions | 35 |
| Failed Assertions | 1 |
| Passed Test Cases | 7 |
| Failed Test Cases | 1 |

## 3. Test Results

| Test ID | Test Description | Result |
|---|---|---|
| TC001 | Get All Products | PASS |
| TC002 | Get Single Product | PASS |
| TC003 | Search Products | PASS |
| TC004 | Create Product | PASS |
| TC005 | Update Product | FAIL |
| TC006 | Partial Update Product | PASS |
| TC007 | Delete Product | PASS |
| TC008 | Invalid Product | PASS |

## 4. Failed Test Details

**Test ID:** TC005

**Test Name:** PUT Update Product

**Expected Response Time:** Below 2000 ms

**Actual Response Time:** 30022 ms

**Reason:** The API response time exceeded the expected limit. Other validations passed.

## 5. Conclusion

The API testing was completed using Postman. Out of 36 assertions, 35 passed and 1 failed due to slow response time.

The API returned the expected status codes and response data for all eight test cases.