# Tax calculator

## Problem statement

Create a tax calculator that applies different tax rates depending on what state you enter. The program will output the total price of all items plus the tax percentage.

## Inputs, processes and outputs

Inputs:

- Total items purchased?
- Cost of each item?
- What state are you in?

Processes:

- Calculate total cost: Total items multiplied by item cost multiplied by state tax rate.

Outputs:

- Total cost including tax.
- Please enter a valid number.

## Test scenarios

Inputs:
Items: 10
Cost of each item: 10
State: UT

Expected Output:
Total: 106.85

---

Inputs:
Items: 10
Cost of each item: 10
State: NW

Expected Output:
Total: 108

---

Inputs:
Items: 10
Cost of each item: 10
State: TX

Expected Output:
Total: 106.25

---

Inputs:
Items: 10
Cost of each item: 10
State: AL

Expected Output:
Total: 104

---

Inputs:
Items: 10
Cost of each item: 10
State: CA

Expected Output:
Total: 108.25

---

Inputs:
Items: -10

Expected output:
Please enter a valid number

---

Inputs:
Items: 10
Cost of each item -10

Expected output:
Please enter a valid number

---

Inputs:
Items: asdf

Expected output:
Please enter a valid number

---

Inputs:
Items: 10
Cost of each item asdf

Expected output:
Please enter a valid number

## Solution in pseudo-code

1. Initialise item count to 0
2. Initialise item cost to 0
3. Initialise state to undefined
4. Initialise UT to 0.0685
5. Initialise NV to 0.08
6. Initialise TX to 0.0625
7. Initialise AL to 0.04
8. Initialise UT to 0.08.25
9. Prompt for item count with "How many items are being purchased?"
10. If item count is not a number
    - Display "Please enter a valid number"
11. If item count is less than 0
    - Display "Please enter a valid number"
12. Prompt for item cost with "How much did each item cost?"
13. If item cost is not a number
    - Display "Please enter a valid number"
14. If item cost is less than 0
    - Display "Please enter a valid number"
15. Prompt for state with "What state are you in?"
16. item count x item cost x state
    - Display total cost
