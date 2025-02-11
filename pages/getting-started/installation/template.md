---
title: Using the IceRPC .NET Project Templates
---

## Template installation

The easiest way to create a new project configured for IceRPC is by using a .NET project template. You can install the
IceRPC project templates with the following [dotnet new] command:

```shell {% showTitle=false %}
dotnet new install IceRpc.Templates
```

## Template list

| Template name            | Description                                                                                                  |
| ------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `icerpc-slice-client`    | A project template for creating an IceRPC + Slice client console application.                                |
| `icerpc-slice-server`    | A project template for creating an IceRPC + Slice server console application.                                |
| `icerpc-slice-di-client` | A project template for creating an IceRPC + Slice client console application using Microsoft's DI container. |
| `icerpc-slice-di-server` | A project template for creating an IceRPC + Slice server console application using Microsoft's DI container. |

#### Create a client application (IceRPC + Slice)

```shell {% showTitle=false %}
dotnet new icerpc-slice-client -o MyClient
```

#### Create a server application (IceRPC + Slice)

```shell {% showTitle=false %}
dotnet new icerpc-slice-server -o MyServer
```

#### Create a client application (IceRPC + Slice and DI)

```shell {% showTitle=false %}
dotnet new icerpc-slice-di-client -o MyClient
```

#### Create a server application (IceRPC + Slice and DI)

```shell {% showTitle=false %}
dotnet new icerpc-slice-di-server -o MyServer
```

[dotnet new]: https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new
