# Top .NET Libraries You Must Know [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

	Most popular .NET libraries every developer should know.

## Give a Star! ⭐️

If you liked this repository or find it useful, please give it a star. Thanks!

## Contents
- [Object Mapper](#object-mapper)
- [IoC](#ioc)
- [Task Scheduler (Background Job)](#task-scheduler--background-job-)
- [Json Serializer](#json-serializer)
- [Binary Serializer](#binary-serializer)
- [Validation](#validation)
- [ORM](#orm)
- [NoSQL](#nosql)
- [Commands/Events Dispatcher](#commands-events-dispatcher)
- [Http Client - REST](#http-client---rest)
- [CSV](#csv)
- [Excel](#excel)
- [DateTime](#datetime)
- [Linq](#linq)
- [JWT](#jwt)
- [HtmlParser](#htmlparser)
- [Profiler](#profiler)
- [Caching](#caching)
- [Testing](#testing)
- [UI Testing](#ui-testing)
- [OpenAPI](#openapi)
- [Functional Programming](#functional-programming)

## Libraries
<!--
	🟡 Recommended - 🟢 Good to know - 🟣 Other options / Possibilities
-->

### Object Mapper
- [**AutoMapper**](https://github.com/AutoMapper/AutoMapper) 
	> A convention-based object-object mapper in .NET. 

	[![GitHub Stars](https://img.shields.io/github/stars/AutoMapper/AutoMapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoMapper/AutoMapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoMapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoMapper)

- [**Maspter**](https://github.com/MapsterMapper/Mapster)
	> A fast, fun and stimulating object to object Mapper

	[![GitHub Stars](https://img.shields.io/github/stars/MapsterMapper/Mapster?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MapsterMapper/Mapster)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Mapster?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Mapster)

### IoC
- Autofac

### Task Scheduler (background job)
- [**HangFire**](https://github.com/HangfireIO/Hangfire)
	> An easy way to perform background job processing in your .NET and .NET Core applications. No Windows Service or separate process required
	
	[![GitHub Stars](https://img.shields.io/github/stars/HangfireIO/Hangfire?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/HangfireIO/Hangfire)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Hangfire?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Hangfire)

- [**Quartz.NET**](https://github.com/quartznet/quartznet)
	> Quartz Enterprise Scheduler .NET

	[![GitHub Stars](https://img.shields.io/github/stars/quartznet/quartznet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/quartznet/quartznet)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Quartz?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Quartz)

- [**Coravel**](https://github.com/jamesmh/coravel)
	> Near-zero config .NET Core micro-framework that makes advanced application features like Task Scheduling, Caching, Queuing, Event Broadcasting, and more a breeze!

	[![GitHub Stars](https://img.shields.io/github/stars/jamesmh/coravel?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jamesmh/coravel)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Coravel?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Coravel)

### Json Serializer
- [**Newtonsoft.Json (Json.NET)**](https://github.com/JamesNK/Newtonsoft.Json)
	> Json .NET is a popular high-performance JSON framework for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/JamesNK/Newtonsoft.Json?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JamesNK/Newtonsoft.Json)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Newtonsoft.Json?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Newtonsoft.Json)

### Binary Serializer
- MessagePack
- Protobuf-Net

### Validation
- [**FluentValidation**](https://github.com/FluentValidation/FluentValidation)
	> A popular .NET validation library for building strongly-typed validation rules.

	[![GitHub Stars](https://img.shields.io/github/stars/FluentValidation/FluentValidation?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FluentValidation/FluentValidation)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentValidation?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentValidation)

### ORM 
- [**Entity Framework**](https://github.com/dotnet/ef6)
	> Entity Framework 6 (EF6) is an object-relational mapper that enables .NET developers to work with relational data using domain-specific objects. It eliminates the need for most of the data-access code that developers usually need to write.

	[![GitHub Stars](https://img.shields.io/github/stars/dotnet/ef6?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/ef6)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/EntityFramework?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EntityFramework)

- [**Entity Framework Core**](https://github.com/dotnet/efcore)
	> EF Core is a modern object-database mapper for .NET. It supports LINQ queries, change tracking, updates, and schema migrations.

	[![GitHub Stars](https://img.shields.io/github/stars/dotnet/efcore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/efcore)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.EntityFrameworkCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore)

- [**Dapper**](https://github.com/StackExchange/Dapper)
	> Dapper - a simple object mapper for .Net

	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/Dapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/Dapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper)

- [**linq2db**](https://github.com/linq2db/linq2db)
	> Linq to database provider.

	[![GitHub Stars](https://img.shields.io/github/stars/linq2db/linq2db?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/linq2db/linq2db)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/linq2db?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/linq2db)
	
### NoSQL
- MongoDb
- Elastic
- Redis

### Commands/Events Dispatcher
- MediatR
- Brighter

### Http Client / REST
- Refit
- RestEase
- RestSharp

### CSV
- [**CsvHelper**](https://github.com/JoshClose/CsvHelper)
	> Library to help reading and writing CSV files

	[![GitHub Stars](https://img.shields.io/github/stars/JoshClose/CsvHelper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JoshClose/CsvHelper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/CsvHelper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/CsvHelper)

### Excel
- [**EPPlus**](https://github.com/JanKallman/EPPlus)
	> Create advanced Excel spreadsheets using .NET

	[![GitHub Stars](https://img.shields.io/github/stars/JanKallman/EPPlus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JanKallman/EPPlus)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/EPPlus?label=Downloads&logo=nuget&cacheSeconds=3600)]( https://www.nuget.org/packages/EPPlus)
	
### DateTime
- [**NodaTime**](https://github.com/nodatime/nodatime)
	> A better date and time API for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/nodatime/nodatime?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nodatime/nodatime)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NodaTime?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NodaTime)

### Linq
- MoreLinq

### JWT

### HtmlParser
- HtmlAgilityPack
- AngleSharp

### Profiler
- MiniProfiler

### Caching
- InMemory
- Distributed
- Caching Abstraction

### Testing
- Test Frameworks
	- xUnit
	- NUnit
- Asseration
	- FluentAssertions
- Mocking
	- Moq
	- FakeItEasy
	- NSubstitute
- Test Data Generator
	- AutoFixture
	- NBuilder

### UI Testing
- Selenium.WebDriver
- Puppeteer Sharp

### OpenAPI
- Swagger (Swashbackle)
	
### Functional Programming

## Contribution
Contributions are always welcome! Feel free to open an [issue][issues] or create a pull request.

## License
[![CC0][license-badge]][license]

To the extent possible under law, [Mohammad Javad Ebrahimi](https://github.com/mjebrahimi) has waived all copyright and related or neighboring rights to this work.

[issues]: https://github.com/mjebrahimi/Top-NET-Libraries-Must-Know/issues/new
[license]: https://creativecommons.org/publicdomain/zero/1.0
[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
