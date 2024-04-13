# Hello, World! - C# (CSharp)

<p align="center">
    <img src="https://img.shields.io/badge/Language-CSharp-blue">
    <img src="https://img.shields.io/badge/Platform-.NET%20Core%20%7C%20.NET%20Framework-blue">
</p>

<p align="center">
       <img src="csharp-logo.png" alt="C# Logo" width="200" height="200">
</p>



`C#` is a general-purpose, multi-paradigm programming language developed by Microsoft. It is widely used for developing desktop applications, web applications, and games.

## .NET CLI

The `.NET` Command Line Interface (CLI) is a cross-platform toolchain for developing, building, running, and publishing .NET applications.

> `.NET` has another name called `dotnet`.

### Installation

To install the .NET CLI, follow the instructions in the [official documentation](https://docs.microsoft.com/en-us/dotnet/core/tools/).

## .NET Core VS .NET Framework

`.NET Core` is a cross-platform, open-source framework for developing modern, cloud-based, and IoT applications. It is a modular framework that allows you to include only the components you need in your application.

`.NET Framework` is a Windows-only framework for building Windows desktop applications, web applications, and services. It is a monolithic framework that includes a large number of libraries and APIs.

### Usage

To create a new console application, run the following command:

```bash
dotnet new console -n HelloWorld
```

This will create a new directory called `HelloWorld` with a `Program.cs` file that contains the following code:

```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
```

To run the application, navigate to the `HelloWorld` directory and run the following command:

```bash
dotnet run
```

This will compile and run the application, and you should see the output `Hello, World!` in the console.

### Top-Level Statements

Starting with C# 9.0, you can use top-level statements to simplify the code for simple console applications. Instead of defining a `Main` method, you can write the code directly in the file without a namespace or class declaration.

```csharp
Console.WriteLine("Hello, World!");
```

## Rider

[Rider](https://www.jetbrains.com/rider/) is a cross-platform .NET IDE developed by JetBrains. It provides a comprehensive set of features for developing .NET applications, including C# code analysis, refactoring, and debugging.

### Installation

To install Rider, download the installer from the [official website](https://www.jetbrains.com/rider/download/) and follow the installation instructions.


