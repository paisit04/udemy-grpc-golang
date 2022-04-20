# gRPC [Golang] Master Class: Build Modern API & Microservices

Ref: https://www.udemy.com/course/grpc-golang

## Prerequisites

https://grpc.io/docs/languages/go/quickstart/#prerequisites

## Makefile

For more information about what are the rules defined in the Makefile, please type:

```shell
make help
```

## Evans

https://github.com/ktr0731/evans

```shell
evans --host localhost --port 50051 --reflection repl
```

## Notes

Could not greet: rpc error: code = Unavailable desc = connection error: desc = "transport: authentication handshake failed: x509: certificate signed by unknown authority (possibly because of \"x509: cannot verify signature: insecure algorithm SHA1-RSA (temporarily override with GODEBUG=x509sha1=1)\" while trying to verify candidate authority certificate \"ca\")"

```shell
GODEBUG=x509sha1=1 ./bin/greet/client
```
