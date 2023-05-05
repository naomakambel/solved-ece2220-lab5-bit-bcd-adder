Download Link: https://assignmentchef.com/product/solved-ece2220-lab5-bit-bcd-adder
<br>
The following is a block diagram of a 4 bit adder like that found in a 7483 IC.  It takes two 4-bit binary numbers in (plus a carry-in) and gives the addition of the two numbers as a 5-bit binary word (4-bit sum and a carry-out).

<ol>

 <li>a) Write a Verilog code to implement the above 4-bit adder circuit.</li>

</ol>

Use switches SW[3], SW[2], SW[1] and SW[0] to input binary number x<sub>3 </sub>x<sub>2 </sub>x<sub>1</sub> x<sub>0 </sub>and SW[9], SW[8], SW[7] and SW[6] to input binary number y<sub>3 </sub>y<sub>2 </sub>y<sub>1</sub> y<sub>0</sub>.




<h1>Display Outputs</h1>

Use BCD to SSD converter technique you implemented in Lab 3 to convert and display the inputs y<sub>4</sub> y<sub>3 </sub>y<sub>2 </sub>y<sub>1 </sub>on the SSD HEX[3] and HEX[2] and x<sub>4 </sub>x<sub>3 </sub>x<sub>2 </sub>x<sub>1 </sub>on the SSD HEX[1] and HEX[0].




<h1>Display Outputs</h1>

Use the BCD to SSD converter to convert the output from the adder – c<sub>4 </sub>s<sub>4</sub> s<sub>3 </sub>s<sub>2 </sub>s<sub>1</sub>. When converted to BCD it needs 2 digits to display the number in decimal format. Therefore you will need two SSD displays. Use HEX[5] and HEX[4] to show each input and output as specified above. If any number is less than 10 the higher decimal should be blank – not zero.




This should be done in several modules. For example a top module, a bitwise full adder module,  an adder module for all four bits, a module to convert the binary number to BCD, and a module to output the numbers to the 7-segment display. If desired, you may use previous code that you have written.




Upload your code, including all modules you have written, to UM Learn.


