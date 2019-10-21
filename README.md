This repository contains a basic glossary Web API implemented in ASP.NET Core 3.0 and secured with [Auth0](https://auth0.com/).

The following article describes the implementation details: [Building and Securing Web APIs with ASP.NET Core 3.0](https://auth0.com/blog/how-to-build-and-secure-web-apis-with-aspnet-core-3/)

## To run this:

1. Clone the repo: `git clone https://github.com/auth0-blog/glossary-web-api-aspnet-core.git`
2. Move to the `glossary` folder 
3. Add Auth0 credentials to the `appsettings.json` configuration file.
4. Type `dotnet run` in a terminal window to launch the Web API.
5. Point your browser to `https://localhost:5001/api/glossary` to get the list of all glossary terms and ensure that the application is working.

## Requirements:

- [.NET Core 3.0](https://dotnet.microsoft.com/download/dotnet-core/3.0) installed on your machine
- An [Auth0](https://auth0.com/) account.
- [curl](https://curl.haxx.se/), [Postman](https://www.getpostman.com/), [Insomnia](https://insomnia.rest/) or any other HTTP client.

