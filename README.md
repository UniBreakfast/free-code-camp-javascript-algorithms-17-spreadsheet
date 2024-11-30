### freeCodeCamp

## JavaScript Algorithms and Data Structures 17

# [Spreadsheet](https://github.com/UniBreakfast/free-code-camp-javascript-algorithms-17-spreadsheet)

[project link](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/learn-functional-programming-by-building-a-spreadsheet/step-1)

![image](https://github.com/user-attachments/assets/6a693ff4-4a1b-4874-8f4e-213ee4b9021f)

# Features

Welcome to our simplified Excel-like spreadsheet app! Below is a list of features that make this application a powerful tool for basic data manipulation and analysis.

## Basic Arithmetic Operations

- **Addition (+)**, **Subtraction (-)**, **Multiplication (*)**, and **Division (/)** are supported.
- **Operator Precedence**: Multiplication and division are evaluated before addition and subtraction, adhering to standard mathematical rules.

## Cell Referencing

- **Direct Cell References**: Use cell IDs (e.g., `A1`, `B2`) in formulas to reference values from other cells.
- **Range References**: Specify ranges using `:` (e.g., `A1:A12`) to include multiple cells in functions.

## Built-in Functions

Our app includes a variety of built-in functions to perform common calculations:

- **Aggregation Functions**:
  - `sum`: Calculates the sum of a list of numbers.  
    *Usage*: `=sum(A1:A12)`
  - `average`: Computes the average of numbers.  
    *Usage*: `=average(1,2,3)`
  - `median`: Finds the median value in a list.  
    *Usage*: `=median(A1:A12)`

- **Logical Functions**:
  - `someeven`: Returns `true` if any numbers in the list are even.  
    *Usage*: `=someeven(A1:A12)`
  - `everyeven`: Returns `true` if all numbers are even.  
    *Usage*: `=everyeven(2,4,6)`
  - `has2`: Checks if the number `2` is present in the list.  
    *Usage*: `=has2(A1:A12)`

- **Array Manipulation Functions**:
  - `even`: Filters out odd numbers, returning only even numbers.  
    *Usage*: `=even(A1:A12)`
  - `firsttwo`: Returns the first two elements of a list.  
    *Usage*: `=firsttwo(A1:A12)`
  - `lasttwo`: Returns the last two elements of a list.  
    *Usage*: `=lasttwo(A1:A12)`
  - `increment`: Increments each number in the list by 1.  
    *Usage*: `=increment(1,2,3)`
  - `nodupes`: Removes duplicate numbers from a list.  
    *Usage*: `=nodupes(A1:A12)`

- **Random and Range Functions**:
  - `random`: Generates a random integer between two numbers (inclusive).  
    *Usage*: `=random(1,10)`
  - `range`: Creates a list of numbers in a specified range.  
    *Usage*: `=range(1,5)` (returns `[1,2,3,4,5]`)

## User-Friendly Interface

- **Intuitive Layout**: The grid consists of 10 columns (`A` to `J`) and 99 rows, resembling a traditional spreadsheet.
- **Easy Data Entry**: Click on any cell to enter values or formulas.
- **Automatic Updates**: Cells update their displayed values immediately after changes are made.

## Case-Insensitive Functions

- Function names are **not case-sensitive**. You can write `SUM`, `Sum`, or `sum`, and they will be recognized as the same function.

## Supported Data Types

- **Numbers**: Supports integer and floating-point numbers.
- **Boolean Values**: Functions can return `true` or `false` for logical evaluations.

## Formula Syntax

- **Start with '='**: All formulas must begin with an equals sign (`=`).
- **No Parentheses for Operations**: While operator precedence is handled, parentheses for grouping are **not supported**.
- **Comma-Separated Arguments**: Function arguments are separated by commas (e.g., `=sum(1,2,3)`).

## Additional Utilities

- **Character Ranges**: Internally supports character code operations for future expansions (e.g., generating ranges of letters).
- **Extensible Functions**: The architecture allows for easy addition of new functions to `spreadsheetFunctions`.
