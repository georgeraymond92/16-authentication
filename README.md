![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Authentication

### Author: George Raymond

### Links and Resources
* [repo](https://github.com/georgeraymond92/16-authentication)
* [travis](http://xyz.com)
* [back-end](http://xyz.com) (when applicable)
* [front-end](http://xyz.com) (when applicable)

#### Documentation
* [swagger](http://xyz.com) (API assignments only)
* [jsdoc](http://xyz.com) (All assignments)

### Modules
#### src
##### `auth`
* middleware.js
* router.js
* users-model.js

##### `middleware`
* 404.js
* error.js

`app.js`

`Index.js`


### Setup
#### `.env` requirements
* `PORT` - 3000
* `MONGODB_URI` - mongodb://localhost:27017/store

#### Running the app
* `npm start`
##### Signup
`echo '{"username":"String","password":"String"}' | http post :3000/signup`
##### Login
`http post :3000/signin -a username:password`

  
#### Tests
`npm test`

