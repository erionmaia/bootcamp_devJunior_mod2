# MOD2 — Java Bootcamp (Module 2)

Small, focused Java exercises and projects for Module 2 of the Bootcamp.

## Description
Collection of small Java projects and exercises covering core Java concepts from Module 2. Each exercise lives in its own directory under `src/` and is designed to be compiled and run locally.

## Prerequisites
- Java JDK 11+ (or Java 8 if required by exercise)
- Git (optional)
- Maven or Gradle (if a build tool is used in a subproject)

## Quick start
1. Clone or copy the repository to your machine.
2. Open a terminal in the repository root.

Compile and run (plain Java source layout):
- Compile:
    ```
    javac -d out $(find src -name "*.java")
    ```
- Run (replace `com.example.Main` with the actual main class):
    ```
    java -cp out com.example.Main
    ```

If a project uses Maven:
```
mvn clean install
mvn exec:java -Dexec.mainClass="com.example.Main"
```

If a project uses Gradle:
```
./gradlew build
./gradlew run --args='...'
```

## Project layout
- src/           — Java source code (each exercise/project in its own package)
- docs/          — Notes, requirements, and design sketches
- tests/         — Unit tests (if present)
- scripts/       — Useful build/run scripts
- README.md      — This file

Adjust the structure to match the specific exercise you're working on.

## Contributing
- Create an issue for bugs or feature ideas.
- Open a pull request with a clear description and tests if applicable.

## License
This repository is available under the MIT License. See LICENSE for details.

## Author
Repository owner
