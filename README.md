# Python Fundamentals – SoftUni (2020)

Solutions to the labs, exercises and mid exams of the [Python Fundamentals course at SoftUni (January 2020)](https://softuni.bg/trainings/2603/python-fundamentals-january-2020#lesson-13907).

Each topic is a single plain-text file (no extension) containing the solutions to that lesson's problems, one after another, each headed by its problem number (`1.`, `2.`, ...).

## Topics

| Topic | What it practises | Solutions |
|---|---|---:|
| [Basic Syntax, Conditional Statements and Loops - Lab](Basic%20Syntax%2C%20Conditional%20Statements%20and%20Loops%20-%20Lab) | Python syntax, conditions, `for`/`while` loops | 5 |
| [Basic Syntax, Conditional Statements and Loops - Exercise](Basic%20Syntax%2C%20Conditional%20Statements%20and%20Loops%20-%20Exercise) | Conditions and loops on console input | 9 |
| [Basic Syntax, Conditional Statements and Loops - More Exercises](Basic%20Syntax%2C%20Conditional%20Statements%20and%20Loops%20-%20More%20Exercises) | Additional problems on conditions and loops | 4 |
| [Data Types and Variables - Lab](Data%20Types%20and%20Variables%20-%20Lab) | Numeric and string types, type conversion | 5 |
| [Data Types and Variables - Exercise](Data%20Types%20and%20Variables%20-%20Exercise) | Integers, floats, strings, chars and conversions | 9 |
| [Data Types and Variables - More Exercises](Data%20Types%20and%20Variables%20-%20More%20Exercises) | Additional data-type problems | 5 |
| [Lists Basics - Lab](Lists%20Basics%20-%20Lab) | Creating, indexing and iterating lists | 4 |
| [Lists Basics - Exercise](Lists%20Basics%20-%20Exercise) | List manipulation with `split`, `append`, `remove` | 10 |
| [Lists Advanced - Lab](Lists%20Advanced%20-%20Lab) | List comprehensions, slicing, `filter`/`map` | 5 |
| [Lists Advanced - Exercise](Lists%20Advanced%20-%20Exercise) | Command-driven list processing | 7 |
| [Lists Advanced - More Exercises](Lists%20Advanced%20-%20More%20Exercises) | Additional list problems | 4 |
| [Functions - Lab](Functions%20-%20Lab) | Defining functions, parameters, return values | 5 |
| [Functions - Exercise](Functions%20-%20Exercise) | Decomposing problems into functions | 9 |
| [Functions - More Exercises](Functions%20-%20More%20Exercises) | Additional function problems | 3 |
| [Objects and Classes - Exericse](Objects%20and%20Classes%20-%20Exericse) | Defining classes, `__init__`, methods, instances | 9 |
| [Dictionaries - Lab](Dictionaries%20-%20Lab) | Dictionaries, dict comprehensions, `defaultdict` | 5 |
| [Dictionaries - Exercise](Dictionaries%20-%20Exercise) | Grouping, counting and sorting with dictionaries | 10 |
| [Dictionaries - More Exercises](Dictionaries%20-%20More%20Exercises) | Additional dictionary problems | 3 |
| [Text Processing - Lab](Text%20Processing%20-%20Lab) | String methods, slicing, joining | 5 |
| [Text Processing - Exercise](Text%20Processing%20-%20Exercise) | Parsing and transforming text | 10 |
| [Text Processing - More Exercises](Text%20Processing%20-%20More%20Exercises) | Additional text-processing problems | 5 |
| [Regular Expressions - Lab](Regular%20Expressions%20-%20Lab) | Pattern matching with the `re` module | 4 |
| [Regular Expressions - Exercise](Regular%20Expressions%20-%20Exercise) | Extracting and validating data with regex | 6 |
| [Regular Expressions - More Exercises](Regular%20Expressions%20-%20More%20Exercises) | Additional regex problems | 3 |
| [bitwise_operations](bitwise_operations) | Binary ↔ decimal conversion | 2 |
| [Mid Exam Retake - 6 August 2019](Mid%20Exam%20Retake%20-%206%20August%202019) | Past mid exam – lists, loops, command processing | 3 |
| [Mid Exam - 2 November 2019 Group 2](Mid%20Exam%20-%202%20November%202019%20Group%202) | Past mid exam – lists, loops, command processing | 3 |
| [Programming Fundamentals Mid Exam - 2 November 2019 Group 2](Programming%20Fundamentals%20Mid%20Exam%20-%202%20November%202019%20Group%202) | Past mid exam – lists, loops, command processing | 3 |
| [Mid Exam - 29 February 2020 Group 1](Mid%20Exam%20-%2029%20February%202020%20Group%201) | Past mid exam – lists, loops, command processing | 3 |
| [Mid Exam - 29 February 2020 Group 2](Mid%20Exam%20-%2029%20February%202020%20Group%202) | Past mid exam – lists, loops, command processing | 3 |

**Total: 161 solved problems.**

## How to run

The files are not standalone scripts – the numbered headers (`1.`, `2.`, ...) separate the individual solutions. To try one:

1. Copy a single solution (the code below one number, up to the next) into a file, e.g. `solution.py`.
2. Run it with Python 3 and type the input, or pipe it in:

```bash
python3 solution.py
echo "5" | python3 solution.py
```

Most solutions read their input from stdin with `input()` and print the result, as required by the SoftUni Judge system.

## Tech

Python 3 (standard library: `re`, `collections`)
