

Variable Declarations:

Several variables are declared, including sentenceLength, numberWords, numberVowels, i, j, k, Sentence, and sum. These variables will be used to store various information about the sentence being analyzed.
Input:

The algorithm reads input from the user, expecting a sentence stored in the variable Sentence.
Calculate Sentence Length:

A WHILE loop runs until a period (.) is encountered in the sentence.
Inside the loop, the sentenceLength is incremented for each character, and the loop index i is incremented.
This loop calculates the length of the sentence.
Count Words:

Another WHILE loop runs through each character of the sentence (j < sentenceLength).
If a space character is encountered (Sentence[j] = " "), the numberWords counter is incremented.
This loop counts the number of words by counting spaces.
Count Vowels:

Similar to the previous loop, a WHILE loop iterates through each character of the sentence (k < sentenceLength).
If the current character is a vowel (a, e, i, o, or u), the numberVowels counter is incremented.
This loop counts the number of vowels in the sentence.
Output:

The algorithm uses the Write() function to output the calculated sentenceLength, numberWords, and numberVowels.
In summary, the algorithm takes a sentence as input and then calculates its length, the number of words, and the number of vowels. It achieves this by utilizing loops and conditional statements.
