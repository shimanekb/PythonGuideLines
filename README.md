# Python 3 Guide Lines
Holds personal guidelines and tips for using Python 3.6.

## Contents
1. [Environment Setup](#environment-setup)
2. [Code Analysis Tools](#code-analysis-tools)
    1. [Pylint](#pylint)
    2. [Pydoc](#pydoc)
    3. [Coverage](#coverage)
3. [Style](#style)
4. [Testing](#testing)
5. [Virtual Environment](#virtual-environment)
6. [Build Mangement](#build-management)
    1. [Dependencies Management](#dependencies)
7. [Project Structures](#project-types)
    1. [Command Line Application](#command-line-application)
    2. [Library](#library)
8. [Readme Templates](#readme-templates)
    1. [General](#general)
    2. [Application or Library](#application-or-library) 
9. [Code Review Checklist](#code-review-checklist)
10. [Recommended Library List](#recommended-library-list)
    1. [REST](#rest)
11. [Misc Tips](#Misc-tips)
    1. [Object Oriented Programming](#object-oriented-programming) 
    2. [Functional Programming](#functional-programming)
    3. [Project Sizes](#project-sizes)
    4. [Requirements](#requirements)

## Environment Setup
Below required installation steps for setting up a working environment for 
Python:
1. Install Python 3 from the [Python Website](#https://www.python.org/) 
2. Upgrade pip (used for installing python modules) from the 
   [Pip Website](#https://pip.pypa.io/en/stable/installing/#upgrading-pip) 
3. Install the code coverage tool Coverage from the 
   [Coverage Website](#https://coverage.readthedocs.io/en/coverage-4.4.1/install.html)
4. Install the code analysis tool Pylint from the 
   [Pylint Website](#https://www.pylint.org/#install)

## Code Analysis Tools

### Pylint
Pylint is used for:
1. Code error detection 
2. Style checks
3. Generating UML documentation

Refer to the [Pylint Website](#https://www.pylint.org/) for use information.

### Pydoc
Pydoc is used for:
1. Generating documentation from Python coded comments

Refer to the [Pydoc Documentation Website](#https://docs.python.org/3.6/library/pydoc.html) 
for use information.

### Coverage
Coverage is used for:
1. Code coverage analysis and reporting

Refer to the [Coverage Website](#https://coverage.readthedocs.io/en/coverage-4.4.1/) 
for use information.

## Style
Refer to the [Pep-008 Python Style Guide](#https://www.python.org/dev/peps/pep-0008/). 

## Testing
Refer to the [Unittest Documentation Website](#https://docs.python.org/3.6/library/unittest.html).

## Virtual Environment

## Build Management

### Dependencies

## Project Structures

### Command Line Application

### Library

## Readme Templates

### General

### Application or Library

## Code Review Checklist

Run through the listed items in order.

1. Check code against requirements.
2. Run automated code analysis tools:
    1. Tests 
    2. Style check
    3. Bug/Error check
    4. Code coverage
3. Test against any downstream dependencies.
4. Code Design General:
    1. SOLID
    2. Consistency
    3. No god classes, methods, or functions
    4. Minimal use of globals
    5. Keep the amount method or function parameters minimal
    6. Configurable
    7. Extendable
5. Code Design Static Type (*Optional):
    1. Interfaces should use Generics instead of implicit types when possible.
6. Code Design Documentation:
    1. Readme is up to date
    2. Public api's are documented
    3. Classes are documented
7. Code Design Testing
    1. Conditional code coverage
    2. Any non-code configurations are tested
    3. Tests for verification against requirements are present

## Recommended Library List

### REST

## Misc Tips

### Object Oriented Programming

### Functional Programming

### Project Sizes

### Requirements
