# Primeiro contato com API's

## Comando para instalar o Entity Framework e usar no seus projetos:

### dotnet tool install --global dotnet-ef   OBS: usar apenas uma vez pois é global

### dotnet add package Microsoft.EntityFrameworkCore.SqlServer
### dotnet add package Microsoft.EntityFrameworkCore.Design   OBS: Toda vez que quiser usar o entity em um projeto

### dotnet-ef migrations add <NomeDaMigration>

### dotnet-ef database update
