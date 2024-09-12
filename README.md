# Discount Calculator

## Overview

This Python script provides a function named `calculate_discount` that calculates the final price of an item after applying a discount. The function takes two parameters:

- `price`: The original price of the item.
- `discount_percent`: The discount percentage to apply.

If the discount is 20% or higher, it is applied to the original price. Otherwise, the original price is returned.

## Features

- Calculates the final price after applying a discount based on the provided percentage.
- Returns the original price if the discount percentage is less than 20%.
- Handles invalid input gracefully by prompting the user to enter numerical values.

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/discount_calculator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd discount_calculator
    ```

3. Run the script:

    ```bash
    python discount_calculator.py
    ```

4. Follow the prompts to enter the original price and discount percentage.

## Example


## Function Definition

The `calculate_discount` function is defined as follows:

```python
def calculate_discount(price, discount_percent):
    """
    Calculate the final price after applying a discount.
    
    Parameters:
    price (float): The original price of the item.
    discount_percent (float): The discount percentage to apply.
    
    Returns:
    float: The final price after applying the discount or the original price if no discount is applied.
    """
    if discount_percent >= 20:
        discount_amount = (price * discount_percent) / 100
        final_price = price - discount_amount
    else:
        final_price = price
    return final_price

### Instructions

1. GitHub smangelent@gmail.com.
2. (https://github.com/smangelent@gmail.com)
