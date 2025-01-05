# Task Management API

This is a RESTful API for managing tasks, designed as part of a Master 1 Computer Science project. It supports CRUD operations (Create, Read, Update, Delete) for managing tasks. The project is built using **PHP**, **MySQL**, **Apache**, and **WAMP Server**.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project allows users to manage tasks using the following operations:
- **POST**: Create a new task
- **GET**: Retrieve a list of tasks or a specific task by its `id`
- **PUT**: Update a task by its `id`
- **DELETE**: Delete a task by its `id`

It is a simple task management API designed to help users perform basic CRUD operations via HTTP requests.

## Features

- **Create a Task**: Add a task with a title and description.
- **Read Tasks**: Retrieve a list of all tasks or a single task by its `id`.
- **Update a Task**: Modify the details of an existing task.
- **Delete a Task**: Remove a task using its `id`.
- Supports JSON format for data exchange.

## Technologies Used

- **PHP**: Backend programming language for the API.
- **MySQL**: Database used for storing tasks.
- **Apache**: Web server for hosting the API.
- **WAMP Server**: Development environment for running Apache, MySQL, and PHP.

## Installation

### Prerequisites

- **WAMP Server** (includes PHP, Apache, and MySQL)
- **Postman** (for testing the API)

### Steps to Install

1. **Install WAMP Server**:
   Download and install [WAMP Server](http://www.wampserver.com/) if you don't already have it.

2. **Clone the Repository**:
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/task-management-api.git
