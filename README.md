Golang-Serverless-Project

API Gateway + DynamoDB + Lambda Comlpete serveless stack

GET all Users Command : curl -X GET <URL>

GET specific user Command : curl -X GET <URL>\?email\=xyz@gmail.com

POST Command : curl --header "Content-Type: application/json" --request POST --data '{"email": "xyz@gmail.com", "firstName": "Somesh", "lastName": "Nayak"}' <URL>

PUT Command : curl --header "Content-Type: application/json" --request PUT --data '{"email": "abc@gmail.com", "firstName": "Somesh", "lastName": "Nayak"}' <URL> 

DELETE Command : curl -X DELETE <URL>\?email\=xyz@gmail.com
