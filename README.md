```markdown
# NATO Phonetic Alphabet Converter 🔤

A Python script that converts any word into its NATO 
phonetic alphabet equivalent.

## What it does
Reads the NATO phonetic alphabet from a CSV file, builds 
a dictionary from it using list comprehension, then converts 
any user input word into the corresponding NATO phonetic codes.

## How to run
1. Make sure Python and Pandas are installed
2. Place `nato_phonetic_alphabet.csv` in the same folder
3. Run the script:
```
python main.py
```
4. Enter any word and get the NATO phonetic equivalent

## Sample output
```
Enter a word: HELLO
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
```

## Concepts used
- Pandas and CSV handling
- Dictionary comprehension
- List comprehension
- String manipulation
- iterrows()
```
