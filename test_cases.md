## API Test Cases

### TC001 - Get all posts

Priority: High

Preconditions:
- API is available

Request:
GET https://jsonplaceholder.typicode.com/posts

Expected result:
- Status code is 200
- Response is JSON
- Response contains list of posts
