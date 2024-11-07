# Takeout Restaurant Menu and Order System

![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Python Version](https://img.shields.io/badge/python-3.x-blue?style=for-the-badge)

## Project Overview
This project implements a restaurant ordering system where a customer can view a menu, place an order, update their order, and receive an itemized receipt. The system is designed for accessibility, enabling users with hearing and vocal impairments to interact with the system using a text-based interface. The core functionalities of the system include viewing menu items, adding them to an order, updating quantities, and receiving a detailed receipt with the total price.

## Features
- **Menu Display**: The customer is shown a list of menu items with categories, names, and prices.
- **Order Placement**: The customer can select items, specify quantities, and choose whether to continue or finish their order.
- **Order Update**: The customer can update the quantity of items already in their order.
- **Itemized Receipt**: Once the order is complete, the customer receives an itemized receipt showing the items, quantities, individual prices, and total price.
- **Error Handling**: The system handles invalid inputs gracefully, prompting the user to try again with valid input.

## Functionality Breakdown

### `place_order()`
The `place_order()` function is responsible for:
- Displaying the menu and continuously prompting the customer for their order.
- Asking for quantities of selected items and allowing the customer to choose whether to continue or stop ordering.
- Calculating the total order price using list comprehensions and `sum()`.
- Returning the final order list and the total price.

### `update_order()`
The `update_order()` function handles:
- Updating an existing order by changing the quantity of a selected item.
- Verifying if the user's input is a valid item and quantity, with appropriate error handling.

### `print_itemized_receipt()`
The `print_itemized_receipt()` function prints the details of the customer's order:
- Iterates through the items in the order list.
- Displays the name, price, and quantity for each item.
- Calculates the total price and displays it.

## Getting Started

### Prerequisites
- Python 3.x
- Basic knowledge of Python functions, loops, conditionals, and error handling.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RubenDguez/python-take-out-restaurant.git
