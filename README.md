# Maven Repo

```
mvn install:install-file \
    -Dmaven.repo.local=<path-to-repo> \
    -Dfile=<path-to-file> \
    -DgroupId=<groupId> \
    -DartifactId=<artifactId> \
    -Dversion=<version> \
    -Dpackaging=jar \
    -DgeneratePom=true
```
