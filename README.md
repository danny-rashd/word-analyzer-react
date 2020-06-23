# WordAnalyzer
Class Activity - Developing React Native App (Word Analyzer)


The word analyzer app that I did is a rather simplistic in terms of design.

For the super (), i initialized all the variables as '' instead of '0'because i wanted the initial display of the output (vowel, consonant,character) to be empty instead of showing '0' from the very start.

In the Analyzeword(), i use the let to declare & initialize the variables as 0 to start the counter (counting vowels, consonants and characters). The length of the input word into 'char' for the total number of characters.

I use the for loop to count the vowels and consonants, 'if' for the vowel(a,e,i,o,u in both lowercase and uppercase) and 'else if'(the rest of the alphabets in both lowercase and uppercase). The reason why i use 'if' and 'else if' instead of 'if' & 'else' is because i want to make a distinction between vowels and consonant while also not counting the 'spaces' and numbers in the 'else' whenever the input has been entered.

In the output, it can be observed that the vowels and consonants are counted as one whether it is uppercase or lowecase. Also, the total number of characters also counts the spaces in the word.

