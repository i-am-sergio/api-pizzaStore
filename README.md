# API-PizzaStore

This is a simple api with connection to sqlite, with C# and .NET

To execute:
1. Clone this repository
2. Restore dependencies:
    ```
    dotnet restore
    ```
3.  Install EF Core Tools:
    ```bash
    dotnet tool install --global dotnet-ef
    ```
4. Generate first migration with EF Core migration tool:
    ```bash
    dotnet ef migrations add InitialCreate
    ```
5. Apply migrations to a database.
    ```bash
    dotnet ef database update
    ```
6. Execute `dotnet build` and `dotnet run` to execute app