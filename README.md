# Circle Class with Interface

## Introduction:
- Be sure to read chapter 1 and C++ Interlude 1 before you start this programming assignment.
- After completing the reading assignment, review this example
- I encourage you to clone this project, and be sure that you can compile and run them.

## IDE:
- My IDE is visual studio with C++ plugin
- I am using MacOS M1 Chip
- I am using Homebrew for managing packages (GCC)
- I compile my program by including both source files in the compilation command. Files are need compile `Circle.cpp` and `driver.cpp`, here's the compilation command:

```bash
g++ Circle.cpp driver.cpp -o driver
```

This command compiles both source files (`Circle.cpp` and `driver.cpp`) and links them to create an executable named `driver`. Then I run this command in the directory where the source files are located. After successfully compiling, I can run my program by executing:

```bash
./driver
```

The result should be:

```bash
t2315297@RGCAFCS92112 ex1-sample-circle-class-interfaces % ./driver
Intital state of the circle
    radius = 1
    area   = 3.14

Current state of the circle
    radius = 2
    area   = 12.56
```