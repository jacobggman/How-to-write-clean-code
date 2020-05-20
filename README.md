# How-to-write-clean-code
This is a guideline for how to write a clean and scalable code

## First Learn This

### KISS and DRY Principles

Keep It Simple, Stupid - Will you in a year or other programmer can read the code and understand the logic and what is done?

Don’t Repeat Yourself - This is coding and not labor. Are you using many copy paste?

### SOLID Principles

S ingle Responsibility Principle - If a function or class is too big, complicated or diverse (different topics, backend and frontend)? can the function or class express in sentence or two?

O pen Closed Principle - if you want to add something to a class or the *program* in the future, can you do it easily? without changing exiting code?

L iskov Substitution Principle - if base class use in the program (as pointer (when you wont to use the children of the class)). If you use children of base class can it break anything? Does  it work as intention?

I nterface Segregation Principle - The class need to do one thing that is related to itself. Do your class forced to implement an interface that it doesn't use?

D ependency inversion Principle - High-level and low-level classes should have API to connect between them (see Adapter design pattern). What if you switch low level tech (mostly big libraries, for Example: database, Graphics Library)? does your need change all your code or just add class?

### Design Patterns

Software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. Design patterns are formalized best practices that the programmer can use to solve common problems when designing an application or system

### Programming Language

Know the programming language you use in the project well, at least.

## Before Starting to Writing

### Use the right programing languages, libraries and tools for your project

### All the code base need to be like one person is writing it, continuously.

### Think ahead how you will make and design this project, write it down if it help you.

## Code Writing Cycle

### Plan
Think how you solve the problem and make the code clear and one direction. Use design patterns, and principles.
### Dev
Have fun and Try to implement the new code.
### Test
Test if the code behaves like intended.
### Clean
Clean bugs, refactor, add comments, unit testing, spelling check, naming and so on. Make sure that your code is quality. Leave the code base cleaner than before.

## While Writing

### No Overlaping
Names and concepts are good. Not the same name for different stuff. Be specific with naming.

### Organize Well
Do you think your project is organized well? the earlier you do it the best.

### Commenting
Comments should not replace clean code. The code need to be obvious like it don't have been documented and documents should be like the user don't have the code source, be many times the user is not really reading the code. Commit at least static dependencies like class and functions and 'unnormal' section of code and design choices.

## Commits and Branchs

### Commit
make commit when finish unit of work, changing or undoing exiting code.

### Branch
make new branch when doing development work that is somewhat experimental in nature.

## Use Websites and Tools Like

### Guideline of the used programming language in your project

### Linter and Static Analysis 

### exercism.io
