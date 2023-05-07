Download Link: https://assignmentchef.com/product/solved-exercise-3-virtual-initialization
<br>
Due by the end of your Week‐4 laboratory class.                                                                               (2 marks)

This exercise is to be done during your week 4 laboratory class. When you complete the exercise show your work to your lab tutor to have your work marked. The marking is based mainly on correct implementation and code readability. You should implement your code in one file (e.g. ex3.cpp, ex3.c, ex3.java). Make sure your program has a header comment block containing the name of the exercise, your name and your student login (e.g. jfk01). You may implement your solution in C, C++, java or Python.




For this exercise you are to implement a virtually initialized array and test it for correctness.




As usual, your program will prompt for the name of an input file and the read and process the data contained in this file.




You will use three integer arrays, <strong>data[]</strong>, <strong>forward[]</strong> and <strong>backward[]</strong> each containing 100 elements.




Your test data will consist of a file containing two parts:

<ol>

 <li>A sequence of pairs: <strong>what</strong>,<strong> where</strong>. You are to store the value <strong>what</strong> in location <strong>where</strong> of the <strong>data</strong> array using virtual initialization. I.e. <strong>data[where] = what</strong>.</li>

 <li>This sequence is terminated by the pair <strong>‐1 ‐1</strong></li>

 <li>This is followed by a sequence of single integer values, <strong>probe</strong>. For each such value you are to test whether <strong>data[probe]</strong> has been initialized and print one of the following two messages:</li>

</ol>

Position <strong>probe</strong> has not been initialized.

Position <strong>probe</strong> has been initialized to value <strong>data[probe]</strong>.

<ol start="4">

 <li>This sequence is terminated by the value <strong>‐1</strong></li>

</ol>

A sample input file might contain:




<strong>42 7 </strong>

<strong>93 9 </strong>

<strong>11 4 </strong>

<strong>‐1 ‐1 </strong>

<strong>7 </strong>

<strong>8 </strong>

<strong>9 </strong>

<strong>‐1 </strong>

<strong> </strong>

For which the output would be:




<strong>Position 7 has been initialized to value 42. </strong>

<strong>Position 8 has not been initialized. </strong>

<strong>Position 9 has been initialized to value 93. </strong>

<strong> </strong>


