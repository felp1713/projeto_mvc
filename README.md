Basic MVC CRUD Project in Ruby on Rails
This is a simple study project designed to explore the fundamental concepts of the MVC (Model-View-Controller) pattern in Ruby on Rails. The project features a basic CRUD (Create, Read, Update, Delete) application for managing products, implementing the core Rails actions: show, edit, new, create, and destroy.

Features
MVC Structure: A straightforward setup following the Rails MVC pattern for clean separation of concerns.
CRUD Operations: Full functionality for creating, reading, updating, and deleting product entries.
Flash Messages: User feedback messages on successful and failed operations.
Routing and Views: Basic routing and view templates for managing products.
Getting Started
Follow these steps to clone and set up the project on your local machine.

Prerequisites
Ruby: Ensure you have Ruby installed (preferably version 3.0 or above).
Rails: Install Rails (version 7 or above is recommended).
Bundler: Install Bundler to manage gem dependencies.
Installation
Clone the repository

bash
git clone https://github.com/felp1713/projeto_mvc.git
cd your-repo-name
Install dependencies Use Bundler to install all gem dependencies.

bash
Copiar código
bundle install
Set up the database Set up the database with the following commands:

bash
Copiar código
rails db:create
rails db:migrate
Run the Rails server Start the Rails server to run the project locally.

bash
Copiar código
rails server
Access the application Open your browser and go to http://localhost:3000 to interact with the application.

Usage
Creating a Product: Go to the "New Product" page to add a new product to the database.
Reading Products: The homepage lists all products, where you can view individual product details.
Updating a Product: Click "Edit" on a product to modify its details.
Deleting a Product: Use the "Delete" button to remove a product from the database.
Troubleshooting
If you encounter an error related to missing dependencies, try running bundle install again.
Ensure that your database configuration matches your local environment. Check config/database.yml if needed.
