# JWT Token

A JWT (JSON Web Token) is a compact and secure way to transmit information between two parties as a JSON object. It is widely used for authentication and authorization in web applications.

## Simplified Explanation:
When a user logs into a web app, instead of storing their session on the server, the server creates a JWT and sends it to the client (browser or app). The client stores this token (usually in local storage or cookies) and includes it in every request to the server, proving the user's authentication status.

### Structure of a JWT:
A JWT consists of three parts:

Header: Contains metadata, such as the token type and the algorithm used for signing.

Payload: Holds the actual data (claims), like the user's ID or roles (this is where user info is stored).

Signature: Ensures the token's authenticity and that it hasn't been tampered with, using a secret key known to the server.
