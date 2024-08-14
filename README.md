Recipe Management System

Overview
The Recipe Management System is a web application built using Python, Flask, and MySQL. This platform allows users to create, edit, delete, and manage their favorite recipes. The application provides a user-friendly interface and RESTful APIs to interact with the MySQL database where all the recipe data is stored.

Features
Create Recipes: Users can add new recipes by providing necessary details such as name, ingredients, and preparation steps.
Edit Recipes: Existing recipes can be updated with new information or modified as per the user's needs.
Delete Recipes: Users can remove recipes that are no longer needed.
View Recipes: All the saved recipes can be viewed with their details.
Technologies Used
Backend: Python, Flask
Database: MySQL
Frontend: HTML, CSS (optional if applicable)
API: RESTful API
Version Control: Git, GitHub

Getting Started
Prerequisites
Python 3.x
MySQL
Git

Installation
Clone the Repository

bash
Copy code
git clone https://github.com/JayBhagat18/Recipe-Management-System.git
cd Recipe-Management-System
Set Up Virtual Environment

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Configure MySQL Database

Create a new database in MySQL:
sql
Copy code
CREATE DATABASE recipe_db;
Update config.py with your MySQL credentials.
Run Database Migrations

bash
Copy code
flask db init
flask db migrate
flask db upgrade
Start the Application

bash
Copy code
flask run
Access the Application

Open your browser and navigate to http://localhost:5000.
API Endpoints
GET /recipes: Retrieve a list of all recipes.
GET /recipes/<id>: Retrieve details of a specific recipe.
POST /recipes: Create a new recipe.
PUT /recipes/<id>: Update an existing recipe.
DELETE /recipes/<id>: Delete a recipe.
Contributing
Contributions are welcome! Please follow the standard GitHub flow for contributing:

Fork the repository
Create a new branch
Make your changes
Submit a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
Jay Bhagat


