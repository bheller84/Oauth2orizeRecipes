OAuth2orizeRecipes
==================

OAuth2 security recipes and examples based on [OAuth2orize](https://github.com/jaredhanson/oauth2orize).

The express2 example from [OAuth2orize](https://github.com/jaredhanson/oauth2orize) is a great and simple
minimal OAuth2 Server in Node.js.  It is an example you can use to get an idea of how to write your
own OAuth2 Server in Node.js.  The recipes here are built from it and are more complete but also a bit more complex.

# Installation
```
git clone https://github.com/FrankHassanabad/Oauth2orizeRecipes.git
cd Oauth2orizeRecipes/resource-server
npm install
node app.js
```
Go here for how to use the REST API
https://github.com/FrankHassanabad/Oauth2orizeRecipes/wiki/OAuth2orize-Authorization-Server-Tests

# Features of the Authorization Server
* All 4 grant types exposed out of the box
* Access Tokens (includes configurable expiration time)
* Refresh Tokens
* REST tokeninfo endPoint for verifying a token is valid.
* Authorization tokens are only useable once
* SSL/HTTPS usage
