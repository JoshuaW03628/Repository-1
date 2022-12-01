---
toc: false
layout: post
description: pre tree notes
categories: [markdown]
title:  Pre tree
---

# Lesson 3.1/2 Variables Assignments and Data Abstraction

## What is a variable

- A variable is an abstraction inside a program that can hold a value

- It organizes data by labeling it with a descriptive name

- It consists of three parts: name, value, and type

- Using meaningful variables names helps with readability of program code and understanding of what values are represented by the variables



## Naming Variables

- Keep the name simple but not too vague
- proper syntax, no spaces


## Types of data

- Integer; A number
- Text/String; A word
- Boolean; Data that determines if something is true or false


## What is Data Abstraction

- Method used in coding to represent data in a useful form, by taking away aspects of data that aren't being used in the situation

- Variables and lists are primary tools in data abstraction

- Provides a separation between the abstract properties of a data type and the concrete details of its representation


## Lists and Strings

- List = ordered sequence of elements.

- Element = individual value in a list that is assigned to a unique index.
- Index = a way to reference the elements in a list or string using natural numbers; each element of a string is referenced by an index.
- String = ordered sequence of characters (Letters, numbers, special characters).

## * AP Exam usage of Data Abstraction


With the properties of the AP Exam pseudocode, lists work differently from what we've learned in python so far, here are the two major differences:

- The index does not start at 0 but 1
- There is only one method of interchanging data between lists, and that is completely overwriting previous list data with the other list\n",


# 3.3/4 Lesson

## Algorithms

- Algorithms has 3 components

    - Sequencing: Algorithms do tasks in the order of specification.
    - Selection: Helps choose two different outcomes based off a decision.
    - Iteration: If a condition is true, then the code can repeat.

- Algorithms can be represented in two ways

    - Flowcharts or Psuedocode.

## Arithmetic Operations

- Basic

Subtraction:
Represented by “-"
num1 = 2 - 1

Addition:
Represented by "+"
num1 = 2 + 1

Multiplication:
Represented by “*”
num1 = 2 * 1

Division:
Represented by “/”
num1 = 2 / 1

Getting the Remainder:
Represented by “MOD” (% in python)
num1 = 5 % 2

- Order of Operations

Arithmetic operations in programming are performed in the same order as operations in mathematics:

- Operations in parentheses should be done first.

- Division and multiplication should be done before addition and subtraction.

- Modulus works similar to multiplication and division.

## Variables

- Different ways values can be stored in a variable
    - Numerical value stored in a variable
    - Value of another variable stored in a variable
    - Result of an operation stored in a variable

## Sequence

Changing the order of the steps changes the overall outcome, since every time the value assigned to a variable is changed, it overrides the last value which was assigned to the same variable. That is why it is important to track the value of variables, especially in code where the value is constantly changing.



## String

A String: A string is a collection of characters. What is a character as character can be anything from numbers, letters, spaces, special symbols, etc.

Certain procedures may be used with strings and they vary from programming language to language Python examples;

- len() to find the length of a string

- lower() to convert to lowercase
 
Pseudocode examples;

- len() returns the length of a string

- concat() returns a string made up of the concatenated strings ex. concat("string1", "string2") would return string1string2

- substring() returns the characters from the string beginning at the at the first position to the last so an example of this would be substring ("abcdefghijk", 2, 5) would print bcde (pseudocode starts at 1)

- SubString 

A substring is a part of and already existing string.

- In pseudocode substring() method is used for instance for concat("Mr.Mortenson is very handsome" 1, 2) the system would return Mr (remember that pseudocode starts at 1)

