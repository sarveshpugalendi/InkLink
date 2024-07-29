# InkLink

InkLink is a modern blog application designed for seamless interaction with a user-friendly interface. Built using Flutter for the frontend and powered by a robust backend system, InkLink offers a comprehensive set of features for managing and discovering blogs.

## Features

- **Authentication**: Secure login, signup, and account recovery using Firebase Authentication.
- **Blog Feed**: View a list of blog posts with a card interface.
- **Blog Details**: Access detailed information about each blog post including user details, and perform actions like deleting, commenting, and liking.
- **Search**: Find specific blogs using search functionality.
- **Find People**: Discover and connect with other users.
- **Profile Management**: View and edit user profiles, with data pulled from the backend.
- **Responsive Design**: Optimized for various screen sizes and devices.

## Tech Stack

- **Frontend**: 
  - **Flutter**: Cross-platform framework for building the mobile app.
- **Backend**:
  - **Spring Boot**: Framework for creating RESTful web services.
  - **PostgreSQL**: Relational database for storing blog and user data.
- **Authentication**:
  - **Firebase Authentication**: Secure authentication for user management.

## Getting Started

To get started with InkLink, follow these steps:

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) installed on your machine.
- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) for Spring Boot.
- [PostgreSQL](https://www.postgresql.org/download/) installed and running.

### API Documentation

## Endpoints

- POST /api/auth/login: Login a user.
- POST /api/auth/signup: Register a new user.
- POST /api/auth/recover: Recover a user's account.
- GET /api/blogs: Retrieve a list of blogs.
- GET /api/blogs/{id}: Retrieve detailed information about a specific blog.
- POST /api/blogs/{id}/like: Like a specific blog.
- POST /api/blogs/{id}/comment: Comment on a specific blog.
- DELETE /api/blogs/{id}: Delete a specific blog.
- GET /api/users: Find users.
- GET /api/users/{id}: Retrieve user profile details.
- PUT /api/users/{id}: Update user profile.

### Screenshots

### Contributing

We welcome contributions to InkLink! To contribute, please follow these guidelines:

- Fork the Repository: Create a personal fork of the repository.
- Create a Branch: Create a new branch for your changes.
- Commit Changes: Make your changes and commit them with a descriptive message.
- Push to GitHub: Push your changes to your fork.
- Open a Pull Request: Submit a pull request to the main branch of the original repository.
