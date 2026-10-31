# MongoDB Practical Assignment

## Objective
To understand the basics of MongoDB, perform CRUD operations, practice query operators, and implement a real-world Library Management System.

## Tools Used
- MongoDB Community Server
- MongoDB Shell (mongosh)
- MongoDB Compass

## 1. Database and Collection Setup
- Database: `studentDB`
- Collections: `students` and `books`

## 2. Insert Operations
- `insertOne()` – Insert a single document.
- `insertMany()` – Insert multiple documents.

## 3. Read Operations
- `find()` – Retrieve all documents.
- `findOne()` – Retrieve a single document.
- Filter documents using specific fields such as course and price.

## 4. Update Operations
- `updateOne()` – Update a single document.
- `updateMany()` – Update multiple documents.

## 5. Delete Operations
- `deleteOne()` – Delete a single document.
- `deleteMany()` – Delete all documents in a collection (practice only).

## 6. Query Operators
Practiced the following MongoDB query operators:

| Operator | Purpose |
|---|---|
| `$gt` | Greater than |
| `$lt` | Less than |
| `$in` | Match any value in an array |
| `$and` | Match all conditions |
| `$or` | Match at least one condition |
| `$exists` | Check whether a field exists |

## 7. Real-World Use Case: Library Management System

Created a `books` collection to manage library book information.

### Document Fields
- `title` – Book title
- `author` – Author name
- `price` – Book price
- `available` – Availability status

### Operations Performed
- Inserted one and multiple books.
- Retrieved all books.
- Searched books by price and author.
- Updated book availability.
- Deleted a book by title.

## Outcome
Successfully practiced MongoDB database and collection creation, CRUD operations, query operators, and a real-world Library Management System.

## Author
Sivaraj G
