# backend-api (.NET 8)

API RESTful con autenticación básica JWT, CORS, Swagger y ejemplo de controlador `UserController`.

## Requisitos

- .NET SDK 8+

## Ejecutar

```bash
dotnet restore
dotnet run
```

## Endpoints

- `GET /api/user/profile` (requiere token)
