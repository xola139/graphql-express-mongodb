# GraphQL + Express + MongoDB

> A small project to illustrate using GraphQL with MongoDB in Express as simply as possible

Whilst trying to learn GraphQL I found a number of resources but they all complicated the process. This repo is intentionally as simple as possible.

## ES6
This project makes use of ES6 which requires a 4+ version of Node https://nodejs.org/en/download/

## MongoDB
In order to run this project you need to install MongoDB and ensure an instance is running.
https://www.npmjs.com/package/mongodb

```js
npm install mongodb --save
mongod
```

## NPM Modules
The following NPM modules are required:

* express
* express-graphql
* graphql
* mongoose
* babel
* babel-node

Install with:

```js
npm install
```

## Running the project
```js
npm start
```


### GraphQLObjectType
Each model has a GraphQLObjectType, you can add more...

### Mongoose Schemea
Contains a schema to let MongoDB know what the data structure is.

We also set up some resolvers for GraphQL to work with to get data from our MongoDB

### GraphQL Queries
Set up queries to work with our resolvers in the Mongoose Schema

#### Find a user

#### Show all users

### GraphQL Mutations
Set up our mutations to save / update with resolvers in our Mongoose Schema

#### Create a user

#### Update a user


# ToDo
* Great gif of the whole flow split screen
* Mutation resolver needs to go into the schema
