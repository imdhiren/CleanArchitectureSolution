# CleanArchitectureSolution

## Description
A sample ASP.NET MVC 4 solution demonstrating Clean Architecture principles with multiple class library projects. The solution includes Core, Application, Infrastructure, and WebUI projects.

## Technologies Used
- ASP.NET MVC 4
- Entity Framework 6
- SQL Server (or any other database)

## Setup Instructions
1. **Clone the repository**: git clone https://github.com/imdhiren/CleanArchitectureSample.git
2. **Navigate into the solution directory**: cd CleanArchitectureSolution   
3. **Set up the environment**:
- Ensure .NET Framework 4.5.2 or later is installed.
- Restore NuGet packages for each project:
  ```
  dotnet restore
  ```

4. **Run the application**:
- Open the `CleanArchitectureSolution.sln` in Visual Studio.
- Set `CleanArchitectureSolution.WebUI` as the startup project.
- Press `F5` to run the application.

## Usage
- Access the application at `http://localhost:port/`.
- Navigate through the Controllers (`Products`, `Categories`) to manage items.
- The Views provide the front-end UI for CRUD operations.

## Contributing
Feel free to fork the repository and submit pull requests. Any contributions are welcome!


