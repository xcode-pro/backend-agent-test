# backend-agent-test

Small Java command-line example for running a binary search against integer input.

## Prerequisites

- Java compiler and runtime available on your `PATH`

## Build

From the repository root:

```bash
javac src/Main.java
```

## Run

From the repository root after compiling:

```bash
java -cp src Main 1 2 3 4 5 3
```

Example output:

```text
Result index: 2
```

## Usage

```text
java -cp src Main <array elements> <target value>
```
