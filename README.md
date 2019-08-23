# POM TREE

**TODO**

- [ ] List artifact versions, by group and artifactId
- [ ] View pom content
- [ ] Goto artifact
- [ ] Analyze pom
  - [ ] Filter dependencies by config `optional` / `scope`
- [ ] search artifact in dependencyManagement, to check exists

## List artifact versions

`GET https://repo.maven.apache.org/maven2/org/springframework/cloud/spring-cloud-config-dependencies/maven-metadata.xml`

## Other document

org.springframework.cloud:spring-cloud-config-dependencies
org/springframework/cloud
->
org/springframework/cloud/spring-cloud-config-dependencies/
+
1.4.3.RELEASE/
```
spring-cloud-config-dependencies-1.4.3.RELEAS...  2018-03-26 16:24      3389      
spring-cloud-config-dependencies-1.4.3.RELEAS...  2018-03-26 16:24       473      
spring-cloud-config-dependencies-1.4.3.RELEAS...  2018-03-26 16:24        32      
spring-cloud-config-dependencies-1.4.3.RELEAS...  2018-03-26 16:24        40      
```
->
spring-cloud-config-dependencies-1.4.3.RELEASE.pom
->
https://repo.maven.apache.org/maven2/org/springframework/cloud/spring-cloud-config-dependencies/1.4.3.RELEASE/spring-cloud-config-dependencies-1.4.3.RELEASE.pom

----


+
maven-metadata.xml
->
list version