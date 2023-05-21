# API Testing Challenge
This repository contains the solution for the API testing challenge, which aims to verify your experience in testing the REST API resources available on https://gorest.co.in/.

## Challenge Description
The second task of the challenge requires you to create a Postman collection that covers the testing of one of the four REST API resources provided by https://gorest.co.in/. The collection should include tests for different levels and types of testing to ensure critical defects are identified. Additionally, the solution should enable the testing of the provided functionality as part of a CI/CD pipeline by utilizing Postman collections executed via Newman.

## API Testing Approach
The chosen approach for API testing includes the following key aspects:

Test Coverage: The tests aim to cover various levels and types of testing, including positive and negative scenarios, boundary value analysis, error handling.

Modularity: The Postman collection is organized in a modular manner, with separate folders or requests for different functionalities or endpoints. This ensures easy maintenance, scalability, and reusability of the tests.

Data-Driven Testing: Whenever applicable, data-driven testing is implemented by parameterizing the requests and utilizing different data sets to verify the behavior of the API across various scenarios.

Assertions and Validation: The tests include assertions and validation checks to verify the correctness of the API responses, including status codes, response headers, response bodies, and specific data elements.

Error Handling: The tests cover error scenarios and verify that the API returns appropriate error responses with meaningful error messages and correct HTTP status codes.

## Solution Details
The solution for this challenge includes the following components:

Postman Collection: The Postman collection file (ChallengeCollection.json) contains the requests, tests, and environments necessary to test the chosen REST API resource. It includes the necessary authentication token obtained from https://gorest.co.in/consumer/login or https://dummy.restapiexample.com/ to authenticate the requests.

## Environment Variables: The environment file (/ChallengeEnvironmentpostman_environment.json) contains the required environment variables, including the authentication token, base URL, and any other necessary variables for the tests to run successfully.

## Execution Instructions: To execute the tests locally, follow these steps:

Import the Postman collection and environment files into your Postman application.
Set the necessary environment variables, including the authentication token.
Run the collection and observe the test results.
Alternatively, you can execute the Postman collection using Newman by running the following command in the terminal:
newman run https://api.getpostman.com/collections/4190699-744a6ae2-453f-4c12-a655-554ee9daf3a9?apikey=PMAK-646a8b24d1209e1f7bad5ebc-b96bc11f1398d393e769d753edccba81de --environment  https://api.getpostman.com/environments/4190699-1bcaf483-08f5-4d69-aa29-fce6e09e1729?apikey=PMAK-646a8b24d1209e1f7bad5ebc-b96bc11f1398d393e769d753edccba81de

## Conclusion
The provided solution demonstrates the testing of a chosen REST API resource from https://gorest.co.in/ using Postman. The tests cover different levels and types of testing, ensuring the thorough verification of critical defects. Additionally, the solution can be seamlessly integrated into a CI/CD pipeline by executing the Postman collection using Newman.

For any questions or further information, please feel free to contact author_name.

Note: If you have developed an automation framework as an extra bonus, please refer to the separate repository for detailed documentation and execution instructions.

Thank you!

