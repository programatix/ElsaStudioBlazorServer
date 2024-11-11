# ElsaStudioBlazorServer


## Running the servers

Run the server
```
dotnet run --project ElsaServer --urls "https://localhost:5001"
```

Run the studio
```
dotnet run --project ElsaStudioBlazorServer --urls "https://localhost:7001"
```

## Credential
user: admin
password: password

## Sample endpoints
- [HTML: Hello world](https://localhost:5001/workflows/hello-world)
- [HTML: Hello world with message](https://localhost:5001/workflows/hello-world?message=My%20name%20is%20John%20Doe)
- [JSON: Hello world](https://localhost:5001/workflows/hello-world-json)
- [JSON: Hello world with message](https://localhost:5001/workflows/hello-world-json?message=My%20name%20is%20John%20Doe)

## Documentation
- https://v3.elsaworkflows.io/docs
- https://v3.elsaworkflows.io/docs/core-concepts/workflow
- https://v3.elsaworkflows.io/docs/expressions/javascript
- https://v3.elsaworkflows.io/docs/expressions/liquid