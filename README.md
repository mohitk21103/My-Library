# My Library Project

A web application for managing a library collection using Flask and SQLAlchemy.

## Table of Contents

1. [About]
2. [Features]
3. [Installation]
4. [Usage]
5. [Contributing]
6. [License]

## About

This project is a web-based library management application built using Flask and SQLAlchemy. It allows users to add, edit, delete books, and view their library collection.

## Features

- **Add New Books:** Users can add new books to their library collection.
- **Edit Book Ratings:** Users can update the ratings of existing books.
- **Delete Books:** Users can remove books from their library.
- **View Library:** Display all books in the library with their details.

## Installation

Follow these steps to set up the project locally on your machine.

### Prerequisites

- Python 3.6+
- Flask
- SQLAlchemy

### Installation Steps

1. Clone the repository:

   
   git clone https://github.com/yourusername/my-library-project.git
   cd my-library-project
   

2. Create a virtual environment (optional but recommended):

  
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
 

3. Install dependencies:

   pip install -r requirements.txt


4. Initialize the database:


   python
   from app import db
   db.create_all()
   exit()
  

## Usage

### Running the Application

Start the Flask development server:


python app.py


Access the application in your web browser at `http://localhost:5000`.

### Using the Application

- **Home Page (`/`):** Displays the library collection with options to add, edit, and delete books.
- **Add New Book (`/add`):** Form to add a new book with title, author, and rating.
- **Edit Book (`/edit?id=<book_id>`):** Form to edit the rating of an existing book.
- **Delete Book (`/delete?id=<book_id>`):** Deletes the selected book from the library.

## Contributing

Contributions are welcome! Please follow these guidelines:

- Fork the repository and clone it locally.
- Create a new branch for your feature or bug fix.
- Commit your changes and push to your fork.
- Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License 
