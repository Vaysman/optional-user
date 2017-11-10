# optional-user
Demo app 

# Run the app

```sh
./mvnw spring-boot:run
```

# Demo
## With credentials
### Request

```sh
curl -X GET http://localhost:8080/user -H 'authorization: Basic dXNlcjpwYXNzd29yZA=='
```

### Response

`user`

## Without credentials
### Request

```sh
curl -X GET http://localhost:8080/user 
```

### Response

`no user`
