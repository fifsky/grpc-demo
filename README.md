## GRPC DEMO


### install
```shell script
brew install protobuf
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc
make proto
```

### run

```
go run server.go
go run client.go
```

### response

```
SayHi 响应： message:"Hi Kitty" 
GetMsg 响应： msg:"Server msg is coming..." 
```