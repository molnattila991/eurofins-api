Build and Run from Terminal:
Use the following commands in the root of the project
- dotnet restore "todo-api/todo-api.csproj"
- dotnet build "todo-api/todo-api.csproj" -c Release
- dotnet .\todo-api\bin\Release\netcoreapp3.1\todo-api.dll

Open the following url in browser
- http://localhost:5000/swagger/index.html

Build and Run in Visual Studio 2019 Community Edition
-Open the Solution
-Run project with IIS Express
-It will open http://localhost:5000/swagger/index.html