# Recipe Application


RecipeApp is an easy-to-use web application that helps users manage and organize their favorite recipes. With a simple interface, this app makes it easy to create, view, update, and delete recipes. Users can also sort their recipes into categories, making it quick and convenient to find the right dish for any occasion. 

First you only need to create a user and then you can start saving and categorizing recipes

## Link to website

The project should be reachable through this link also:

https://recipe-application-tsoha.fly.dev/


## Table of Contents

- [Features For Future](#features-for-future)
- [Prerequisites](#prerequisites)
- [Setting up the Virtual Environment](#setting-up-the-virtual-environment)
- [Creating the Database](#creating-the-database)
- [Running the Application](#running-the-application)

## Features For Future


- Recipe Sharing
- Implement a search functionality based on recipe names.
- Allow users to search for recipes using specific ingredients.
- Enable the use of pre-existing ingredients to search for recipes
- Introduce a "Recipe of the Day" feature.
- Shopping Cart feature

## To test or Use the application locally

### Prerequisites

- Python 3.x
- PostgreSQL


## Setting up the virtual environment

1. Navigate to the root folder of the project:

```bash
cd recipe-app-tsoha
```

2. Create and activate virtual environment:

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```


3. Install dependencies


```bash
pip install -r ./requirements.txt
```

## Creating the Database


You can create a datbase with the following commands:

```bash
psql
```

```bash
CREATE DATABASE MY_DATABASE_NAME;
```

## Setting up the Environment Variables

1. Create .env file to project root 

Replace the placeholders with your actual database connection details and secret key. (You need to create a new database for this)

```bash
SQLALCHEMY_DATABASE_URI=<local-database-address>
SECRET_KEY=<secret-key>
```

2. Replace the placeholders with your actual database connection details and secret key.

- on mac for example my database address is:
```bash
SQLALCHEMY_DATABASE_URI=postgresql://localhost:port/MY_DATABASE_NAME
```

## Running the Application

1. Run application

```bash
flask run
```

Please report any issues or suggestions for improvement on the project's GitHub repository.

