# .Net

## Windows

### Install dotnet Entity Framework Core tools
```sh
dotnet tool install --global dotnet-ef
```

### Update dotnet Entity Framework Core tools
```sh
dotnet tool update --global dotnet-ef
```

### Add New Migration to database
```sh
dotnet ef migrations add InitialCreate
```
### Upgrade Migrations to database
```sh
dotnet ef database update
```
### Remove Migrations to database
```sh
dotnet ef migrations remove
```
### Run Application
```sh
dotnet run
```
