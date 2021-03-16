# spring-native-example
 Code example as seen at https://codetinkering.com/spring-native-application-example/

Create an executable of the application using the following:
```bash
mvn clean -Pnative-image package
```

Create a cloud image (Docker) of the application using:
```bash
mvn spring-boot:build-image
```