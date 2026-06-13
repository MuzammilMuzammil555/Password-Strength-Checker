# Password-Strength-Checker-Project

## Overview

Password Strength Checker is a Python-based command-line application that evaluates the strength of a password using common security best practices. The program analyzes a password against five security criteria and provides a score, rating, and suggestions for improvement.

This project demonstrates the use of Python functions, loops, conditional statements, regular expressions, and user input handling.

---

## Features

* Checks password length
* Detects uppercase letters
* Detects lowercase letters
* Detects numeric digits
* Detects special characters
* Calculates a strength score out of 5
* Classifies passwords as Weak, Medium, or Strong
* Provides personalized improvement suggestions
* Allows multiple password checks without restarting the program

---

## Technologies Used

* Python 3
* Regular Expressions (`re` module)

---

## How It Works

The program evaluates a password using five rules:

### Rule 1: Password Length

The password must contain at least 8 characters.

Example:

Password123

Passes this rule because it contains more than 8 characters.

---

### Rule 2: Uppercase Letter

The password must contain at least one uppercase letter (A-Z).

Example:

Password123

Contains "P", so it passes.

---

### Rule 3: Lowercase Letter

The password must contain at least one lowercase letter (a-z).

Example:

Password123

Contains lowercase letters, so it passes.

---

### Rule 4: Number

The password must contain at least one numeric digit (0-9).

Example:

Password123

Contains "123", so it passes.

---

### Rule 5: Special Character

The password must contain at least one special character.

Examples:

@

#

$
!

Password123!

Passes this rule because it contains "!".

---

## Scoring System

Each successful rule adds 1 point.

| Score | Rating |
| ----- | ------ |
| 0-2   | Weak   |
| 3-4   | Medium |
| 5     | Strong |

---

## Example Output

### Weak Password

Input:

password

Output:

Score: 1/5

Rating: WEAK

How to improve:

* Add at least one UPPERCASE letter
* Add at least one number (0-9)
* Add a special character like @, #, $, !

---

### Medium Password

Input:

Password123

Output:

Score: 4/5

Rating: MEDIUM

How to improve:

* Add a special character like @, #, $, !

---

### Strong Password

Input:

Password123!

Output:

Score: 5/5

Rating: STRONG

Perfect! Your password is very strong.

---

## Learning Objectives

This project helped practice:

* Python Functions
* Loops (`while`)
* Conditional Statements (`if`, `elif`, `else`)
* Lists
* User Input Handling
* Regular Expressions
* Code Organization
* Basic Cybersecurity Concepts

---

## Future Improvements

Possible enhancements include:

* Password entropy calculation
* Common password blacklist checking
* Password history validation
* GUI version using Tkinter
* Password generation feature
* Export results to a file

---

## Author

Muzammil Rana

Cybersecurity Student | Learning Python and Security Fundamentals
