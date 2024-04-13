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

Top-level statements allows you to write executable code directly at the root of a file, eliminating the need for wrapping your code in a class or method. This means you can create programs without the ceremony of a `Program` class and a `Main` method.


```csharp
Console.WriteLine("Hello, World!");
```