# Java-Course-Program-1
This program was the introduction to the Java course in Spring 2024. This was a basic assignment designed to get us familiar with the language

# Program Outline
The program is meant to prompt the user for a grade in the range of 0-100.
The program should open the keyboard for reading, and read in a real number grade from the user
The program data entry loop should terminate when a grade entered is outside the valid range
After loop termination, the program will
  1. print the total of the grades
  2. print the number of grades entered
  3. print the average of the grades entered

The program should be able to handle any errors including NaN


# Implementation
This program introduced concepts of the BufferedReader, isNaN() method, and isInfinite() method

The program starts by intializing multiple variables to zero and opening a BufferedReader

The program then begins a do while loop that prompts the user for a grade between 0-100. The program then reads the line and converts the user's value into a double. If the grade is within the valid range, 1 is added to the count and the grade entered is added to the count.

After the loop, a new double is created with the value of sum/count. This value is then checked with the isNan() method and isInfinite() method. If both of these methods return false, the value of the double is assigned to variable named average and the average, sum, and count is displayed on the screen.
