# MongoDB Fundamentals - Week 1

## Setup Instructions

Before you begin this assignment, please make sure you have the following installed:

1. **MongoDB Community Edition** - [Installation Guide](https://www.mongodb.com/docs/manual/administration/install-community/)
2. **MongoDB Shell (mongosh)** - This is included with MongoDB Community Edition
3. **Node.js** - [Download here](https://nodejs.org/)

### Node.js Package Setup

Once you have Node.js installed, run the following commands in your assignment directory:

```bash
# Initialize a package.json file
npm init -y

# Install the MongoDB Node.js driver
npm install mongodb
Assignment Overview

This week focuses on MongoDB fundamentals including:

Creating and connecting to MongoDB databases

CRUD operations (Create, Read, Update, Delete)

MongoDB queries and filters

Aggregation pipelines

Indexing for performance

Database and Collection

Database: plp_bookstore

Collection: books

Sample Data: 12 books with fields: title, author, genre, published_year, price, in_stock, pages, publisher

Running the Scripts

Run the following command to insert the sample books into your database:
node insert_books.js
All MongoDB queries for CRUD, advanced queries, aggregation, and indexing are in queries.js.
You can run them in mongosh to test your queries.



### Files Included

Week1-Assignment.md: Detailed assignment instructions

insert_books.js: Script to populate your MongoDB database

queries.js: MongoDB queries organized by Task 2 → Task 5

README.md: Instructions and setup details

## Screenshot
A screenshot of the `books` collection in MongoDB Compass is included in this repository as `screenshot.png`.


## Requirements

Node.js (v18 or higher)

MongoDB (local installation or Atlas account)

MongoDB Shell (mongosh) or MongoDB Compass

## Resources

MongoDB Documentation

MongoDB University

MongoDB Node.js Driver

---

✅ Changes made:
- Added **database and collection info**.  
- Included **instructions for running `insert_books.js`**.  
- Mentioned `queries.js` as part of the submission.  
- Clean, simple, and aligned with expected outcomes.  

---


