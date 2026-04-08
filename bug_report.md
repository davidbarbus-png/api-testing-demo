## 🐞 Bug Report: BUG001

**Title:** API returns incorrect status code for invalid post ID

**Steps to reproduce:**
1. Send GET https://jsonplaceholder.typicode.com/posts/999999

**Expected Result:**
- Status code 404 Not Found

**Actual Result:**
- Status code 200 OK
- Empty response returned

**Severity:** Medium  
**Priority:** High
