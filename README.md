# java-webapp
java ee, apache tomcat7, openJDK 11
```bash
mvn archetype:generate \
-DgroupId=com.name.example \
-DartifactId=myjava-webapp \
-Dversion=1.0.0-release \
-DarchetypeCatalog=internal \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DarchetypeArtifactId=maven-archetype-webapp
```
run with apache tomcat :
```bash
mvn -DskipTests clean package tomcat7:run
```
