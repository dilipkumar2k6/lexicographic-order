# lexicographic-order
-  The lexicographical order is one way of formalizing word order given the order of the underlying symbols.
- The formal notion starts with a finite set A, often called the alphabet, which is totally ordered. 
- That is, for any two symbols a and b in A that are not the same symbol, either a < b or b < a.
- The words of A are the finite sequences of symbols from A, including words of length 1 containing a single symbol, words of length 2 with 2 symbols, and so on, even including the empty sequence  with no symbols at all.

The lexicographical order on the set of all these finite words orders the words as follows:
1. Given two different words of the same length, say a = a1a2...ak and b = b1b2...bk, the order of the two words depends on the alphabetic order of the symbols in the first place i where the two words differ (counting from the beginning of the words): a < b if and only if ai < bi in the underlying order of the alphabet A.
2. If two words have different lengths, the usual lexicographical order pads the shorter one with "blanks" (a special symbol that is treated as smaller than every element of A) until the words are the same length, and then the words are compared as in the previous case.
- However, in combinatorics, another convention is frequently used for the second case, whereby a shorter sequence is always smaller than a longer sequence. This variant of the lexicographical order is sometimes called shortlex order.
- In lexicographical order, the word "Thomas" appears before "Thompson" because they first differ at the fifth letter ('a' and 'p'), and letter 'a' comes before the letter 'p' in the alphabet. Because it is the first difference, in this case the 5th letter is the "most significant difference" for alphabetical ordering.
- An important property of the lexicographical order is that for each n, the set of words of length n is well-ordered by the lexicographical order (provided the alphabet is finite); that is, every decreasing sequence of words of length n is finite (or equivalently, every non-empty subset has a least element).[1][2] It is not true that the set of all finite words is well-ordered; for example, the set { 1, 01, 001, 0001, ... } has no least element.

# Problems
https://leetcode.com/problems/verifying-an-alien-dictionary/

https://leetcode.com/problems/custom-sort-string/

https://leetcode.com/problems/alien-dictionary/

# Reference
https://en.wikipedia.org/wiki/Lexicographic_order