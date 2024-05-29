# Temperature-Converter
This project is a simple web-based temperature conversion tool designed to convert temperatures between Celsius and Fahrenheit. It consists of an HTML form, a CSS file for styling (referenced but not provided), and a JavaScript file for handling the conversion logic.

 HTML Structure
The HTML form provides a user interface where users can input a temperature value and select the desired conversion type. It includes:
1. An input field for entering the temperature.
2. Two radio buttons for selecting the conversion direction: Celsius to Fahrenheit or Fahrenheit to Celsius.
3. A submit button to trigger the conversion process.
4. A paragraph element to display the conversion result or error messages.

The form ensures user inputs are captured correctly and provides a clear interface for interacting with the tool.

JavaScript Functionality
The JavaScript code handles the core functionality of the temperature conversion. It does the following:
1. Retrieves user input from the text box.
2. Checks if the input is a valid number.
3. Determines which conversion type is selected (Celsius to Fahrenheit or Fahrenheit to Celsius).
4. Performs the appropriate conversion calculation:
   - For Celsius to Fahrenheit: `temp = temp * 9 / 5 + 32`
   - For Fahrenheit to Celsius: `temp = (temp - 32) * 5 / 9`
5. Displays the result with one decimal place for precision.
6. Provides error messages for invalid inputs or if no conversion type is selected.

User Experience
The project emphasizes user experience by:
1. Ensuring input validation to avoid incorrect calculations.
2. Providing immediate feedback through alerts and result display.
3. Offering a clean and intuitive interface that guides the user through the conversion process.

### Applications and Improvements
This tool can be useful for educational purposes, quick temperature conversions, and as a basic example of form handling and data processing in web development. Potential improvements could include:
1. Enhanced styling with CSS for better visual appeal.
2. Adding more conversion options, such as Kelvin.
3. Improving accessibility by ensuring compatibility with screen readers and adding keyboard navigation.

Overall, this project serves as an excellent example of integrating HTML, CSS, and JavaScript to create a functional and interactive web application.
