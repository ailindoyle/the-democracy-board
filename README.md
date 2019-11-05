# The Democracy Board

## Git Repository 

To clone:
```
$ git clone git@github.com:ailindoyle/the-democracy-board.git
```

## Building and running the application

### Prerequisites:
- node ^8 (8.11.1)
- npm ^5 (5.8.0)

To check which versions of the above you have, you can run `node -v` and `npm -v` on the command line.

### To install:

Pulls all packages defined in `package.json` into `node_modules` directory
```
$ cd /the-democracy-board
$ npm install 
```

### To run client side

Client runs on port 8000
```
$ cd client
$ gatsby develop
```

### To run server side

Server runs on port 8080
```
$ cd server
$ node server.js
```

### To verify the application is up and running correctly:
- Use Postman to send requests to http://localhost:8080/api
- Use any of the routes in the project

## Database Structure

## API Routes