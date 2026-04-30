# Triangle Angle Calculator

A simple program that computes the three angles of a triangle given the (x, y) coordinates of its vertices.

## Overview

This project takes three points in a 2D plane and calculates the triangle’s internal angles using the Law of Cosines.

## How It Works

1. The user inputs three points:
   - (x1, y1)
   - (x2, y2)
   - (x3, y3)

2. The program computes the side lengths using the distance formula.

3. It then calculates each angle using:

A = acos((a² - b² - c²) / (-2bc))  
B = acos((b² - a² - c²) / (-2ac))  
C = acos((c² - a² - b²) / (-2ab))

## Example

Input:
(0, 0), (1, 0), (0, 1)

Output:
A = 90°  
B = 45°  
C = 45°

## Features

- Simple and minimal
- Uses standard geometric formulas
- Works for any valid triangle

## Notes

- Input points must not be collinear (or the triangle is invalid)
- Angles are returned in degrees

## Future Improvements

- Input validation
- GUI version
- Visualization of the triangle

## License

MIT
