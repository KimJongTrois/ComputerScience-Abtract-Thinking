# ComputerScience-Abtract-Thinking

1. The word 'RACECAR'
--> To Identify whether this word is a palindrome, I would simply (or make the computer) take each letter starting from the back to the front and reassemble the word in this order. I would then compare the original word with the new word that has been reassembled and scan for any differences in the letter order. If the order of the letters in both words are the same, then the word RACECAR is a palindrome, otherwise it's not. Seeing as RACECAR is RACECAR backwards, it is a palindrome.
2. The word 'DEFIED'
--> I would use the same method as described above. In this case, the word 'DEFIED', in reverse order is 'DEIFED'. Seeing as DEFIED and DEIFED do not have the same letter order, the word 'DEFIED' is not a palindrome.

3. My informal algorith (in English) to define a palindromes.

--> The word/palindrome would be assigned to a variable, for example, called _word_. An empty variable would then be created, called _reverseWord_. The computer would then iterate/loop over the length of the variable _word_. The loop (depending on how many iterations it has gone through) would take the last letter of _word_ (that the loop hasn't already gone over) and add that letter to the _reverseWord_ variable using string concatenation. When the loop is finished, the computer would then compare the the two variables, if they are equal, the original word is a palindrome, however, if the words are not eaqual, the word is not a palindrome.
