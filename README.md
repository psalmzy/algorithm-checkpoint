# algorithm-checkpoint

1. Initialize variables called "length", "word_count", and "vowel_count" to 0.
2. Initialize a variable called "last_character" to an empty string.
3. Prompt the user to enter a sentence that ends with a point.
4. Read the input from the user character by character until the last character is reached.
5. For each character in the sentence:
    a. Increment the "length" variable by 1.
    b. If the character is a vowel (i.e. 'a', 'e', 'i', 'o', or 'u'), increment the "vowel_count" variable by 1.
    c. If the character is a space, increment the "word_count" variable by 1.
6. Add 1 to "word_count" to account for the last word in the sentence (which does not have a space after it).
7. Print the values of "length", "word_count", and "vowel_count" to display the results.

