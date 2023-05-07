
# Book Directory REST API

This project is a REST API for managing a book directory. It provides endpoints for creating, retrieving, updating, and deleting books in the directory. The API is built with Node.js and uses the Express.js framework for handling HTTP requests.

## Getting Started


The server will start on port 5000 by default. You can change this by setting the `PORT` environment variable.

### Usage

The API provides the following endpoints:

- `GET /books`: Get all books in the directory.
- `GET /books/:id`: Get a specific book by ID.
- `POST /books`: Add a new book to the directory.
- `PUT /books/:id`: Update an existing book by ID.
- `DELETE /books/:id`: Delete a book from the directory by ID.


## TODO
- [ ] Use MongoDB to store book information.
- [ ] Implement authentication and authorization to secure the API.
- [ ] Add unit and integration tests to ensure API functionality.


