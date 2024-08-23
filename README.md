# Go Rest API Automation

## Overview
This Postman collection tests the REST API endpoints for GoRest, specifically focusing on the following resources:
* Users
* Posts
* Comments
* Todos

## Prequisites
1. Postman: Ensure you have Postman installed on your machine.
2. API Token: Obtain an API token from GoRest by signing up or logging in. This token is required for authentication.

## Setting Up the Environment
1. Open Postman.
2. Create a new environment named GoRest API.
3. Add the following variables to the environment:
    * baseUrl: https://gorest.co.in/public/v2
    * token: Your GoRest API token.
    * userId: This will be set dynamically during the test run.
    * postId: This will be set dynamically during the test run.
    * commentId: This will be set dynamically during the test run.
    * todoId: This will be set dynamically during the test run.
  
## Steps to Add Environment Variables:
1. In Postman, go to the Environments tab.
2. Click on Add to create a new environment.
3. Name the environment GoRest.
4. Add the above variables along with the values.

## Importing the Collection and Environment
1. Download the Postman collection and environment files (.json) from the repository.
2. Open Postman.
3. Click on the Import button in the top-left corner.
4. Select the downloaded collection and environment files to import them into Postman.

## Running the Tests
1. Open the Collections tab in Postman.
2. Select the imported GoRest API Test Collection.
3. Make sure the GoRest environment is selected.
4. Click on the Run button to open the Collection Runner.
5. In the Collection Runner:
    * Ensure the GoRest environment is selected.
    * Click on Start Run.
  
## Additional Information
* For more details about the GoRest API, refer to the official documentation.
* For Postman-specific issues, check out the Postman Learning Center.
