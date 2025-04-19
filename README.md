![WebExpress](https://raw.githubusercontent.com/ReneSchwarzer/WebExpress/main/assets/banner.png)

# WebExpress
`WebExpress` is a lightweight web server optimized for use in low-performance environments (e.g. Rasperry PI). By providing a powerful plugin system and a comprehensive API, web applications can be easily and quickly integrated into a .net language (e.g. C#). Some advantages of `WebExpress` are:

- It is easy to use.
- It offers a variety of features and tools that can help you build and manage your website.
- It is fast and efficient and can help you save time and money.
- It is flexible and can be customized to meet your specific requirements.

The `WebExpress` family includes the following projects:

- [WebExpress](https://github.com/ReneSchwarzer/WebExpress#readme) - The web server for `WebExpress` applications and the documentation.
- [WebExpress.WebCore](https://github.com/ReneSchwarzer/WebExpress.WebCore#readme) - The core for `WebExpress` applications.
- [WebExpress.WebUI](https://github.com/ReneSchwarzer/WebExpress.WebUI#readme) - Common templates and controls for `WebExpress` applications.
- [WebExpress.WebIndex](https://github.com/ReneSchwarzer/WebExpress.WebIndex#readme) - Reverse index for `WebExpress` applications.
- [WebExpress.WebApp](https://github.com/ReneSchwarzer/WebExpress.WebApp#readme) - Business application template for `WebExpress` applications.

`WebExpress` is part of the `WebExpress` family. The project provides a web server for `WebExpress` applications.

To get started with `WebExpress`, use the following links.

- [installation guide](https://github.com/ReneSchwarzer/WebExpress/blob/main/doc/installation_guide.md) 
- [development guide](https://github.com/ReneSchwarzer/WebExpress/blob/main/doc/development_guide.md)

# Tutorial
This tutorial guides you through demonstrating the UI elements of a `WebExpress` application. Learn how to effectively use the templates and controls provided by the `WebExpress.WebUI` project.

## Prerequisites
- Create a `WebExpress` application after the [WebApp](https://github.com/ReneSchwarzer/WebExpress.Tutorial.WebApp#readme) tutorial but name it `WebExpress.Tutorial.WebIndex`.

## Compile and register in WebExpress
- Compile the solution as a release. To do this, open the command line or terminal in the solution directory and run the following command:
  ```bash
  dotnet build --configuration Release
  ```
  This command compiles the solution in release mode. You can find the compiled files in the `bin/Release` directory of your project.

- Run the solution by starting the `WebApp.App` project.
  ```bash
  cd WebApp.App\bin\Release\net9.0
  dotnet run --project ../../../WebApp.App.csproj
  ```

- After compiling, there should be a file with the `.wxp` extension in the `pkg/Release` directory. This file do you need in `WebExpress`.

## Try the application
- Check the result by calling up the following URL in the browser: http://localhost/webui

Good luck building stunning web applications with `WebExpress`!
    
# Tags
#WebExpress #WebServer #WebCore #WebUI #Tutorial #DotNet


