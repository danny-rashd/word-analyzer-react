## Class Activity - Developing React Native App: Word Analyzer

The Word Analyzer app I have developed is a simple yet effective tool for analyzing words.

To ensure a clean initial display of the output (vowel, consonant, character), I have initialized all variables as empty strings ('') instead of '0' using the super() method.

Within the Analyzeword() function, I use let to declare and initialize the counting variables as 0, which allows me to start counting vowels, consonants, and characters from the beginning. The length of the input word is stored in the char variable to determine the total number of characters.

I have employed a for loop to count the vowels and consonants. By using an if statement, I accurately identify and count the vowels (including both lowercase and uppercase). For the remaining alphabets, I utilize an else if statement. This approach allows me to distinguish between vowels and consonants while excluding spaces and numbers from the count using the else statement.

The output of the app presents the count of vowels and consonants as a unified total, regardless of whether they are uppercase or lowercase. Additionally, the count of total characters includes spaces within the word.

With its straightforward design and efficient word analysis capabilities, the Word Analyzer app offers a valuable tool for users seeking to examine the composition of words.
