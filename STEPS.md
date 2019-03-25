# European Variation Archive (EVA)

1. Clone the repository: https://github.com/EBIvariation/eva-ws
```sh
git clone https://github.com/EBIvariation/eva-ws.git
cd eva-ws
```

2. Download into the main project directory the Maven Wrapper plugin, `mvnw`
```sh
mvn -N io.takari:maven:wrapper
```
**Reference:** https://www.baeldung.com/maven-wrapper

3. Build project
  + Windows
```sh
mvnw clean package -pl "!dgva-server"
```
  + Linux (Unix?)
```sh
mvnw clean package -pl '!dgva-server'
```

4. Testing
```sh
mvnw test
```
