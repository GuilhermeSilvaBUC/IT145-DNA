# IT145 – Lesson 12 – Assignment 2: DNA

## Project Description
This Python program identifies a person by comparing DNA sequences with profiles stored in a CSV database.

## How It Works
1. Reads a CSV database using `csv.DictReader`.
2. Reads a DNA sequence from a text file.
3. Finds the longest consecutive repetition of each STR.
4. Compares the STR counts with each person's profile.
5. Prints the matching person's name or `No match`.

## How to Run
Run the program from the folder containing `dna.py`, `databases`, and `sequences`.

```bash
python dna.py databases/small.csv sequences/1.txt
```

Expected output:
```text
Bob
```

## Testing
The program passed all 29 checks using CS50's `check50`.

## Technologies
- Python 3
- CSV module
- CS50 Codespace

## Reference
Harvard University. (2026). DNA. CS50. https://cs50.harvard.edu/x/psets/6/dna/
