# template

To compile the website, just run

```
mvn clean package site:site site:deploy -DskipTests -Dsite.root=[host/dir]/templatewebsite/ -Dsite-path=file://[dir]/templatewebsite
```
