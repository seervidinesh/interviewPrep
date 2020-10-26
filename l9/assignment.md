# Day 2 Assignment

Create a REST API Server with ExpressJS containing the following endpoints - 

1. `/auth/signup` - Signs up an user taking `email`, `password` and `name`.
2. `/auth/login` - Logins an user and sends a JWT token back to the client.
3. `/auth/me` - The client sends a JWT token in the header and this route decodes it, and send back the logged in user information.

Please note that all routes should validate the client request data and throw appropriate errors on different situations.

Also, you should use proper HTTP response codes for errors, valid response etc.