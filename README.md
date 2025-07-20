# Operators-in-C-

Aim : To study and implement Operators in C++

Software Used : VS Code

Theory : This program takes two float inputs representing the x and y coordinates of a point.
It uses conditional (if-else) statements to determine the point's location on the coordinate plane.
The program checks whether the point lies on an axis, in one of the four quadrants, or at the origin.
Based on the condition met, an appropriate message is displayed using cout.

Algorithm :

1. Start the program.

2. Input the x and y coordinates from the user.

3. Check if x == 0 and y == 0, then print "Origin".

4. Else if x == 0, print "Y-axis"; else if y == 0, print "X-axis".

5. Else, use conditionals to check and print the corresponding quadrant:

6. If x > 0 && y > 0 → First Quadrant

7. If x < 0 && y > 0 → Second Quadrant

8. If x < 0 && y < 0 → Third Quadrant

9. If x > 0 && y < 0 → Fourth Quadrant

10. End the program.
