# ASP.NET Core and .NET Core Library Support

## Contents
 - [ORM/DBs](#ormdbs)
 - [Image](#image)
 - [RPC](#rpc)
 - [Message Queuing](#message-queuing)
 - [Web](#web)
 - [DI / IoC Containers](#di--ioc-containers)
 - [Logging](#logging)
 - [Serialization](#serialization)
 - [Testing](#testing)
 - [Microservice](#microservice)
 - [Other](#other)
 - [Project](#project)

## ASP.NET Core and .NET Core 支持的类库
你可以通过 issue 或者 fork 来增加ASP.NET Core and .NET Core 支持的类库。

欢迎大家贡献及star。

---

## ORM/DBs
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Dapper](https://github.com/StackExchange/dapper-dot-net) | Install-Package Dapper | Yes | Yes | [github.io](https://stackexchange.github.io/dapper-dot-net)
[EF Core](https://github.com/aspnet/EntityFramework) | Install-Package EntityFramework.MicrosoftSqlServer | Yes | Yes | [efproject.net](http://docs.efproject.net/en/latest/)
[Npgsql](https://github.com/npgsql/Npgsql) | Install-Package Npgsql | Yes | Yes | [npgsql.org](http://www.npgsql.org)
[NEST](https://github.com/elastic/elasticsearch-net) | Install-Package NEST -Pre | Yes | Yes | [elastic.**co**](https://www.elastic.co)
[StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis) | Install-Package StackExchange.Redis -Pre | Yes | Yes | 
[MySQL](https://github.com/mysql/mysql-connector-net) | Install-Package MySql.Data -Pre | Yes | Yes | 
[MongoDB](https://github.com/mongodb/mongo-csharp-driver) | Install-Package mongocsharpdriver | Yes | Yes | 
[NPoco](https://github.com/schotime/NPoco) | Install-Package NPoco | Yes | Yes | 
[Chloe](https://github.com/shuxinqin/Chloe/tree/master/src/DotNetCore) |  | Yes | Yes |
[Lolita](https://github.com/PomeloFoundation/Lolita)| Install-Package Pomelo.EntityFrameworkCore.Lolita | Yes | Yes | 

## Image
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) | Not yet ([myget](https://www.myget.org/gallery/imagesharp)) | Yes | Yes | [imageprocessor.org](http://imageprocessor.org)

## RPC
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[JsonRpc](https://github.com/edjCase/JsonRpc) |Install-Package EdjCase.JsonRpc.Router | Yes | Yes | 
[gRPC](http://www.grpc.io) |Install-Package Grpc -Pre| Yes | Yes | [c#](http://www.grpc.io/docs/quickstart/csharp.html)


## Message Queuing
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[RestBus](https://github.com/tenor/RestBus) | Install-Package RestBus.AspNet -Pre ([guide](https://github.com/tenor/RestBus/wiki/ASP.NET-Core-service-%28RabbitMQ-callable%29)) | Yes | Yes | [restbus.org](http://restbus.org) ([Blog](http://ahuwanya.net/blog/post/Introducing-RestBus))
[RdKafka](https://github.com/ah-/rdkafka-dotnet) | Install-Package RdKafka | Yes | Yes | [ah-.github.io/rdkafka-dotnet](http://ah-.github.io/rdkafka-dotnet/)

## Web
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Nancy](https://github.com/NancyFx/Nancy) | Install-Package Nancy -Pre | Yes | Yes | [nancyfx.org](http://nancyfx.org)
[SignalR](https://github.com/aspnet/SignalR-Server) |  | Yes | Yes | [signalr.net](http://signalr.net/)
[ReactJS.NET](https://github.com/reactjs/React.NET) | Install-Package React.AspNet | No | Yes | [ReactJS.NET](http://reactjs.net/)
[Swashbuckle](https://github.com/domaindrivendev/Ahoy) | Install-Package Swashbuckle -Pre | Yes | Yes | 
[YOYOFx](https://github.com/maxzhang1985/YOYOFx) |  | Yes | Yes | 

## DI / IoC Containers
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Autofac](https://github.com/autofac/Autofac) | Install-Package Autofac -Pre | Yes | Yes | [autofac.org](http://autofac.org/)
[SimpleInjector](https://github.com/simpleinjector/SimpleInjector) | Install-Package SimpleInjector | Yes | Yes | [simpleinjector.org](https://simpleinjector.org)
[StructureMap](https://github.com/structuremap/structuremap) | Install-Package StructureMap | Yes | Yes | [structuremap.github.io](https://structuremap.github.io)
ASP.NET Core contains built-in [DI](https://docs.asp.net/en/latest/fundamentals/dependency-injection.html)

## Logging
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Serilog](https://github.com/serilog/serilog) | Install-Package Serilog | Yes | Yes | 
[NLog](https://github.com/NLog/Nlog) | Install-Package NLog.Extensions.Logging -Pre |  | Yes | 
[log4net](https://github.com/apache/log4net) |  | Yes | Yes | 
ASP.NET Core contains built-in [logging](https://docs.asp.net/en/latest/fundamentals/logging.html)

## Serialization
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[JSON.NET](https://github.com/JamesNK/Newtonsoft.Json) | Install-Package Newtonsoft.Json | Yes | Yes | [newtonsoft.com/json](http://www.newtonsoft.com/json)
[protobuf-net](https://github.com/mgravell/protobuf-net) | Install-Package protobuf-net | Yes | Yes

## Testing
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[xUnit.net](https://github.com/xunit/xunit) |  | [Yes](http://xunit.github.io/docs/getting-started-dotnet-core.html) | [Yes](http://xunit.github.io/docs/getting-started-dotnet-core.html) | 
[Nunit](https://github.com/nunit/nunit) | Install-Package NUnit | Yes | Yes | 
[Moq](https://github.com/moq/moq4) | Install-Package Moq -Pre | Yes | Yes | 

## Microservice
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Microphone](https://github.com/AsynkronIT/Microphone) | Install-Package Microphone.AspNet | Yes | Yes | [blog](http://blog.nethouse.se/2015/10/19/introducing-microphone-microservices-with-service-discovery-for-net/)
[Consul](https://www.consul.io/)||||[Consul入门](http://soft.dog/2016/03/19/consul-cluster/)


## Other
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[AutoMapper](https://github.com/AutoMapper/AutoMapper) | Install-Package AutoMapper | Yes | Yes | [automapper.org](http://automapper.org/)
[HtmlAgilityPack](https://github.com/linezero/HtmlAgilityPack) |  | Yes | Yes | 
[YesSql](https://github.com/sebastienros/yessql) |  | Yes | Yes | 
[WeiXinMPSDK](https://github.com/JeffreySu/WeiXinMPSDK) | Install-Package Senparc.Weixin.MP | Yes | Yes |
[Hangfire](https://github.com/HangfireIO/Hangfire) | Install-Package HangFire | Yes | Yes |
[Quartz.NET](https://github.com/quartznet/quartznet) | Install-Package Quartz -Pre | Yes | Yes | 
[IdentityServer4](https://github.com/IdentityServer/IdentityServer4) | Install-Package IdentityServer4 -Pre | Yes | Yes |   
[NPOI.Core](https://github.com/yuleyule66/Npoi.Core) | Install-Package Savorboard.Npoi.Core.OOXML | Yes | Yes |  
[EPPlus.Core](https://github.com/VahidN/EPPlus.Core) | Install-Package EPPlus.Core | Yes | Yes |  Linux need to install libgdiplus
[SharpCompress](https://github.com/adamhathcock/sharpcompress)| Install-Package sharpcompress | Yes | Yes | [sharpcompress](https://github.com/adamhathcock/sharpcompress#sharpcompress)
[SharpZipLib](#) | Install-Package SharpZipLib.NETStandard | Yes | Yes | 
[CWSharp](https://github.com/zhengchun/CWSharp) | Install-Package CWSharp | Yes | Yes | .NET跨平台中英文分词

## Project

Project | Website
------- | -------
[Orchard](https://github.com/OrchardCMS/Orchard2) | [orchardproject.net](http://orchardproject.net)
[MusicStore](https://github.com/aspnet/MusicStore) |
[NETCoreBBS](https://github.com/linezero/NETCoreBBS) |

# License

收集来自于 [NETCoreLibrary](https://github.com/linezero/NETCoreLibrary) ,转载复制请注明来源.

# Contributing

[LineZero](https://github.com/linezero)

[gutun](https://github.com/gutun)
