# Impledge-Code
# Solution-Word-Composition-Problem-Impledge-Technologies
Overview : 
This is a program that finds the longest and second-longest concatenated words. And the time required to compile this. A compounded word can be constructed by combining shorter words also found in the same file.

Problem: Develop a program to read two files containing word lists sorted alphabetically. 
The program should identify and display the longest and second longest compounded words found in the files. Also, it should show the time taken to process the files. 
Design: We'll use a Trie data structure to efficiently store and retrieve words from the files. This structure will help determine if a word can be formed by concatenating shorter words. Our custom Trie implementation includes links to characters and flag variables to indicate the end of a word. Steps for execution: 
1. Install a Java compiler on your computer. 
2. Clone the repository containing the program. 
3. Download the input files to obtain the desired output. 
4. Open the code.java file in your compiler and execute the program.
 Approach: 
1. Each node in the Trie consists of an array of links to its child nodes for each alphabet (a-z) and a boolean flag to indicate the end of a word. 
2. The Trie includes functions to manipulate the flag and array. 
3. The main class, Solution, generates the solution for the problem. 
4. Insert Function: This function inserts words into the Trie and marks the last node as the end of a word. 
5. Search Function: This function recursively searches for compound words. It checks if a given string can be formed by combining two or more other words from the list. The search begins at the root of the Trie and progresses through each character in the input string. If the end of the input string is reached and the current node is marked as the end of a word, it confirms that the string is a compound word.
