# Getting Started

### Debug
1. To start your Quarkus application in debug mode with JVM, enter the following command:
```shell script
mvn spring-boot:run -Dspring-boot.run.jvmArguments="-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=8000"
```
2. Attach a debugger to localhost:port.
