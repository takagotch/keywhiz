### keywhiz
---
https://github.com/square/keywhiz

```
```

```sh
mvn install
java -jar server/targt/keywhiz-server-*-shaded.jar [COMMAND] [OPTIONS]
SERVER_JAR="server/target/keywhiz-server-*-shaded.jar"
KEYWHIZ_CONFIG="server/target/classes/keywhiz-development.yaml"
java -jar $SERVER_JAR migrate $KEYWHIZ_CONFIG
java -jar $SERVER_JAR add-user $KEYWHIZ_CONFIG
java -jar $SERVER_JAR server $KEYWHIZ_CONFIG
mv install -pl model -Pgenerate-jooq-sources
```

```
```
