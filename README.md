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
- [Query Builder](#query-builder)
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
- [Logging](#logging)

## Libraries
<!--
	🟡 Recommended - 🟢 Good to know - 🟣 Other options / Possibilities
-->

### Object Mapper
- [**AutoMapper**](https://github.com/AutoMapper/AutoMapper) 
	> A convention-based object-object mapper in .NET

	[![GitHub Stars](https://img.shields.io/github/stars/AutoMapper/AutoMapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoMapper/AutoMapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoMapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoMapper)

- [**Maspter**](https://github.com/MapsterMapper/Mapster)
	> A fast, fun and stimulating object to object Mapper

	[![GitHub Stars](https://img.shields.io/github/stars/MapsterMapper/Mapster?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MapsterMapper/Mapster)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Mapster?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Mapster)

### IoC
- [**Autofac**](https://github.com/autofac/Autofac)
	> Autofac is an IoC container for .NET. It manages the dependencies between classes so that applications stay easy to change as they grow in size and complexity.

	[![GitHub Stars](https://img.shields.io/github/stars/autofac/Autofac?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/autofac/Autofac)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Autofac?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Autofac)

### Task Scheduler (background job)
- [**HangFire**](https://github.com/HangfireIO/Hangfire)
	> An easy way to perform background job processing in your .NET and .NET Core applications. No Windows Service or separate process required.
	
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
- [**MessagePack**](https://github.com/neuecc/MessagePack-CSharp)
	> Extremely Fast MessagePack (MsgPack) Serializer for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/neuecc/MessagePack-CSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/neuecc/MessagePack-CSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/MessagePack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MessagePack)

- [**Protobuf-Net**](https://github.com/protobuf-net/protobuf-net)
	> protobuf-net is a contract based serializer for .NET code, that happens to write data in the "protocol buffers" serialization format engineered by Google.
	
	[![GitHub Stars](https://img.shields.io/github/stars/protobuf-net/protobuf-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/protobuf-net/protobuf-net)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/protobuf-net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/protobuf-net)

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
	> Dapper - a simple object mapper for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/Dapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/Dapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper)

- [**linq2db**](https://github.com/linq2db/linq2db)
	> Linq to database provider.

	[![GitHub Stars](https://img.shields.io/github/stars/linq2db/linq2db?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/linq2db/linq2db)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/linq2db?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/linq2db)
	
### NoSQL
- [**MongoDb**](https://github.com/mongodb/mongo-csharp-driver)
	> The official MongoDB C#/.NET Driver provides asynchronous interaction with MongoDB.
	
	[![GitHub Stars](https://img.shields.io/github/stars/mongodb/mongo-csharp-driver?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mongodb/mongo-csharp-driver)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoDB.Driver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoDB.Driver)

- [**Elastic**](https://github.com/elastic/elasticsearch-net)
	> Exposes all the Elasticsearch API endpoints but leaves you in control of building the request and response bodies. 

	[![GitHub Stars](https://img.shields.io/github/stars/elastic/elasticsearch-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/elastic/elasticsearch-net)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Elasticsearch.Net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Elasticsearch.Net)

- [**Redis**](https://github.com/StackExchange/StackExchange.Redis)
	> High performance Redis client, incorporating both synchronous and asynchronous usage.
	
	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/StackExchange.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/StackExchange.Redis)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/StackExchange.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/StackExchange.Redis)

- [**LiteDB**](https://github.com/mbdavid/litedb)
	> LiteDB is a small, fast and lightweight .NET NoSQL embedded database.
	
	[![GitHub Stars](https://img.shields.io/github/stars/mbdavid/litedb?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mbdavid/litedb)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/LiteDB?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/LiteDB)

### Query Builder
- [**SqlKata**](https://github.com/sqlkata/querybuilder)
	> SqlKata Query Builder is a powerful SQL Query Builder written in C#.
	
	[![GitHub Stars](https://img.shields.io/github/stars/sqlkata/querybuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sqlkata/querybuilder)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/SqlKata?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SqlKata)

### Commands/Events Dispatcher
- [**MediatR**](https://github.com/jbogard/MediatR)
	> Simple, unambitious mediator implementation in .NET
	
	[![GitHub Stars](https://img.shields.io/github/stars/jbogard/MediatR?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jbogard/MediatR)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/mediatr?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/mediatr)

- [**Brighter**](https://github.com/BrighterCommand/Brighter)
	> The Command Dispatcher pattern is an addition to the Command design pattern that decouples the dispatcher for a service from its execution.
	
	[![GitHub Stars](https://img.shields.io/github/stars/BrighterCommand/Brighter?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/BrighterCommand/Brighter)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/paramore.brighter?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/paramore.brighter)

### Http Client / REST
- [**Refit**](https://github.com/reactiveui/refit)
	> The automatic type-safe REST library for Xamarin and .NET

	[![GitHub Stars](https://img.shields.io/github/stars/reactiveui/refit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/reactiveui/refit)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Refit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Refit)

- [**RestEase**](https://github.com/canton7/RestEase)
	> Easy-to-use typesafe REST API client library, which is simple and customisable.
	
	[![GitHub Stars](https://img.shields.io/github/stars/canton7/RestEase?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/canton7/RestEase)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/RestEase?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RestEase)

- [**RestSharp**](https://github.com/restsharp/RestSharp)
	> Simple REST and HTTP API Client for .NET
	
	[![GitHub Stars](https://img.shields.io/github/stars/restsharp/RestSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/restsharp/RestSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/RestSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RestSharp)

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
- [**MoreLinq**](https://github.com/morelinq/MoreLINQ)
	> Extensions to LINQ to Objects.

	[![GitHub Stars](https://img.shields.io/github/stars/morelinq/MoreLINQ?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/morelinq/MoreLINQ)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/morelinq?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/morelinq)

### JWT

### HtmlParser
- [**HtmlAgilityPack**](https://github.com/zzzprojects/html-agility-pack)
	> HAP is an HTML parser written in C# to read/write DOM and supports plain XPATH or XSLT.
	
	[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/html-agility-pack?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/html-agility-pack)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/HtmlAgilityPack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/HtmlAgilityPack)

- [**AngleSharp**](https://github.com/AngleSharp/AngleSharp)
	> The ultimate angle brackets parser library parsing HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specifications.
	
	[![GitHub Stars](https://img.shields.io/github/stars/AngleSharp/AngleSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AngleSharp/AngleSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AngleSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AngleSharp)

### Profiler
- [**MiniProfiler**](https://github.com/MiniProfiler/dotnet)
	> A simple but effective mini-profiler for ASP.NET (and Core) websites.

	[![GitHub Stars](https://img.shields.io/github/stars/MiniProfiler/dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MiniProfiler/dotnet)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/MiniProfiler.AspNetCore.Mvc?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc)

### Caching
- InMemory
- Distributed
- Caching Abstraction

### Testing
- Test Frameworks
	- [**xUnit**](https://github.com/xunit/xunit)
		> xUnit is a developer testing framework, built to support Test Driven Development, with a design goal of extreme simplicity and alignment with framework features.

		[![GitHub Stars](https://img.shields.io/github/stars/xunit/xunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xunit/xunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit)
	
	- [**NUnit**](https://github.com/nunit/nunit)
		> NUnit is a unit-testing framework for all .NET languages.

		[![GitHub Stars](https://img.shields.io/github/stars/nunit/nunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nunit/nunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NUnit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NUnit)

- Asseration
	- [**FluentAssertions**](https://github.com/fluentassertions/fluentassertions)
		> A very extensive set of extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style unit tests. 

		[![GitHub Stars](https://img.shields.io/github/stars/fluentassertions/fluentassertions?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/fluentassertions/fluentassertions)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentAssertions?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentAssertions)

- Mocking
	- [**Moq**](https://github.com/moq/moq4)
		> The most popular and friendly mocking library for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/moq/moq4?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/moq/moq4)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Moq?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Moq)

	- [**FakeItEasy**](https://github.com/FakeItEasy/FakeItEasy)
		> A .NET dynamic fake library for creating all types of fake objects, mocks, stubs etc.
		
		[![GitHub Stars](https://img.shields.io/github/stars/FakeItEasy/FakeItEasy?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FakeItEasy/FakeItEasy)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FakeItEasy?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FakeItEasy)
	
	- [**NSubstitute**](https://github.com/nsubstitute/NSubstitute)
		> A friendly substitute for .NET mocking libraries.

		[![GitHub Stars](https://img.shields.io/github/stars/nsubstitute/NSubstitute?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nsubstitute/NSubstitute)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NSubstitute?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NSubstitute)

- Test Data Generator
	- [**AutoFixture**](https://github.com/AutoFixture/AutoFixture)
		> AutoFixture makes it easier for developers to do Test-Driven Development by automating non-relevant Test Fixture Setup, allowing the Test Developer to focus on the essentials of each test case.
		
		[![GitHub Stars](https://img.shields.io/github/stars/AutoFixture/AutoFixture?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoFixture/AutoFixture)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoFixture?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoFixture)
	
	- [**NBuilder**](https://github.com/nbuilder/nbuilder)
		> Through a fluent, extensible interface, NBuilder allows you to rapidly create test data, automatically assigning values to properties and public fields that are one of the built in .NET data types (e.g. ints and strings). NBuilder allows you to override for properties you are interested in using lambda expressions.
		
		[![GitHub Stars](https://img.shields.io/github/stars/nbuilder/nbuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nbuilder/nbuilder)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/nbuilder?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/nbuilder)

### UI Testing
- [**Selenium.WebDriver**](https://github.com/SeleniumHQ/selenium)
	> Selenium is a set of different software tools each with a different approach to supporting browser automation. These tools are highly flexible, allowing many options for locating and manipulating elements within a browser, and one of its key features is the support for automating multiple browser platforms.
	
	[![GitHub Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SeleniumHQ/selenium)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Selenium.WebDriver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Selenium.WebDriver)

- [**Puppeteer Sharp**](https://github.com/hardkoded/puppeteer-sharp)
	>  Headless Chrome .NET API

	[![GitHub Stars](https://img.shields.io/github/stars/hardkoded/puppeteer-sharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/hardkoded/puppeteer-sharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/PuppeteerSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PuppeteerSharp)

### OpenAPI
- [**Swagger (Swashbuckle)**](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	> Swagger tooling for API's built with ASP.NET Core. Generate beautiful API documentation, including a UI to explore and test operations, directly from your routes, controllers and models.
	
	[![GitHub Stars](https://img.shields.io/github/stars/domaindrivendev/Swashbuckle.AspNetCore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/swashbuckle.aspnetcore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/swashbuckle.aspnetcore)

- [**NSwag**](https://github.com/RicoSuter/NSwag)
	> The OpenAPI/Swagger API toolchain for .NET and TypeScript.

	[![GitHub Stars](https://img.shields.io/github/stars/RicoSuter/NSwag?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/RicoSuter/NSwag)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NSwag.AspNetCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NSwag.AspNetCore)

### Functional Programming

### Logging
- [**Serilog**](https://github.com/serilog/serilog)
	> Serilog is a diagnostic logging library for .NET applications. It is easy to set up, has a clean API, and runs on all recent .NET platforms.
	
	[![GitHub Stars](https://img.shields.io/github/stars/serilog/serilog?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/serilog/serilog)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/serilog?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/serilog)

## Contribution
Contributions are always welcome! Feel free to open an [issue][issues] or create a pull request.

## License
[![CC0][license-badge]][license]

To the extent possible under law, [Mohammad Javad Ebrahimi](https://github.com/mjebrahimi) has waived all copyright and related or neighboring rights to this work.

[issues]: https://github.com/mjebrahimi/Top-NET-Libraries-Must-Know/issues/new
[license]: https://creativecommons.org/publicdomain/zero/1.0
[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
