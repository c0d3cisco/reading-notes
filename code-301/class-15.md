# Authentication

## What is OAuth?

1. What is OAuth?<br>
OAuth is a protocol or framework that dictates how multiple systems can safely share a user's login/info.
2. Give an example of what using OAuth would look like.<br>
When we've been connecting to render or netlify by clicking on the gitHub or Google as a method of logging in.
3. How does OAuth work? What are the steps that it takes to authenticate the user?<br>
A user logs into the first site. That site then connects to the second site on behalf of the user after it receives a request token from the second site. The user uses second site as authenticator with the request token. The second site sends the user an approved access token. The users then gives the second token to the first site. The first site gives that token to the second site as proof of authentication on the user's behalf. The second site gives necessary information.
4. What is OpenID?<br>
It is another authentication protocol/framework but it works fundamentally different. OpenID does not has websites authentication between each other, but rather it has the user be the sole approver of the transactions.

## Authorization and Authentication Flows

1. What is the difference between authorization and authentication?<br>
Authentication verifies someone's identity, authorization determines the level of access that person has after authentication.
2. What is Authorization Code Flow?<br>
It is the OAuth2.0 and the flow is described above. This flow has three parties, client, and two sites.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?<br>
Additional security measures for the Authorization Code Flow that protects the client.
4. What is Implicit Flow with Form Post?<br>
It is the flow of OAuth2.0, but it all happens at one location (the same server).
5. What is Client Credentials Flow?<br>
This directly uses the clients information/credentials to gain an access token, rather than using the request token.
6. What is Device Authorization Flow?<br>
This flow is used for when it is hard to type in credential information for authentication purposes. It utilizes an external devise such as a phone to provide the authentication.
7. What is Resource Owner Password Flow?<br>
Similar to the Client credential but the user will specifically share their username and password, so this flow should only be used if no other flow is appropriate.
