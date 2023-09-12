# SvelteCalculator

This calculator allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division. 
The result is displayed in the input field.

## Below the input field, there are 3 sections:
1. operations
2. numbers
3. equal
 
## Variables: 
- total: Represents the accumulated result of the arithmetic operations.
- console: Stores the current input value as a string.
- state: Keeps track of the current operation state.

## Methods:
- resolveState(): handles the arithmetic operations based on the current state, parses the console value to a float and performs the corresponding operation, updating the total accordingly.
- setOperation(operation): handle the previous operation and sets the new operation in the state variable.
- setValue(value): handles the updating of the console value based on the user's input.
- equal(): handle the current operation and displays the final result in the console.