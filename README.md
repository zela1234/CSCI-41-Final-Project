# CSCI-41-Final-Project

Please Post all Code you create on the server in a Google Docs Folder in your Folder in this Google Drive

General Overview of Assignment:
 The project will be to create a program that can do algebra, with one special
  twist: every time you use a variable, it will update its value afterwards. So
  if x equals 3, then x+x would return 7, since x was 3 the first time, and then
  4 the next time, and would be 5 afterwards.



THIS PROGRAM WILL ONLY BE IN 1 FILE:   main.cc

PLEASE COMMENT YOUR CODE SO MYSELF AND LY KNOW WHAT YOUR CODE IS DOING

After working on code, please send a message in the group chat explaining what you did, who you are waiting on, and offer help to anyone who is stuck

Seriously guys, my grade depends on it

Gibson- You will be writing the functions that perform the operations on the inputs
 2) Input an algebraic equation. The code will output the result (or BAD INPUT
  if the user types in something bad) of the algebra. Note THERE IS NO ORDER OF
  OPERATIONS, just parse the equation from left to right.
  So if x = 2 and y = 10, x + y * 2 will output 24, not 22.
 
  x will then be equal to 3, and y will be equal to 11, since every time you
  access the value of a variable, it will postincrement the value after returning
  it. So if the next line is x + y * 2 again, it will output 28.
 
 You must support the following algebraic operations:
  + (addition)
  - (subtraction)
  * (multiplication)
  / (division)
  ^ (exponentiation)
  % (modulus)
 
  Precodition: Every operand and operator will have a space before it, you don't
  have to check for this.
 





Rodriguez- You will be writing a portion of int main(){ } and you will be writing the classes to create variables as they are entered from the test cases

CLASS CONTIANS:GET/SETS, HOLDS THE INTS ENTERED, and INCREMENTS THE VALUES ALREADY ENTERED

 You will read one line of input at a time. The input will be in one of three
 forms:
  1) Create a variable. All variables are single letters, like x or y. They can
  hold values only between 0 and 255.
  Valid Example: LET x = 7
  Error: LET x = 9 (you can't redeclare a variable - x is already declared to be 7.)
  Error: LET bob = 27 (bob is 3 letters)
  Error: LET y = 300 (300 is out of range)
  Error: z = 2 (forgot the LET)
  
  On an error, print "BAD INPUT" and quit. You should probably make a die()
  function.

3) If the line contains "quit" (or "QUIT") or is just an end of file, then the
 58 program terminates.

 You must create a class for holding monotoniclly increasing 8-bit integers.
 The class must throw an exception on overflow (varable value exceeding 255),
  but the results of the algebraic expressions themselves can be 32-bit ints.
  When an exception is thrown, you must catch it in main and die with BAD INPUT.




Yaish- You will be writing the Test Cases and helping anybody who needs additional help with their part







Lade- You will be working with Rodriguez to implement a HashTable that works with his class, if you finish early, coordinate with Rodriguez to work on the class together

You must create a data structure for tracking all of the variables that
 have been created and what values they currently hold. Looking up a variable
 must be O(1).

EXAMPLE:    map<char, (HECTOR’S CLASS NAME)> nameofVariable;

Ly- You will be compiling the code and making sure all variables, classes, and functions work together in Main.cc (You are grabbing everybodys work and stitching it together)
