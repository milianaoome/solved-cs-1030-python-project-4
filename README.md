Download Link: https://assignmentchef.com/product/solved-cs-1030-python-project-4
<br>
Before starting to code your solutions, write pseudocode and/or draw flowcharts. Do not start coding until you have a deeper understanding of what the solutions should look like. Write pseudocode from which you can directly code your program. I am deliberately not giving step-by-step specifications as it is good practice for you to do that on your own. However, feel free to contact me for help or clarifications. See “What and how to submit” near the end of this document for file naming conventions.




<ol>

 <li><strong> Scrabble<sup>tm</sup> – File, Loop and Dictionary Practice</strong></li>

</ol>




Write a program that reads a list of words and calculates the Scrabble<sup>tm</sup> point value of each word. If the word has 0 characters or 10 characters or more, assign a point value of 0. The words are read one per line from file

1030 Project 04 01 Words.txt

which is included with this specification. Convert lower case letters to upper case with a statement like

letter = character.upper()

and ignore all characters that aren’t letters. You can test if a character is a letter with

if letter.isalpha()

Point values are based on this table which can be conveniently implemented with a dictionary:




<table>

 <tbody>

  <tr>

   <td width="72"># points</td>

   <td width="192">Letters</td>

  </tr>

  <tr>

   <td width="72">1</td>

   <td width="192">A, E, I, L, N, O, R, S, T, U</td>

  </tr>

  <tr>

   <td width="72">2</td>

   <td width="192">D, G</td>

  </tr>

  <tr>

   <td width="72">3</td>

   <td width="192">B, C, M, P</td>

  </tr>

  <tr>

   <td width="72">4</td>

   <td width="192">F, H, V, W, Y</td>

  </tr>

  <tr>

   <td width="72">5</td>

   <td width="192">K</td>

  </tr>

  <tr>

   <td width="72">8</td>

   <td width="192">J, X</td>

  </tr>

  <tr>

   <td width="72">10</td>

   <td width="192">Q, Z</td>

  </tr>

 </tbody>

</table>




An actual Scrabble<sup>tm</sup> board includes some squares that multiply the value of a letter or the value of an entire word. For this problem, ignore these squares. The output should be in a list with the word and its points, with the point total displayed at the end of the program. For example:




Word                     Points

CAT                            3

DOG                          5

FOX                          13

HIPPO                      12

PLATYPUS               15




Total                          48




This problem is derived from <em>The Python Workbook</em>, by Ben Stephenson, page 66, exercise 137.




<ol start="2">

 <li><strong> Letter Frequencies – File, Loop and Dictionary Practice</strong></li>

</ol>

<strong> </strong>

Write a program that reads sentences from file

1030 Project 04 02 Sentences.txt




(included with this specification) and calculates letter frequencies (total counts of how often each letter appears) for all sentences in the file. Print the original lines as you read them. Then, convert lower case letters to upper case and ignore all characters that aren’t letters. Frequency analysis is one approach to decrypting messages. The letters E and T are the most common letters in the English language, so a frequency analysis of a long message would likely show high counts for letters E and T.




After processing all lines in the input file, display on the screen and write to output file

FirstnameLastname (Your section # here) 04 02 Output.txt

the letters and their frequencies. Here’s an example. Given lines

See Spot.

See Spot code in Python.

The screen display and output file would look something like:




Letter   Frequency

A             0

B             0

….          ….

E            5

….          ….

O           4

P            1

….          ….

S            4

etc.         etc.







This problem is derived from <em>The Python Workbook</em>, by Ben Stephenson, page 71 exercise 146.




<ol start="3">

 <li><strong> Concatenate Multiple Files – File and List Practice</strong></li>

</ol>

<strong> </strong>

Write a program that concatenates (combines) one or more files, writing them to an output file:

<ol>

 <li>Reads input file 1030 Project 04 03 Files.txt which itself is a list of files</li>

 <li>Read each of the files, writing them to output file</li>

</ol>

FirstnameLastname (Your section # here) 04 03 Output.txt




For example, say input file 1030 Project 04 03 Files.txt has these three lines:

1030 Project 04 03 File 1.txt

1030 Project 04 03 File 2.txt

1030 Project 04 03 File 3.txt

The first file has these lines:

Line 1

Line 2

The second one has this line:Line 3

The third file has these lines:

Line 4

Line 5

Line 6










The output file, FirstnameLastname (Your section # here) 04 03 Output.txt, would look like this:

Line 1

Line 2

Line 3

Line 4

Line 5

Line 6




This problem is derived from <em>The Python Workbook</em>, by Ben Stephenson, page 70, exercise 143.




<strong>What and how to submit</strong>




You have now created these files:




FirstnameLastname (Your section # here) 04 01.py




FirstnameLastname (Your section # here) 04 02.py

FirstnameLastname (Your section # here) 04 02 Output.txt




FirstnameLastname (Your section # here) 04 03.py

FirstnameLastname (Your section # here) 04 03 Output.txt




<strong>Note you do not submit the input files. </strong>If your IDE supports it, turn on line numbering before printing. Submit your programs and accompanying files together in the order shown above. You will lose points if you don’t follow this submission guide.




<strong>How your programs are evaluated</strong>




<ol>

 <li>Do they work according to the specifications?</li>

 <li>Are the input files and prompts correct?</li>

 <li>Are the programs documented?</li>

 <li>Do the programs follow Python and file naming standards?</li>

</ol>








