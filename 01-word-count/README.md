# Word count

## Prerequisites

  * Maven
  * Java 6+
  * Storm 0.9+

## How to run

compile project:

```
$ mvn package
```

run locally:

```
$ storm jar target/01-word-count-0.1-SNAPSHOT.jar storm.WordCountTopology
```

for development testing you can compile and run project with:
```
$ mvn compile exec:java -Dstorm.topology=storm.WordCountTopology
```

