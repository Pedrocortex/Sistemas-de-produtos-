# Product Registration and Management System

## Description

This project was developed in **Python** to register, manage, and analyze products using a dictionary.

The application validates user input, stores product names and prices, calculates statistics, and allows products to be removed from the inventory.

## Features

### Product Registration

The user can choose how many products will be registered.

For each product, the system validates the name before adding it to the dictionary.

### Name Validation

The program prevents:

* Empty names.
* Names beginning with a space.
* Names ending with a space.
* Duplicate product names.
* Product names containing only numbers.

If an invalid name is entered, the user is prompted to enter another one.

### Price Registration

Each product must receive a valid price.

The program accepts only:

* Numeric values.
* Prices greater than zero.

Invalid values are rejected until a valid price is entered.

### Product Listing

After registration, the system displays every product together with its corresponding price.

### Statistics

The program calculates and displays:

* Total value of all registered products.
* Average product price.
* Most expensive product(s).
* Least expensive product(s).

If multiple products share the highest or lowest price, all of them are displayed.

### Product Removal

The user can specify how many products should be removed.

For each removal:

* The product name is requested.
* If the product exists, it is removed.
* Otherwise, an error message is displayed and another attempt is requested.

At the end, the updated product list is displayed.

## Technologies Used

* Python
* Dictionaries
* Functions
* Loops
* Conditional statements
* Exception handling (`try` / `except`)
* Input validation

## Project Structure

The project includes functions responsible for:

* Name validation.
* Duplicate name detection.
* Numeric name validation.
* Total price calculation.
* Finding the most expensive product(s).
* Finding the least expensive product(s).

## Running the Project

### Google Colab

1. Open the project in Google Colab:

   https://colab.research.google.com/drive/1s5VmRCv8Ot_ueg2gqa7MUrEPjUp_fVgY

2. Click the **Run** button (▶) in the upper-left corner.

3. Follow the prompts displayed in the console.

## Learning Objectives

This project was created to practice:

* Dictionary manipulation.
* Data validation.
* User input handling.
* Modular programming with functions.
* Basic data analysis.
* Exception handling.
