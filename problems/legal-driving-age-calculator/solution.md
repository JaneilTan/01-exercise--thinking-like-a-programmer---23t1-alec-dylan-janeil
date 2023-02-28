# Legal Driving Age Calculator

**Note:** Watch [Solving programming challenges](https://www.loom.com/share/8834b77f10034c689e870e0c75b9d0db) to see how this solution was achieved

## Problem statement

Create a legal driving age calculator. The program should prompt you for your age, and then check if you are old enough to drive. The program will determine you are old enough if you are 16 years or older, which is the legal driving age.

## Inputs, processes and outputs

- Inputs: age
- Processes: check the age is of legal driving age (sixteen)
- Outputs:
  - You are old enough to legally drive
  - You are not old enough to legally drive.
  - Please enter a valid number

## Test scenarios

Inputs:
age: 17

Expected output:
You are old enough to legally drive

---

Inputs:
age: 16

Expected output:
You are old enough to legally drive

---

Inputs:
age: abcdefg

Expected output:
Please enter a valid number

---

Inputs:
age: -10

Expected output:
Please enter a valid number

## Solution in pseudo-code

1. Initialise legalDrivingAge to 16
2. Initialise age to 0
3. Prompt for age with "How old are you?"
4. If age is not a number
   - Display "Please enter a valid number"
5. If age is less than 0
   - Display "Please enter a valid number"
6. If age is equal to or greater than legalDrivingAge
   - Display "You are old enough to legally drive"
7. Else
   - Display "You are not old enough to legally drive."
