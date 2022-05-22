# **Express Bookstore**

## **Overview**

An express.js application that validates a resource and then add tests to the application.

## **Requirements**

You will be adding validation to an application that stores one resource, books. Here is an example of what a book object should look like:

```json
{
  "isbn": "0691161518",
  "amazon_url": "http://a.co/eobPtX2",
  "author": "Matthew Lane",
  "language": "english",
  "pages": 264,
  "publisher": "Princeton University Press",
  "title": "Power-Up: Unlocking the Hidden Mathematics in Video Games",
  "year": 2017
}
```

- GET /books
  - Responds with a list of all the books
- POST /books
  - Creates a book and responds with the newly created book
- GET /books/[isbn]
  - Responds with a single book found by its isbn
- PUT /books/[isbn]
  - Updates a book and responds with the updated book
- DELETE /books/[isbn]
  - Deletes a book and responds with a message of “Book deleted”

## **Technologies Used:**

- [Node.js](https://nodejs.org/en/)
- [PostgreSQL](https://www.postgresql.org)
- [Express](https://expressjs.com/en/4x/api.html)
- [JSON Schema](https://json-schema.org)
- [Jest](https://jestjs.io)
- [Supertest](https://www.npmjs.com/package/supertest)
- [VSCode](https://code.visualstudio.com/docs)

## **How to Run**

```bash
# Clone Repository
$ git clone https://github.com/cng008/36.2_express-bookstore.git
$ npm install
$ createdb books
$ psql < data.sql
$ nodemon server.js
open http://localhost:3000/ in API viewer
```
