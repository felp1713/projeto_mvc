# Basic MVC CRUD Project in Ruby on Rails

[![Rails](https://upload.wikimedia.org/wikipedia/commons/6/62/Ruby_On_Rails_Logo.svg)](https://rubyonrails.org/)

This is a simple study project designed to explore the fundamental concepts of the MVC (Model-View-Controller) pattern in Ruby on Rails. The project features a basic CRUD (Create, Read, Update, Delete) application for managing products, implementing the core Rails actions: `show`, `edit`, `new`, `create`, and `destroy`.

## Features

- **MVC Structure**: A straightforward setup following the Rails MVC pattern for clean separation of concerns.  
- **CRUD Operations**: Full functionality for creating, reading, updating, and deleting product entries.  
- **Flash Messages**: User feedback messages on successful and failed operations.  
- **Routing and Views**: Basic routing and view templates for managing products.

## Tech

This project was built using:

- [Ruby on Rails](https://rubyonrails.org/) - Web application framework  
- [SQLite3](https://sqlite.org/index.html) - Lightweight database for development  

## Getting Started

Follow these steps to clone and set up the project on your local machine.

### Prerequisites

- **Ruby**: Ensure you have Ruby installed (preferably version 3.0 or above).  
- **Rails**: Install Rails (version 7 or above is recommended).  
- **Bundler**: Install Bundler to manage gem dependencies.

### Installation

1. **Clone the repository**
   ```sh
   git clone git@github.com:felp1713/projeto_mvc.git
   cd projeto_mvc
   ```

2. **Install dependencies**  
   Use Bundler to install all gem dependencies.
   ```sh
   bundle install
   ```

3. **Set up the database**  
   Set up the database with the following commands:
   ```sh
   rails db:create
   rails db:migrate
   ```

4. **Run the Rails server**  
   Start the Rails server to run the project locally.
   ```sh
   rails server
   ```

5. **Access the application**  
   Open your browser and go to `http://localhost:3000` to interact with the application.

## Usage

- **Creating a Product**: Go to the "New Product" page to add a new product to the database.  
- **Reading Products**: The homepage lists all products, where you can view individual product details.  
- **Updating a Product**: Click "Edit" on a product to modify its details.  
- **Deleting a Product**: Use the "Delete" button to remove a product from the database.
