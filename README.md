Base.Platform


Parent configuration for all Base.Platform subprojects.

All buils now stored in cloudbees repos, so can add the following line to you maven settings.xml file:
```
<repositories>
    <repository>
      <id>anr-ru</id>
      <name>ANR-RU Public repositories</name>
      <url>https://repository-projectdgc.forge.cloudbees.com/anr-ru/</url>
      <releases>
        <enabled>false</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
```
