# API Test Cases

## TC001 - Get all posts

Description:
Verify that the API returns a list of posts.

Priority: High

Preconditions:
- API is available

Request:
GET https://jsonplaceholder.typicode.com/posts

Expected result:
- Status code is 200
- Response is JSON
- Response contains list of posts

---

## TC002 - Get single post

Description:
Verify that a specific post can be retrieved by ID.

Priority: High

Preconditions:
- API is available

Request:
GET https://jsonplaceholder.typicode.com/posts/1

Expected result:
- Status code is 200
- Response contains post with ID = 1

---

## TC003 - Invalid endpoint

Description:
Verify that API returns correct error for invalid endpoint.

Priority: Medium

Preconditions:
- API is available

Request:
GET https://jsonplaceholder.typicode.com/invalid

Expected result:
- Status code is 404

---

## TC004 - Non-existing post ID

Description:
Verify behavior when requesting non-existing resource.

Priority: Medium

Preconditions:
- API is available

Request:
GET https://jsonplaceholder.typicode.com/posts/9999

Expected result:
- Status code is 404 or empty response
