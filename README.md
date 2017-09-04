LTI Library
===========
There are two .NET projects in this solution to support IMS LTI Tool Providers and Tool Consumers. The Visual Studio solution and project files are compatible with Visual Studio 2015 (v14.0).

**This code base is not actively maintained**. See the [LtiLibrary repository](https://github.com/andyfmiller/LtiLibrary) for the latest .NET Core source for LtiLibrary.

## LtiLibrary.NetCore
This is the only library you need if you are going to roll your own support for web pages or native apps.

This library includes the classes, properties, and methods to support LTI 1.x launch, outcomes, content items and tool consumer profiles for both Tool Consumers and Tool Providers.

Available on NuGet: https://www.nuget.org/packages/LtiLibrary.Core

## Ltibrary.AspNetCore
This library depends on LtiLibrary.NetCore and adds useful extensions and helper methods for ASP.NET Core 2.0 applications such as an OutcomesApiController which implements the LTI Outcomes API as a Controller.

Available on NuGet: https://www.nuget.org/packages/LtiLibrary.AspNet

## Test Projects
There are also two xUnit test projects: one for each project above. These can be helpful examples for how to use the libraries.