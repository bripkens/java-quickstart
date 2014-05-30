# Maven Java Quickstart Archetype

Just a simple alternative to the Maven Quickstart archetypes that comes with:

 - a recent JUnit version
 - Hamcrest and its additional matchers
 - logback runtime and test configurations
 - a `.editorconfig` file with encoding setup correctly

## Usage

```
  mvn archetype:generate \
    -DarchetypeGroupId=de.bripkens \
    -DarchetypeArtifactId=java-quickstart \
    -DarchetypeVersion=0.2.0
```
