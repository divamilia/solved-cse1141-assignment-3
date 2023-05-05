Download Link: https://assignmentchef.com/product/solved-cse1141-assignment-3
<br>
In this assignment, you will write the following programs by using loops.

<ol>

 <li>Write a program that takes an integer argument <sub>N </sub>at each iteration and uses a <sub>while</sub> loop to compute the number of times you need to divide <sub>N</sub> by 2 until it is strictly less than 1. Print out the error message “<sub>Illegal input</sub>” if <sub>N</sub> is negative. Whenever the user enters the value of 0, your program should end. <em>This program simply computes the number of bits in the binary representation of N. </em></li>

</ol>

Example:

Enter an integer number: 1 The number of bits: 1

Enter an integer number: 2 The number of bits: 2

Enter an integer number: 4

The number of bits: 3




Enter an integer number: 8

The number of bits: 4




Enter an integer number: 16

The number of bits: 5




Enter an integer number: 1000

The number of bits: 10




Enter an integer number: -25

The number of bits: Illegal input




Enter an integer number: 0

Program ends. Bye













<ol start="2">

 <li>A special sequence of numbers is defined as follows. The first two numbers in the sequence are 0 and 1, and each subsequent number is 4 times the previous number minus the one before that. In other words, let A<sub>x</sub> be the <em>x</em>-th number in sequence.</li>

</ol>

Then,  A<sub>x</sub> = (4 × A<sub>x-1</sub> ) – A<sub>x-2</sub>




The sequence is: 0, 1, 4, 15, 56, 209, 780, 2911…




Write a program that calculates the <em>x</em>-th number in the sequence. The program asks the user for the value of <em>x</em> and prints it out to the screen.




Example:




Please enter an integer number:

8

In position 8, the value is 2911.




<ol start="3">

 <li>Write a program that takes a string as input and prints the following pattern.Please consider the necessary controls to print the first and the last characters of the string only a single time! You have to use loops in your implementation, otherwise you cannot get any points!</li>

</ol>




<u>1</u><sup>st</sup><u> Sample run:</u>




Enter an input string: COMPUTER




COMPUTERETUPMOCOMPUTERETUPMOC

COMPUTE ETUPMOCOMPUTE ETUPMOC

COMPUT   TUPMOCOMPUT   TUPMOC

COMPU     UPMOCOMPU     UPMOC

COMP       PMOCOMP       PMOC

COM         MOCOM         MOC

CO           OCO           OC

C             C             C

<u>2</u><sup>nd</sup><u> Sample run:</u>




Enter an input string: MARMARA




MARMARARAMRAMARMARARAMRAM

MARMAR RAMRAMARMAR RAMRAM

MARMA   AMRAMARMA   AMRAM

MARM     MRAMARM     MRAM

MAR       RAMAR       RAM

MA         AMA         AM

M           M           M

<u>3</u><sup>rd</sup><u> Sample run:</u>




Enter an input string: 12345678




12345678765432123456787654321

1234567 7654321234567 7654321

123456   65432123456   654321

12345     543212345     54321

1234       4321234       4321

123         32123         321

12           212           21

1             1             1