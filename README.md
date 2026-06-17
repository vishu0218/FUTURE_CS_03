# FUTURE_CS_03 – API Security Risk Analysis

## Project Overview

This project was completed as part of the Future Interns Cyber Security Internship Task 03. The objective was to perform a read-only API Security Risk Analysis on a public API and identify common security risks based on industry best practices and the OWASP API Security Top 10 framework.

## API Tested

JSONPlaceholder REST API

Base URL:
https://jsonplaceholder.typicode.com

## Objective

* Analyze public API endpoints
* Review authentication mechanisms
* Inspect API responses and headers
* Identify common API security risks
* Assess risk severity
* Provide remediation recommendations

## Tools Used

* Postman
* Browser Developer Tools
* JSONPlaceholder Documentation
* Microsoft Word
* GitHub

## Methodology

1. Reviewed API documentation.
2. Identified available endpoints and supported methods.
3. Tested endpoints using Postman.
4. Inspected API responses and headers.
5. Evaluated authentication requirements.
6. Identified potential security risks.
7. Classified findings based on severity.
8. Prepared a professional security assessment report.

## Endpoints Tested

* GET /users
* GET /posts
* GET /comments
* GET /users/1
* GET /users/2

## Findings Summary

### 1. Unauthenticated Access

Severity: Medium

The API allows access to resources without requiring authentication credentials.

### 2. Excessive Data Exposure

Severity: Medium

User-related information such as email, phone number, address, and company details are exposed in API responses.

### 3. Predictable Resource Enumeration

Severity: Low-Medium

Sequential numeric identifiers allow easy enumeration of available resources.

### 4. Missing Recommended Security Headers

Severity: Low

Some recommended security headers such as Content-Security-Policy (CSP), Strict-Transport-Security (HSTS), and X-Frame-Options were not observed.

## Risk Summary

| Finding                              | Severity   |
| ------------------------------------ | ---------- |
| Unauthenticated Access               | Medium     |
| Excessive Data Exposure              | Medium     |
| Predictable Resource Enumeration     | Low-Medium |
| Missing Recommended Security Headers | Low        |

## Screenshots

Screenshots of API testing and header analysis are available in the Screenshots folder.

## Conclusion

The assessment identified several common API security concerns including unauthenticated access, excessive data exposure, predictable resource identifiers, and missing recommended security headers. While the tested API is intended for learning and development purposes, these findings demonstrate important API security concepts that should be addressed in production environments.

## Author

Vishwajeet Godse

Future Interns – Cyber Security Internship 2026
