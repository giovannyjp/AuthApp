# AuthApp
heroku, angular, node.js

Full Stack Website 


[Part 1 ] 
Rest API - Node.js/ Express 
Token Generation & Authentication
CORS
Mongoose ODM
Angular 2/ Angular-CLI 
Angular Router, HTTP Module 
Angular 2-JWT
Auth Guard 
Angular Flash Message Module 
Compile & Deploy on Heroku 

[ Part 2 ]
Set-up backend Express server along with dependencies including: Mongoos, BCryptjs, Passport & more. We will create our users routes such as /register and /authenticate. 

Installations

Node.js 


1.What is Node.js ?
JavaScript runtime built on Chrome’s V8 JavaScript engine 
JavaScript running on the server
Used to build powerful, fast & scalable web applications
Uses an event-driven, non-blocking I/O model 
Works on a single thread using non-blocking I/O calls 
Supports tens of thousands concurrent connections 
Optimizes throughput and scalability in web apps with many I/O operations 
 This makes Node.JS FAST & EFFICIENT 

2.Installing Node.js
3.Using the REPL
4.NPM - Node Package Manager
Used to install node programs/modules 
Easy to specify link dependencies 
Modules get installed into the “node_modules” folder
 		$ npm install express 
`		$ npm install -g express 

5. Modules Work
Express - web dev framework 
Connect - Extensible HTTP server framework 
Socket.io - server side component for websockets 
Pug/ Jadde - template engine inspired by HAML 
Mongo / Mongoose - Wrappers to interact with MongoDB
Coffee-Script - CoffeeScript cmplier 
Redis - Redis client library 

6. package.json File
Goes in the root of your package/app
Tells npm how your package is structured and what to do to install it 
                             $ npm init 
*Remark: “author” name 
7.Basic Web Server

Download 
Node.js (   https://nodejs.org/en/ ) 
          		
 		 Folder Path ->    C:\Program Files\nodejs
			  	     		     C:\Projects\test
mongoDB (  https://www.mongodb.com/ )
		MongoDB NoSQL database and look at the fundamentals and the syntax to create,  
                            read, update and delete documents/data

[Part 3] - User Model & Register
Create our Mongoose user model and schema with the user fields. We will also complete the /register post route to sign up a new user and encrypt passwords with Bcrypt

Download 
Postman
https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop/related?hl=en


[Part 4] - API Authentication and Token
Implement Passport.js and JWT (Json Web Tokens) for authentication. Users will be able to register with the API and get a token to be able to submit to protected routes

ISSUE:
http://localhost:3000/users/authenticate

C:\Projects\meanauthapp\node_modules\jsonwebtoken\sign.js:97
    throw err;
    ^

Error: Expected "payload" to be a plain object.

[Part 5] - Angular 2 Components & Routes
We will create our front end Angular app using the Angular-CLI. We will generate all of the components and implement the router. We will also use a Bootstrap navbar. 

[Part 6] - Register Component, Validation & Flash Messages
We will add the homepage markup, create the register form component, create a validation service and implement the Angular2 flash messages module.

[Part 7] - Auth Service & User Registration
We will create the authentication service and the user registration functionality using the backend API /users/register endpoint.

[Part 8] - Login & Logout
We will make the login form and authenticate request giving us back a json web token and user data that we can then store in localstorage. We will also create the logout functionality. 

[Part 9] - Protected Requests & Auth Guard
We will create the service function to make requests to protected routes and we will add the authentication guard to protect pages.

