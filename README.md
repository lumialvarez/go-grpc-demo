# go-grpc-demo
Ejemplo de cliente y servidor conectados por gRCP usando Go

## Documentación:
- Overview: https://developers.google.com/protocol-buffers/docs/overview#simple
- Compilador protobuffers: https://grpc.io/blog/installation/

## Comando
Comando para generar el codigo fuente a partir del archivo .proto 

`protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative src/server/proto/wishlist.proto`