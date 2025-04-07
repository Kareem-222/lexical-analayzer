# Lexical Analyzer

## Overview

This project implements a **lexical analyzer** (also known as a lexer or tokenizer) that reads an input file containing a sequence of characters and converts them into a stream of tokens. It recognizes basic programming constructs such as identifiers, integer literals, arithmetic operators, parentheses, and assignment operators.

## Purpose

The purpose of this project is to demonstrate how lexical analysis works. The program reads from an input file (`front.in`) and breaks down the input into recognizable tokens. These tokens are output to the console with their corresponding lexemes.

## Features

- **Identifier Recognition**: Detects variable names (composed of letters and digits).
- **Integer Literals**: Recognizes sequences of digits as integer values.
- **Arithmetic Operators**: Identifies the basic arithmetic operators (`+`, `-`, `*`, `/`).
- **Parentheses**: Recognizes opening and closing parentheses `(` and `)`.
- **Assignment Operator**: Detects the assignment operator `=`.
- **Whitespace Handling**: Skips over whitespace characters and processes the relevant tokens.

## File Structure

- **main.cpp**: The main C++ program that implements the lexical analyzer.
- **front.in**: The input file containing the characters to be analyzed (must be provided in the same directory as the program).
- **README.md**: This file, providing an overview of the project.
