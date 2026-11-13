# Postman API Testing Summary

## Project
SauceDemo Manual Testing Project

## API Tool
Postman

## API Used
JSONPlaceholder REST API

## API Testing Performed

| HTTP Method | Endpoint | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| GET | `/users/1` | User details returned | User details returned | PASS |
| POST | `/users` | New user created | User created with ID 11 | PASS |
| PUT | `/users/1` | User information updated | User information updated | PASS |
| DELETE | `/users/1` | User deleted successfully | Empty response returned | PASS |

## Test Results

- GET: **PASS** – 200 OK
- POST: **PASS** – 201 Created
- PUT: **PASS** – 200 OK
- DELETE: **PASS** – 200 OK

## Validation Performed

- Verified HTTP status codes
- Verified response body
- Verified POST response returned a new user ID
- Verified PUT response reflected updated user information
- Verified DELETE request returned a successful response

## Overall Result

**PASS**

## Conclusion

API requests were executed and validated successfully using Postman. The testing covered GET, POST, PUT, and DELETE operations.
