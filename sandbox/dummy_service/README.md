# dummy_service

### table of contents

1. service definition
2. generate stubs from service definition
    - ``` protoc $arg1 $arg2 $arg3 ```
    - arg1: plugin path
    - arg2: source folder to pick proto file from
    - arg3: destination folder where all generated classes will be placed
    - 


set PROTO_FOLDER_PATH=/Proto
set PROTO_PLUGIN_PATH=/Proto/protoc-gen-grpc-java



protoc --plugin=protoc-gen-grpc-java="/Users/tim/Desktop/protocol-buffers/plugin/protoc-gen-grpc-java-1.48.0-osx-aarch_64.exe" --grpc-java_out="/Users/tim/code/java-protobuf-template/sandbox/dummy_service/generated_files" --java_out="/Users/tim/code/java-protobuf-template/sandbox/dummy_service/dummy.proto"


```
protoc --plugin=protoc-gen-grpc-java="/Users/tim/Desktop/protocol-buffers/plugin/protoc-gen-grpc-java-1.48.0-osx-aarch_64.exe" --grpc-java_out="/Users/tim/code/java-protobuf-template/sandbox/dummy_service/generated_files" --java_out="/Users/tim/code/java-protobuf-template/sandbox/dummy_service/dummy.proto"
```















