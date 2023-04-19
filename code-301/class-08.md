# APIs

## API Design Best Practices

1. What does REST stand for?<br>
Representational State Transfer
2. REST APIs are designed around a ____.<br>
It is designed around Platform independence and Service evolution.
3. What is an identifier of a resource? Give an example.<br>
It is a URL that 'unlocks' the resource data. 
4. What are the most common HTTP verbs?<br>
`GET`, `POST`, `PUT`, `PATCH`, and `DELETE`.
5. What should the URIs be based on?<br>
You should name them with logical names, they are used to group data sets as well as target specific data points.
6. Give an example of a good URI.<br>
`https://getpokemon.com/pokemons/original151/25`
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?<br>
A 'chatty' web API is a bad thing because it means a lot of small data packages are sent to the client. It is best to group data before sending. 
8. What status code does a successful `GET` request return?<br>
200
9. What status code does an unsuccessful `GET` request return?<br>
404
10. What status code does a successful `POST` request return?<br>
201
11. What status code does a successful `DELETE` request return?<br>
204

## Things I want to know more about
