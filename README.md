# freeCodeCamp Cash Register Project

This project is a JavaScript implementation of a cash register function, developed as part of the freeCodeCamp JavaScript Algorithms and Data Structures certification[1][4].

## Project Overview

The Cash Register project simulates a real-world scenario of calculating change in a cash transaction. It demonstrates proficiency in JavaScript, particularly in handling complex calculations and data structures[4].

## Key Features

- **Dynamic Change Calculation:** Accurately determines the change to be returned based on the purchase price and payment amount[4].
- **Multiple Currency Denominations:** Handles various US currency units, from pennies to $100 bills[4].
- **Intelligent Cash Drawer Management:** Assesses the cash-in-drawer status and returns appropriate messages[4].

## Implementation Details

- **Language:** JavaScript
- **Main Function:** `checkCashRegister(price, cash, cid)`
  - `price`: Purchase price
  - `cash`: Payment amount
  - `cid`: Cash-in-drawer array

## Functionality

The function returns an object with a status and change array, based on three possible outcomes:
1. "INSUFFICIENT_FUNDS": When there's not enough cash in the drawer
2. "CLOSED": When the cash in drawer equals the change due
3. "OPEN": When there's sufficient change and the drawer remains open[4]

## Skills Demonstrated

- Array and object manipulation
- Complex conditional logic
- Precision in financial calculations
- Problem-solving in a practical scenario

## Project Significance

This project showcases the ability to create a practical, user-focused application that handles complex logical operations, demonstrating readiness for real-world programming challenges[4].

## Future Improvements

- Implement a user interface for interactive use
- Extend functionality to handle multiple currencies
- Add unit tests to ensure accuracy across various scenarios
