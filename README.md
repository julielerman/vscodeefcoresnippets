# EFCore Snippets Visual Studio Code Extension

This extension contains a number of snippets that you may find useful when writing C# code against Entity Framework Core.

## Features
Snippets included for your class that inherits from DbContext 

### override onconfiguring

Creates OnConfiguring override method 

### override onmodelcreating
Creates OnModelCreating override method

### override onmodelcreating plural
Creates OnModelCreating with logic to pluralize the table names of each of the mapped entities

### ctorDbContextOptions

Adds a new constructor to allow alternate provider for testing. Includes a parameterless ctor which you will need if you are using a custom ctor

These snippets will get added to your csharp snippets.


## Requirements

Requires Microsoft.EntityFrameworkCore via NuGet

### 0.0.1

Testing


**Enjoy!**  
Julie Lerman  
github.com/julielerman   
@julielerman