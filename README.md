Overview
The Word Occurrence Counter is a simple C++ program that reads words from a text file, counts the occurrences of each word, and displays the results. The program is case-insensitive, treating words with different cases (e.g., "Word" and "word") as the same.

Features:

Reads words from a specified text file (words.txt).

Counts occurrences of each word.

Outputs the word and its occurrence count to the console.

Case-insensitive word counting.

Requirements:

C++11 or later

A text file named words.txt containing the words to be counted.

How to Use:

Prepare the Input File: Create a text file named words.txt in the same directory as the program. Populate it with words, one per line.

Compile the Program: Use a C++ compiler to compile the program. For example, using g++:
          
      g++ -o word_counter word_counter.cpp

Run the Program: Execute the compiled program:

      ./word_counter

View the Output: The program will output each unique word from the file along with its occurrence count.

Code Explanation

Struct Ayo: Defines a structure to hold a word and its occurrence count.

Function toLowercase: Converts a string to lowercase for case-insensitive comparison.


Main Function:
Opens the words.txt file for reading.
Reads each word, converts it to lowercase, and counts occurrences.
Outputs the results to the console.
Error Handling
If the program cannot open the words.txt file, it will display an error message and terminate.

Example:

Given a words.txt file with the following content:

    Hello
    world
    hello
    World

The output will be:

    hello 2
    world 2
