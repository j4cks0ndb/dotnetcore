## .Net Core

dotnet new webapi -n ProAgil.WebAPI #Cria projeto WebAPI \n

dotnet run #Executa aplicação \n
dotnet run --project .\GameTOP\GameTOP.csproj #Executa aplicação \n
dotnet watch run #Executa a aplicação e fica monitorando alteração em arquivos e reinicia a aplicação caso algum arquivo seja modificado e salvo \n

# Integração com EF
dotnet ef migrations add init
dotnet ef database update
dotnet ef migrations add 'image_evento'
dotnet ef database update

npm install #instala package.json
