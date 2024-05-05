## buuidと実行方法

```shell
gradlew build
gradle bootRun
```

## 起動状況の確認

```shell
curl http://localhost:8080
curl http://localhost:8080/hello 
```

<!-- ## jarファイルの作成

```shell
gradle bootJar
jar tvf build/libs/demo-0.0.1-SNAPSHOT.jar
java -jar build/libs/demo-0.0.1-SNAPSHOT.jar
``` -->

```shell
google-java-format --replace **/*.java
```

https://spring.io/quickstart
https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.first-application.executable-jar.gradle
