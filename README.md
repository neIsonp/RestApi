# User Management API

This API was created with the aim of managing users, allowing for listing, creation, update and deletion of records. Below is a description of the API endpoints:

## Endpoints

### GET /api/user/all

Returns all registered users.

### GET /api/user/{id}

Returns the user corresponding to the given ID.

### POST /api/user

Creates a new user. The request body must contain the user data to be created in JSON format.

### PUT /api/user/{id}

Updates the data of an existing user. The request body must contain the updated user data in JSON format.

### DELETE /api/user/{id}

Deletes the user corresponding to the given ID.
