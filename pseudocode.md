## Pseudocode Exercises
## Exercise 1: Feet to Centimeters

Pseudocode:

- Input LFT (Length in Feet)
- LCM = LFT * 30.48 (Note: 30.48 is the precise conversion)
- Print LCM

## Exercise 2: Area of a Rectangle

Pseudocode:

- Input W (Width), L (Length)
- A = W * L
- Print A

## Exercise 3: Largest of Three Numbers

Pseudocode:

- Input N1, N2, N3
- If N1 > N2 AND N1 > N3 Then
    Max = N1
- Else If N2 > N3 Then
    Max = N2
- Else
    Max = N3
- Print Max

## Exercise 4: Triangle Validity Check

Note: For a triangle to be possible, the sum of any two sides must be greater than the third side.

Pseudocode:

- Input S1, S2, S3 (Sides)
- If (S1 + S2 > S3) AND (S1 + S3 > S2) AND (S2 + S3 > S1) Then
    Print "Triangle is possible"
- Else
    Print "Triangle is NOT possible"

## Exercise 5: Student Grading System

Pseudocode:

- Input Name, Marks
- If Marks >= 80 Then
    Grade = "A"
- Else If Marks >= 60 Then
    Grade = "B"
- Else If Marks >= 40 Then
    Grade = "C"
- Else
    Grade = "No Grade"
- Print Name, Grade