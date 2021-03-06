# Domino

[![Build Status](https://dev.azure.com/dillon-adams/GitHub/_apis/build/status/Domino)](https://dev.azure.com/dillon-adams/GitHub/_build/latest?definitionId=6) [![SonarCloud Coverage](https://sonarcloud.io/api/project_badges/measure?project=DillonAd_Domino&metric=coverage)](https://sonarcloud.io/dashboard?id=DillonAd_Domino) [![NuGet](https://img.shields.io/nuget/v/domino.svg)](https://www.nuget.org/packages/domino/)

Domino is a file watcher that runs a custom script when changes occur.

## Installation

This tool is available as a DotNet global tool. It can be installed by running `dotnet tool install -g domino`.

## Commands

### Start

`domino start {scriptName}`

This command will start the file watcher that will trigger the script on file changes in the current directory (and subdirectories).

### Ignore

`domino ignore {filePattern}`

This command will create a `.dominoignore` file in the current directory and add the specified file pattern to the file. 

## Contributing

Please check out the [Contributing Guide](http://github.com/DillonAd/Domino/blob/master/CONTRIBUTING.md)
