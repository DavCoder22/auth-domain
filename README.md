# Authentication Domain

This repository contains the authentication domain for a microservices-based application. The domain includes two main services: `auth-service` and `user-service`.

## Services

### auth-service

The `auth-service` handles user authentication and authorization. It provides endpoints for user registration, login, and token management.

#### Endpoints

- **Register**: Register a new user.
- **Login**: Authenticate a user and return a JWT token.
- **Token Management**: Endpoints for token validation and refresh.

#### Dependencies

- **Database**: PostgreSQL
- **JWT Library**: For token generation and validation.

### user-service

The `user-service` manages user-related operations such as user profile management, updating user information, and retrieving user details.

#### Endpoints

- **Get User**: Retrieve user details by user ID.
- **Update User**: Update user information.
- **Delete User**: Delete a user account.

#### Dependencies

- **Database**: PostgreSQL

## Directory Structure

The repository is structured as follows:

