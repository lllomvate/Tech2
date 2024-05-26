# Tech2
# My Number Processor

This project demonstrates basic operations on a list of numbers read from a file, such as finding the minimum, maximum, sum, and product. It also includes CI/CD setup using GitHub Actions.

## How to Run

1. Generate test files:
    ```sh
    mvn compile exec:java -Dexec.mainClass="org.myexample.MyGenerateTestFiles"
    ```

2. Run tests:
    ```sh
    mvn test
    ```

## Project Structure

- `src/main/java/org/myexample/MyNumberProcessor.java`: Main class with number processing functions.
- `src/main/java/org/myexample/MyGenerateTestFiles.java`: Utility to generate test files.
- `src/test/java/org/myexample/MyNumberProcessorPerformanceTest.java`: Performance tests.
- `src/test/resources/`: Directory containing test files.

## CI Status

![CI Status](https://github.com/YOUR_USERNAME/my-number-processor/actions/workflows/ci.yml/badge.svg)
