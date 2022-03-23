# Entity Framework Core

### Run it

```sh
# install dependencies
dotnet restore

# update database to the most recent migrations
dotnet ef database update

# run the app
dotnet run
```

### Database

EF migrations helper code:

```s
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet ef migrations add InitialCreate
dotnet ef database update
```

## Reference

[Getting Started with EF Core](https://docs.microsoft.com/en-us/ef/core/get-started)