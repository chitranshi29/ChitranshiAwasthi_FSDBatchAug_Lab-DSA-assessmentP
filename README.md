# ChitranshiAwasthi_FSDBatchAug_Lab-DSA-assessmentP
First problem : A java Program Balancing Brackets, use a suitable data structure to print whether the string entered is a Balanced Brackets or Unbalanced String
Sample input---
( [ [ { } ] ] )
Sample Output---
The entered String has Balanced Brackets

BalancedParenthesesExample1 is class .First, we declare a character stack.Convert input string into a character array.
Traverse the input string(By traversing the character array).We push the current character to stack if it is a starting bracket('(' or '{' or '[').
We pop the current character from the stack if it is a closing bracket. If the popped character doesn't match with the starting bracket, brackets are not balanced.
Once the traversing is finished and there are some starting brackets left in the stack, the brackets are not balanced.
We can implement the code for ba


Second problem:
Input: sum = 28, given BST
output Sum = 130
Pair is (60,70)
Please find attched Image.


Sum_Binary_tree is the class.The idea is based on Hashing. 
We traverse binary search tree by inorder way and insert node’s value into a set. Also check for any node,
difference between given sum and node’s value in set, if it is found then pair exists otherwise it doesn’t exist. 
