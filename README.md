# Go Fiber API Starter

A starter template for building APIs using Fiber with Golang.

## Features

- Fiber v2
- Config management with dotenv
- Basic folder structure
- Example routes and middleware

## Prerequisites

- Go 1.18 or higher
- Git

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/vijityannapon/go-fiber-api-starter.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd go-fiber-api-starter
   ```

3. **Install the dependencies**

   ```bash
   go mod download
   ```

4. **Copy `.env.example` to `.env` and modify as needed**

   ```bash
   cp .env.example .env
   ```

## Usage

1. **Run the server**

   ```bash
   go run cmd/app/main.go
   ```

2. **The server should now be running at `http://localhost:8080`**

## Folder Structure

```
go-fiber-api-starter/
├── cmd/
│   └── app/
│       └── main.go    # Entry point of the application
├── config/            # Configuration files
├── controllers/       # Controllers for handling HTTP requests
├── middleware/        # Custom middleware
├── routes/            # Route definitions
├── utils/             # Utility functions
├── go.mod             # Go module file
├── go.sum             # Go dependencies file
└── .env.example       # Example environment file
```

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.
