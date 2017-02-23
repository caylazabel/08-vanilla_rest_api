![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67)  Lab 08 In-Memory Resourse API
===
## The build out of this API:
- Created a HTTP server using the native node.js http module
- Created an object constructor which then creates a simple resourse with three properties
-       1. id
-       2. fruit
-       3. apple
- Created a custom url parser module that returns a promise
- Created a router constructor which handles GET, POST, PUT, & DELETE requests
- Created a storage module that stores resources by their schema type

## Server Endpoints
 ### '/api/mine'
 - POST Request
 - GET Request
 - DELETE Request


## Tests
-Wrote tests to ensure the /api/mine endpoint responds as described for each condition below:
- GET: test 404, it should respond with 'not found' for valid requests made with an id that was not found
- GET: test 400, it should respond with 'bad request' if no id was provided in the request
- GET: test 200, it should contain a response body for a request made with a valid id
- POST: test 400, it should respond with 'bad request' if no request body was provided or the body was invalid
- POST: test 200, it should respond with the body content for a post request with a valid body
