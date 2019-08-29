# Huffman-Coding
Huffman Coding in C

Huffman coding uses a specific method for choosing the representation for each symbol, resulting in a prefix code (sometimes called "prefix-free codes", that is, the bit string representing some particular symbol is never a prefix of the bit string representing any other symbol). Huffman coding is such a widespread method for creating prefix codes that the term "Huffman code" is widely used as a synonym for "prefix code" even when such a code is not produced by Huffman's algorithm.


In this repository you will find my code for compression of a textfile into a sequence of 1's and 0's.
And again retrieving the original textfile from the sequence of the this sequence of 1's and 0's
 Here, I have used a priority queue and implemented it using max heap. The characters occuring in the text file are first counted and frequency table is constructed on basis of the occurence of characters. Higher frequency characters are at less distance from the root.In order to find the encoded code for a character we have to search the heap.if go left from a root then 0 is appended to its code and when we go right 1 is appended to its code.
 
