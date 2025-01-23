# Change double numbers
This pull requests adapts the product unit price.
<br/>

## What's new?
•⁠  ⁠Switch the prices to "int" which represent the money in cents (1€ = 100c).

## Why is it important?
•⁠ ⁠This eliminates the need for floating-point arithmetic altogether and ensures accurate calculations.
- Operations that should result in exact values (like multiplying 0.1 by 10) might not produce the expected outcome due to these rounding errors, which could lead to an unexpected outcome due to these rounding errors.

## How to Use?
•⁠  ⁠Change the doubles for integers and int the end of calculationg the final price of the purchase, divide the reached number by 100 to get the price in "€".

<br/>
<br/>
