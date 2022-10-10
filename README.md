# GildedRose Refactoring Kata
This is an exercise to hone your clean coding skills, by improving an existing code base.
It is inspired by the Kata from https://github.com/NotMyself/GildedRose, as well as the Java implementation from https://github.com/emilybache/GildedRose-Refactoring-Kata.

What you have to do:
- Read and understand the requirements.
- Read the code in src/, specifically the GildedRose.java file.
- Refactor the code to improve the readability.
  - Focus on best practices for naming and function definitions.
- Write JavaDoc where relevant to document the functionality.
- (Optional) Write unit tests to test the functionality as stated by the requirements.
  - (Optional) Write the units tests using TDD (Test-Driven Design).

As you go along, you can run the program (Main.java) to get print-outs, which can help you confirm if the functionality is correct.

# Contents
The repository contains the following:

- lib/
  - External libraries used for compiling the program
- src/
  - The actual source code for the program, as well as any unit test files
- target/
  - Output java-compiled .class files

Furthermore a couple of scripts are including, as a help to run the program as well as the unit tests.
- run.sh and run.ps1
  - Compile and execute the src/Main.java program.
- test.sh and test.ps1
  - Compile and execute any unit tests in src/ using the JUnit JAR file in lib/

# Run program
## Requirements
- Java
- bash or PowerShell

## Scripts
To execute the program, run the following script:

Linux/macOS with bash terminal:
$ ./run.sh

Windows with PowerShell:
> ./run.ps1

# Run tests
To execute the unit tests, run the following script:

Linux/macOS with bash terminal:
$ test.sh

Windows with PowerShell:
> ./test.ps1