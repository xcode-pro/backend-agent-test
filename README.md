# backend-agent-test

Simple Java CLI application that runs a binary search on command-line input.

## Build

```bash
javac src/Main.java
```

## Run

The final argument is the target value; all preceding values are the array to search.

```bash
java -cp src Main 1 2 3 4 5 3
```

Output example:

```text
Result index: 2
```
