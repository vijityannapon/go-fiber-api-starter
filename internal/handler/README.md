# internal/handler

This directory contains the HTTP handlers that define the routes and their respective request handling logic.

## Files

- **hello_handler.go**: This file contains a simple handler for the root route (`/`). It responds with a JSON message saying "Hello world".

# internal/handler/hello_handler.go

This file defines a simple HTTP handler for the root route (`/`).

## Key Functions

- `Hello(c *fiber.Ctx)`: Responds with a JSON message saying "Hello world".
