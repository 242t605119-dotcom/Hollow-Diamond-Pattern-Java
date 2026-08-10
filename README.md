# Hollow Diamond Pattern - Java

## Description

This program prints a hollow diamond pattern using stars. The user enters the number of rows and the program creates the upper and lower parts of the diamond.

Unlike a normal diamond, only the boundary is printed with stars and the inside is left empty.

## Features

- Takes the number of rows from the user
- Prints a hollow diamond pattern
- Uses nested loops
- Uses spaces to create the shape
- Uses conditions to print only the boundary
- Works with different row sizes

## Logic

The pattern is divided into two parts: the upper half and the lower half.

Spaces are printed before the stars to keep the diamond centered. For each row, stars are printed only at the first and last positions.

The lower half repeats the same logic in reverse order.

## Concepts Used

- Java
- Scanner
- for loops
- Nested loops
- if condition
- Pattern printing
- User input

## Algorithm

1. Read the number of rows.
2. Print the upper half of the diamond.
3. Print spaces before each row.
4. Print stars only at the boundary.
5. Print the lower half in reverse order.
6. Display the complete hollow diamond.

## Time Complexity

O(n²)

## Space Complexity

O(1)

## Sample Input

Enter number of rows: 5

## Sample Output

    *
   * *
  *   *
 *     *
*       *
 *     *
  *   *
   * *
    *

## How to Run

Compile the program:

javac HollowDiamondPattern.java

Run the program:

java HollowDiamondPattern

## Learning Outcome

This program helps in understanding nested loops, spaces, conditions and boundary logic. It also improves problem-solving skills while creating patterns in Java.

## Author

T.Nandhini
