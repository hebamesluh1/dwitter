# Dwitter
A lightweight, Twitter-inspired social media platform for sharing posts, following users, and engaging in real-time communication.

## Introduction
Dwitter is a minimalistic platform that emulates core Twitter functionalities. It allows users to post, follow others, and interact with the community in real-time.

## Features
- User authentication and profiles.
- Create and share posts.
- Follow/unfollow users.
- Responsive design for mobile and desktop.

## Installation

### Prerequisites
- Python (>= 3.8)
- Django (>= 4.x)
- PostgreSQL or SQLite

### Steps

1. **Clone the repository**:  
   Run the following command to clone the repository:
   ```bash
   git clone https://github.com/hebamesluh1/dwitter.git
   cd dwitter
   
2. **Set up the environment**:  
   Use Anaconda or run the following commands to create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Set up database** :
   ```bash
   python manage.py migrate

5. **Create a super user** :
   ```bash
   python manage.py createsuperuser

6. **Run the server** :
   ```bash
   python manage.py runserver

7. **Access the Application**
   Open your browser and navigate to the following URL: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Technology Used : 
1. **Django** for backend .
2. **HTML and Bulma CSS** for frontend .
3. **SQLite** for database .
   
