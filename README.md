# Hello World Java Example

This repository contains a minimal Maven-based Java program that prints `Hello, World!`.

## Files

- `pom.xml`: Minimal Maven project configuration for Java 17.
- `src/main/java/Main.java`: Prints `Hello, World!` to the console.

## Run

Compile the program with Maven:

```bash
mvn compile
```

Run it with Maven:

```bash
mvn exec:java
```

Or run the compiled class directly:

```bash
java -cp target/classes Main
```
