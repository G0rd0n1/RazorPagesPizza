# RazorPagesPizza

## Create a web UI with ASP.NET Core

ASP.NET Core supports creating webpages using a native templating engine called Razor. 
I learnt how to create web pages using Razor with ASP.NET Core. I created a basic application with a Navigation bar.
In this Navbar I created a 'Pizza List' link which takes you to a form that supports the app's product data management requirements.



## INSTALLATIONS 

### _Visual Studio Code_
Visual Studio Code, also commonly referred to as VS Code, is a source-code editor made by Microsoft with the Electron Framework, for Windows, Linux and macOS.
Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git.

Run the following command in your preferred terminal:<br>

Ubuntu:
  - sudo snap install --classic code 

Or Download directly from the website:
  - [ https://code.visualstudio.com/download ]


### C#
C# (pronounced see sharp) is a general-purpose, high-level multi-paradigm programming language. C# encompasses static typing, strong typing, lexically scoped, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines.

C# language support is an optional install from the Marketplace:
  - You can install it from within VS Code by searching for 'C#' in the Extensions view (Ctrl+Shift+X)<br>


If you already have a project with C# files:
  - VS Code will prompt you to install the extension as soon as you open a C# file.<br>
    
    
[ https://code.visualstudio.com/docs/languages/csharp ]

### _.NET SDK_
This module uses the .NET CLI and Visual Studio Code (Windows, Linux, and macOS) to demonstrate ASP.NET Core Razor Pages development.

This project needs you to have .NET 6.0 SDK installed.<br>

Run the following command in your preferred terminal:<br>
  - dotnet --list-sdks

### Expected output:

  - 3.1.100 [C:\program files\dotnet\sdk]
  - 5.0.100 [C:\program files\dotnet\sdk]
  - 6.0.100 [C:\program files\dotnet\sdk]

Ensure that a version that starts with 6 is listed.

If none is listed or the command isn't found, install the most recent .NET 6.0 SDK.

## Running the program
In the Visual Studio Code terminal, enter the following command:
  - dotnet watch
