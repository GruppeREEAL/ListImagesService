# Brug officiel ASP.NET 10.0 runtime image
FROM mcr.microsoft.com/dotnet/aspnet:10.0

WORKDIR /app

# Kopier det publicerede projekt
COPY bin/Release/net10.0/publish/ .

# Entry point
ENTRYPOINT ["dotnet", "listservice.dll"]