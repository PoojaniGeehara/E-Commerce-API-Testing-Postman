# E-Commerce Product API Testing Using Postman

## 1. Project Overview
This project focuses on testing E-Commerce Product APIs using Postman and DummyJSON.

It includes API requests, automated testing, positive testing, negative testing, and response validation.

## 2. Tools Used
- Postman
- DummyJSON API
- JavaScript
- JSON
- Excel

## 3. API Details
**Base URL:** https://dummyjson.com

**API Documentation:** https://dummyjson.com/docs/products

## 4. Test Cases

| Test ID | Test Description | Method | Result |
|---|---|---|---|
| TC001 | Get All Products | GET | PASS |
| TC002 | Get Single Product | GET | PASS |
| TC003 | Search Products | GET | PASS |
| TC004 | Create Product | POST | PASS |
| TC005 | Update Product | PUT | FAIL |
| TC006 | Partial Update Product | PATCH | PASS |
| TC007 | Delete Product | DELETE | PASS |
| TC008 | Invalid Product | GET | PASS |

## 5. Test Validations
The following validations were performed:

- HTTP status codes
- Response body
- Product ID
- Product title and price
- Response time
- Error responses

## 6. Test Execution Results

| Metric | Result |
|---|---|
| Total Test Cases | 8 |
| Total Assertions | 36 |
| Passed Assertions | 35 |
| Failed Assertions | 1 |
| Passed Test Cases | 7 |
| Failed Test Cases | 1 |

**Failed Test:** TC005 – PUT Update Product

**Reason:** Response time was 30022 ms, exceeding the expected limit of 2000 ms.

The remaining validations passed successfully.

## 7. Project Structure

```text
E-Commerce-API-Testing-Postman/
│
├── collection/
│   └── E-Commerce-Product-API-Tests.json
│
├── screenshots/
│   └── Postman test screenshots
│
├── test-cases/
│   └── API-Test-Cases.xlsx
│
├── reports/
│   └── test-summary.md
│
└── README.md


## 8. How to Run
1. Open Postman.
2. Import the API test collection.
3. Select the E-Commerce API Environment.
4. Open Collection Runner.
5. Run the collection.
6. Check the test results.

## 9. Learning Outcomes
Through this project, I gained experience in:

- REST API testing
- Using Postman
- Writing automated test scripts
- Positive and negative testing
- Validating API responses
- Documenting test cases

## 10. Conclusion
This project helped me improve my API testing skills using Postman. Out of 36 assertions, 35 passed and 1 failed due to response time exceeding the expected limit.