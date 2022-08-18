# Rest Client

- github: [Huachao/vscode-restclient](https://github.com/Huachao/vscode-restclient)
- vscode: [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

## Run

```bash
vi request.http
```

```http
GET https://reqres.in/api/users

###

POST https://reqres.in/api/users
Content-Type: application/json

{
    "name": "morpheus",
    "job": "leader"
}

###
```
