# Users Service

The **Users Service** is a mock AWS Lambda service that provides CRUD operations for managing user records. This is part of the Infomedia Developer Portal POC.

## Features

- List all users
- Get a user by ID
- Create new users
- Update user data
- Delete a user

## Endpoints

- `GET /users` – Get all users
- `GET /users/{id}` – Get user by ID
- `POST /users` – Create a new user
- `PUT /users/{id}` – Update a user
- `DELETE /users/{id}` – Remove a user

## OpenAPI Spec

You can find the full OpenAPI specification [here](./openapi.yaml).
