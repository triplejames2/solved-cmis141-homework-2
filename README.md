Download Link: https://assignmentchef.com/product/solved-cmis141-homework-2
<br>
Before attempting this project, be sure you have completed all of the reading assignments, hands-on labs, discussions, and assignments to date.

Design a Java class named Guitar that contains:

<ul>

 <li>A private int data field named numStrings that defines the number of strings on the guitar. The default value should be 6.</li>

 <li>A private double data field named guitarLength that defines the length of the guitar in inches. The default value should be 28.2</li>

 <li>A private String data field named guitarManufacturer that defines the manufacturer of the guitar. The default value should be “Gibson”.</li>

 <li>A private Color data field named guitarColor that defines the color of the guitar. The default value should be Color.Red.</li>

 <li>A no argument constructor that creates a Guitar using the default number of strings, length, manufacturer and color.</li>

 <li>A constructor that creates a Guitar using a specified number of strings, length, manufacturer and color.</li>

 <li>Getter methods for all data fields.</li>

 <li>A playGuitar() method that returns a string representation of 16 randomly selected musical notes of random duration. For example, the first part of the string returned might look like this: [A(2), G(3), B(0.5), C(1), C(1), D(0.25), …]. You can assume one octave in the key of C where valid notes include A, B, C, D, E, F and G and duration values are .25, .5, 1, 2, and 4 representing sixteenth notes, eighth notes, quarter notes, half notes and whole notes, respectively.</li>

 <li>A toString() method that displays the number of strings, length, manufacturer and color in String format</li>

</ul>

Be sure your code compiles.

Write a Java test program, named TestGuitar, to create 3 different Guitars representing each representing a unique test case and call each all of the getter methods along with the toString and playGuitar() methods and document the output. For example for a Guitar with 7 strings, length of 30.2, manufactured by Fender with a color of Black, the output may look similar to this:

***Output***

toString(): (numStrings=7, Length=30.2, manufacturer=Fender, color=Black) getNumStrings(): 7 getGuitarLength(): 30.2 getGuitarManufacturer(): Fender

getGuitarColor(): Black

playGuitar(): [A(2), G(3), B(0.5), C(1), C(1), D(0.25), E(2), F(2), G(0.25), C(4), C(1), F(0.25),A(1), C(2), D(4),C(4)]

Document your test cases in the form of table with columns indicating the input values, expected output, actual output and if the test case passed or failed. This table should contain 4 columns with appropriate labels and a row for each test case. An example template is shown below.  Note that the actual output should be the actual results you receive when running your program and applying the input for the test record.

Keep in mind, for three guitars, you will have three different output results. Also, note there is no requirement to actually play the notes of the guitar. The notes are just a string representation.

<strong>Example test cases: </strong>

<table width="623">

 <tbody>

  <tr>

   <td width="165"><strong>Input  </strong></td>

   <td width="205"><strong>Expected Output </strong></td>

   <td width="205"><strong>Actual Output </strong></td>

   <td width="48"><strong>Pass</strong><strong>? </strong></td>

  </tr>

  <tr>

   <td width="165"><strong>Constructor:</strong> numStrings=7 guitarLength=30.2 Manufacturer=Fende rColor=Black</td>

   <td width="205">** Output **toString(): (numStrings=7, Length=30.2, manufacturer=Fender, color=Black) getNumStrings(): 7 getGuitarLength(): 30.2 getGuitarManufacturer(): FendergetGuitarColor(): BlackplayGuitar(): [A(2), G(3),B(0.5), C(1), C(1), D(0.25), E(2),F(2), G(0.25), C(4), C(1),F(0.25),A(1), C(2), D(4),C(4)] <strong> </strong></td>

   <td width="205">** Output **toString(): (numStrings=7, Length=30.2, manufacturer=Fender, color=Black) getNumStrings(): 7 getGuitarLength(): 30.2 getGuitarManufacturer(): FendergetGuitarColor(): BlackplayGuitar(): [A(2), G(3),B(0.5), C(1), C(1), D(0.25), E(2),F(2), G(0.25), C(4), C(1),F(0.25),A(1), C(2), D(4),C(4)]<strong> </strong></td>

   <td width="48"><strong>Yes </strong></td>

  </tr>

  <tr>

   <td width="165"><strong>Test case 2 here </strong></td>

   <td width="205"><strong> </strong></td>

   <td width="205"><strong> </strong></td>

   <td width="48"><strong> </strong></td>

  </tr>

  <tr>

   <td width="165"><strong>Test case 3 here </strong></td>

   <td width="205"><strong> </strong></td>

   <td width="205"><strong> </strong></td>

   <td width="48"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

The google recommended Java style guide, provided as link in the week 2 content, should be used to format and document your code. Specifically, the following style guide attributes should be addressed:

<ul>

 <li>Header comments include filename, author, date and brief purpose of the program.</li>

 <li>In-line comments used to describe major functionality of the code.</li>

 <li>Meaningful variable names and prompts applied.</li>

 <li>Class names are written in UpperCamelCase.</li>

 <li>Variable names are written in lowerCamelCase.</li>

 <li>Constant names are in written in All Capitals.  Braces use K&amp;R style<strong>.</strong></li>

</ul>

<strong>Submission requirements </strong>

Deliverables include all Java files (.java) and a single word (or PDF) document. The Java files should be named appropriately for your applications. The word (or PDF) document should include screen captures showing the successful compiling and running of each of the test cases. Each screen capture should be properly labeled clearly indicated what the screen capture represents. The test cases table should be included in your word or PDF document and properly labeled as well.

Submit your files to the Homework 2 assignment area no later than the due date listed in your LEO classroom. You should include your name and HW2 in your word (or PDF) file submitted (e.g. firstnamelastnamehw2.docx or firstnamelastnamehw2.pdf)

<strong>Grading Rubric: </strong>

The following grading rubric will be used to determine your grade:

<table width="642">

 <tbody>

  <tr>

   <td width="208"><strong>Attribute </strong></td>

   <td width="434"><strong>Meets </strong></td>

  </tr>

  <tr>

   <td width="208">Guitar Class</td>

   <td width="434">10 pointsA private int data field named numStrings that defines the number of strings on the guitar was included. The default value was 6. (0.5 point)A private double data field named guitarLength that defines the length of the guitar in inches was included. The default value was28.2. (0.5 point)A private String data field named guitarManufacturer that defines the manufacturer of the guitar was included. The default value was “Gibson”. (0.5 point)A private Color data field named guitarColor that defines the color of the guitar was included.  The default value was Red. (0.5 point)A no argument constructor that creates a Guitar using the default number of strings, length, manufacturer and color was included. (1 point)A constructor that creates a Guitar using a specified number of strings, length, manufacturer and color was included. (1 point)   Getter methods were included for all data fields. (2 points)A playGuitar() method that returns a string representation of 16 randomly selected musical notes of random duration was included .(2 points)A toString() method that displays the number of strings, length, manufacturer and color in String format was included. (2 point)</td>

  </tr>

  <tr>

   <td width="208">Test Guitar Class</td>

   <td width="434">5 points</td>

  </tr>

  <tr>

   <td width="208"></td>

   <td width="434">TestGuitar class was used to construct at least, different 3 Guitar objects. (3 points)For each of the objects constructed, each of the methods was called with results output. (2 point) </td>

  </tr>

  <tr>

   <td width="208">Test Cases</td>

   <td width="434">5 pointsA minimum of 3 test cases was used in the form of table with columns indicating the input values, expected output, actual output and if the test case passed or failed. The table should contain 4 columns with appropriate labels and a row for each test case. (5 points)</td>

  </tr>

  <tr>

   <td width="208">Documentation and Style guide</td>

   <td width="434">5 pointsScreen captures were provided and labeled for compiling your code, and running each of your 3 test cases. (1.5 points)Header comments include filename, author, date and brief purpose of the program. (0.5 points)In-line comments used to describe major functionality of the code.(0.5 points)Meaningful variable names and prompts applied. (0.5 points)Class names are written in UpperCamelCase. (0.5 points)Variable names are written in lowerCamelCase. (0.5 points)Constant names are in written in All Capitals. (0.5 points)Braces use K&amp;R style<strong>. </strong>(0.5 points)</td>

  </tr>

 </tbody>

</table>

<strong> </strong>