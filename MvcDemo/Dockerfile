FROM mcr.microsoft.com/dotnet/aspnet:5.0 AS runtime
WORKDIR /app
COPY publish/MvcDemo.dll ./
ENTRYPOINT ["dotnet", "MvcDemo.dll"]
