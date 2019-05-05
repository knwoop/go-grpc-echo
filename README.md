# Unary RPC --- 1 request / 1 response

### compile .proto file
```
$ protoc --proto_path proto --go_out=plugins=grpc:./proto/ ./proto/echo.proto
```

### Run the gRPC server
```
$ go run ./server
```

### Execute the client app
```
$ go run ./client hello
```