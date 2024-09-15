# Problem 1
If lengths of three sides of a triangle are input through the keyboard, write a program to find the area of the triangle.

# Problem 2
If a five-digit number is input through the keyboard, write a program to reverse the number.

# Problem 3
Consider a currency system in which there are notes of six denominations, namely, Re. 1, Rs. 2, Rs. 5, Rs. 10, Rs. 50, Rs. 100. If a sum of Rs. N is entered through the keyboard, write a program to compute the smallest number of notes that will combine to give Rs. N.

# Homework Problems

## (a)
If a five-digit number is input through the keyboard, write a program to calculate the sum of its digits. (Hint: Use the modulus operator `%`.)

## (b)
Write a program to receive Cartesian coordinates (x, y) of a point and convert them into polar coordinates (r, φ). 
- Hint: 
  - \( r = \sqrt{x^2 + y^2} \) 
  - \( \varphi = \arctan\left(\frac{y}{x}\right) \)

## (c)
Write a program to receive values of latitude (L1, L2) and longitude (G1, G2), in degrees, of two places on the earth and output the distance (D) between them in nautical miles. 
- The formula for distance in nautical miles is: 
  \[
  D = 3963 \cdot \cos^{-1} \left(\sin L1 \cdot \sin L2 + \cos L1 \cdot \cos L2 \cdot \cos(G2 - G1)\right)
  \]

## (d)
Wind-chill factor is the felt air temperature on exposed skin due to wind. The wind-chill temperature is always lower than the air temperature and is calculated as per the following formula:
  \[
  \text{wcf} = 35.74 + 0.6215t + (0.4275t - 35.75) \cdot v^{0.16}
  \]
  where \( t \) is the temperature and \( v \) is the wind velocity. Write a program to receive values of \( t \) and \( v \) and calculate the wind-chill factor (wcf).

## (e)
If the value of an angle is input through the keyboard, write a program to print all its trigonometric ratios.

## (f)
Two numbers are input through the keyboard into two locations C and D. Write a program to interchange the contents of C and D.
