# Project Management System

![Java](https://img.shields.io/badge/Java-17+-brightgreen)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0+-brightgreen)
![React](https://img.shields.io/badge/React-18+-brightgreen)
![Vite](https://img.shields.io/badge/Vite-4.0+-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-blue)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

Project Management System is a full-stack web application designed to help teams manage their projects efficiently. It allows users to create, manage, and track projects and tasks, with the ability to assign tasks to specific users and monitor their status.

## Features

- **User Management**: Create and manage users.
- **Project Management**: Create, update, delete projects.
- **Task Management**: Assign tasks to users, update task statuses (e.g., assigned, in-progress, done).
- **React Frontend**: Modern UI built with React and Vite. (WIP)
- **Spring Boot Backend**: RESTful API built with Spring Boot.
- **PostgreSQL Database**: Data storage and retrieval using PostgreSQL. (WIP)


### Prerequisites

- **Java 21+**
- **Node.js 18+ and npm**
- **PostgreSQL 14+**


## API Endpoints

### Users

- **GET /api/users**: Get all users.
- **POST /api/users**: Create a new user.
- **PUT /api/users/{id}**: Update a user by ID.
- **DELETE /api/users/{id}**: Delete a user by ID.

### Projects

- **GET /api/projects**: Get all projects.
- **POST /api/projects**: Create a new project.
- **PUT /api/projects/{id}**: Update a project by ID.
- **DELETE /api/projects/{id}**: Delete a project by ID.

### Tasks

- **GET /api/tasks**: Get all tasks.
- **POST /api/tasks**: Create a new task.
- **PUT /api/tasks/{id}**: Update a task by ID.
- **DELETE /api/tasks/{id}**: Delete a task by ID.

## Testing

- Use Postman or similar tools to test API endpoints.
- Ensure your Spring Boot application is running and connected to PostgreSQL before running tests.


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
