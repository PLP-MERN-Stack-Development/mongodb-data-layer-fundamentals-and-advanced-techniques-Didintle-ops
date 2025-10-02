📚 Week 1: MongoDB – Data Layer Fundamentals and Advanced Techniques
🚀 Objective

This project demonstrates both foundational and advanced MongoDB techniques, including:

Data insertion

CRUD operations

Aggregation pipelines

Indexing

🛠️ Setup Instructions
1. Install MongoDB

Choose one of the following options:

Option A: Download MongoDB Community Edition

Option B: Create a Free MongoDB Atlas Cluster

2. Clone the Repository
git clone https://github.com/PLP-MERN-Stack-Development/mongodb-data-layer-fundamentals-and-advanced-techniques-Didintle-ops.git
cd mongodb-data-layer-fundamentals-and-advanced-techniques-Didintle-ops

3. Install Dependencies
npm install mongodb

📂 Files Included
File	Description
insert_books.js	Script to populate the plp_bookstore database with sample book data.
queries.js	MongoDB queries including CRUD, filtering, aggregation, and indexing.
README.md	Setup instructions and usage guide (this file).
screenshot.png	Screenshot of MongoDB Compass or Atlas showing collections and sample data.
📦 How to Run the Scripts
1. Populate the Database

Run the data insertion script:

node insert_books.js


This will:

Connect to your MongoDB instance

Drop the existing books collection if it exists

Insert 10+ sample book documents

Display the inserted documents in the terminal

2. Run Queries
✅ Option A: Using MongoDB Shell (mongosh)
mongosh
use plp_bookstore
load('queries.js')

✅ Option B: Using MongoDB Compass

Connect to your local or Atlas MongoDB cluster

Navigate to the plp_bookstore database

Open the books collection

Run the queries manually from queries.js

🧪 Expected Outcome

By completing this project, you should achieve the following:

A fully populated plp_bookstore MongoDB database

Verified CRUD operations and advanced queries

Aggregation pipelines for analyzing data

Indexed fields for optimized performance

✅ Submission Checklist

 insert_books.js with sample data

 queries.js with all required queries

 README.md with setup and usage instructions

 Screenshot (screenshot.png) of your data in MongoDB Compass or Atlas

 All files committed and pushed to GitHub

👤 Author

Didintle Lloyd Motshabi
MongoDB Week 1 Assignment
PLP MERN Stack Development Program
