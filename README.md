# composition-and-interfaces
CMP202 class (class 3) composition and interface


classwork for composition and interfaces
ALGORITHM

 First, convert the input word to a character array using the toCharArray() method.
 Initialize two pointers, start and end, to the beginning and end of the character array, respectively.
 Iterate through the character array, comparing the characters at the start and end pointers.
If they are not equal, the word is not a palindrome.
 If the characters at the start and end pointers are equal, swap them using a temporary variable and move the start pointer to the right and the end pointer to the left.
 Repeat steps 3 and 4 until the start pointer is greater than or equal to the end pointer. 
 If the loop completes without finding any unequal characters, the word is a palindrome.
