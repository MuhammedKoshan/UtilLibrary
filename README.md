# UtilLibrary
Utility Library &amp; Date Handling Classes (C++ Project) This project is a collection of reusable C++ helper classes designed to make small-to-medium applications easier to build. It includes a full utility module for randomization, encryption, swapping, array operations, and a complete date-processing class with dozens of useful features.


1. clsUtil – Utility & Randomization Library

A static helper class that provides a wide range of commonly used functions, such as:

- Random Generators

Random numbers within a range
Random characters (small, capital, digits, special)
Random words
Random formatted keys "XXXX-XXXX-XXXX-XXXX"
Functions to fill arrays with random numbers/words/keys

- Utility Tools

Shuffle arrays (string & int)

Swap function overloads:

int, double, string, bool, char, and even clsDate

Generate tabs/spacing for formatted console output

- Encryption Tools

Simple text encryption
Simple text decryption
(using a numeric key that shifts ASCII values)



2. clsDate – Full Date Management Class

A powerful class that handles all date operations, including:

📅 Date Construction

Today’s system date

From string "dd/mm/yyyy"

From day order in the year

From day/month/year

🧮 Date Calculations

Leap year check

Number of days/hours/minutes/seconds in:

a day

a month

a year

Convert date to day-order in the year

Convert day-order back to a date

Add days to a date

🔍 Comparison & Validation

Validate dates

Compare dates

Check if last day of month

Check if last month of year

🗓️ Calendar Printing

Print full month calendar

Print full year calendar

3. Main.cpp – Demonstration Program

A sample driver file that tests all clsUtil and clsDate functionalities:

Generate random numbers, characters, words, and keys

Swap different variable types

Shuffle int/string arrays

Fill arrays with random data

Perform basic encryption/decryption

Test date creation and swapping

This file shows how the library can be used like building LEGO pieces — each small function works independently, and you can connect them to create larger features.

🎯 Purpose of the Project

This repository represents the beginning of a foundational utility library that you can expand over time as you grow in C++.

It helps you learn:

How to organize reusable code

How to split projects into classes

How to build modules that work together

How to think in a “LEGO mindset”:
small blocks → bigger systems
