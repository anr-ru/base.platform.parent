## Base.Platform Project

### Base.Platform Parent

The parent configuration for all Base.Platform projects.

All builds now stored in package.io repositories, so can add the following line to you maven settings.xml file:

```xml
<repositories>
    <repository>
      <id>anr-ru</id>
      <name>ANR-RU Public repositories</name>
      <url>https://packagecloud.io/ruanr/baseparent/maven2</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
