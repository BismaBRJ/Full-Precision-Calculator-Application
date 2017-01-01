# Full-Precision Calculator Application
A calculator application that is programmed in a way that overcomes the machine's computational limitations.

# What computational limitations?
Here are some examples:
- Some programming languages (such as C) have number types (such as int and float) that, depending on the machine, has a limit in which computations cannot be done for numbers above that limit (for example, in C, an unsigned long int cannot be of a value at least above 2^64, though it is implementation-specific, but there is still a limit).
- Calculators, as far as the developer is concerned, only display division results up to 50 decimal places.
- In machines, numbers are stored in binary, and seemingly terminating decimals that are repeating in binary (such as the binary form of 0.1 being 0.0001100110011...) are rounded, causing some operations to not follow logic (such as Python 3 stating 0.1 + 0.1 + 0.1 == 0.3 as False)

# How will these limitations be overcome?
This calculator will refrain from using the built-in mathematical operations at all, and instead take advantage of strings and classes as well as functions and methods.

# Current state of development
Currently, it is under development using Python 3.
The source code consists of 2 separate scripts: One for all the calculation functions (which can be imported as a module) and another for the GUI.
Unfortunately, this calculator application is still in its very early stages that not even the very first version is finished; It (the very first version) is planned to be finished by mid-January 2016, and will be uploaded as soon as it is.
