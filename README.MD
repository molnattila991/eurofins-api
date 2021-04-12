Build and Run from Terminal:
Use the following commands
- git clone https://github.com/molnattila991/eurofins-api
- cd .\eurofins-api\
- dotnet restore "todo-api/todo-api.csproj"
- dotnet build "todo-api/todo-api.csproj" -c Release
- dotnet .\todo-api\bin\Release\netcoreapp3.1\todo-api.dll

Open the following url in browser
- http://localhost:63334/swagger/index.html

Build and Run in Visual Studio 2019 Community Edition
-Open the Solution
-Run project with IIS Express
-It will open http://localhost:{PORT}/swagger/index.html