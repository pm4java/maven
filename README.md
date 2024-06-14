The `repo` subdirectory is a Maven repository of ProM packages.

To add new packages use the following:
```bash
$ mvn install:install-file -Dfile=FILE.jar -DgroupId=GROUP_ID -DartifactId=ARTIFACT_NAME -Dversion=VERSION -Dpackaging=jar -DgeneratePom=true -Dmaven.repo.local=repo/
```
