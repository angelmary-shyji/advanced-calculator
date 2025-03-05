# Advanced Calculator Application

This is an advanced calculator application that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division, as well as advanced operations such as square and square root. The calculator has a sleek and modern user interface with a responsive layout that adjusts to different screen sizes.

## Features
- **Basic Operations**: Addition, subtraction, multiplication, and division.
- **Advanced Operations**: Square root (`√`) and squaring (`x²`) of a number.
- **Clear and Delete**: Clear the display or delete the last entered digit.
- **Responsive Layout**: The calculator layout adapts to different screen sizes and resolutions.
- **User-Friendly Design**: Smooth button interactions with hover effects for a pleasant user experience.

## Structure

### HTML (`index.html`)
- The HTML file creates the structure of the advanced calculator:
  - A header displaying the title "Advanced Calculator."
  - An input field (`display`) to show the current value.
  - A set of buttons for each digit (0-9), operators (+, -, *, /), advanced functions (√, x²), and control buttons (C for clear, Del for delete).

### JavaScript (`script.js`)
- **Append Numbers**: The `appendNumber` function adds digits or the decimal point to the current operand, ensuring that multiple decimal points are not allowed.
- **Choose Operations**: The `chooseOperation` function sets the operator for the calculation.
- **Calculate**: The `calculate` function performs the operation (addition, subtraction, multiplication, division) based on the selected operator.
- **Square Root and Squaring**: The `calculateSquareRoot` and `calculateSquare` functions calculate the square root and square of the current operand, respectively.
- **Clear and Delete**: The `clearDisplay` function resets all operands and clears the display, while the `deleteLast` function removes the last entered digit from the current operand.
- **Update Display**: The `updateDisplay` function updates the input field with the current operand value after any operation or user interaction.

### CSS (`style.css`)
- **Overall Layout**: The calculator is centered on the screen with a full-page gradient background.
- **Calculator Styling**: The calculator has a white background, rounded corners, and a subtle shadow to give it a modern look. It is responsive and adjusts its size based on the screen dimensions.
- **Buttons Styling**: Buttons are styled with bold text, rounded corners, and a transition effect on hover. Different colors are used for operators, advanced functions, and control buttons:
  - Operators have a green background.
  - Advanced functions (square root, square) have a yellow background.
  - Clear and delete buttons have a red background.
- **Display Styling**: The display field has a large font size, right-aligned text, and a subtle shadow to make the digits easy to read.

## How it Works
1. **Number Entry**: When a user clicks on a number button, it is appended to the `currentOperand`. If the number is a decimal point (`.`), the function ensures there is no more than one decimal point.
2. **Choosing an Operation**: When an operator is selected, the `chooseOperation` function stores the current operand and operator for calculation.
3. **Performing Calculation**: The `calculate` function processes the operation based on the stored operator and operands, displaying the result in the input field.
4. **Advanced Operations**: The `calculateSquareRoot` and `calculateSquare` functions calculate the square root and square of the current operand and display the result.
5. **Clear and Delete**: The `clearDisplay` function resets the current operand, previous operand, and operation, clearing the display. The `deleteLast` function removes the last digit or character entered.
6. **Display Update**: After each operation or input, the `updateDisplay` function ensures the input field shows the correct value.

## How to Use
1. Open the `index.html` file in your browser to load the calculator interface.
2. Click on the number buttons (0-9) to input numbers.
3. Choose an operator (+, -, *, /) to perform basic arithmetic operations.
4. Use the `√` button to calculate the square root of the current number and `x²` to square the current number.
5. Click `C` to clear the display or `Del` to delete the last entered digit.
6. Press `=` to perform the calculation and display the result.
