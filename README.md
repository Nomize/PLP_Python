# Basic Calculator Program

A simple Python calculator that performs basic mathematical operations on two numbers.

## Description

This program allows users to perform four fundamental mathematical operations:
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

The calculator takes two numbers and an operation as input, then displays the result in a clear, readable format.

## Features

- **User-friendly interface** with clear prompts
- **Error handling** for division by zero
- **Input validation** for invalid operations
- **Decimal number support** for precise calculations
- **Clean output formatting** showing the complete equation

## Requirements

- Python 3.x
- No additional libraries required

## Installation

1. Download or clone this repository
2. Ensure Python 3.x is installed on your system
3. No additional setup required

## Usage

### Running the Program

1. Open your terminal or command prompt
2. Navigate to the directory containing the calculator file
3. Run the program:
   ```bash
   python calculator.py
   ```

### Example Usage

```
Welcome to the Basic Calculator!
Available operations: +, -, *, /
-----------------------------------
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
10.0 + 5.0 = 15.0

Thank you for using the Basic Calculator!
```

### More Examples

**Addition:**
```
Enter the first number: 7.5
Enter the second number: 2.3
Enter the operation (+, -, *, /): +
7.5 + 2.3 = 9.8
```

**Division:**
```
Enter the first number: 20
Enter the second number: 4
Enter the operation (+, -, *, /): /
20.0 / 4.0 = 5.0
```

**Error Handling:**
```
Enter the first number: 10
Enter the second number: 0
Enter the operation (+, -, *, /): /
Error: Cannot divide by zero!
```

## How It Works

1. **Input Collection**: The program prompts the user for two numbers and a mathematical operation
2. **Operation Processing**: Uses conditional statements to determine which calculation to perform
3. **Calculation**: Performs the mathematical operation on the input numbers
4. **Result Display**: Shows the complete equation with the result
5. **Error Handling**: Manages edge cases like division by zero and invalid operations

## File Structure

```
basic-calculator/
│
├── calculator.py          # Main calculator program
└── README.md             # This documentation file
```

## Code Structure

The program follows a simple linear structure:
- Welcome message and instructions
- User input collection (2 numbers + operation)
- Conditional logic for operation handling
- Result calculation and display
- Error handling for edge cases

## Error Handling

The calculator handles several error scenarios:
- **Division by zero**: Displays error message instead of crashing
- **Invalid operations**: Informs user of valid operation choices
- **Input validation**: Guides users to correct input format

## Future Enhancements

Potential improvements for this calculator:
- [ ] Support for more operations (power, square root, etc.)
- [ ] Memory functions (store/recall results)
- [ ] Multiple operations in sequence
- [ ] GUI interface
- [ ] History of calculations

## Contributing

This is a basic educational project. Feel free to fork and enhance it with additional features or improvements.

## License

This project is open source and available for educational purposes.

## Author

Created as a learning exercise for basic Python programming concepts including:
- User input handling
- Conditional statements
- Basic arithmetic operations
- Error handling
- String formatting

---

**Note**: This calculator is designed for educational purposes to demonstrate fundamental programming concepts in Python.
