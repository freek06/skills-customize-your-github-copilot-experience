# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API using FastAPI, including defining endpoints, handling HTTP methods, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create a FastAPI CRUD API

#### Description

Build a small FastAPI application that manages a list of books. Implement routes to create, read, update, and delete book records using standard HTTP methods.

#### Requirements
Completed program should:

- Define a FastAPI app in `main.py`.
- Create a `Book` data model with fields `id`, `title`, `author`, and `year`.
- Implement the following endpoints:
  - `GET /books` to return all books.
  - `GET /books/{book_id}` to return a single book by ID.
  - `POST /books` to add a new book.
  - `PUT /books/{book_id}` to update an existing book.
  - `DELETE /books/{book_id}` to delete a book.
- Return proper JSON responses, status codes, and error messages for missing books.

### 🛠️ Add request validation and documentation

#### Description

Use FastAPI models and built-in docs to validate input data and expose API documentation automatically.

#### Requirements
Completed program should:

- Use Pydantic models for request data validation.
- Return HTTP 422 validation errors for invalid input.
- Include example data or model descriptions where useful.
- Verify that the OpenAPI docs are available at `/docs`.
