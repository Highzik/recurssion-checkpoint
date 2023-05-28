1. Start with a word, inputWord.
2. Initialize two pointers, start and end, pointing to the beginning and end of the word, respectively.
3. While start is less than or equal to end:
   - Compare inputWord[start] and inputWord[end].
   - If they are not equal, return false as the word is not a palindrome.
   - Increment start by 1 and decrement end by 1.
4. If the loop completes without returning false, the word is a palindrome, so return true.
