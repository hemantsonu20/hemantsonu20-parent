![Java CI with Maven](https://github.com/hemantsonu20/hemantsonu20-parent/workflows/Java%20CI%20with%20Maven/badge.svg)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.hemantsonu20/hemantsonu20-parent.svg?label=Maven%20Central&color=brightgreen)](https://search.maven.org/search?q=g:%22com.github.hemantsonu20%22%20AND%20a:%22hemantsonu20-parent%22)


# hemantsonu20-parent
A parent pom for maven based projects under this account.

# Maven Artifact
```xml
<dependency>
  <groupId>com.github.hemantsonu20</groupId>
  <artifactId>hemantsonu20-parent</artifactId>
  <version>2.0.0</version>
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
