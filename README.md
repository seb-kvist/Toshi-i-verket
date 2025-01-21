# Toshi-I-Verket

Toshi-I-Verket is a web-based auction platform developed with .NET 8.0 and ASP.NET Core. The platform is designed to showcase various creations organized into multiple categories and facilitate auction management.

## Requirements

Before running the project, ensure the following are installed on your system:

- **.NET 8.0 SDK** or later
- A code editor, such as **Visual Studio** (recommended) or **Visual Studio Code**

## Packages

The project uses the following NuGet packages, which are automatically restored when you build the project:

- `Microsoft.EntityFrameworkCore` (9.0.0)
- `Microsoft.EntityFrameworkCore.InMemory` (9.0.0)

You do not need to install these manually. They will be restored by running `dotnet restore`.

## Setup Instructions

### Clone this repository:
```bash
git clone https://github.com/seb-kvist/toshi-i-verket.git
cd toshi-i-verket
```

### Restore required packages:
```bash
dotnet restore
```

### Run the application:
```bash
dotnet run
```

Open your browser and navigate to [https://localhost:5001](https://localhost:5001) (or the port specified in the console output).

## Testing

To run tests, use the following command:
```bash
dotnet test
```

## Features

- Utilizes **Entity Framework Core** with an in-memory database for development purposes.
- Displays a catalog of creations sorted by categories.
- Basic auction functionality.
