# Book REST API

A REST API and simple web frontend for managing books using Node.js and Express.

## Project Structure

book-rest-api/
├── server.js
├── package.json
├── .gitignore
├── README.md
└── public/
    ├── index.html
    └── style.css

## Installation

Open this folder in VS Code and run:

npm install

## Start

npm start

Open:

http://localhost:3000

## API Endpoints

GET /books - Get all books
GET /books/:id - Get one book
POST /books - Add a book
PUT /books/:id - Update a book
DELETE /books/:id - Delete a book

## Frontend

The HTML and CSS frontend is inside the public folder. It allows you to view, add, and delete books through the REST API.

## Note

Books are stored in memory and reset when the server restarts.
