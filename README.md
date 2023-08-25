# Clucker Website Project

**Clucker** is a modern web application developed as part of a module project at King's College London. Built using the latest features of the Python Django framework, Clucker aims to provide users with an intuitive and dynamic experience for thoughts sharing social meadia platform. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Clucker is a dynamic web application that leverages the power of Python Django, a high-level web framework known for its speed, security, and versatility. Developed as a project for Software Engineering GP at King's College London, Clucker embraces the latest advancements in Django, including mixin views, advanced routing, and more. The project focuses on delivering a seamless user experience while demonstrating the capabilities of Django's cutting-edge features.

## Features

- **User Authentication and Registration**: Secure user accounts with advanced authentication mechanisms provided by Django's built-in User model.

- **Real-time Notifications**: Utilise Django Channels to implement real-time notifications, ensuring users are updated promptly.

- **Dynamic Data Display**: Leverage Django's Template Language and model views to render dynamic data that keeps users engaged.

- **Advanced Routing with Mixins**: Implement sophisticated routing logic using Django's mixin views, allowing for reusable and modular code.

- **Profile Customization**: Allow users to personalise their profiles with the help of Django's forms and model manipulation.

## Installation

Follow these steps to set up and run Clucker on your local machine:

1. Clone the repository:
```
git clone https://github.com/XEZ1/clucker.git
cd clucker
```
2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate
```
3. Install the dependencies:
```
pip install -r requirements.txt
```
4. Run the migrations:
```
python manage.py migrate
```
5. Make sure all migrations have been deployed to the database:
```
python manage.py showmigrations
```
6. Create a superuser:
```
python manage.py createsuperuser
```
7. Run the server:
```
python manage.py runserver
```
8. Navigate to `localhost:8000` in your browser to view the application.

**P'S** host address might vary depending on the available hosts on your local machine. You can specify the host you would like to be used for the application in the command line.
