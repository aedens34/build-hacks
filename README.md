# Java Project

A clean, simple Java 17 project ready for GitHub.

## Requirements
- Java 17 or newer
- Gradle (or just use the wrapper)

## Build

```bash
# Generate wrapper (first time only)
gradle wrapper --gradle-version 8.8

# Build
./gradlew build
```

The jar will be in `build/libs/`.

## Run

```bash
./gradlew run
```

or

```bash
java -jar build/libs/java-project-1.0.0.jar
```

## GitHub Actions

This project includes a working GitHub Actions workflow that builds the project automatically.
