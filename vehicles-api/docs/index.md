# Vehicle Service API

This is a mock AWS Lambda CRUD API for managing vehicle data used for Infomedia's POC in Backstage.

## Overview

The Vehicle Service API provides endpoints to:

- List all vehicles
- Get a single vehicle by ID
- Create a new vehicle
- Update an existing vehicle
- Delete a vehicle

## API Details

- **Base URL**: `https://iqtz5jlenb.execute-api.us-east-1.amazonaws.com`
- **OpenAPI Spec**: [openapi.yaml](./openapi.yaml)

## Example Vehicle Object

```json
{
  "id": "1",
  "make": "Toyota",
  "model": "Corolla",
  "year": 2020
}
