# Shipping Ships API

This API is designed to handle HTTP requests for managing ships, haulers, and docks. It provides endpoints for creating, reading, updating, and deleting resources.

## Endpoints

The API has the following endpoints:

* **GET /ships**: Retrieves a list of all ships
* **GET /ships/:id**: Retrieves a specific ship by ID
* **POST /ships**: Creates a new ship
* **PUT /ships/:id**: Updates a specific ship by ID
* **DELETE /ships/:id**: Deletes a specific ship by ID

* **GET /haulers**: Retrieves a list of all haulers
* **GET /haulers/:id**: Retrieves a specific hauler by ID
* **POST /haulers**: Creates a new hauler
* **PUT /haulers/:id**: Updates a specific hauler by ID
* **DELETE /haulers/:id**: Deletes a specific hauler by ID

* **GET /docks**: Retrieves a list of all docks
* **GET /docks/:id**: Retrieves a specific dock by ID
* **POST /docks**: Creates a new dock
* **PUT /docks/:id**: Updates a specific dock by ID
* **DELETE /docks/:id**: Deletes a specific dock by ID

## Sequence Diagram

[Sequence Diagram](./sequence_diagram.mmd)

## Running the API

To run the API, execute the `json_server.py` file. The API will be available at `http://localhost:8000`.
