# pipeline-test

- configurar java, maven, git, python y docker en manage jenkins, global tool configuration
- crear fichero pom.xml
```
<project>
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.miorganizacion.app</groupId>
  <artifactId>mi-app</artifactId>
  <version>1</version>
</project>
```
- hacer test maven local
`mvn package -Dmaven.test.skip=true`
- <https://maven.apache.org/guides/introduction/introduction-to-the-pom.html#Minimal_POM>
