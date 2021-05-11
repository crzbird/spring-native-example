# spring-native-example
example for spring native

Create an executable of the application using the following:
```bash
mvn clean -Pnative-image package
```

Create a cloud image (Docker) of the application using:
```bash
mvn spring-boot:build-image
```
