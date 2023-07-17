# API Integration

## Review API Server Build

1. Explain the different between a query string parameter and a path parameter.\
A query string parameter is a key value pair that is appended to the end of a URL. A path parameter is a value that is passed in the path of a URL.

2. What would our API URL with a path id parameter be given the following information:\
`http://oursite.com/v3/stuff/things`
3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.\
A dynamic API allows developers to simplify the process of creating an API by using a single source to handle all requests. So essentially one part of the URL, if changes, can take you to different parts of the website. This allows for the website to work without less bugs.

## Review Auth Server Build

1. Describe how you would use middleware to implement basic and bearer auth.\
Basic auth is used to authenticate a user with a username and password. Bearer auth is used to authenticate a user with a token. Middleware is used to check if the user is authorized to access the route.
2. Describe the handshake necessary to implement OAuth.\
OAuth is a way to authenticate a user with a third party. The user is redirected to the third party to login and then redirected back to the website with a token.
3. Describe how Role Based Access Control works to a non-technical friend.\
Role Based Access Control is a way to restrict access to certain parts of a website based on the user's role. For example, an admin would have access to all parts of the website, while a user would only have access to certain parts of the website.
