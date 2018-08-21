MusicStore (test application)
=============================

AppVeyor: [![AppVeyor][appveyor-badge]][appveyor-build]

Travis:   [![Travis][travis-badge]][travis-build]

[appveyor-badge]: https://ci.appveyor.com/api/projects/status/ja8a7j6jscj7k3xa/branch/dev?svg=true
[appveyor-build]: https://ci.appveyor.com/project/aspnetci/MusicStore/branch/dev
[travis-badge]: https://travis-ci.org/aspnet/MusicStore.svg?branch=dev
[travis-build]: https://travis-ci.org/aspnet/MusicStore

This project is part of ASP.NET Core. You can find samples, documentation and getting started instructions for ASP.NET Core at the [Home](https://github.com/aspnet/home) repo.

## About this repo

This repository is a test application used for ASP.NET Core internal test processes.
It is not intended to be a representative sample of how to use ASP.NET Core.

Samples and docs for ASP.NET Core can be found here: <https://docs.asp.net>.

## How to run

```
PS C:\Users\savis\work\MusicStore> .\build.cmd
Downloading KoreBuild 3.0.0-alpha1-20180817.3
Using KoreBuild 3.0.0-alpha1-20180817.3
Adding C:\Users\savis\.dotnet\x64 to PATH
dotnet-install: Downloading link: https://dotnetcli.blob.core.windows.net/dotnet/Sdk/2.1.400/dotnet-sdk-2.1.400-win-x64.zip
dotnet-install: Extracting zip from https://dotnetcli.blob.core.windows.net/dotnet/Sdk/2.1.400/dotnet-sdk-2.1.400-win-x64.zip
dotnet-install: Adding to current process PATH: "C:\Users\savis\.dotnet\x64\". Note: This change will not be visible if PowerShell was run as a child process.
dotnet-install: Installation finished
>>> dotnet.exe msbuild -restore -t:noop -v:m C:\Users\savis\.dotnet\buildtools\korebuild\3.0.0-alpha1-20180817.3\scripts/../modules/BundledPackages/BundledPackageRestorer.csproj

Welcome to .NET Core!
---------------------
Learn more about .NET Core: https://aka.ms/dotnet-docs
Use 'dotnet --help' to see available commands or visit: https://aka.ms/dotnet-cli-docs

Telemetry
---------
The .NET Core tools collect usage data in order to help us improve your experience. The data is anonymous and doesn't include command-line arguments. The data is collected by Microsoft and shared with the community. You can opt-out of telemetry by setting the DOTNET_CLI_TELEMETRY_OPTOUT environment variable to '1' or 'true' using your favorite shell.

Read more about .NET Core CLI Tools telemetry: https://aka.ms/dotnet-cli-telemetry

Configuring...
--------------
A command is running to populate your local package cache to improve restore speed and enable offline access. This command takes up to one minute to complete and only runs once.
Decompressing 100% 11614 ms
Expanding 24%
```
