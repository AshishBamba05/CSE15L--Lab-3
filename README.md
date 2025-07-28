# CSE15L - Lab 3

This lab focuses on practicing core Java programming concepts such as arrays, linked lists, file traversal, and unit testing. It demonstrates the use of JUnit for test automation and reinforces Java standard library usage, recursion, and custom data structure implementation.

## 📂 File Overview

| File                    | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `ArrayExamples.java`    | Contains methods for reversing arrays (in-place and new copy) and computing average excluding the lowest value. |
| `ArrayTests.java`       | JUnit test cases verifying correctness of array operations.                 |
| `FileExample.java`      | Recursively traverses a file directory and returns all file paths.         |
| `LinkedListExample.java`| Custom singly linked list implementation with methods like `append`, `prepend`, `first`, `last`, `length`, and `toString`. |
| `ListExamples.java`     | Implements `filter()` and `merge()` for `List<String>` using iteration.     |

## ✅ Topics Covered

- Array manipulation and logic
- Custom linked list data structures
- Recursive file system traversal with `java.io.File`
- Unit testing with JUnit
- Basic Git usage and version control
- Manual debugging and CLI-based testing workflow

## 🧪 How to Run Tests

Ensure JUnit and Hamcrest are included in the `lib/` folder.

### Compile
```bash
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
```
### Run 
```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests
```

### Requirements

Java 8+
JUnit 4.13.2
Bash (for script automation)

