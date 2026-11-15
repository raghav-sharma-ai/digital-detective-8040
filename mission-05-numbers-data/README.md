# MISSION 5 — Numbers and Data

## 1. Task

The objective of this mission was to understand how computers represent numbers and text. I practised converting decimal, binary and hexadecimal numbers. I also used Python to verify my answers and created a small number converter program.

## 2. Work completed

In this mission, I completed four tasks.

### Task 5.1 — Manual number conversions

I converted the given numbers by showing the calculation steps.

| Question | Answer |
|---|---|
| Decimal 13 to binary | 1101 |
| Decimal 25 to binary | 11001 |
| Binary 1010 to decimal | 10 |
| Binary 1101 to decimal | 13 |
| Hexadecimal A to decimal | 10 |
| Hexadecimal 1F to decimal | 31 |
| Binary 1111 to hexadecimal | F |

### Task 5.2 — Python verification

I used Python's built-in functions to check my manual calculations.

| Python expression | Result |
|---|---|
| `bin(13)` | 0b1101 |
| `bin(25)` | 0b11001 |
| `int("1010", 2)` | 10 |
| `int("1101", 2)` | 13 |
| `int("A", 16)` | 10 |
| `int("1F", 16)` | 31 |
| `hex(15)` | 0xf |

The Python results matched my manual calculations.

### Task 5.3 — Number converter program

I created a Python file named `number_converter.py`.

The program asks the user to enter a decimal number. It then converts the number into binary and hexadecimal and displays both results.

#### Test results

| Input number | Binary output | Hexadecimal output |
|---|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 100 | 0b1100100 | 0x64 |

### Task 5.4 — Text encoding

I learned that computers use character encoding to represent text.

- ASCII code of uppercase A = 65.
- ASCII code of lowercase a = 97.
- UTF-8 supports a much wider range of characters than basic ASCII.
- An example of a character outside basic ASCII is ₹.

A computer needs an encoding standard because it stores information using bits. Encoding gives a common way to represent letters, numbers and symbols.

## 3. Commands

| Command / Function | Purpose |
|---|---|
| `python3` | Opens the Python environment or runs a Python file |
| `bin()` | Converts an integer into binary |
| `hex()` | Converts an integer into hexadecimal |
| `int()` | Converts a value into an integer, with a base when needed |
| `input()` | Takes input from the user |
| `print()` | Displays output on the screen |
| VS Code | Used to write the Python program |
| Terminal | Used to run and test the program |

## 4. My understanding

I understood that computers represent information using bits, which have values 0 and 1.

Decimal is base 10, binary is base 2 and hexadecimal is base 16. I learned how to convert numbers between these systems using calculations.

I also understood how Python's built-in functions make number conversion easier. The number converter helped me understand how input, conversion and output work together in a program.

I learned that ASCII and UTF-8 are used to represent text in computers.

## 5. Difficulties faced

I found it a little confusing to convert binary numbers into decimal and understand the hexadecimal values from A to F.

I also needed to understand how to use Python's conversion functions correctly.

## 6. How I resolved them

I practised the conversion steps and used Python to verify my answers. I also tested the number converter with different positive numbers to check its output.

## 7. Evidence 

- `number_converter.py` — Python program for decimal to binary and hexadecimal conversion.
- `README.md` — Mission explanation, conversion answers and text-encoding notes.

## 8. Commit details
- **Commit Message**: "Build number converter and practise data representation"
- **Pushed to GitHub**: Yes (Verified visible on GitHub repository)