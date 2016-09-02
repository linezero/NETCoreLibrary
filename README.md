# ASP.NET Core and .NET Core Library Support

## Contents
 - [ORM/DBs](#ormdbs)
 - [Image](#image)
 - [RPC](#RPC)
 - [Message Queuing](#message-queuing)
 - [Web](#web)
 - [DI / IoC Containers](#di--ioc-containers)
 - [Logging](#logging)
 - [Serialization](#serialization)
 - [Testing](#testing)
 - [Other](#other)

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
MySQL | Install-Package MySql.Data.Core -Pre | Yes | Yes | 
[NPoco](https://github.com/schotime/NPoco) | Install-Package NPoco | Yes | Yes | 
[Chloe](https://github.com/shuxinqin/Chloe/tree/master/src/DotNetCore) |  | Yes | Yes | 

## Image
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[ImageProcessorCore](https://github.com/JimBobSquarePants/ImageProcessor/tree/Core) | Not yet ([myget](https://www.myget.org/gallery/imageprocessor)) | Yes | Yes | [imageprocessor.org](http://imageprocessor.org)

## RPC
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[JsonRpc](https://github.com/edjCase/JsonRpc) |Install-Package EdjCase.JsonRpc.Router | Yes | Yes | 


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
[Moq](https://github.com/moq/moq4) |  |  |  | 

## Other
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[AutoMapper](https://github.com/AutoMapper/AutoMapper) | Install-Package AutoMapper | Yes | Yes | [automapper.org](http://automapper.org/)
[HtmlAgilityPack](https://github.com/linezero/HtmlAgilityPack) |  | Yes | Yes | 
[Orchard](https://github.com/OrchardCMS/Orchard2) |  |  |  | [orchardproject.net](http://orchardproject.net)
[YesSql](https://github.com/sebastienros/yessql) |  | Yes | Yes | 
[WeiXinMPSDK](https://github.com/JeffreySu/WeiXinMPSDK) | Install-Package Senparc.Weixin.MP | Yes | Yes |
[Hangfire](https://github.com/HangfireIO/Hangfire) | Install-Package HangFire | Yes | Yes |  
[NETCoreBBS](https://github.com/linezero/NETCoreBBS) |  |  |  |

# License

收集来自于 [LineZero](https://github.com/linezero) ,转载复制请注明来源.
