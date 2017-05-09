# vigenere-py
Algorithm for deciphering a message encoded with Vigenère cipher written in python 3
The code runs the following steps:
1. try to find the key length by using the Friedman test method (according to the given upper and lower bound of the sum of letter frequencies)
2. once the key length is known, use the letter distribution / relative frequency histograms of the cipher subsequences to decode the deduce the key word
3. decode the cipher using the key word

(for simplicity, only upper case characters of the English alphabet have been considered)
