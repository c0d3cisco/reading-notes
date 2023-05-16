# Express REST API

## Review: ES6 Classes

1. Classes are a template for creating **objects**.
2. Can a class declaration be hoisted?\
No, a class declaration cannot be hoisted. Hoisting is the process where you can call on a variable/function before declaring it without resulting in an error. Although class are a specialized function in javascript, it cannot be hoisted like a regular function; rather, it behaves like a variable declared with `let` or `const`.
3. How would you describe a constructor and contextual “this” to a non-technical friend?\
Good code is easy to read and efficient in its syntax so you can accomplish what is needed with fewer lines. The `this` is a JavaScript syntax allows a class to call on itself in order to more simply and efficiently call on itself in order to perform actions or additional attributes.

## Using Express Routing

1. Within Express, what does routing refer to?\
Routing refers to the endpoints response to a client request.
2. What is the difference between a route path and a route method?\
A route method is called on the express app in our server code. A few are  `get`, `post`, `use`. A route path is combined with the route methods to point the client to the correct endpoint.
3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?\
The parameter `next` can be added to a route handler whenever there it must pass some request to another route for further processing. If you include a `next` parameter, a follow up function must be included, otherwise the next will result in an error.

## Express Routing

1. What is an Express Router?\
It a minimal Express application that provides routing APIs like `.use`, `.get`, `.param`, and `route`
2. By what mean do we initialize express.Router() in an express server?\
It means you bring in the route instance by using `const router = express.Router()`, then the routes can be applied, and point the application to the specific routes.
3. What do we use route middleware for?\
Route middleware can be used to process data before it reaches an endpoint, as well as add modifications or additions to the endpoint URL.

## Reflection

1. What are your learning goals after reading and reviewing the class README?\
Is it bad to say that my learning goal is to keep up during this part and make sure I don't fall behind? I was able to keep up during the readings when talking about Express routes which I was understanding, but the sequelize and then adding the SQL operations seemed a bit overwhelming. That is why my goal is to keep an open mind and just "accept" the information as it is present it and try to really understand it at a later time.
