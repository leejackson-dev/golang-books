# Book Store API

Author: Lee Jackson  
Language: Go (Golang)  

---

## Project Summary

The Book Store API is a simple RESTful backend service built with Go, designed to manage a collection of books. It demonstrates core backend development skills including API design, CRUD operations, request handling, routing, and interaction with a data model layer.

This project is well-suited for recruiter review and showcases:
- Clean REST API design
- Practical use of Go’s standard library
- Clear separation of concerns (controllers, models, utilities)
- Use of third-party routing with Gorilla Mux
- JSON-based request and response handling

The API supports creating, reading, updating, and deleting books.

---

## Tech Stack

- Go (Golang)
- net/http
- Gorilla Mux
- encoding/json
- MVC-inspired project structure

- # Bookstore API – Endpoint Overview

## Get All Books
**Method:** GET  
**Endpoint:** `/books`  
**Description:** Retrieve a list of all books in the system.

---

## Get Book by ID
**Method:** GET  
**Endpoint:** `/books/{bookId}`  
**Description:** Retrieve details of a single book by its unique ID.

---

## Create Book
**Method:** POST  
**Endpoint:** `/books`  
**Description:** Create a new book entry.

---

## Update Book
**Method:** PUT  
**Endpoint:** `/books/{bookId}`  
**Description:** Update an existing book’s details by ID. Only provided fields are updated.

---

## Delete Book
**Method:** DELETE  
**Endpoint:** `/books/{bookId}`  
**Description:** Remove a book from the system by its ID.
