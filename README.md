# Simple Hosted API

A basic Express.js API demonstrating how to create, host, and deploy a simple REST API.

## Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

The API will be available at `http://localhost:3000`

## API Endpoints

- `GET /` - Welcome message and endpoint documentation
- `GET /users` - Get all users
- `GET /users/:id` - Get a specific user by ID
- `POST /users` - Create a new user (requires name and email in request body)
- `GET /status` - API health status

## Example Requests

### Get all users
```
GET /users
```

### Create a new user
```
POST /users
Content-Type: application/json

{
  "name": "Alice Cooper",
  "email": "alice@example.com"
}
```

### Get a specific user
```
GET /users/1
```