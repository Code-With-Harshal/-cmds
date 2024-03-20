# .Net

## Windows

### Install dotnet Entity Framework Core tools
```
dotnet tool install --global dotnet-ef
```

### Update dotnet Entity Framework Core tools
```
dotnet tool update --global dotnet-ef
```

### Add New Migration to database
```
dotnet ef migrations add InitialCreate
```
### Upgrade Migrations to database
```
dotnet ef database update
```
### Remove Migrations to database
```
dotnet ef migrations remove
```
### Run Application
```
dotnet run
```
