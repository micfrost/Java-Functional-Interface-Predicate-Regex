# Java Password Validator Application

## Overview
The Java Password Validator is a simple application designed to demonstrate the use of the `Predicate.not()` method in Java for password validation. This application checks whether a password entered by the user meets specific criteria.

## Features
- **Password Validation**: Validates passwords based on predefined criteria.
- **Criteria Check**: Ensures passwords are at least 8 characters long, contain at least one uppercase letter, and one digit.
- **Use of Predicate.not()**: Demonstrates the use of `Predicate.not()` to negate the result of a predicate for validation.

## Java Features
- **Functional Programming**: Employs Java's functional programming constructs for concise and readable code.
- **Regular Expressions**: Uses regular expressions to check for uppercase letters and digits.
- **Java Predicates**: Demonstrates the use of `Predicate` interface for conditional checks.


## How to Use
1. **Run the Application**: Start by running the `Main` class.
2. **Enter a Password**: Input a password when prompted.
3. **Validation Output**: The application will then display a message indicating whether the password is valid or not, based on the set criteria.

## Requirements for a Valid Password
- **Minimum Length**: The password must be at least 8 characters long.
- **Uppercase Letter**: At least one uppercase letter is required.
- **Digit Inclusion**: At least one digit must be included.

## Technical Details
- **validatePassword Method**: This method takes a password as input and returns a `Predicate<String>` indicating whether the password meets the criteria.
- **isInvalidPassword Predicate**: Utilizes `Predicate.not()` to create a predicate that checks if the password does not meet the criteria.

## Purpose
This application serves as a practical example for those looking to understand and implement `Predicate.not()` in Java, particularly in the context of string validation. It is an excellent resource for beginners and intermediate Java programmers interested in learning more about functional programming in Java.



## Author
Made by Michal Frost.

Happy Coding.