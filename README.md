# Hi, I'm Justin 👋

I build open-source .NET resilience packages — **Polly v8 contrib libraries** that make it trivial to add retry, timeout, and circuit-breaker to any .NET library with a single line of code.

## Polly v8 Contrib Packages

| Package | Downloads | What it wraps |
|---|---|---|
| [![NuGet](https://img.shields.io/nuget/v/PollyEFCore.svg)](https://www.nuget.org/packages/PollyEFCore) [PollyEFCore](https://github.com/Swevo/PollyEFCore) | ![Downloads](https://img.shields.io/nuget/dt/PollyEFCore.svg) | Entity Framework Core |
| [![NuGet](https://img.shields.io/nuget/v/PollyDapper.svg)](https://www.nuget.org/packages/PollyDapper) [PollyDapper](https://github.com/Swevo/PollyDapper) | ![Downloads](https://img.shields.io/nuget/dt/PollyDapper.svg) | Dapper (any IDbConnection) |
| [![NuGet](https://img.shields.io/nuget/v/PollySqlClient.svg)](https://www.nuget.org/packages/PollySqlClient) [PollySqlClient](https://github.com/Swevo/PollySqlClient) | ![Downloads](https://img.shields.io/nuget/dt/PollySqlClient.svg) | SQL Server + Azure SQL |
| [![NuGet](https://img.shields.io/nuget/v/PollyNpgsql.svg)](https://www.nuget.org/packages/PollyNpgsql) [PollyNpgsql](https://github.com/Swevo/PollyNpgsql) | ![Downloads](https://img.shields.io/nuget/dt/PollyNpgsql.svg) | Npgsql (PostgreSQL) |
| [![NuGet](https://img.shields.io/nuget/v/PollyMongo.svg)](https://www.nuget.org/packages/PollyMongo) [PollyMongo](https://github.com/Swevo/PollyMongo) | ![Downloads](https://img.shields.io/nuget/dt/PollyMongo.svg) | MongoDB.Driver |
| [![NuGet](https://img.shields.io/nuget/v/PollyCosmosDb.svg)](https://www.nuget.org/packages/PollyCosmosDb) [PollyCosmosDb](https://github.com/Swevo/PollyCosmosDb) | ![Downloads](https://img.shields.io/nuget/dt/PollyCosmosDb.svg) | Azure Cosmos DB |
| [![NuGet](https://img.shields.io/nuget/v/PollyRedis.svg)](https://www.nuget.org/packages/PollyRedis) [PollyRedis](https://github.com/Swevo/PollyRedis) | ![Downloads](https://img.shields.io/nuget/dt/PollyRedis.svg) | StackExchange.Redis |
| [![NuGet](https://img.shields.io/nuget/v/PollyAzureBlob.svg)](https://www.nuget.org/packages/PollyAzureBlob) [PollyAzureBlob](https://github.com/Swevo/PollyAzureBlob) | ![Downloads](https://img.shields.io/nuget/dt/PollyAzureBlob.svg) | Azure Blob Storage |
| [![NuGet](https://img.shields.io/nuget/v/PollyAzureServiceBus.svg)](https://www.nuget.org/packages/PollyAzureServiceBus) [PollyAzureServiceBus](https://github.com/Swevo/PollyAzureServiceBus) | ![Downloads](https://img.shields.io/nuget/dt/PollyAzureServiceBus.svg) | Azure Service Bus |
| [![NuGet](https://img.shields.io/nuget/v/PollyRabbitMQ.svg)](https://www.nuget.org/packages/PollyRabbitMQ) [PollyRabbitMQ](https://github.com/Swevo/PollyRabbitMQ) | ![Downloads](https://img.shields.io/nuget/dt/PollyRabbitMQ.svg) | RabbitMQ.Client v7+ |
| [![NuGet](https://img.shields.io/nuget/v/PollyGrpc.svg)](https://www.nuget.org/packages/PollyGrpc) [PollyGrpc](https://github.com/Swevo/PollyGrpc) | ![Downloads](https://img.shields.io/nuget/dt/PollyGrpc.svg) | gRPC .NET |
| [![NuGet](https://img.shields.io/nuget/v/PollyMediatR.svg)](https://www.nuget.org/packages/PollyMediatR) [PollyMediatR](https://github.com/Swevo/PollyMediatR) | ![Downloads](https://img.shields.io/nuget/dt/PollyMediatR.svg) | MediatR |
| [![NuGet](https://img.shields.io/nuget/v/PollyOpenAI.svg)](https://www.nuget.org/packages/PollyOpenAI) [PollyOpenAI](https://github.com/Swevo/PollyOpenAI) | ![Downloads](https://img.shields.io/nuget/dt/PollyOpenAI.svg) | OpenAI + Azure OpenAI |
| [![NuGet](https://img.shields.io/nuget/v/PollyHealthChecks.svg)](https://www.nuget.org/packages/PollyHealthChecks) [PollyHealthChecks](https://github.com/Swevo/PollyHealthChecks) | ![Downloads](https://img.shields.io/nuget/dt/PollyHealthChecks.svg) | ASP.NET Core Health Checks |
| [![NuGet](https://img.shields.io/nuget/v/PollyBackoff.svg)](https://www.nuget.org/packages/PollyBackoff) [PollyBackoff](https://github.com/Swevo/PollyBackoff) | ![Downloads](https://img.shields.io/nuget/dt/PollyBackoff.svg) | Custom retry backoff strategies |
| [![NuGet](https://img.shields.io/nuget/v/PollyChaos.svg)](https://www.nuget.org/packages/PollyChaos) [PollyChaos](https://github.com/Swevo/PollyChaos) | ![Downloads](https://img.shields.io/nuget/dt/PollyChaos.svg) | Chaos engineering (Simmy) |

> Each package wraps its target library with a **one-liner** — `connection.WithPolly(pipeline)` — and ships a pre-built transient error predicate so you don't have to look up which exceptions to retry.
| [PollyMailKit](https://github.com/Swevo/PollyMailKit) | MailKit SMTP email client | [![NuGet](https://img.shields.io/nuget/v/PollyMailKit.svg)](https://www.nuget.org/packages/PollyMailKit/) |
| [PollyAzureQueueStorage](https://github.com/Swevo/PollyAzureQueueStorage) | Azure Queue Storage QueueClient | [![NuGet](https://img.shields.io/nuget/v/PollyAzureQueueStorage.svg)](https://www.nuget.org/packages/PollyAzureQueueStorage/) |
| [PollyHangfire](https://github.com/Swevo/PollyHangfire) | Hangfire IBackgroundJobClient | [![NuGet](https://img.shields.io/nuget/v/PollyHangfire.svg)](https://www.nuget.org/packages/PollyHangfire/) |