## 🧪 Test Case: TC001 - Get all posts

**Description:**  
Verify that the API returns a list of posts successfully.

**Priority:** High

**Preconditions:**  
- API is available

**Steps:**
1. Send GET request to https://jsonplaceholder.typicode.com/posts

**Expected Result:**
- Status code is 200
- Response is in JSON format
- Response contains a list of posts
- Each post contains: id, title, body

**Actual Result:**
- Status code is 200
- Response returned JSON array with posts
- Structure is correct

**Status:** PASS
## 🧪 Test Case: TC002 - Get post by valid ID

Steps:
1. Send GET /posts/1

Expected:
- 200 OK
- Returns post with ID = 1

Actual:
- Works correctly

Status: PASS
## 🧪 Test Case: TC003 - Get post by invalid ID

Steps:
1. Send GET /posts/999999

Expected:
- 404 Not Found

Actual:
- API returns 200 with empty object

Status: FAIL
