# Gorest API automation via Postman

## Components:
* Postman_collection.json
* Environment.json

## Description:

1. Collection.json file contains CRUD operations requests with pre-request scripts and tests for endpoint: /public/v2/users
2. Environment.json file contains token and values of variables

### How to run test:
1. Import collection.json and environment.json files into postman
2. Open environment.json file in Postman and update Bearer token
Token can be generated here: https://gorest.co.in/my-account/access-tokens
3. Open Collection runner in Postman;
4. Run Gorest API collection;
