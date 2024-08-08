# internal/database

This directory contains database connection and setup logic.

## Files

- **database.go**: This file contains functions to connect to the PostgreSQL database using GORM and handle database-related initialization.

# internal/database/database.go

This file contains the logic for connecting to the PostgreSQL database using GORM.

## Key Functions

- `ConnectDatabase()`: Establishes a connection to the database and initializes the GORM DB object.
