Project Summary

Project Title: API Testing Project – Automation Exercise

*Description:

-This project uses the publicly-available APIs from Automation Exercise for practicing API testing. The collection includes requests such as getting product lists, searching products, user registration/login, and user account operations.

*Objectives:

-To import the API collection into Postman and explore the available endpoints (GET, POST, PUT, DELETE).

-To validate correct response codes and messages for different scenarios (valid input, invalid input, missing parameters).

-To improve skills in API test design: positive flow tests, negative tests, edge cases.

-To document tests and results for future reference or as a portfolio piece.

*Environment / Setup:

-Imported the collection in Postman (format: v2.1)

(Optional) Imported any required environment variables (e.g., base URL)

-Executed the requests and recorded responses:

-Example: GET /api/productsList → expected response code 200 and JSON list of products. (automationexercise.com)

-Example: POST /api/searchProduct without search_product parameter → expected response code 400 and error message “Bad request, search_product parameter is missing”. (automationexercise.com)

-Example: POST /api/verifyLogin with invalid details → expected code 404 and message “User not found!”. (automationexercise.com)

*Test Scenarios Covered:
-Retrieve full product list – GET /api/productsList

-Try unsupported method (POST) on /api/productsList – negative test

-Retrieve full brands list – GET /api/brandsList

-Invalid method (PUT) on /api/brandsList – negative test

-Search product with valid parameter – POST /api/searchProduct

-Search product missing parameter – POST /api/searchProduct with no search_product → check error response

-User login with valid credentials – POST /api/verifyLogin

-User login missing parameter (email or password) – negative test

-Create user account – POST /api/createAccount

-Delete user account – DELETE /api/deleteAccount

-Update user account – PUT /api/updateAccount

-Get user detail by email – GET /api/getUserDetailByEmail

*Why This Project is Valuable:

-Demonstrates ability to engage in API testing (not only UI testing).

-Shows knowledge of HTTP methods, status codes, request parameters, and response validation.

-Provides repository-ready material to showcase in CV or portfolio for test-automation roles.

-Flexible foundation: additional endpoints or complex scenarios can be added later.
