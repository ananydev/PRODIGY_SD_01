FEATURES :

- User Input: The program uses the Scanner class to read user inputs for the temperature value and its unit.
- Temperature Conversion: It supports conversion between Celsius, Fahrenheit, and Kelvin.
- Switch Case: The unit input is handled using a switch-case statement to determine which conversion method to call.
- Conversion Methods: Three static methods (convertFromCelsius, convertFromFahrenheit, convertFromKelvin) handle the conversions and print the results.
- 


DETAILED BREAKDOWN :

1. Importing Scanner: The program imports java.util.Scanner to handle user inputs.

2. Main Method:
   - Prompts the user to enter a temperature value.
   - Prompts the user to enter the unit of the temperature (C for Celsius, F for Fahrenheit, K for Kelvin).
   - Uses a switch statement to determine the unit entered and calls the appropriate conversion method.
   - Closes the Scanner object to avoid resource leaks.

3. Conversion Methods:
   - convertFromCelsius: Converts the given Celsius temperature to Fahrenheit and Kelvin, then prints all three values.
   - convertFromFahrenheit: Converts the given Fahrenheit temperature to Celsius and Kelvin, then prints all three values.
   - convertFromKelvin: Converts the given Kelvin temperature to Celsius and Fahrenheit, then prints all three values.
     
Each conversion method performs the necessary mathematical operations and prints the results in a clear and formatted manner.

This file provides a user-friendly way to convert temperatures and demonstrates basic Java programming concepts such as user input, conditionals, and methods.






