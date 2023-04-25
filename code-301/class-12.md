# CRUD

## Why this topic matters

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents: <br>
100’s = <br> These are information codes about data transfer that lets the client know that the header has been received and accepted.
200’s = <br>  These are reserved for the success code.
300’s = <br> These are redirection codes. Tell the client that a resource is not available. It is up the client to request a new location.
400’s = <br> These are client error codes. The error is on the client side and it is usually caused by sending incorrect request with invalid parameters.
500’s = <br> These are server code. Usually resolved by requesting again but could ultimately be a bug with how the server is processing data. 
2. What is a status code 202? <br> In asynchronous processing, this code signifies that all validation requirements for the request where fulfilled when the request was send, and it will finish processing sometime after.
3. What is a status code 308? <br>  This is for the read action and it is used to permanently redirect the client request to a particular endpoint to another.
4. What code would you use if an update didn’t return data to a client? <br> 204
5. What code would you use if a resource used to exist but no longer does? <br> 410
6. What is the ‘Forbidden’ status code? <br> A 403 means the client does not have authority to that endpoint.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env? <br> 
A .env file contains sensitive information and it is not shared in the cloud. There are other mechanisms for implementing these pieces of sensitive information directly in MongoDB.
2. What is middleware? <br> 
Middleware is the code that stands between the request from the client and the server code.
3. What does `app.use(express.json())` do? <br>
Allows a JSON request to be parsed.
4. What does the `/:id` mean in a route? <br>
This is how the server routes the client's request.
5. What is the difference between `PUT` and `PATCH`? <br>
`PATCH` udpates part of the resource, while `PUT` updates the entire resource file. 
6. How do you make a default value in a schema? <br>
When writing the schema, include a default property next to the style of property with the content you want to make default.
7. What does a `500` error status code mean? <br>
It means there was an internal error with the server thus the client's request could not be fulfilled.
8. What is the difference between a status `200` and a status `201`? <br>
`202` means that a request has been fully, successfully processed, while a `201` status means that only a request has been successfully accepted.

## Things I want to know more about
