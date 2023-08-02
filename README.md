# Book Management

The Book Management project is a simple web-based application that allows users to manage books in a library. The application provides a set of RESTful APIs to perform various operations such as adding new books, updating book details, deleting books, and retrieving book information.

## Features

- Add a new book to the library.
- Update book details such as title, author, genre, and publication year.
- Delete books from the library.
- Get a book using id
- Get a list of all books available in the library.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 database
- Maven (for build and dependency management)
- RESTful API principles

## Getting Started

To get started with the Book Management application, follow the instructions below:

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL or another compatible relational database
- Maven

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/VivekPandey09032002/book-management.git
cd book-management

### **Book Management endpoints**

| Method | Endpoint                 | Description                              |
|--------|--------------------------|------------------------------------------|
| POST   | /books                   | Add a new book                           |
| PUT    | /books/{bookId}          | Update book details                      |
| DELETE | /books/{bookId}          | Delete a book                            |
| GET    | /books                   | Get a list of all books                  |
| GET    | /books/{bookId}          | Get details of a specific book by ID     |



