# User Management Backend

## API Endpoints

### Register a new user
**POST** `/api/users/register`

**Request Body:**
```json
{
    "username": "exampleUser",
    "password": "examplePass",
    "email": "user@example.com"
}

### Login a user
**POST** `/api/users/login`

**Request Body:**
```json
{
    "email": "user@example.com",
    "password": "examplePass"
}



