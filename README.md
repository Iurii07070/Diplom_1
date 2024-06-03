<h3 align="center">YANDEX PRACTICUM JAVA AUTOMATION</h3>

## Stellar Burgers Unit Testing

## Overview
This project involves writing unit tests for a program that helps order burgers in Stellar Burgers. The goal is to achieve at least 70% code coverage using unit tests. The project utilizes Jacoco, Mockito, and JUnit 4 libraries for testing and coverage reports.

## Steps to Complete the Task

### 1. Clone the Repository
Clone the repository with the code template:
```sh
git clone git clone https://github.com/yandex-praktikum/QA-java-diplom-1
cd QA-java-diplom-1
```
### 2. Setup the Project
Ensure that the required libraries are included in your `pom.xml`:
- Jacoco
- Mockito
- JUnit 4

### 3. Write Unit Tests
Write unit tests for the following classes:
- `Bun`
- `Burger`
- `Ingredient`
- `IngredientType`

Use mocks, stubs, and parameterization as needed. Ensure that the test names and variable names are meaningful and follow the naming conventions.

### 4. Run Tests and Generate Reports
#### Running Tests
To run the tests, use the following Maven command:

```sh
mvn clean test
```
#### Generating Jacoco Report
To generate a Jacoco coverage report, use the following Maven command:

```sh
mvn jacoco:report
```
The report will be generated in the target/site/jacoco directory.

#### Generating Surefire Report
To generate a Surefire report, use the following Maven command:

```sh
mvn surefire-report:report
```
The report will be generated in the target/site directory.

## Submitting the Work
1. **Commit and Push Changes**:
```sh
git add .
git commit -m "Add unit tests and coverage reports"
git push origin main
```

2. **Create a Pull Request**: Follow the instructions in the repository to create a pull request and include the Jacoco report.


## Evaluation Criteria
- **Correct Naming**: Test and variable names should follow naming conventions learned in the course.
- **Test Execution**: Tests should run without errors.
- **Usage of Mocks and Parameterization**: Tests should include mocks and parameterization where appropriate.
- **Jacoco Coverage**: Ensure code coverage is at least 70%. Include the Jacoco report in the pull request.
- **Non-redundant Tests**: Avoid unnecessary tests.
- **Test Location**: All tests should be placed in the `test/java` directory.
- **Clean `pom.xml`**: Ensure the `pom.xml` file contains only the necessary dependencies and plugins.

## Additional Notes
- **IDE Setup**: Ensure your IDE is set up correctly with the necessary plugins for Maven and unit testing.
- **.gitignore**: Ensure your `.gitignore` file is configured to exclude build artifacts but include the necessary coverage reports.

## Useful Links
- [Project Repository](https://github.com/yandex-praktikum/QA-java-diplom-1)
- [Instruction PDF](https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/upload-task-1.pdf)