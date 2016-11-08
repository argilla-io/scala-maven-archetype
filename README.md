# scala-maven-archetype
Simplest scala maven archetype

## Build
``mvn clean install`` 

## Create a scala maven project 

```
$>mkdir my-awesome-scala-project
$>cd my-awesome-scala-project && mvn archetype:generate -DarchetypeCatalog=local
```

The archetype creation process will guide you to create your project 

```
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Stub Project (No POM) 1
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] >>> maven-archetype-plugin:2.4:generate (default-cli) > generate-sources @ standalone-pom >>>
[INFO]
[INFO] <<< maven-archetype-plugin:2.4:generate (default-cli) < generate-sources @ standalone-pom <<<
[INFO]
[INFO] --- maven-archetype-plugin:2.4:generate (default-cli) @ standalone-pom ---
[INFO] Generating project in Interactive mode
[INFO] No archetype defined. Using maven-archetype-quickstart (org.apache.maven.archetypes:maven-archetype-quickstart:1.0)
Choose archetype:
1: local -> recognai:scala-project-archetype (Data Processing module)
```
