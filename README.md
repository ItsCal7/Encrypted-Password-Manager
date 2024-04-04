# Encrypted Password Manager
This C++ program encrypts and decrypts stored usernames and passwords based on the numerical key you input.
Each key is unique and will only return legible answers if you enter the proper key. 
Each number in the key acts as an ASCII Caesar cypher
But because each digit in the key corresponds to each digit in the word you are encrypting, it is not vulnerable to frequency analysis
Keys shorter than the word will produce un-decryptable codewords and should be avoided, hence the warning in the program.
User may choose a different key for each encryption for extra safety, though it would be much harder to manage
