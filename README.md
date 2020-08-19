# Algorithms-Chapter2 Studio

Use the provided BST example below, carry out these operations in the order specified:

Insert 9
Remove 2
Insert 12
Remove 6

You may type up or draw each resulting tree to turn in. If drawing your trees, use your smartphone to take a pic of each resulting tree.

    _____8
   /      \
 _3___     10
/     \      \
1      6      14
 \    / \
  2  5   7
  

1. Insert 9

    _____8__
   /        \
 _3___       _10_
/     \     /    \
1      6   9      14
 \    / \
  2  5   7
  
 2. Remove 2
 
     _____8__
   /         \
 _3___       _10_
/     \     /    \
1      6   9      14
      / \
     5   7
     
     
3. Insert 12

     _____8__
   /         \
 _3___       _10_
/     \     /    \
1      6   9     14
      / \        /
     5   7     12
     
     
4. Remove 6

     _____8__
   /         \
 _3___       _10_
/     \     /    \
1      7   9      14
      /          /
     5         12
 
2.5.2. Bonus Mission
Write a program that has a function, binarySearch(item, list), that searches for item in the sorted list, list. The function should return the index of the item, if found, and -1 otherwise.
