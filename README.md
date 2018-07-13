# grpc-hello-world
Hello World gRPC example in java

Steps:
mvn clean install

With the help of protobuf-maven-plugin it will generate stub

Client and server code is written in HelloWorldClient  & HelloWorldServer

With the help of maven-shade-plugin it will create fat jar.
Now to see the demo you can follow below steps.

Start Server
java -cp target/grpc-hello-world-1.0-SNAPSHOT.jar com.grpc.practice.HelloWorldServer

Run Client
java -cp target/grpc-hello-world-1.0-SNAPSHOT.jar com.grpc.practice.HelloWorldClient <<input>>
java -cp target/grpc-hello-world-1.0-SNAPSHOT.jar com.grpc.practice.HelloWorldClient world
