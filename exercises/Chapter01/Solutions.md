# Solutions for Chapter 1

## Exercise 1.1

### 1. Why can a programmer use different languages, for example, C# and F#, to write applications that run on .NET?

Multiple languages are supported on .NET Core because each one has a compiler that translates the source code into IL (intermediate laguage) code. This IL code is the compiled to native CPU instructions at run time by the CLR (Common Language Runtime).

### 2. What do you type at the propt to create a console app?

```console
dotnet new console
```

### 3. What do you type at the prompt to build and execute C# source code?

```console
dotnet run
```

### 4. What is the Visual Studio Code keyboard shortcut to view Terminal?

ctrl + `

### 5. Is Visual Studio 2019 better than Visual Studio Code?

It depends...

### 6. Is .NET Core better than .NET Framework?

Yes, .NET Core is faster than .NET Framework because the architecture of .NET Core is written or restructured from scratch to make it a modular, lightweight, fast, and cross-platform Framework.

### 7. What is .NET Standard and why is it still important?

NET Standard is a specification that represents a set of APIs that all .NET platforms need to implement. It is introduced to support cross-platform development and bring uniformity across the .NET ecosystem.

### 8. What is the name of the entry point method of a .NET console application and how should it be declared?

The Main method is the entry point of an executable program; it is where the program control starts and ends. Main is declared inside a class or struct. Main must be static and it need not be public.

### 9. Where would you look for help about a C# keyword?

Microsoft Documentation.

### 10. Where would you look for solutions to common programming problems?

Google and Stackoverflow.
