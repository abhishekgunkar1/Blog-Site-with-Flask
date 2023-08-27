# Blog Site with Flask

Welcome. This is a web application built using Python and Flask, designed for users to create, update, and share their blogs. The application includes features for user registration, authentication, and profile management.

## Features

#### - User Registration: New users can sign up for an account.
#### - User Login: Registered users can log in securely.
#### - User Profile: Users can manage their profile information.
#### - Blog Creation: Users can write and publish their blogs.
#### - Blog Listing: Display a list of published blogs.
#### - Encryption: User passwords are securely hashed using Flask-Bcrypt.
#### - Database: SQLite is used to store user credentials and blogs.

## Prerequisites

Before you get started, make sure you have the following installed:

#### - Python 
#### - Flask
#### - Flask-WTF
#### - Flask-Login
#### - Flask-Bcrypt
#### - SQLite 

## Installation

1. Clone this repository:

```
git clone https://github.com/abhishekgunkar1/Blog-Site-with-Flask.git
cd Blog-Site-with-Flask
```


2. Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```
pip3 install -r requirements.txt
```

4. Set up environment variables:
Go to config.py file and update it with your configuration details.

5. Start the application:
```
python3 run.py
```


