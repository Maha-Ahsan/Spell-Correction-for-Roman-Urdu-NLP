# Spell-Correction-for-Roman-Urdu-NLP
Under the domain of Natural Language Processing

1. Trained a uni-gram model using the corpus provided in data.txt.
2. Created insert, delete, substitution and transposition tables for alphabets a-z using the provided mis-
spellings.txt. The tables can be implemented using Python dictionaries.
3. Created a function that calculates P(x|w) using the Error Model tables.
4. Created a function that returns the set of candidate words which are one insert, delete, substitute or
transpose away from a given word x. The set of candidate words must be a subset of the vocabulary V .
This means that for each candiate word w, P(w) > 0.
5. Created a function that takes a list of candidate words, P(x|w), and P(w) to return the most probable
corrected word ˆw for the misspelled word x.
6.Solution must also be able to handle cases when there are no candidate words.
