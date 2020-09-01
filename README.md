![Java CI with Maven](https://github.com/hemantsonu20/hemantsonu20-parent/workflows/Java%20CI%20with%20Maven/badge.svg)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.hemantsonu20/hemantsonu-parent.svg?label=Maven%20Central&color=brightgreen)](https://search.maven.org/search?q=g:%22com.github.hemantsonu20%22%20AND%20a:%22hemantsonu-parent%22)


# hemantsonu20-parent
A parent pom for maven based projects under this account.

# Maven Artifact
```xml
<dependency>
  <groupId>com.github.hemantsonu20</groupId>
  <artifactId>hemantsonu-parent</artifactId>
  <version>1.0.4</version>
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
