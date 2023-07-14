# 📦 Awesome Nuget Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

    A collection of awesome and top .NET packages sorted by most popular needs.

## Give a Star! ⭐️

If you liked this repository or find it useful, please give it a star. Thanks!

## Contents
- [Object Mapper](#object-mapper)
- [IoC](#ioc)
- [Task Scheduler/Background Job](#task-scheduler--background-job)
- [Serialization](#serialization)
- [Database, Database Drivers, and Migration](#database-database-drivers-and-migration)
- [ORM](#orm-and-micro-orm)
- [NoSQL](#nosql)
- [Messaging and Queue](#messaging-and-queue)
- [Http Client - REST](#http-client--rest)
- [Mail and SMTP Server](#mail-and-smtp-server)
- [Security](#security)
- [CSV, Excel, Word, and PDF](#csv-excel-word-and-pdf)
- [DateTime](#datetime)
- [Linq](#linq)
- [Reflection and Expression](#reflection-and-expression)
- [Validation](#validation)
- [HtmlParser](#htmlparser)
- [Profiler](#profling-tracing-and-metrics)
- [Caching](#caching)
- [Testing](#testing)
- [OpenAPI](#openapi)
- [Logging](#logging)
- [Console](#console)

## Libraries
<!--
	🟡 Recommended - 🟢 Good to know - 🟣 Other options / Possibilities
-->

### Object Mapper
- [**AutoMapper**](https://github.com/AutoMapper/AutoMapper) 
	> A convention-based object-object mapper in .NET

	[![GitHub Stars](https://img.shields.io/github/stars/AutoMapper/AutoMapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoMapper/AutoMapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoMapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoMapper)

- [**Mapperly**](https://github.com/riok/mapperly)
	> A .NET source generator for generating object mappings. No runtime reflection.

	[![GitHub Stars](https://img.shields.io/github/stars/riok/mapperly?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/riok/mapperly)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Riok.Mapperly?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Riok.Mapperly)

- [**Maspter**](https://github.com/MapsterMapper/Mapster)
	> A fast, fun and stimulating object to object Mapper

	[![GitHub Stars](https://img.shields.io/github/stars/MapsterMapper/Mapster?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MapsterMapper/Mapster)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Mapster?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Mapster)

### IoC
- [**Autofac**](https://github.com/autofac/Autofac)
	> Autofac is an IoC container for .NET. It manages the dependencies between classes so that applications stay easy to change as they grow in size and complexity.

	[![GitHub Stars](https://img.shields.io/github/stars/autofac/Autofac?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/autofac/Autofac)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Autofac?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Autofac)

### Task Scheduler / Background Job
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

### Serialization
- Json Serializer
	- [**Newtonsoft.Json (Json.NET)**](https://github.com/JamesNK/Newtonsoft.Json)
		> Json .NET is a popular high-performance JSON framework for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/JamesNK/Newtonsoft.Json?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JamesNK/Newtonsoft.Json)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Newtonsoft.Json?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Newtonsoft.Json)

- Binary Serializer
	- [**MessagePack**](https://github.com/neuecc/MessagePack-CSharp)
		> Extremely Fast MessagePack (MsgPack) Serializer for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/neuecc/MessagePack-CSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/neuecc/MessagePack-CSharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MessagePack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MessagePack)

	- [**Protobuf-Net**](https://github.com/protobuf-net/protobuf-net)
		> protobuf-net is a contract based serializer for .NET code, that happens to write data in the "protocol buffers" serialization format engineered by Google.
		
		[![GitHub Stars](https://img.shields.io/github/stars/protobuf-net/protobuf-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/protobuf-net/protobuf-net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/protobuf-net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/protobuf-net)

- XML Serializer
	- [**System.Xml.XmlSerializer**](https://docs.microsoft.com/en-us/dotnet/api/system.xml.serialization.xmlserializer)
		> Provides classes for serializing objects to the Extensible Markup Language (XML) and deserializing XML data to objects.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/System.Xml.XmlSerializer?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/System.Xml.XmlSerializer)

### Database, Database Drivers, and Migration
- Database
	- [**LiteDB**](https://github.com/mbdavid/litedb)
		> LiteDB is a small, fast and lightweight .NET NoSQL embedded database.
		
		[![GitHub Stars](https://img.shields.io/github/stars/mbdavid/litedb?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mbdavid/litedb)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/LiteDB?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/LiteDB)

	- [**RavenDB.Client**](https://github.com/ravendb/ravendb)
		> An ACID NoSQL Document Database.
		
		[![GitHub Stars](https://img.shields.io/github/stars/ravendb/ravendb?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ravendb/ravendb)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RavenDB.Client?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RavenDB.Client)

- Database Connector
	- [**Npgsql**](https://github.com/npgsql/Npgsql)
		> Npgsql is the .NET data provider for PostgreSQL.
		
		[![GitHub Stars](https://img.shields.io/github/stars/npgsql/Npgsql?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/npgsql/Npgsql)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Npgsql?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Npgsql)

	- [**MongoDB.Driver**](https://github.com/mongodb/mongo-csharp-driver)
		> The official MongoDB C#/.NET Driver provides asynchronous interaction with MongoDB.
		
		[![GitHub Stars](https://img.shields.io/github/stars/mongodb/mongo-csharp-driver?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mongodb/mongo-csharp-driver)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoDB.Driver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoDB.Driver)

	- [**MySql.Data**](https://dev.mysql.com/downloads)
		> MySql.Data.MySqlClient .NET Core Class Library.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MySql.Data?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MySql.Data)

- Database Migrations
	- [**FluentMigrator**](https://github.com/fluentmigrator/fluentmigrator)
		> Fluent Migrator is a migration framework for .NET much like Ruby on Rails Migrations.
		
		[![GitHub Stars](https://img.shields.io/github/stars/fluentmigrator/fluentmigrator?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/fluentmigrator/fluentmigrator)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentMigrator?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentMigrator)

### ORM and Micro-ORM 
- ORM
	- [**Entity Framework**](https://github.com/dotnet/ef6)
		> Entity Framework 6 (EF6) is an object-relational mapper that enables .NET developers to work with relational data using domain-specific objects. It eliminates the need for most of the data-access code that developers usually need to write.

		[![GitHub Stars](https://img.shields.io/github/stars/dotnet/ef6?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/ef6)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EntityFramework?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EntityFramework)

	- [**Entity Framework Core**](https://github.com/dotnet/efcore)
		> EF Core is a modern object-database mapper for .NET. It supports LINQ queries, change tracking, updates, and schema migrations.

		[![GitHub Stars](https://img.shields.io/github/stars/dotnet/efcore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/efcore)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.EntityFrameworkCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore)

	- [**linq2db**](https://github.com/linq2db/linq2db)
		> Linq to database provider.

		[![GitHub Stars](https://img.shields.io/github/stars/linq2db/linq2db?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/linq2db/linq2db)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/linq2db?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/linq2db)

- Micro ORM
	- [**Dapper**](https://github.com/StackExchange/Dapper)
		> Dapper - a simple object mapper for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/Dapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/Dapper)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper)

	- [**ServiceStack.OrmLite**](https://github.com/ServiceStack/ServiceStack.OrmLite)
		>  Fast, Simple, Typed ORM for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/ServiceStack/ServiceStack.OrmLite?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ServiceStack/ServiceStack.OrmLite)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ServiceStack.OrmLite?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ServiceStack.OrmLite)

- Entity Framework Core Extensions and Helpers
	- [**EFCore.BulkExtensions**](https://github.com/borisdj/EFCore.BulkExtensions)
		> Entity Framework Core Bulk Batch Extensions for Insert Update Delete and Read (CRUD) operations on SQL Server and SQLite.
		
		[![GitHub Stars](https://img.shields.io/github/stars/borisdj/EFCore.BulkExtensions?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/borisdj/EFCore.BulkExtensions)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EFCore.BulkExtensions?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EFCore.BulkExtensions)

	- [**Z.EntityFramework.Plus.EFCore**](https://github.com/zzzprojects/EntityFramework-Plus)
		> Entity Framework Plus extends your DbContext with must-haves features: Include Filter, Auditing, Caching, Query Future, Batch Delete, Batch Update, and more.
		
		[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/EntityFramework-Plus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/EntityFramework-Plus)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Z.EntityFramework.Plus.EFCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Z.EntityFramework.Plus.EFCore)

	- [**EF Core Second Level Cache Interceptor**](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		> Entity Framework Core Second Level Caching Library.

		[![GitHub Stars](https://img.shields.io/github/stars/VahidN/EFCoreSecondLevelCacheInterceptor?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EFCoreSecondLevelCacheInterceptor?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EFCoreSecondLevelCacheInterceptor)

- Entity Framework Core Providers
	- [**Microsoft.EntityFrameworkCore.SqlServer**](https://github.com/dotnet/efcore)
		> Microsoft SQL Server database provider for Entity Framework Core.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.EntityFrameworkCore.SqlServer?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer)

	- [**Microsoft.EntityFrameworkCore.InMemory**](https://github.com/dotnet/efcore)
		> In-memory database provider for Entity Framework Core (to be used for testing purposes).
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.EntityFrameworkCore.InMemory?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.InMemory)

	- [**MySql.Data.EntityFrameworkCore**](https://dev.mysql.com/doc/connector-net/en/connector-net-entityframework-core.html)
		> MySql database provider for Entity Framework Core.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MySql.Data.EntityFrameworkCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MySql.Data.EntityFrameworkCore)

	- [**Npgsql.EntityFrameworkCore.PostgreSQL**](https://github.com/npgsql/efcore.pg)
		> Entity Framework Core provider for PostgreSQL.
		
		[![GitHub Stars](https://img.shields.io/github/stars/npgsql/efcore.pg?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/npgsql/efcore.pg)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Npgsql.EntityFrameworkCore.PostgreSQL?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Npgsql.EntityFrameworkCore.PostgreSQL)

- Dapper Extensions and Helpers
	- [**Dapper.Contrib**](https://github.com/StackExchange/Dapper)
		> The official collection of get, insert, update and delete helpers for Dapper.net. Also handles lists of entities and optional "dirty" tracking of interface-based entities.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper.Contrib?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper.Contrib)

	- [**Dapper.SqlBuilder**](https://github.com/StackExchange/Dapper)
		> The Dapper SqlBuilder component, for building SQL queries dynamically.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper.SqlBuilder?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper.SqlBuilder)

	- [**Dapper.FluentMap**](https://github.com/henkmollema/Dapper-FluentMap)
		> Simple API to fluently map POCO properties to database columns when using Dapper.
		
		[![GitHub Stars](https://img.shields.io/github/stars/henkmollema/Dapper-FluentMap?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/henkmollema/Dapper-FluentMap)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper.FluentMap?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper.FluentMap)

- SQL Query Builder
	- [**SqlKata**](https://github.com/sqlkata/querybuilder)
		> SqlKata Query Builder is a powerful SQL Query Builder written in C#.
		
		[![GitHub Stars](https://img.shields.io/github/stars/sqlkata/querybuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sqlkata/querybuilder)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SqlKata?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SqlKata)

	- [**ExpressionExtensionSQL**](https://github.com/gambarra/ExpressionExtensionSQL)
		> ExpressionExtensionSQL is a NuGet library which you can add to your project to achieve lambda expression in SQL code. [Dapper Extension](https://www.nuget.org/packages/ExpressionExtensionSQL.Dapper)
		
		[![GitHub Stars](https://img.shields.io/github/stars/gambarra/ExpressionExtensionSQL?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/gambarra/ExpressionExtensionSQL)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ExpressionExtensionSQL?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ExpressionExtensionSQL)

### NoSQL
- [**Elastic**](https://github.com/elastic/elasticsearch-net)
	> Exposes all the Elasticsearch API endpoints but leaves you in control of building the request and response bodies. 

	[![GitHub Stars](https://img.shields.io/github/stars/elastic/elasticsearch-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/elastic/elasticsearch-net)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Elasticsearch.Net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Elasticsearch.Net)

- [**StackExchange.Redis**](https://github.com/StackExchange/StackExchange.Redis)
	> High performance Redis client, incorporating both synchronous and asynchronous usage.
	
	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/StackExchange.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/StackExchange.Redis)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/StackExchange.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/StackExchange.Redis)

### MongoDb
- MongoDb Helpers/Repository
	- [**Mongo2Go**](https://github.com/Mongo2Go/Mongo2Go)
		> MongoDB for integration tests & local debugging
		
		[![GitHub Stars](https://img.shields.io/github/stars/Mongo2Go/Mongo2Go?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Mongo2Go/Mongo2Go)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Mongo2Go?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Mongo2Go)

	- [**MongoDbGenericRepository**](https://github.com/alexandre-spieser/mongodb-generic-repository)
		> An example of generic repository implementation using the MongoDB C# Sharp 2.0 driver (async).
		
		[![GitHub Stars](https://img.shields.io/github/stars/alexandre-spieser/mongodb-generic-repository?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/alexandre-spieser/mongodb-generic-repository)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoDbGenericRepository?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoDbGenericRepository)

- MongoDb Framework
	- [**MongoFramework**](https://github.com/TurnerSoftware/MongoFramework)
		> An "Entity Framework"-like interface for MongoDB.
		
		[![GitHub Stars](https://img.shields.io/github/stars/TurnerSoftware/MongoFramework?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/TurnerSoftware/MongoFramework)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoFramework?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoFramework)

- MongoDb Identity Integration
	- [**AspNetCore.Identity.MongoDbCore**](https://github.com/alexandre-spieser/AspNetCore.Identity.MongoDbCore)
		> A MongoDb UserStore and RoleStore adapter for Microsoft.AspNetCore.Identity 2.0. Allows you to use MongoDb instead of SQL server with Microsoft.AspNetCore.Identity 2.0.
		
		[![GitHub Stars](https://img.shields.io/github/stars/alexandre-spieser/AspNetCore.Identity.MongoDbCore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/alexandre-spieser/AspNetCore.Identity.MongoDbCore)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/AspNetCore.Identity.MongoDbCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AspNetCore.Identity.MongoDbCore)

- MongoDb Migrations
	- [**MongoDBMigrations**](https://bitbucket.org/i_am_a_kernel/mongodbmigrations/src/master/)
		> MongoDbMigrations uses the official MongoDB C# Driver to migrate your documents in your mongo database via useful fluent API.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoDBMigrations?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoDBMigrations)

### Messaging and Queue
- Commands/Events Dispatcher
	- [**MediatR**](https://github.com/jbogard/MediatR)
		> Simple, unambitious mediator implementation in .NET
		
		[![GitHub Stars](https://img.shields.io/github/stars/jbogard/MediatR?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jbogard/MediatR)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/mediatr?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/mediatr)

	- [**Brighter**](https://github.com/BrighterCommand/Brighter)
		> The Command Dispatcher pattern is an addition to the Command design pattern that decouples the dispatcher for a service from its execution.
		
		[![GitHub Stars](https://img.shields.io/github/stars/BrighterCommand/Brighter?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/BrighterCommand/Brighter)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/paramore.brighter?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/paramore.brighter)

- Message Bus
	- [**Confluent.Kafka**](https://github.com/confluentinc/confluent-kafka-dotnet)
		> Confluent's Apache Kafka .NET client.
		
		[![GitHub Stars](https://img.shields.io/github/stars/confluentinc/confluent-kafka-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/confluentinc/confluent-kafka-dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Confluent.Kafka?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Confluent.Kafka)

	- [**kafka-sharp**](https://github.com/criteo/kafka-sharp)
		> A .NET implementation of the Apache Kafka client side protocol geared toward performance (both throughput and memory wise). It is especially suited for scenarios where applications are streaming a large number of messages across a fair number of topics.
		
		[![GitHub Stars](https://img.shields.io/github/stars/criteo/kafka-sharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/criteo/kafka-sharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/kafka-sharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/kafka-sharp)

	- [**RabbitMQ.Client**](https://github.com/rabbitmq/rabbitmq-dotnet-client)
		> RabbitMQ .NET client
		
		[![GitHub Stars](https://img.shields.io/github/stars/rabbitmq/rabbitmq-dotnet-client?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/rabbitmq/rabbitmq-dotnet-client)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RabbitMQ.Client?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RabbitMQ.Client)

- Service Bus
	- [**MassTransit**](https://github.com/MassTransit/MassTransit)
		> MassTransit is a free, open-source distributed application framework for .NET. MassTransit makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliability, and scalability.
		
		[![GitHub Stars](https://img.shields.io/github/stars/MassTransit/MassTransit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MassTransit/MassTransit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MassTransit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MassTransit)

	- [**NServiceBus**](https://github.com/Particular/NServiceBus)
		> MassTransit is a free, open-source distributed application framework for .NET. MassTransit makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliability, and scalability.
		
		[![GitHub Stars](https://img.shields.io/github/stars/Particular/NServiceBus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Particular/NServiceBus)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NServiceBus?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NServiceBus)

### API and RPC
- API Frameworks
	- [**ServiceStack**](https://github.com/ServiceStack/ServiceStack)
		> ServiceStack is a simple and fast alternative to WCF, MVC and Web API in one cohesive framework for all your services and web apps that's intuitive and Easy to use!
		
		[![GitHub Stars](https://img.shields.io/github/stars/ServiceStack/ServiceStack?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ServiceStack/ServiceStack)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ServiceStack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ServiceStack)
	
	- [**Microsoft.OData.Core**](https://github.com/OData/odata.net)
		> Open Data Protocol - .NET Libraries and Frameworks 
		
		[![GitHub Stars](https://img.shields.io/github/stars/OData/odata.net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/OData/odata.net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.OData.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.OData.Core)

- gRPC
	- [**Grpc.Core**](https://github.com/grpc/grpc)
		> A C# implementation of gRPC based on the native gRPC Core library.
		
		[![GitHub Stars](https://img.shields.io/github/stars/grpc/grpc?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/grpc/grpc)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Grpc.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Grpc.Core)

- GraphQL
	- [**HotChocolate**](https://github.com/ChilliCream/hotchocolate)
		> The Hot Chocolate GraphQL query execution engine and query validation.
		
		[![GitHub Stars](https://img.shields.io/github/stars/ChilliCream/hotchocolate?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ChilliCream/hotchocolate)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/HotChocolate?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/HotChocolate)

	- [**GraphQL for .NET**](https://github.com/graphql-dotnet/graphql-dotnet)
		> An implementation of Facebook's GraphQL in .NET.
		
		[![GitHub Stars](https://img.shields.io/github/stars/graphql-dotnet/graphql-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/graphql-dotnet/graphql-dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/GraphQL?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/GraphQL/)		

- WCF - SOAP
	- [**SoapCore**](https://github.com/DigDes/SoapCore)
		> SOAP protocol middleware for ASP.NET Core.
		
		[![GitHub Stars](https://img.shields.io/github/stars/DigDes/SoapCore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/DigDes/SoapCore)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SoapCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SoapCore)

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

### Mail and SMTP Server
- Mail
	- [**MailKit**](https://github.com/jstedfast/MailKit)
		> MailKit is an Open Source cross-platform .NET mail-client library that is based on MimeKit and optimized for mobile devices.
		
		[![GitHub Stars](https://img.shields.io/github/stars/jstedfast/MailKit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jstedfast/MailKit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MailKit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MailKit)

- Mail Service SDK
	- [**Sendgrid**](https://github.com/sendgrid/sendgrid-csharp)
		> The Official Twilio SendGrid Led, Community Driven C#, .NET Standard, .NET Core API Library.
		
		[![GitHub Stars](https://img.shields.io/github/stars/sendgrid/sendgrid-csharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sendgrid/sendgrid-csharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SendGrid?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SendGrid)

	- [**SendGrid.SmtpApi**](https://github.com/sendgrid/smtpapi-csharp)
		> Easily build SendGrid SMTPAPI headers.
		
		[![GitHub Stars](https://img.shields.io/github/stars/sendgrid/smtpapi-csharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sendgrid/smtpapi-csharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SendGrid.SmtpApi?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SendGrid.SmtpApi)

	- [**SendGrid.CSharp.HTTP.Client**](https://github.com/sendgrid/csharp-http-client)
		> A Simple Fluent REST API Client.
		
		[![GitHub Stars](https://img.shields.io/github/stars/sendgrid/csharp-http-client?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sendgrid/csharp-http-client)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SendGrid.CSharp.HTTP.Client?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SendGrid.CSharp.HTTP.Client)

- SMTP Server and POP3
	- [**netDumbster**](https://github.com/cmendible/netDumbster)
		> netDumbster is a .NET Fake SMTP Server clone of the popular Dumbster.
		
		[![GitHub Stars](https://img.shields.io/github/stars/cmendible/netDumbster?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/cmendible/netDumbster)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/netDumbster?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/netDumbster)

### Security
- Security Libraries
	- [**NWebsec**](https://github.com/NWebsec/NWebsec)
		> NWebsec consists of several security libraries for ASP.NET applications.

		[![GitHub Stars](https://img.shields.io/github/stars/NWebsec/NWebsec?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/NWebsec/NWebsec)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NWebsec.AspNetCore.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NWebsec.AspNetCore.Core)

- Authentication and Authorization
	- [**Microsoft.AspNetCore.Identity**](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity)
		> ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data. ASP.NET Core Identity allows you to add login features to your application and makes it easy to customize data about the logged in user.

		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.AspNetCore.Identity?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity)

	- [**IdentityServer4**](https://github.com/IdentityServer/IdentityServer4)
		> IdentityServer is a free, open source OpenID Connect and OAuth 2.0 framework for ASP.NET Core.

		[![GitHub Stars](https://img.shields.io/github/stars/IdentityServer/IdentityServer4?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/IdentityServer/IdentityServer4)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/IdentityServer4?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/IdentityServer4)

- Captcha
	- [**PaulMiami.AspNetCore.Mvc.Recaptcha**](https://github.com/PaulMiami/reCAPTCHA)
		> The reCAPTCHA 2.0 for ASPNET Core.

		[![GitHub Stars](https://img.shields.io/github/stars/PaulMiami/reCAPTCHA?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/PaulMiami/reCAPTCHA)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PaulMiami.AspNetCore.Mvc.Recaptcha?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PaulMiami.AspNetCore.Mvc.Recaptcha)

- Password Valdiator/Generator
	- [**PasswordGenerator**](https://github.com/prjseal/PasswordGenerator)
		> A library which generates random passwords with different settings to meet the OWASP requirements.

		[![GitHub Stars](https://img.shields.io/github/stars/prjseal/PasswordGenerator?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/prjseal/PasswordGenerator)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PasswordGenerator?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PasswordGenerator)

- Cryptography
	- [**Portable.BouncyCastle**](https://github.com/novotnyllc/bc-csharp)
		> A library which generates random passwords with different settings to meet the OWASP requirements.

		[![GitHub Stars](https://img.shields.io/github/stars/novotnyllc/bc-csharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/novotnyllc/bc-csharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Portable.BouncyCastle?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Portable.BouncyCastle)

### Compression
- Zip Compression
	- [**SharpZipLib**](https://github.com/icsharpcode/SharpZipLib)
		> #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.

		[![GitHub Stars](https://img.shields.io/github/stars/icsharpcode/SharpZipLib?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/icsharpcode/SharpZipLib)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SharpZipLib?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SharpZipLib)

- Compression Algorithms
	- [**Brotli.NET**](https://github.com/XieJJ99/brotli.net)
		> The .NET implementation of the brotli algorithm, provides similar interface to Google official API.

		[![GitHub Stars](https://img.shields.io/github/stars/XieJJ99/brotli.net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/XieJJ99/brotli.net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Brotli.NET?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Brotli.NET)

### CSV, Excel, Word, and PDF
- CSV
	- [**CsvHelper**](https://github.com/JoshClose/CsvHelper)
		> Library to help reading and writing CSV files

		[![GitHub Stars](https://img.shields.io/github/stars/JoshClose/CsvHelper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JoshClose/CsvHelper)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/CsvHelper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/CsvHelper)

- Excel
	- [**EPPlus**](https://github.com/EPPlusSoftware/EPPlus)
		> Create advanced Excel spreadsheets using .NET

		[![GitHub Stars](https://img.shields.io/github/stars/EPPlusSoftware/EPPlus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/EPPlusSoftware/EPPlus)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EPPlus?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EPPlus)

	- [**NPOI**](https://github.com/nissl-lab/npoi)
		> a .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.

		[![GitHub Stars](https://img.shields.io/github/stars/nissl-lab/npoi?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nissl-lab/npoi)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NPOI?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NPOI)

- Word
	- [**DocX**](https://github.com/xceedsoftware/DocX)
		> DocX is a .NET library that allows developers to manipulate Microsoft Word files, in an easy and intuitive manner. DocX is fast, lightweight and best of all it does not require Microsoft Word or Office to be installed.

		[![GitHub Stars](https://img.shields.io/github/stars/xceedsoftware/DocX?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xceedsoftware/DocX)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/DocX?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DocX)
	
	- [**NPOI**](https://github.com/nissl-lab/npoi)
		> a .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.

		[![GitHub Stars](https://img.shields.io/github/stars/nissl-lab/npoi?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nissl-lab/npoi)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NPOI?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NPOI)
	
- PDF
	- Reporting
		- [**FastReport**](https://github.com/FastReports/FastReport)
			> FastReport provides free open source report generator for .NET 5/.NET Core/.NET Framework. You can use the FastReport Open Source in MVC, Web API, console applications.

			[![GitHub Stars](https://img.shields.io/github/stars/FastReports/FastReport?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FastReports/FastReport)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/FastReport.OpenSource?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FastReport.OpenSource/)
		
		- [**PdfReport.Core**](https://github.com/VahidN/PdfReport.Core)
			> PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries
			
			[![GitHub Stars](https://img.shields.io/github/stars/VahidN/PdfReport.Core?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/VahidN/PdfReport.Core)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/PdfRpt.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PdfRpt.Core/)
	
	- Renderers
		- [**DinkToPdf**](https://github.com/rdvojmoc/DinkToPdf)
			> .NET Core P/Invoke wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.

			[![GitHub Stars](https://img.shields.io/github/stars/rdvojmoc/DinkToPdf?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/rdvojmoc/DinkToPdf)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/DinkToPdf?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DinkToPdf)

	- Create, Edit and Extract
		- [**itext7**](https://github.com/itext/itext7-dotnet)
			> iText 7 allows you to build custom PDF scenarios for web, mobile, desktop or cloud apps in .NET.

			[![GitHub Stars](https://img.shields.io/github/stars/itext/itext7-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/itext/itext7-dotnet)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/itext7?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/itext7)
	
### DateTime
- [**NodaTime**](https://github.com/nodatime/nodatime)
	> A better date and time API for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/nodatime/nodatime?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nodatime/nodatime)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NodaTime?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NodaTime)

- [**DateTimeExtensions**](https://github.com/joaomatossilva/DateTimeExtensions)
	> This project is a merge of several common DateTime operations on the form of extensions to System.DateTime, including natural date difference text (precise and human rounded), holidays and working days calculations on several culture locales.

	[![GitHub Stars](https://img.shields.io/github/stars/joaomatossilva/DateTimeExtensions?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/joaomatossilva/DateTimeExtensions)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/DateTimeExtensions?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DateTimeExtensions)

### Linq
- [**MoreLinq**](https://github.com/morelinq/MoreLINQ)
	> Extensions to LINQ to Objects.

	[![GitHub Stars](https://img.shields.io/github/stars/morelinq/MoreLINQ?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/morelinq/MoreLINQ)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/morelinq?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/morelinq)

### Reflection and Expression
- Reflection
	- [**FastMember**](https://github.com/mgravell/fast-member)
		> In .NET reflection is slow... well, kinda slow. If you need access to the members of an arbitrary type, with the type and member-names known only at runtime - then it is frankly hard (especially for DLR types). This library makes such access easy and fast.

		[![GitHub Stars](https://img.shields.io/github/stars/mgravell/fast-member?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mgravell/fast-member)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FastMember?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FastMember)

- Expression
	- [**System.Linq.Dynamic.Core**](https://github.com/zzzprojects/System.Linq.Dynamic.Core)
		> This is a .NET Standard / .NET Core port of the the Microsoft assembly for the .NET 4.0 Dynamic language functionality. [EF Core Extension](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.DynamicLinq)
		
		[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/System.Linq.Dynamic.Core?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/System.Linq.Dynamic.Core)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/System.Linq.Dynamic.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/System.Linq.Dynamic.Core)

- Expression Builder
	- [**Castle.DynamicLinqQueryBuilder**](https://github.com/castle-it/dynamic-linq-query-builder)
		> A truly generic and dynamic linq query builder to compliment jQuery QueryBuilder and other dynamic linq query generation needs.
		
		[![GitHub Stars](https://img.shields.io/github/stars/castle-it/dynamic-linq-query-builder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/castle-it/dynamic-linq-query-builder)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Castle.DynamicLinqQueryBuilder?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Castle.DynamicLinqQueryBuilder)

- Expressions Interpreter/Evaluator
	- [**Z.Expressions.Eval**](https://eval-expression.net)
		> Evaluate, Compile and Execute C# code at runtime.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Z.Expressions.Eval?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Z.Expressions.Eval)

### Validation
- [**FluentValidation**](https://github.com/FluentValidation/FluentValidation)
	> A popular .NET validation library for building strongly-typed validation rules.

	[![GitHub Stars](https://img.shields.io/github/stars/FluentValidation/FluentValidation?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FluentValidation/FluentValidation)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentValidation?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentValidation)

### HtmlParser
- [**HtmlAgilityPack**](https://github.com/zzzprojects/html-agility-pack)
	> HAP is an HTML parser written in C# to read/write DOM and supports plain XPATH or XSLT.
	
	[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/html-agility-pack?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/html-agility-pack)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/HtmlAgilityPack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/HtmlAgilityPack)

- [**AngleSharp**](https://github.com/AngleSharp/AngleSharp)
	> The ultimate angle brackets parser library parsing HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specifications.
	
	[![GitHub Stars](https://img.shields.io/github/stars/AngleSharp/AngleSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AngleSharp/AngleSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AngleSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AngleSharp)

### Profling, Tracing, and Metrics
- Profiling/Monitoring
	- [**MiniProfiler**](https://github.com/MiniProfiler/dotnet)
		> A simple but effective mini-profiler for ASP.NET (and Core) websites.

		[![GitHub Stars](https://img.shields.io/github/stars/MiniProfiler/dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MiniProfiler/dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MiniProfiler.AspNetCore.Mvc?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc)

- Tracing
	- [**prometheus-net**](https://github.com/prometheus-net/prometheus-net)
		> .NET library to instrument your code with Prometheus metrics.

		[![GitHub Stars](https://img.shields.io/github/stars/prometheus-net/prometheus-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/prometheus-net/prometheus-net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/prometheus-net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/prometheus-net)
	
- Metrics
	- [**App.Metrics**](https://github.com/AppMetrics/AppMetrics)
		> App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application.

		[![GitHub Stars](https://img.shields.io/github/stars/AppMetrics/AppMetrics?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AppMetrics/AppMetrics)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/App.Metrics?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/App.Metrics)

### Caching
- InMemory
	- [**Microsoft.Extensions.Caching.Memory**](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
		> In-memory cache implementation of Microsoft.Extensions.Caching.Memory.IMemoryCache.

		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.Extensions.Caching.Memory?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.Extensions.Caching.Memory)

- Distributed
	- [**StackExchange.Redis**](https://github.com/StackExchange/StackExchange.Redis)
		> High performance Redis client, incorporating both synchronous and asynchronous usage.
	
		[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/StackExchange.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/StackExchange.Redis)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/StackExchange.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/StackExchange.Redis)

	- [**ServiceStack.Redis**](https://github.com/ServiceStack/ServiceStack.Redis)
		> ServiceStack Redis Client is a simple, high-performance and feature-rich Client for Redis with native support and high-level abstractions for serializing POCOs and Complex Types.
	
		[![GitHub Stars](https://img.shields.io/github/stars/ServiceStack/ServiceStack.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ServiceStack/ServiceStack.Redis)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ServiceStack.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ServiceStack.Redis) 

- Caching Frameworks
	- [**CacheManager.Core**](https://github.com/MichaCo/CacheManager)
		> CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.

		[![GitHub Stars](https://img.shields.io/github/stars/MichaCo/CacheManager?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MichaCo/CacheManager)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/CacheManager.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/CacheManager.Core)
	- [**FusionCache**](https://github.com/jodydonetti/ZiggyCreatures.FusionCache)
		> FusionCache is an easy to use, high performance and robust cache with an optional distributed 2nd layer and some advanced features.

		[![GitHub Stars](https://img.shields.io/github/stars/jodydonetti/ZiggyCreatures.FusionCache?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jodydonetti/ZiggyCreatures.FusionCache)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ZiggyCreatures.FusionCache?label=Downloads&logo=nuget&cacheSeconds=3600)](https://github.com/jodydonetti/ZiggyCreatures.FusionCache)

- Second Level Cache
	- [**EF Core Second Level Cache Interceptor**](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		> Entity Framework Core Second Level Caching Library.

		[![GitHub Stars](https://img.shields.io/github/stars/VahidN/EFCoreSecondLevelCacheInterceptor?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EFCoreSecondLevelCacheInterceptor?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EFCoreSecondLevelCacheInterceptor)

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
		
	- [**MyTested.AspNetCore.Mvc**](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc)
		> MyTested.AspNetCore.Mvc is a strongly-typed unit testing library providing an easy fluent interface to test the ASP.NET Core framework, perfectly suitable for 			both MVC and API scenarios. It is testing framework agnostic so that you can combine it with a test runner of your choice (e.g. xUnit, NUnit, etc.).

		[![GitHub Stars](https://img.shields.io/github/stars/ivaylokenov/MyTested.AspNetCore.Mvc?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MyTested.AspNetCore.Mvc?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MyTested.AspNetCore.Mvc/)

- Asserations
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

- Fixture - Data Generator
	- [**AutoFixture**](https://github.com/AutoFixture/AutoFixture)
		> AutoFixture makes it easier for developers to do Test-Driven Development by automating non-relevant Test Fixture Setup, allowing the Test Developer to focus on the essentials of each test case.
		
		[![GitHub Stars](https://img.shields.io/github/stars/AutoFixture/AutoFixture?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoFixture/AutoFixture)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoFixture?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoFixture)
	
	- [**NBuilder**](https://github.com/nbuilder/nbuilder)
		> Through a fluent, extensible interface, NBuilder allows you to rapidly create test data, automatically assigning values to properties and public fields that are one of the built in .NET data types (e.g. ints and strings). NBuilder allows you to override for properties you are interested in using lambda expressions.
		
		[![GitHub Stars](https://img.shields.io/github/stars/nbuilder/nbuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nbuilder/nbuilder)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/nbuilder?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/nbuilder)

- Helpers
	- [**Respawn**](https://github.com/jbogard/Respawn)
		> Respawn is a small utility to help in resetting test databases to a clean state. Instead of deleting data at the end of a test or rolling back a transaction, Respawn resets the database back to a clean checkpoint by intelligently deleting data from tables.
		
		[![GitHub Stars](https://img.shields.io/github/stars/jbogard/Respawn?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jbogard/Respawn)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Respawn?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Respawn)

- HttpClient Mocking
	- [**RichardSzalay.MockHttp**](https://github.com/richardszalay/mockhttp)
		> MockHttp is a testing layer for Microsoft's HttpClient library. It allows stubbed responses to be configured for matched HTTP requests and can be used to test your application's service layer.
		
		[![GitHub Stars](https://img.shields.io/github/stars/richardszalay/mockhttp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/richardszalay/mockhttp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RichardSzalay.MockHttp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RichardSzalay.MockHttp)

- EF/Queryable Mocking
	- [**Effort.EF6**](https://github.com/zzzprojects/EntityFramework-Effort)
		> Effort is a powerful tool that enables a convenient way to create automated tests for Entity Framework based applications. [Learn more](https://entityframework-effort.net)

		[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/EntityFramework-Effort?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/EntityFramework-Effort)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Effort.EF6?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Effort.EF6)

	- [**MockQueryable**](https://github.com/romantitov/MockQueryable)
		> Moking Entity Framework Core operations such as ToListAsync, FirstOrDefaultAsync etc.

		[![GitHub Stars](https://img.shields.io/github/stars/romantitov/MockQueryable?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/romantitov/MockQueryable)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MockQueryable.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MockQueryable.Core)

- Temp Database
	- [**EfCore.TestSupport**](https://github.com/JonPSmith/EfCore.TestSupport)
		> Tools for helping in unit testing applications that use Entity Framework Core.

		[![GitHub Stars](https://img.shields.io/github/stars/JonPSmith/EfCore.TestSupport?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JonPSmith/EfCore.TestSupport)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EfCore.TestSupport?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EfCore.TestSupport)

	- [**Mongo2Go**](https://github.com/Mongo2Go/Mongo2Go)
		> MongoDB for integration tests (.NET Core)

		[![GitHub Stars](https://img.shields.io/github/stars/Mongo2Go/Mongo2Go?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Mongo2Go/Mongo2Go)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Mongo2Go?label=Downloads&logo=nuget&cacheSeconds=3600)](https://nuget.org/packages/Mongo2Go)

- Log Testing
	- [**Serilog.Sinks.XUnit**](https://github.com/trbenning/serilog-sinks-xunit)
		> The xunit test output sink for Serilog.

		[![GitHub Stars](https://img.shields.io/github/stars/trbenning/serilog-sinks-xunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/trbenning/serilog-sinks-xunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Serilog.Sinks.XUnit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Serilog.Sinks.XUnit)

- Snapshot Testing
	- [**Snapshooter**](https://github.com/SwissLife-OSS/snapshooter)
		> Snapshooter is a flexible snapshot testing tool to simplify the result validation in your unit tests in .NET

		[![GitHub Stars](https://img.shields.io/github/stars/SwissLife-OSS/snapshooter?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SwissLife-OSS/snapshooter)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Snapshooter?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Snapshooter)

- BDD Testing
	- [**SpecFlow**](https://github.com/SpecFlowOSS/SpecFlow)
		> SpecFlow is a pragmatic BDD solution for .NET. It provides test automation for .NET (.NET Framework, .NET Core and Mono), based on the Gherkin specification language and integrates to Visual Studio.

		[![GitHub Stars](https://img.shields.io/github/stars/SpecFlowOSS/SpecFlow?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SpecFlowOSS/SpecFlow)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SpecFlow?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SpecFlow)

- UI Testing
	- [**Selenium.WebDriver**](https://github.com/SeleniumHQ/selenium)
		> Selenium is a set of different software tools each with a different approach to supporting browser automation. These tools are highly flexible, allowing many options for locating and manipulating elements within a browser, and one of its key features is the support for automating multiple browser platforms.
		
		[![GitHub Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SeleniumHQ/selenium)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Selenium.WebDriver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Selenium.WebDriver)

	- [**Puppeteer Sharp**](https://github.com/hardkoded/puppeteer-sharp)
		>  Headless Chrome .NET API

		[![GitHub Stars](https://img.shields.io/github/stars/hardkoded/puppeteer-sharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/hardkoded/puppeteer-sharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PuppeteerSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PuppeteerSharp)

- Code Coverage
	- [**Coverlet**](https://github.com/coverlet-coverage/coverlet)
		>  Cross platform code coverage for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/coverlet-coverage/coverlet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/coverlet-coverage/coverlet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/coverlet.collector?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/coverlet.collector)
	- [**ReportGenerator**](https://github.com/danielpalme/ReportGenerator)
		> Powerful code coverage visualization, ReportGenerator converts coverage reports generated by coverlet, OpenCover, dotCover, Visual Studio, NCover, Cobertura, JaCoCo, Clover, gcov or lcov into human readable reports in various formats.

		[![GitHub Stars](https://img.shields.io/github/stars/danielpalme/ReportGenerator?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/danielpalme/ReportGenerator)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ReportGenerator?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ReportGenerator)

- XUnit Extensions\Helpers
	- [**xunit.analyzers**](https://github.com/xunit/xunit.analyzers)
		> Code Analyzers for projects using xUnit.net that help find and fix frequent issues when writing tests.

		[![GitHub Stars](https://img.shields.io/github/stars/xunit/xunit.analyzers?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xunit/xunit.analyzers)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit.analyzers?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit.analyzers)

	- [**xunit.categories**](https://github.com/brendanconnolly/Xunit.Categories)
		> Friendlier attributes to help categorize your tests.

		[![GitHub Stars](https://img.shields.io/github/stars/brendanconnolly/Xunit.Categories?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/brendanconnolly/Xunit.Categories)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit.categories?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit.categories)

### OpenAPI
- [**Swagger (Swashbuckle)**](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	> Swagger tooling for API's built with ASP.NET Core. Generate beautiful API documentation, including a UI to explore and test operations, directly from your routes, controllers and models.
	
	[![GitHub Stars](https://img.shields.io/github/stars/domaindrivendev/Swashbuckle.AspNetCore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/swashbuckle.aspnetcore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/swashbuckle.aspnetcore)

- [**NSwag**](https://github.com/RicoSuter/NSwag)
	> The OpenAPI/Swagger API toolchain for .NET and TypeScript.

	[![GitHub Stars](https://img.shields.io/github/stars/RicoSuter/NSwag?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/RicoSuter/NSwag)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NSwag.AspNetCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NSwag.AspNetCore)

### Logging
- Logging libraries
	- [**Serilog**](https://github.com/serilog/serilog)
		> Serilog is a diagnostic logging library for .NET applications. It is easy to set up, has a clean API, and runs on all recent .NET platforms.
		
		[![GitHub Stars](https://img.shields.io/github/stars/serilog/serilog?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/serilog/serilog)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/serilog?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/serilog)

	- [**NLog**](https://github.com/NLog/NLog)
		> NLog is a free logging platform for .NET with rich log routing and management capabilities. It makes it easy to produce and manage high-quality logs for your application regardless of its size or complexity.

		[![GitHub Stars](https://img.shields.io/github/stars/NLog/NLog?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/NLog/NLog)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NLog?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NLog)

- Logging Management
	- [**Sentry**](https://github.com/getsentry/sentry-dotnet)
		> Open-source error tracking that helps developers monitor and fix crashes in real time.

		[![GitHub Stars](https://img.shields.io/github/stars/getsentry/sentry-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/getsentry/sentry-dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Sentry?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Sentry)

### Templating
- Template Engine
	- [**DotLiquid**](https://github.com/dotliquid/dotliquid)
		> .NET Port of Tobias Lütke's Liquid template language.
		
		[![GitHub Stars](https://img.shields.io/github/stars/dotliquid/dotliquid?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotliquid/dotliquid)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/DotLiquid?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DotLiquid)

- Razor Templating (Core)
	- [**RazorLight**](https://github.com/toddams/RazorLight)
		> Template engine based on Microsoft's Razor parsing engine for .NET Core.
		
		[![GitHub Stars](https://img.shields.io/github/stars/toddams/RazorLight?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/toddams/RazorLight)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RazorLight?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RazorLight)

- Razor Templating MVC5
	- [**RazorEngine**](https://github.com/Antaris/RazorEngine)
		> Open source templating engine based on Microsoft's Razor parsing engine.
		
		[![GitHub Stars](https://img.shields.io/github/stars/Antaris/RazorEngine?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Antaris/RazorEngine)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RazorEngine?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RazorEngine)

### Console
- [**Spectre.Console**](https://github.com/spectresystems/spectre.console)
	> A library that makes it easier to create beautiful, cross platform, console applications.
	
	[![GitHub Stars](https://img.shields.io/github/stars/spectresystems/spectre.console?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/spectresystems/spectre.console)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/spectre.console?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/spectre.console)

## Contribution
Contributions are always welcome! Feel free to open an [issue][issues] or create a pull request.

## License
[![CC0][license-badge]][license]

To the extent possible under law, [Mohammad Javad Ebrahimi](https://github.com/mjebrahimi) has waived all copyright and related or neighboring rights to this work.

[issues]: https://github.com/mjebrahimi/Awesome-DotNet-Packages/issues/new
[license]: https://creativecommons.org/publicdomain/zero/1.0
[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
