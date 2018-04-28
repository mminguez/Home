# ![Dolittle Logo](Media/Logo.png)

[![Join the chat at https://gitter.im/dolittle/home](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dolittle/home?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Important information

Since Dolittle is in **alpha** and in a volatile state with things moving around and you want to try things out. You might want to consider looking at the stabile version called [Bifrost](https://github.com/dolittle/bifrost) with its documentation sitting [here](http://www.dolittle.io/bifrost).


## Contributing

Read our [contribution guide](http://www.dolittle.io/Articles/contributing.html) and get familiar with our [code of conduct](CODE_OF_CONDUCT.md).

## Projects

This repository holds the issues across all projects organized in the [Projects](https://github.com/dolittle/Home/projects) tab above.It also contains the links to all the projects organized from here.

## Getting Started

Go to our [documentation site](http://www.dolittle.io) and learn more about the project and how to get started.

## Organizations

Dolittle consists of quite a few projects all geared towards different aspects. All these aspects has an organization representing them:

| Aspect | Description |
| ------ | ----------- |
| [Home / Main](https://github.com/dolittle) | Our landing point - the home of Dolittle. This is where you'll find things like the [DotNet SDK](http://github.com/dolittle/dotnet.sdk), [Runtime](http://github.com/dolittle/runtime) and [Fundamentals](http://github.com/dolittle/dotnet.fundamentals) |
| [Interaction](https://github.com/dolittle-interaction) | All interaction layers are found here. An interaction layer is for instance a frontend, API or similar |
| [Tools](https://github.com/dolittle-tools) | All tools for the platform |
| [Platform](https://github.com/dolittle-platform) | Most of Dolittle is open source, but there are aspects associated with the hosted experience that is closed source; this is where you find that. It has however all the issues as a [public repository](https://github.com/dolittle-platform/home) |
| [Extensions](https://github.com/dolittle-extensions) | The closed source part of our platform - it has however all the issues in public |
| [Samples](https://github.com/dolittle-samples) | All samples for using Dolittle |
| [Entropy](https://github.com/dolittle-entropy) | When we want to try out new things, we keep them here first. A way of brainstorming around new concepts and ideas. |
| [Contribs](https://github.com/dolittle-contribs) | Contributions to the platform. This is often a stepping stone on becoming formalized into the core frameworks and platform. |
| [Boilerplates](https://github.com/dolittle-boilerplates) | Boilerplates for tooling experience for getting started with different projects and artifacts |

## Issues

All the different projects has their own issues and we keep track of everything in our [Waffle Board](https://waffle.io/dolittle/home)

[![Stories in Ready](https://badge.waffle.io/dolittle/home.png?label=ready&title=Ready)](http://waffle.io/dolittle/home)
## Packages

| Platform | Production   | From CI  |
| ------- | ------- | ------ |
| .NET Fundamentals | [![NuGet](https://img.shields.io/nuget/v/dolittle.Assemblies.svg)](https://www.nuget.org/packages?q=dolittle) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.Assemblies.svg)](https://www.myget.org/gallery/dolittle) |
| .NET Runtime | [![NuGet](https://img.shields.io/nuget/v/dolittle.Runtime.Events.svg)](https://www.nuget.org/packages?q=dolittle.Runtime) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.Runtime.Events.svg)](https://www.myget.org/gallery/dolittle) |
| .NET SDK | [![NuGet](https://img.shields.io/nuget/v/dolittle.svg)](https://www.nuget.org/packages?q=dolittle.sdk.commands) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.sdk.commands.svg)](https://www.myget.org/gallery/dolittle) |
| ASP.NET Core | [![NuGet](https://img.shields.io/nuget/v/dolittle.aspnetcore.commands.svg)](https://www.nuget.org/packages?q=dolittle.aspnetcore) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.aspnetcore.commands.svg)](https://www.myget.org/gallery/dolittle) |
| Autofac | [![NuGet](https://img.shields.io/nuget/v/dolittle.dependencyinversion.autofac.svg)](https://www.nuget.org/packages?q=dolittle.dependencyinversion.autofac) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.dependencyinversion.autofac.svg)](https://www.myget.org/gallery/dolittle) |
| ReadModels.MongoDB | [![NuGet](https://img.shields.io/nuget/v/dolittle.readmodels.mongodb.svg)](https://www.nuget.org/packages?q=dolittle.readmodels.mongodb) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.readmodels.mongodb.svg)](https://www.myget.org/gallery/dolittle) |
| Runtime.Events.Storage.Azure | [![NuGet](https://img.shields.io/nuget/v/dolittle.runtime.events.storage.azure.svg)](https://www.nuget.org/packages?q=dolittle.runtime.events.storage.azure) | [![MyGet](https://img.shields.io/myget/dolittle/vpre/dolittle.runtime.events.storage.azure.svg)](https://www.myget.org/gallery/dolittle) |


## Build Status


| Project | Windows | Linux / macOS |
| -------- | ------ | ------------- |
| .NET Fundamentals | [![Build status](https://ci.appveyor.com/api/projects/status/r53j9v19idi903ol?svg=true)](https://ci.appveyor.com/project/Dolittle/dotnet-fundamentals) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/dotnet-fundamentals.svg)]() | [![Travis Build Status](https://travis-ci.org/dolittle/DotNET.Fundamentals.svg?branch=master)](https://travis-ci.org/dolittle/DotNET.Fundamentals) |
| .NET Runtime | [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/83b4tlt2euskb582?svg=true)](https://ci.appveyor.com/project/Dolittle/dotnet-runtime) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/dotnet-runtime.svg)]() | [![Travis Build Status](https://travis-ci.org/dolittle/DotNET.Runtime.svg?branch=master)](https://travis-ci.org/dolittle/DotNET.Runtime) |
| .NET SDK | [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/umi5t4qs6stw9uud?svg=true)](https://ci.appveyor.com/project/Dolittle/core) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/core.svg)]() | [![Travis Build Status](https://travis-ci.org/dolittle/DotNET.SDK.svg?branch=master)](https://travis-ci.org/dolittle/DotNET.SDK) |
| ASP.NET Core | [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/r2q9b9ya1vygyx9o?svg=true)](https://ci.appveyor.com/project/Dolittle/aspnetcore) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/aspnetcore.svg)]() |  |
| Autofac | [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/cijukudqo5wobrst?svg=true)](https://ci.appveyor.com/project/Dolittle/dotnet-dependencyinversion-autofac) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/dotnet-dependencyinversion-autofac.svg)]() |  |
| ReadModels.MongoDB | [![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/s95va5xrrg57sfdp?svg=true)](https://ci.appveyor.com/project/Dolittle/readmodels-mongodb) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/readmodels-mongodb.svg)]() |  |
| Runtime.Events.Storage.Azure | [![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/ykb6utw13tn0qbkm?svg=true)](https://ci.appveyor.com/project/Dolittle/runtime-events-storage-azure) [![AppVeyor tests](https://img.shields.io/appveyor/tests/Dolittle/runtime-events-storage-azure.svg)]() |  |




