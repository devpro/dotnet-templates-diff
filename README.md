# dotnet-templates-diff

Easy review of differences between projects generated from .NET templates.

The idea come from using the excellent tool of Cédric Exbrayat: [cexbrayat/angular-cli-diff](https://github.com/cexbrayat/angular-cli-diff).

## Projects

### ASP.NET Core / Angular

- In Visual Studio, create a new project from template ".NET Core > ASP.NET Core Web Application", named "WebApp", in a new solution named "AspNetCoreAngularWebApp"
- In the configuration window, select "Angular", check "Configure for HTTPS" and click sur "OK"

### ASP.NET Core API

- In Visual Studio, create a new project from template ".NET Core > ASP.NET Core Web Application", named "WebApp", in a new solution named "AspNetCoreApiWebApp"
- In the configuration window, select "API", check "Enable Docker Support" (OS: Linux), check "Configure for HTTPS" and click sur "OK"

### .NET Core Console

- In Visual Studio, create a new project from template ".NET Core > Console App (.NET Core)", named "ConsoleApp", in a new solution named "NetCoreConsoleApp"

### .NET Standard Library

- In Visual Studio, create a new project from template ".NET Standard > Class Library (.NET Standard)", named "SharedLib", in a new solution named "NetStandardLibrary"
