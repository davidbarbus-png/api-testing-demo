# API Bug Report

## Bug 001 - Inconsistent response for non-existing post

Steps to reproduce:
1. Send GET request to /posts/9999

Expected result:
API should return 404 Not Found

Actual result:
API returns empty object instead of clear error

Severity: Medium  
Priority: Medium  
Environment: Postman / Desktop

---

## Bug 002 - Generic error response for invalid endpoint

Steps to reproduce:
1. Send GET request to /invalid

Expected result:
Clear and structured error message

Actual result:
Unclear or generic response

Severity: Low  
Priority: Low  
Environment: Postman / Desktop
