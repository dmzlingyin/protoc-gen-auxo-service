# protoc-gen-auxo-service
a extension for auxo to generate svc code automatically.

## Build
```
go build .
```

## Run the plugin
```
protoc --plugin ./protoc-gen-auxo-service --auxo-service_out=output test_hello.proto
```