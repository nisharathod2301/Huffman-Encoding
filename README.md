# Huffman-Encoding
Given a string S of distinct character of size N and their corresponding frequency f[ ] i.e. character S[i] has f[i] frequency. We have to build the Huffman tree print all the huffman codes in preorder traversal of the tree.


Example 1:


S = "abcdef"
f[] = {5, 9, 12, 13, 16, 45}


Output:


0 100 101 1100 1101 111


Explanation:
Steps to print codes from Huffman Tree
HuffmanCodes will be:


f : 0
c : 100
d : 101
a : 1100
b : 1101
e : 111
Hence printing them in the PreOrder of Binary 
Tree.


Expected Time complexity: O(N * LogN) 
Expected Space complexity: O(N) 

Constraints:
1 ≤ N ≤ 26
