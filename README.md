# eTickets System

## Project Overview
The **eTickets Movie Management System** is a web application that allows users to view movies currently showing in cinemas. Users can browse through available movies, view detailed information about them, and check which cinemas are screening them. Admin users have the ability to manage the movie catalog by adding or removing movies from the system. This platform streamlines the process of managing and viewing current movie screenings.

## Features

### User Features
- 🎥 **Browse Movies**: View a list of all movies currently available in cinemas, including detailed information such as title, description, genre, release date, and cinema details.
- 🏷️ **View Movie Details**: Users can click on any movie to view full details about the movie, including cast and crew, and the cinemas where the movie is being shown.

### Admin Features
- 🛠️ **Manage Movies**: Admins can add new movies, edit existing movies, or remove movies from the list of available screenings. Each movie contains detailed information, including title, description, release date, and the cinemas in which the movie is available.

## Tech Stack
- **Backend**: .NET Core MVC (Version 8.0)
- **Database**: Microsoft SQL Server
- **ORM**: Entity Framework Core

## Installation & Setup

### Prerequisites
- **Visual Studio 2022** (with .NET 8.0 SDK installed)
- **SQL Server** (local or cloud-based)

### Required NuGet Packages:
- `Microsoft.EntityFrameworkCore`
- `Microsoft.EntityFrameworkCore.SqlServer`
- `Microsoft.EntityFrameworkCore.Tools`
- `Microsoft.AspNetCore.Identity.EntityFrameworkCore`

### Steps to Run in Visual Studio

1. **Clone the repository**:
    ```bash
    git clone https://github.com/VaibhavDhanani/DOT-Net-Project.git
    ```

2. **Open the solution**:
    - Open the `.sln` file in Visual Studio.

3. **Set up the database connection**:
    - In the `appsettings.json` file, update the connection string to match your local SQL Server configuration:
    ```json
    "ConnectionStrings": {
      "DefaultConnectionString": "Server=YOUR_SERVER_NAME;Initial Catalog=eTicketsDB;Integrated Security=True;Connect Timeout=30;"
    }
    ```

4. **Run the following commands** in the Package Manager Console to set up the database:
    ```bash
    add-migration initial
    update-database
    ```

5. **Run the application**:
    - Press `F5` in Visual Studio to run the project.

## About
This project provides an efficient and user-friendly platform to manage movie screenings, allowing admins to keep movie listings updated and users to stay informed about what’s currently showing in cinemas.

## Resources
- **Readme**: For detailed instructions on setting up and running the project.
- **Languages**: C#, HTML

## Footer
© 2024 eTickets Movie Management System
