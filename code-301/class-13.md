# More CRUD

## Why this topic matters

1. Which HTTP method would you use to update a record through an API?<br>
We will be using the PUT HTTP method to update items in the db.
2. Which REST methods require an ID parameter?<br>
UPDATE and DELETE both need the ID parameter as they target specific items. GET can use an ID to read specific IDs

## Speed Coding: Building a CRUD API

1. What’s the relationship between REST and CRUD?<br>
They are each a side of the same coin. REST methods are those that communicate between the client and the server. These HTTP methods are used to call specific CRUD methods. CRUD methods are used by the server to interact with the database - this is the other side of that coin.
2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?<br>

>1. Set up the server to take in incoming request.
>2. Link Server to database.
>3. Set up internals of server to handle/process incoming request.
>4. Map those request send through REST methods through the necessary CRUD methods
>5. Send data to client

## Things I want to know more about
