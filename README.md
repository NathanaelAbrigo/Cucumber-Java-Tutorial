# Cucumber-Tutorial
This is a quick hands on project tutorial about using Cucumber as a test tool in a Java environment when utilizing Behaviour Driven Development.

### Source
https://cucumber.io/docs/guides/10-minute-tutorial/?lang=java

### Notes
1. For creating a new project directory, the given snippet in the tutorial is for Unix-like Systems (Linux, macOS). For Windows, use the code snippet provided here
```
mvn archetype:generate ^
   "-DarchetypeGroupId=io.cucumber" ^
   "-DarchetypeArtifactId=cucumber-archetype" ^
   "-DarchetypeVersion=7.18.0" ^
   "-DgroupId=hellocucumber" ^
   "-DartifactId=hellocucumber" ^
   "-Dpackage=hellocucumber" ^
   "-Dversion=1.0.0-SNAPSHOT" ^
   "-DinteractiveMode=false"

```
2. You can comment or delete the example.feature file while doing the tutorial since that file is also included in the 'mvn test' runs, which may cause confusions while following
