# Impledge-recruitment-solution
this is a question was given by recruitment team of impledge

Problem Statement :

Write a program that:
1. Reads provided files (Input_01.txt and Input_02.txt) containing alphabetically sorted words list (one
word per line, no spaces, all lower case) 
2. Identifies & display below given data in logs/console/output file
        o longest compounded word
        o second longest compounded word
        o time taken to process the input file


Note: A compounded word is one that can be constructed by combining (concatenating) shorter words 
also found in the same file

I was also Provided with two input files one with less number of words and other had 100000 words for input

# project

Longest Compounded Words

This Python program finds the longest and second-longest compounded words by combining two alphabetically sorted word lists from separate files.

Features:

Reads  text files containing alphabetically sorted words (one word per line).
Generates and analyzes all possible compounded words formed by combining words from  files.
Identifies and displays the longest and second-longest compounded words.
Measures and displays the time taken to process the input files.

Requirements:

Python 3.x, jupyter notebook


Methodology:

TrieNode Class
    Description: Represents a node in the trie data structure.
    Attributes:

        children: A dictionary to store child nodes.
        is_end_of_word: A flag indicating the end of a word.

insert_word:

    Description: Inserts a word into the trie.
    Parameters:
    root: The root node of the trie.
    word: The word to be inserted.

is_compounded_word:

    Description: Checks if a word is a compounded word.
    Parameters:
    root: The root node of the trie.
    word: The word to be checked.
    Returns: True if the word is compounded, False otherwise.

find_longest_compounded_word:

    Description: Finds the longest and second-longest compounded words from a list.
    Parameters:
    words: A list of words to be processed.
    Returns: A tuple containing the longest and second-longest compounded words.



