# lab-1

This is a simple program that will print out the greetings for you.

endpoint: http://localhost:8080
path: greeting
Request type: GET
Optional parameter: name (String)

Use case:
1. No parameter: 
{
    "id": 1,
    "content": "Hello, World!"
}

2. Input name parameter:

{
    "id": 2,
    "content": "Hello, {name_input}!"
}

Instructions:
1. Download the simple-rest-service repository
2. Open the project in a local IDEA
3. Go to SimpleRestServiceApplication.java class
4. Hit the run button next to the SimpleRestServiceApplication.java class to start the service
5. You can test out the endpoint using Postman
