# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?  
    A selected point in the program which pauses the program before that line runs and launches the debugger console. Allows the developer to see the current state of variables and run code one line at a time.

2. Does the line of code on a breakpoint run when you start debugging?  
    No, the program is paused one line before the breakpoint line.

3. How do we debug the next line of code?  
    Clicking the 'step over' button (or F8)

4. What does the step into command do?  
    Goes into a method called on the current line. It opens the method where it is declared and pauses at the top of that method.

5. What is the difference between evaluate expression and evaluate code fragment?  
    Evaluate expression allows the developer to run a single line of code based on the state of the program where it is paused by the debugger.
    Evaluate code fragment gives the developer more options such as writing multiple lines of code and creating temporary variables.

