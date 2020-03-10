# .NET

## Commands

### new

- `dotnet new webapi -n MyProject` : Creates a new ASP .NET Core Web API with the name `MyProject`.
- `dotnet new mvc -n MyProject` : Creates a new ASP .NET Web app with the name `MyProject`.

### add package

- `dotnet add package Newtonsoft.Json` : Adds the `Newtonsoft.Json` package reference.
- `dotnet add package Newtonsoft.Json -v 1.0.0` : Adds the `Newtonsoft.Json` version 1.0.0 package reference.

### build

- `dotnet build` : Builds the project.

### run

- `dotnet run` : Builds and runs the project.
- `dotnet watch run` : Builds and runs the project. Saving a file recompiles and re-runs.

### clean

- `dotnet clean` : Cleans the build outputs of the project.

### ef
- `dotnet tool install --global dotnet-ef` : Installs ef commands.
- `dotnet ef migrations add "DescriptionOfMigration" -p MyPersistenceProject -s MyAPIProject` : Adds a migration to the project.
- `dotnet ef database drop -p MyPersistenceProject -s MyAPIProject` : Drops the database of the project.