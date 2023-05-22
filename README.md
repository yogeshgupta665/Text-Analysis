# Text-Analysis
The project focuses on developing a language translation and text analysis tool using Python. It encompasses several functions and components to perform various operations on textual data.Here is a summary of the key functionalities:

1. Text Processing:
   - The project includes functions to read text from files, remove punctuation, split text into sentences, and extract word lists from sentences.
   - The `read_file` function reads the contents of a file and returns them as a string.
   - The `remove_punc2` function removes punctuation characters from a given text, creating a clean version of the text.

2. Language Translation:
   - The translation functionality involves converting English words to their Latin counterparts.
   - The `translate` function utilizes a rule-based approach to transform English words to Latin. It identifies the first vowel occurrence, moves consonants before it to the end, and appends the suffix 'ay'.

3. Text Analysis:
   - The project includes functions for analyzing and manipulating text data.
   - The `split_sentences` function splits a text string into a list of sentences based on common sentence-ending markers like '.', '?', and '!'.
   - The `starts_with_vowel` function checks if a given string starts with a vowel.
   - The `following` function retrieves the list of users that a specific user is following in a social network, based on a list of follower-followee relationships.

4. Social Network Analysis:
   - The project incorporates functionalities related to social network analysis.
   - The `list_textfiles` function returns a list of filenames ending in '.txt' in a specified directory.
   - The code reads follower-followee relationships from a file and stores them in a dictionary data structure (`edge_dict`).
   - The `following2` function utilizes the `edge_dict` to find the list of users a given user is following.

5. Performance Evaluation:
   - The project includes the use of the `%timeit` magic command to measure the execution time of specific functions.

Overall, the project combines various components to offer language translation capabilities, text analysis functionalities, and social network analysis features. It provides users with tools to process text data, analyze relationships in social networks, and translate words from English to Latin.
