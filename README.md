# Bakery System

By James Fox

An MVC application written in C# to help organize Treats and Flavors. All data is stored on a SQL database. And Identity is used for users.

## Technologies Used

- C#
- GIT
- DotNet MVC Architecture
- HTML
- CSS
- MySql
- Entity Framework Core
- Identity

## Info

A site to help pair Treats with Flavores and vice versa.

## Project Requirements

1. .Net 5 SDK
2. MySQL
3. MySQLWorkbench

## Project Setup

1. Clone this repository to your desktop using git clone

```
git clone https://github.com/jfox25/Bakery.Solution
```

2. cd into Directive

```
cd Bakery.Solution
```

3. cd into the Project

```
cd Bakery
```

4. Run dotnet restore in the terminal

```
dotnet restore
```

### Setting up the Database

1. In Sql WorkBench, create a new schema.
2. Create an appsettings.json in the Bakery.Solution/Bakery directive.
3. Configure the following code snippet for your database, then add it to your appsettings.json file

```

{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database={DATABASE NAME};uid=root;pwd={PASSWORD};"
  }
}

```

4. Run this command.

```

dotnet ef Migrations add Initial

```

5. then run this command.

```

dotnet ef database update

```

### To Run the Project

1. Make sure you are in the Bakery.Solution/Bakery directive
2. Make sure you have your mySql server running
3. Start the project

```

dotnet run

```

4. Go to the localhost and you should be able to view the application

## GitHub Link

[Link to Code on GitHub](https://github.com/jfox25/Bakery.Solution)

## Bugs

No known bugs at this time.

## Future Improvements

- Plan to add full crud functionality to the application and make the selects smarter.

## License

MIT
Copyright (c) 2022 James Fox

```

```
