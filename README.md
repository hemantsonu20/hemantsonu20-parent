![Java CI with Maven](https://github.com/hemantsonu20/hemantsonu20-parent/workflows/Java%20CI%20with%20Maven/badge.svg)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.hemantsonu20/hemantsonu20-parent/badge.svg)](https://maven-badges.herokuapp.com/com.github.hemantsonu20/hemantsonu20-parent)


# hemantsonu20-parent
A parent pom for maven based projects under this account

# Maven Artifact
```xml
<dependency>
  <groupId>com.github.hemantsonu20</groupId>
  <artifactId>hemantsonu-parent</artifactId>
  <version>1.0.1</version>
</dependency>
```

# Steps to release
```
$ mvn clean
$ mvn release:prepare # -DdryRun=true
$ mvn release:perform
$ git push --tags
$ git push origin master
```
