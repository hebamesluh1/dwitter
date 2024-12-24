# Dwitter
A lightweight, Twitter-inspired social media platform for sharing posts, following users, and engaging in real-time communication.

# Introduction
Dwitter is a minimalistic platform that emulates core Twitter functionalities. It allows users to post, follow others, and interact with the community in real-time.

# Features
User authentication and profiles.
Create and share posts.
Follow/unfollow users.
Responsive design for mobile and desktop.

# Installation
Python (>= 3.8)
Django (>= 4.x)
PostgreSQL or SQLite

# Steps 
1. Clone the repository:
   ``` git clone https://github.com/hebamesluh1/dwitter.git
cd dwitter ```
 2. Set up environment 
 you can open Anaconda or by : 
 ``` python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows ```
3. Install dependencies
``` pip install -r requirements.txt ```
4. Set up database
``` python manage.py migrate ```
5. Create super user
``` python manage.py createsuperuser ```
6. Run Server
``` python manage.py runserver ```
7. Access the application at
``` http://127.0.0.1:8000 ```


