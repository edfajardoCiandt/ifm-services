# Vehicle Service

This is a mock AWS Lambda CRUD service for managing vehicles in Infomedia's developer portal.

## Available Endpoints

- `GET /`: Get all vehicles
- `GET /{id}`: Get a specific vehicle
- `POST /`: Create a new vehicle
- `PUT /{id}`: Update an existing vehicle
- `DELETE /{id}`: Delete a vehicle

## Sample Vehicle Object

```json
{
  "id": "1",
  "make": "Toyota",
  "model": "Corolla",
  "year": 2020
}
