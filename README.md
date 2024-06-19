# Dotnet Web Api Starter Project

A C# .NET Web Api project can be created using the dotnet command line.
```shell
> dotnet new webapi -n "DotNetWebApi" -controllers
```
The above command creates a Web Api project with controllers instead of using the Minimal APIs. The Minimal APIs are explained [here](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis/overview?view=aspnetcore-8.0).

## Framework Design Guidelines
The solution follows the .NET [Framework Design Guidelines](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/).

The [StyleCop.Analyzers](https://www.nuget.org/packages/StyleCop.Analyzers/) package is installed for code analysis.

The built-in [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) can also be used in Visual Studio with the .NET 8 SDK.

## Testing
The api endpoints can be testing using
[.http files](https://learn.microsoft.com/en-us/aspnet/core/test/http-files).
