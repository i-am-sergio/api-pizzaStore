# API-PizzaStore

This is a simple api with connection to sqlite, with C# and .NET

To execute:
1. git clone del repository
2. dotnet restore
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
6. dotnet build and dotnet run to execute app