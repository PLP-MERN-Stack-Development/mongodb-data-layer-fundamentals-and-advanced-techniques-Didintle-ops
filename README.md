 # 📚 Week 1: MongoDB – Data Layer Fundamentals and Advanced Techniques

## 🚀 Objective
This project demonstrates foundational and advanced MongoDB techniques including data insertion, CRUD operations, aggregation pipelines, and indexing.

---

## 🛠️ Setup Instructions

### 1. Install MongoDB
- Option A: [Download MongoDB Community Edition](https://www.mongodb.com/try/download/community)
- Option B: [Create a free MongoDB Atlas cluster](https://www.mongodb.com/cloud/atlas/register)

### 2. Clone the Repository
```bash
git clone https://github.com/PLP-MERN-Stack-Development/mongodb-data-layer-fundamentals-and-advanced-techniques-Didintle-ops.git
cd mongodb-data-layer-fundamentals-and-advanced-techniques-Didintle-ops


Install Dependencies
bash
npm install mongodb

📂 Files Included
insert_books.js – Script to populate the plp_bookstore database with sample book data.

queries.js – MongoDB queries for CRUD, advanced filtering, aggregation, and indexing.

README.md – Instructions for setup and usage.

screenshot.png – Screenshot of MongoDB Compass or Atlas showing your collections and sample data.

📦 How to Run the Scripts

1. Run insert_books.js to populate the database
bash
node insert_books.js


This will:

Connect to your MongoDB instance

Drop the existing books collection if it exists

Insert 10+ sample book documents

Display inserted books in the terminal

2. Run Queries Using MongoDB Shell or Compass

Option A: Using MongoDB Shell (mongosh)
bash
mongosh
use plp_bookstore
load('queries.js')

Option B: Using MongoDB Compass
Connect to your local or Atlas cluster

Navigate to the plp_bookstore database

Open the books collection

Run queries manually from queries.js

🧪 Expected Outcome
A functioning MongoDB database with structured book data

Verified CRUD and advanced queries

Aggregation pipelines for analysis

Indexed fields with performance improvements

✅ Submission Checklist
[x] insert_books.js with sample data

[x] queries.js with all required queries

[x] README.md with setup and usage instructions

[x] Screenshot of MongoDB Compass or Atlas showing your data

[x] All files committed and pushed to GitHub

👤 Author
Didintle Lloyd Motshabi MongoDB Week 1 Assignment – PLP MERN Stack Development
