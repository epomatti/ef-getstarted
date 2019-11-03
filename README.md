# Entity Framework Core

## Database

Migration that creates the database:

```s
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet ef migrations add InitialCreate
dotnet ef database update
```

## Reference

[Getting Started with EF Core](https://docs.microsoft.com/en-us/ef/core/get-started)