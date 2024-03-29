# Galois Field Operations (Using QT5)
An application for constructing and performing basic arithmetic operations on Galois Fields.

Please wait while the demonstration GIF loads on this page :)
![Header](https://github.com/Smaug-DS/Smaug-DS/blob/main/assets/gf.gif)

## Table of Contents
- [Overview](#overview)
- [Usage Instructions](#usage-instructions)
- [Building a Finite Field](#building-a-finite-field)
- [Performing Operations](#performing-operations)

## Overview
The Galois Field Operations application is designed for building and executing fundamental arithmetic operations on finite fields. You can perform operations in both a simple finite field and an extended finite field.

## Usage Instructions
1. Select one of the four available modes:
   - Build a Simple Field
   - Build an Extended Field
   - Perform Operations in a Simple Field
   - Perform Operations in an Extended Field

## Building a Finite Field
### Build a Simple Field
1. Enter the characteristic of the field in the "характеристика" field.
2. Click "Построить"

### Build an Extended Field
1. Enter the characteristic and dimension of the field in the respective fields.
2. Click "Построить"
3. **Note:** This application supports specific irreducible polynomials for extended fields: 2^2, 2^3, 2^4, 2^5, 2^6, 3^2, 3^3, 5^2, 5^5.

## Performing Operations
### Operations in a Simple Field
1. Enter the characteristic of the field in the "характеристика" field.
2. Enter the operands.
3. Select the desired operation (Addition, Subtraction, Multiplication, or Division).
4. Click "Рассчитать"

### Operations in an Extended Field
1. Enter the characteristic and dimension of the field in the respective fields.
2. Enter the operands. For multiplication and division, specify the corresponding exponent. For addition and subtraction, provide the coefficients of the polynomials.
3. Select the operation (Addition and Subtraction are performed in polynomial form, e.g. the polynomial 1 + x should be represented as 11, and the polynomial 1 + x^2 should be represented as 101, while Multiplication and Division are carried out in power form).
4. Click "Рассчитать"
5. **Note:** This application supports specific irreducible polynomials for extended fields: 2^2, 2^3, 2^4, 2^5, 2^6, 3^2, 3^3, 5^2, 5^5.

### Technology Stack:

I employed the following technologies for this project:

![C++](https://img.shields.io/badge/-C++-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC)
![QT](https://img.shields.io/badge/-QT-090909?style=for-the-badge&logo=QT&logoColor=0d544f)
![STL\Boost](https://img.shields.io/badge/-STL\Boost-090909?style=for-the-badge&logo=Boost&logoColor=629665)

Feel free to use this application for your Galois Field calculations!
