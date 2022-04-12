# ECS796PLab1

Based upon grpc tutorial at <https://github.com/eugenp/tutorials/tree/master/grpc>

Commands for preparing the enviornment (Assuming you are in the main folder e.g. the one with the pom.xml file in it)

## Update & Install

```bash
sudo apt update
```

```bash
sudo apt install default-jdk maven
```

```bash
mvn clean package install
```

## Server

```bash
mvn exec:java -Dexec.mainClass="server.GrpcServer"
```

## Client (Need to run this from a seperate terminal or ssh connection)

```bash
mvn exec:java -Dexec.mainClass="client.GrpcClient"
```
