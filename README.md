# Golang Calculator

## Overview

This project is a basic calculator implemented in Go. It supports both arithmetic operations on integers and conversion between Roman and Arabic numerals.

## Features

- **Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Numeral Conversion**: Convert between Roman numerals and Arabic numbers.

## Getting Started

To run the program, use the following command:

```bash
go run main.go
```

The program will prompt you for input and perform calculations based on the provided numbers and operators.

Input Format:

- Enter the first number (can be either a Roman numeral or an Arabic number).
- Enter the second number (must match the format of the first number).
- Choose an operation from ```+, -, *, /```.

## Exit:

Type ```exit``` when prompted for the first number to quit the application.

## Examples

#### Addition:

```sql
Enter the expression (or type 'exit' to quit):
>>> 5 + 3
Result: 8
```
      
#### Roman Numerals:

```sql
Enter the expression (or type 'exit' to quit):
>>> V + V
Result: X
```

## Testing
To run tests, use the following command:
      
```bash
go test ./...
```
The tests cover basic arithmetic operations, division by zero, and Roman numeral conversions.

## Code Structure
- calculator: Contains the calculator logic and operations.
- roman: Functions for Roman numeral conversion.

## Roman Numbers In Use

- I (1)
- II (2)
- III (3)
- IV (4)
- V (5)
- VI (6)
- VII (7)
- VIII (8)
- IX (9)
- X (10)
- XX (20)
- XXX (30)
- XL (40)
- L (50)
- LX (60)
- LXX (70)
- LXXX (80)
- XC (90)
- C (100)

## Error Handling
- Division by Zero: Handled with a panic mechanism.
- Invalid Inputs: Error messages guide the user to provide valid inputs.

## Contributing
Feel free to contribute to the project. You can submit issues or pull requests on GitHub.
