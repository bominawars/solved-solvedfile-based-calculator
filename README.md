Download Link: https://assignmentchef.com/product/solved-solvedfile-based-calculator
<br>
This week we will write modify the memory calculator from Assignment 9 to be able to save all of the calculations done to a file. There are multiple ways to do this, but I suggest creating an ArrayList of String objects. Each time the user performs an operation (add, subtract, multiply, divide, or clear), add a new String. For instance, if the current value is 6 and the user chooses to add 2, you would create a new String “6 + 2 = 8” and add that String to the ArrayList. You will also need to add a new “Save” item to the menu. When the user chooses this option, you should call a method that displays a JFileChooser dialog to the user, allow them to select where to save the data, and then write all of the strings from the ArrayList to that file. Be sure to handle exceptions gracefully. Sample output: The current value is 0.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 1 What is the second number? 5 The current value is 5.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 2 What is the second number? 3 The current value is 2.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 3 What is the second number? 5 The current value is 10.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 4 What is the second number? 0 The current value is NaN Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 5 The current value is 0.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 6 The current value is 0.0 Menu 1. Add 2. Subtract 3. Multiply 4. Divide 5. Clear 6. Save 7. Quit What would you like to do? 7 Goodbye! The data in the file should look like this: Initial value is 0 0.0 + 5.0 = 5.0 5.0 – 3.0 = 2.0 2.0 * 5.0 = 10.0 10.0 / 0.0 = NaN Cleared