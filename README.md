# API Testing Project using Postman

## Overview
This project demonstrates end-to-end API testing using Postman, covering real-world scenarios such as authentication, request chaining, and response validation.

## Workflow
Login → Create Product → Create Order → Get Order Details → Delete Product

## Key Features
- Token-based authentication (Bearer Token)
- API chaining using collection variables
- Dynamic data handling (token, productId, orderId)
- Pre-request scripting for generating dynamic values
- Test scripting using JavaScript (pm.expect)
- Response validation (status code, body, headers, response time)
- JSON parsing and schema validation
- SOAP API testing with XML response handling
- File upload testing (multipart/form-data)
- Error handling and debugging using Postman Console

## Variables Handling
All dynamic values such as token, productId, and orderId are managed using Postman collection variables.  
No separate environment file is used, keeping the project simple and self-contained.

## Tools Used
- Postman
- JavaScript (for scripting)
- REST & SOAP APIs

## How to Run
1. Import the collection JSON file into Postman
2. Run the collection using Collection Runner
3. Ensure internet connection for API endpoints

## Learning Outcome
- Hands-on experience in API automation testing
- Understanding of authentication and API workflows
- Improved debugging and validation skills
