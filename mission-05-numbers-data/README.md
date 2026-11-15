# Mission 5 — Numbers and Data

## 1. Task / Objective

The objective of this mission was to understand different number systems, convert decimal, binary and hexadecimal values, verify conversions using Python, build a small number converter and understand text encoding.

## 2. Work Completed

- Converted decimal numbers into binary.
- Converted binary numbers into decimal.
- Converted hexadecimal numbers into decimal.
- Converted binary numbers into hexadecimal.
- Verified number conversions using Python built-in functions.
- Created a Python number converter program.
- Tested the converter with three positive numbers.
- Studied ASCII and UTF-8 character encoding.

### Task 5.1 — Manual Number Conversions

**1. Convert decimal 13 to binary**

Repeated division by 2:

| Division | Quotient | Remainder |
|---|---:|---:|
| 13 ÷ 2 | 6 | 1 |
| 6 ÷ 2 | 3 | 0 |
| 3 ÷ 2 | 1 | 1 |
| 1 ÷ 2 | 0 | 1 |

Reading remainders from bottom to top:

**Answer: 1101**

**2. Convert decimal 25 to binary**

| Division | Quotient | Remainder |
|---|---:|---:|
| 25 ÷ 2 | 12 | 1 |
| 12 ÷ 2 | 6 | 0 |
| 6 ÷ 2 | 3 | 0 |
| 3 ÷ 2 | 1 | 1 |
| 1 ÷ 2 | 0 | 1 |

Reading remainders from bottom to top:

**Answer: 11001**

**3. Convert binary 1010 to decimal**

Working:

1 × 2³ + 0 × 2² + 1 × 2¹ + 0 × 2⁰

= 8 + 0 + 2 + 0

**Answer: 10**

**4. Convert binary 1101 to decimal**

Working:

1 × 2³ + 1 × 2² + 0 × 2¹ + 1 × 2⁰

= 8 + 4 + 0 + 1

**Answer: 13**

**5. Convert hexadecimal A to decimal**

A represents 10 in hexadecimal.

**Answer: 10**

**6. Convert hexadecimal 1F to decimal**

F represents 15.

Working:

1 × 16¹ + 15 × 16⁰

= 16 + 15

**Answer: 31**

**7. Convert binary 1111 to hexadecimal**

Working:

1111 in binary = 15 in decimal.

15 in hexadecimal = F.

**Answer: F**

### Task 5.2 — Verify Using Python

Python's built-in conversion functions were used to verify the manual calculations.

| Python expression | Result | Matches manual calculation? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int("1010", 2)` | `10` | Yes |
| `int("1101", 2)` | `13` | Yes |
| `int("A", 16)` | `10` | Yes |
| `int("1F", 16)` | `31` | Yes |
| `hex(15)` | `0xf` | Yes |

All Python verification results match the manual calculations.

### Task 5.3 — Build a Small Number Converter

**File name:** `number_converter.py`

The program accepts a decimal number from the user and converts it into binary and hexadecimal.

**Python code:**

```python
number = int(input("Enter a decimal number: "))

binary = bin(number)
hexadecimal = hex(number)

print("Binary:", binary)
print("Hexadecimal:", hexadecimal)
```

**Functions used:**

- `input()` accepts a number from the user.
- `int()` converts the entered value into an integer.
- `bin()` converts the decimal number into binary.
- `hex()` converts the decimal number into hexadecimal.
- `print()` displays the converted results.

**Test results:**

| Decimal input | Binary output | Hexadecimal output |
|---:|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 31 | 0b11111 | 0x1f |

**How the converter works:**

First, the program accepts a decimal number using the input() function. The int() function converts the input into an integer. The bin() and hex() functions convert the number into binary and hexadecimal respectively. Finally, print() displays both results.

### Task 5.4 — How Is Text Stored?

Computers store text using character-encoding standards.

**ASCII**

ASCII stands for American Standard Code for Information Interchange.

| Character | ASCII decimal code |
|---|---:|
| Uppercase A | 65 |
| Lowercase a | 97 |

**UTF-8**

UTF-8 is a character-encoding standard that supports a wide range of languages, symbols and characters.

Examples of characters outside basic ASCII include:

- ₹ — Indian rupee symbol
- é — Accented letter
- 😀 — Emoji

**Why does a computer need an encoding standard to store text?**

A computer needs an encoding standard to convert characters into numerical values that can be stored and processed as binary data. ASCII represents a basic set of characters, while UTF-8 supports a much wider range of languages and symbols.

## 3. Commands / Tools Used

| Command / Function | Purpose |
|---|---|
| `cd` | Changes the current directory |
| `python3` | Starts Python and executes programs |
| `input()` | Accepts user input |
| `int()` | Converts input into an integer |
| `bin()` | Converts integers into binary |
| `hex()` | Converts integers into hexadecimal |
| `print()` | Displays output |
| `exit()` | Exits Python interactive mode |
| TextEdit | Creates and edits Python files |
| Terminal | Runs Python commands and programs |

## 4. My Understanding

I learned that computers represent information using bits. A bit can have a value of 0 or 1, and a group of eight bits is called a byte.

I understood that decimal uses base 10, binary uses base 2 and hexadecimal uses base 16.

I learned how to convert numbers manually using repeated division and positional values. I also verified my answers using Python built-in conversion functions.

I created a Python number converter that accepts a decimal number and displays its binary and hexadecimal equivalents.

I also understood that ASCII and UTF-8 are character-encoding standards that help computers represent and store text.

## 5. Difficulties Faced

Initially, converting decimal numbers into binary and understanding hexadecimal positional values were confusing.

I also needed practice understanding how Python's built-in conversion functions work.

## 6. How I Resolved Them

I practised repeated division by 2 to convert decimal numbers into binary. I used positional values to convert binary and hexadecimal numbers into decimal.

I verified my manual calculations using Python's bin(), int() and hex() functions. I also tested the number converter with different positive numbers to check its output.

## 7. Evidence / Files

- `README.md` — Contains manual calculations, Python verification and text-encoding explanations.
- `number_converter.py` — Contains the working Python number converter.
- Python interactive environment — Used to verify number conversions.
- Terminal output — Shows the number converter test results for 13, 25 and 31.

## 8. Commit Details

**Commit message:** Build number converter and practise data representation

**Repository:** digital-detective-8021

**Repository visibility:** Public

**Push status:** Pending Git commit and push.

