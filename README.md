# Weather API

Esta é uma API de previsão do tempo desenvolvida em .NET 8.0.

## Tecnologias Utilizadas

- **.NET 8.0**: Framework utilizado para construir e executar a aplicação.
- **ASP.NET Core**: Utilizado para criar a API.
- **Swashbuckle.AspNetCore**: Utilizado para gerar a documentação Swagger da API.
- **Microsoft OpenAPI**: Utilizado para definir a especificação OpenAPI.

## Como Executar

1. Clone o repositório:
    ```sh
    git clone https://github.com/DanilloAraujo/weather-api.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd weather-api
    ```
3. Restaure as dependências do projeto:
    ```sh
    dotnet restore
    ```
4. Execute o projeto:
    ```sh
    dotnet run
    ```

## Endpoints

### GET /weatherforecast

Retorna a previsão do tempo.

**Exemplo de Requisição:**
```http
GET /weatherforecast/ HTTP/1.1
Host: localhost:5231
Accept: application/json
```
**Exemplo de Resposta**
```json
[
  {
    "date": "2023-10-01T00:00:00Z",
    "temperatureC": 25,
    "temperatureF": 77,
    "summary": "Sunny"
  }
]
```
