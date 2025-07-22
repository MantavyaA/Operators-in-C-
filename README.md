# Operators-in-C-

Aim : To study and implement Operators in C++

Software Used : VS Code

Theory : This program accepts two float inputs representing the x and y coordinates of a point on a 2D plane. It uses conditional (if-else) statements to evaluate the position of the point. The logic checks whether the point lies exactly at the origin, on either the X-axis or Y-axis, or within one of the four quadrants. If both x and y are zero, the point is at the origin. If only x is zero, the point lies on the Y-axis, and if only y is zero, it lies on the X-axis. If both x and y are non-zero, the program determines whether the point is in Quadrant I, II, III, or IV based on the signs of the coordinates. An appropriate message is then displayed using cout to indicate the exact location of the point.


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
