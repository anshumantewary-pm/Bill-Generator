# Bill Generator

A beginner Python console program that works out a restaurant bill with tip and splits it between people. Enter the bill amount, a tip percentage and the number of people, and it prints the total and each person's share. Written as an early exercise in numeric input, type conversion and f-strings.

## Features

- Prompts for the total bill, tip percentage (12, 15 or 20 suggested; any number works) and number of people
- Calculates the tip and the bill including tip
- Splits the total evenly per person

## Tech stack

- Python 3 (standard library only, no dependencies)

## Getting started

Prerequisites: Python 3 installed.

```bash
git clone https://github.com/anshumantewary-pm/Bill-Generator.git
cd Bill-Generator
python "Bill Generator.py"
```

Example session:

```text
What was the total bill? 1200
please choose a particular tip 12%, 15%, 20% 15
How many people to split the bill? 4
Your bill is 1380.0
Each people should pay 345.0
```

Enter the tip as a number without the `%` sign. Amounts are not rounded, so some inputs print many decimal places.

## Project structure

```text
.
├── Bill Generator.py   # the whole program
└── README.md
```

---

Anshuman Tewary · [GitHub](https://github.com/anshumantewary-pm) · [LinkedIn](https://www.linkedin.com/in/tewary-anshuman/)
