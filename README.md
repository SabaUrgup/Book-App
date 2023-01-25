# Book-App

Book Application

It is a repo created by learning and running the medium article[^1] from the developer named Steven Victor

> A Simple Book RestAPI

## Technologies Used

[node]: (https://nodejs.org)

- [Node.js](node)
- [PostgreSQL](node)
- [Express.js](https://expressjs.com).
- [ESLint](https://eslint.org/).
- [Airbnb](https://www.npmjs.com/package/eslint-config-airbnb).

## Installations

#### Getting started

- You need to have Node and NPM installed on your computer.
- Installing [Node](node) automatically comes with npm.

#### Clone

- Clone this project to your local machine

#### Setup

- Installing the project dependencies
  > Run the command below
  ```shell
  $ npm install
  ```
- Start your node server
  > run the command below
  ```shell
  $ npm run dev
  ```
- Use `http://localhost:8000` as base url for endpoints

## API Endpoints

| METHOD | DESCRIPTION                             | ENDPOINTS                 |
| ------ | --------------------------------------- | ------------------------- |
| POST   | Add a book                              | `/api/v1/books`           |
| GET    | Get all the book                        | `/api/v1/books`           |
| PUT    | Update the details of a book            | `/api/v1/books/:bookId`   |
| GET    | Get a book particular book              | `/api/v1/books/:bookId`   |
| DELETE | Remove a book                           | `/api/v1/books/:bookId`   |

## Resources

Some websites were consulted for library and commands.

* victorsteven Medium[^1]
* [victorsteven Github](https://github.com/victorsteven/Book-app-NodeJS-PostgreSQL-Travis-Coveralls-Code-Climate)
[^1]: [victorsteven Medium](https://medium.com/@victorsteven/restful-api-with-nodejs-express-postgresql-sequelize-travis-mocha-coveralls-and-code-climate-f28715f7a014)
