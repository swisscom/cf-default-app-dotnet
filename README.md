# CF Default App .NET

The default .NET app that will be pushed in the Swisscom Application Cloud if no source code is provided

Based on [ASP.NET](https://www.asp.net/)

## Run locally

1. Install [.NET Core](https://www.microsoft.com/net/core)
1. Run `dotnet restore`
1. Run `dotnet run`
1. Visit [http://localhost:5000](http://localhost:5000)

## Run in the cloud

1. Install the [cf CLI](https://github.com/cloudfoundry/cli#downloads)
1. Run `cf push --random-route`
1. Visit the given URL

## Create ZIP

1. Run `zip -r dotnet_app.zip Controllers Views wwwroot Program.cs project.json Startup.cs`
