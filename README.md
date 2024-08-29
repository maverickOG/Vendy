# Vendy

## Overview

Vendy is a C++ project simulating a simple virtual vending machine. It demonstrates object-oriented programming concepts using classes, objects, `this` pointer, and arrays of objects.

## Features

* Create and manage multiple vending machines.
* Add, remove, and display products in each machine.
* Apply discounts to individual products or all products in a machine.
* Efficiently manage products using arrays of objects.

## Classes

* **`Product`**
    * Attributes: name, price, quantity
    * Methods: `displayInfo()`, `applyDiscount()`
* **`VendingMachine`**
    * Attributes: name, array of products
    * Methods: `addProduct()`, `removeProduct()`, `displayProducts()`, `applyDiscountToAll()`

## Key Concepts Demonstrated

* **Classes and Objects:** Encapsulation of data and behavior.
* **`this` Pointer:** Referencing the current object within its methods.
* **Arrays of Objects:** Efficiently storing and managing multiple products.

## How to Use

1. **Compile:** `g++ Main.cpp -o Main`
2. **Run:** `./Main`
3. **Compile and Run:** `g++ Main.cpp -o Main && ./Main`

## Sample Output

```
Created a new vending machine: Snack Machine
Added Chips to Snack Machine
Added Candy to Snack Machine
Displaying products in Snack Machine:
Product: Chips, Price: $1.50, Quantity: 5
Product: Candy, Price: $1.00, Quantity: 10
Applied 10% discount to all products in Snack Machine
```

### Future Enhancements

- **Coin/Bill Acceptance:** Implement a system for accepting coins or bills as payment.
- **Change Calculation:** Calculate and dispense the appropriate change.
- **Product Restock:** Allow for restocking of products.
- **Inventory Management:** Track inventory levels and generate reports.

### Additional Notes

- **Random Seed:** The program uses a random seed based on the current time for consistent discount application.
- **Error Handling:** Basic input validation is included to ensure user-entered data is within expected ranges.
- **Code Structure:** The code is organized into well-defined classes and functions for better readability and maintainability.

### Copyright and License

**© 2024 [Sajit Magesh](https://github.com/maverickOG)**

MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This code is protected by copyright laws. Unauthorized use, reproduction, or distribution is prohibited.

**Feel free to contribute to this project by submitting pull requests or raising issues on GitHub!**

### Additional Tips

* **Code Clarity:** Use meaningful variable and function names, consistent indentation, and comments to improve code readability.
* **Error Handling:** Implement error handling mechanisms to prevent unexpected behavior (e.g., handling invalid input or out-of-stock products).
* **Testing:** Write unit tests to ensure the correctness of your code.
* **Efficiency:** Consider optimizing your code for performance, especially if dealing with large datasets.

By following these guidelines, you can create a well-structured and maintainable virtual vending machine project. Good luck with your coding! 🚀

---

[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-blue?logo=github)]()
