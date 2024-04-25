# MovieStore - ASP.NET Core App
## Requirements: .NET 8 SDK, SQL Server
### Topics covered:
- MVC pattern
- EF Core
    - CRUD
    - Migrations
    - Many-to-many relationships
- Identity
    - Authentication
    - Authorization (Roles)
- N-tier architecture
- Repository and UnitOfWork patterns

---

### Execution in terminal:
```bash
> git clone https://github.com/yanulia8/MovieStore.git
> cd .\MovieStore\MovieStore.Web\
```
> If needed, modify connection string in ./MovieStore.Web/appsettings.json according to your SQL Server path
```bash
> dotnet ef database update
> dotnet run
```
> Terminal log: **Now listening on: http://localhost:port**

---

## In order to access Content Management menu, log in as admin using pre-defined account: { login: **admin@gmail.com**, password: **Admin1234_** }

### Database schema:
![Database schema](https://i.imgur.com/r7Dk156.png)