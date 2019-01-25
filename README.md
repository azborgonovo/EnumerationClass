[![Build status](https://ci.appveyor.com/api/projects/status/h7bt0gkq33oidhto?svg=true)](https://ci.appveyor.com/project/AndreBorgonovo/enumerationclass)

# EnumerationClass

A simple, stable and reusable Enumeration base class.

Documentation is available at https://github.com/azborgonovo/EnumerationClass/tree/master/doc

## Installing

You should install EnumerationClass with NuGet:

    Install-Package EnumerationClass

Or via the .NET Core command line interface:

    dotnet add package EnumerationClass

## When to use enumeration classes?

- To enable your set of constants with all rich features of an object-oriented language (in comparisson to enum types);
- Your code needs a *static reference to an object* (e.g. for application control flow);

If you rather simply need a set of named integral constant values, declare an [enum type](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/enum) instead. Of course, be aware of what enum types are meant for and how to [use it](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/enum#robust-programming).

## What EnumerationClass package provides?

An abstract class with standard properties and useful methods that facilitate the implementation and use of enumeration classes.

## Example

[to be written]

## More info

Find more elaboration on the differences, advantages and disadvantages of enum types and enumeration classes on the following links.

- Jimmy Bogard. Enumeration classes
https://lostechies.com/jimmybogard/2008/08/12/enumeration-classes/

- Microsoft .NET Microservices: Architecture for Containerized .NET Applications: Use enumeration classes instead of enum types
https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/microservice-ddd-cqrs-patterns/enumeration-classes-over-enum-types