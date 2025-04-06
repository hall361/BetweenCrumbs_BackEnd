# BetweenCrumbs (Backend)

BetweenCrumbs es un proyecto que incluye un frontend desarrollado en Visual C# y un backend desarrollado en .NET 8.0. Este repositorio corresponde al backend, que gestiona la lógica de negocio y las funcionalidades relacionadas con la aplicación.

## Estructura del Proyecto

El backend está organizado en las siguientes capas:

- **BC.Application**: Contiene la lógica de negocio y los servicios.
- **BC.Models**: Define los modelos de datos y DTOs utilizados en la aplicación.
- **BC.Repositories**: Implementa la capa de acceso a datos y utilidades relacionadas.
- **BetweenCrumbsAPI**: Contiene la configuración principal de la API, controladores y archivos de configuración.

## Requisitos Previos

Antes de ejecutar el backend, asegúrate de tener instalados los siguientes componentes:

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) o cualquier IDE compatible con .NET
- [SQL Server](https://www.microsoft.com/sql-server) (si la base de datos está configurada para usar SQL Server)

## Configuración

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone <URL_DEL_REPOSITORIO>