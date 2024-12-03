# protoc-gen-auxo-service
an extension for auxo to generate svc code automatically.

## Build
```
go build .
```

## Run the plugin
```
protoc --plugin ./protoc-gen-auxo-service --auxo-service_out=. test_hello.proto
```