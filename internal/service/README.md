# internal/service

This directory contains the business logic of the application. Services handle the core functionality and interactions between different parts of the application.

## Files

- **user_service.go**: This file contains functions to handle business logic related to users, such as retrieving users from the repository.

# internal/service/user_service.go

This file contains business logic related to users.

## Key Functions

- `GetUsers()`: Retrieves all users by calling the repository function `GetAllUsers()`.
