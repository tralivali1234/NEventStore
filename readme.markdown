NEventStore
===

NEventStore is a persistence library used to abstract different storage implementations
when using event sourcing as storage mechanism. This library is developed with a specific focus on [DDD](http://en.wikipedia.org/wiki/Domain-driven_design)/[CQRS](http://cqrsinfo.com) applications.

NEventStore currently supports:

- dotnet framework 4.5
- dotnet standard 2.0, dotnet core 2.0 

Build Status (AppVeyor)
===

Branches: 

- master [![Build status](https://ci.appveyor.com/api/projects/status/frg36pb2oh1j2ddi/branch/master?svg=true)](https://ci.appveyor.com/project/AGiorgetti/neventstore/branch/master)
- develop [![Build status](https://ci.appveyor.com/api/projects/status/frg36pb2oh1j2ddi/branch/develop?svg=true)](https://ci.appveyor.com/project/AGiorgetti/neventstore/branch/develop)


Documentation
===

Please see the [documentation](https://github.com/NEventStore/NEventStore/wiki) to get started and for more information.

ChangeLog can be [found here](Changelog.md)

### Developed with:

[![Resharper](http://neventstore.org/images/logo_resharper_small.gif)](http://www.jetbrains.com/resharper/)
[![TeamCity](http://neventstore.org/images/logo_teamcity_small.gif)](http://www.jetbrains.com/teamcity/)
[![dotCover](http://neventstore.org/images/logo_dotcover_small.gif)](http://www.jetbrains.com/dotcover/)
[![dotTrace](http://neventstore.org/images/logo_dottrace_small.gif)](http://www.jetbrains.com/dottrace/)

# How to build

To build the project locally on a Windows Machine:

- Install [Chocolatey](https://chocolatey.org/).
- Open a Powershell console in Administrative mode and run the build script `build.ps1` in the root of the repository.
