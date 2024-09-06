
# Features
The application provides basic calculation functionality – addition, subtraction, multiplication, division, modulus, power, and square root in addition to providing buttons for numbers, decimal point, ‘Clear’, and backspace.
It uses string, colour, dimension and style resources. The base layout used in Constraint layout with components like LinearLayout, TextViews, Buttons, and ImageButton. There are two layouts – one for portrait mode and one for landscape mode.
A separate java class is used for the calculation implementation. SavedInstanceState is used to make sure that the data doesn’t clear if the screen is rotated. There is no keyboard input – it is done using the buttons provided on the screen. The following possible errors are considered, and appropriate action is taken –
* Making sure that there is only one decimal point in a number
* The length of the number of characters does not exceed by 10
* The root button works even if there is no first number provided
* Possible division errors

This icon represents the application. Made using Font Awesome Icons and MDBootstrap. It follows material design guidelines.

# Usage
The usage of the application is self-explanatory. However, the following steps can be followed –
1. Enter a number (up to 10 digits) using the number pad provided
2. Enter an operation using the number pad
3. Enter the second number (up to 10 digits)
4. Press the ‘=’ button to perform the calculation
5. Use the backspace button to delete the last character
6. Enter the first number before entering an operation.
7. Use ‘C’ button to clear all the fields
