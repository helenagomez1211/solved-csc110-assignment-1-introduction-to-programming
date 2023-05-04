Download Link: https://assignmentchef.com/product/solved-csc110-assignment-1-introduction-to-programming
<br>
<strong>Learning Outcomes: </strong>

When you have completed this assignment, you should understand:

<ul>

 <li>How to design, compile, run and check a simple and complete Java program on your own.</li>

 <li>The effect of escape sequences on printed strings.</li>

 <li>How to write basic static methods.</li>

 <li>The flow of control (i.e. the effects of method calls and assignment statements).  How to format and document a Java program.</li>

</ul>




<strong>Part 1 – ASCII Art </strong>

In this part of the assignment, you will write the Java code that prints out a simple totem pole using American standard keyboard (ASCII) characters.  You will create the code, in three separate static methods, printPig, printFrog and printTotemPole.  You may use more methods and call them what you like, but these three must be spelled exactly as shown. The main method will direct the flow, by calling these three methods.




<h1>Detailed steps</h1>

<ol>

 <li>Create the public class called FirstAssignment<sub>.java</sub>.</li>

 <li>Save and compile this file, making sure there are no errors before proceeding.</li>

 <li>Add a <sub>main </sub>

  <ul>

   <li>Method header: public static void main(String[] args) {</li>

   <li>Inside this method, write a statement that prints out “Welcome!” to the console</li>

   <li>Save, compile, and run the program. Repeat until error-free and output is similar to the following image:</li>

  </ul></li>

 <li>Write and test the printPig

  <ul>

   <li>Method header: public static void printPig() {  Call this method from the main</li>

   <li>Save, compile and run the program. Repeat until error-free and output is similar to the following image:</li>

  </ul></li>

 <li>Write and test the <sub>printFrog</sub>

  <ul>

   <li>The header is similar to the <sub>printPig</sub></li>

   <li>Call this method from the <sub>main</sub></li>

   <li>Save, compile, and run the program. Repeat until error-free and output is similar the following image:</li>

  </ul></li>

 <li>Write and test the <sub>printTotemPole</sub>

  <ol>

   <li>In printTotemPole, call printFrog and printPig to stack the animals as shown in the image on the next page.

    <ol>

     <li>Note that there is a <em>spacer line</em> between each of the animals.</li>

     <li>Note also that you will have to modify <sub>printPig</sub> so it sits evenly on the totem pole.</li>

    </ol></li>

   <li>Replace the calls to <sub>printPig</sub> and <sub>printFrog </sub>in the <sub>main</sub> method with a call to printTotemPole.</li>

   <li>Save, compile and run the program. Repeat until error-free and output is similar to the image on the next page:</li>

  </ol></li>

</ol>







NOTE:  These images are done on a Windows computer using the Consolas font, different fonts may result in slightly different outputs, you will not be penalized for this, don’t worry!

<strong>Part II – Math Calculations</strong>

In the same FirstAssignment.java file, you are to write code to calculate the surface area of a closed cylinder that has a given height and diameter.  The formula for the surface area is twice the area of a circle (the top and bottom), added to the area of the rectangle when you cut and flatten the <em>wall </em>of the cylinder.  See the diagram below:

Rather than write out the whole formula in one step, you will break it down into smaller steps, storing each result into a variable that you create and name appropriately.  Each subsequent step will use only the variables and NOT the literal values.  You will be successful if the calculations are correct AND there is only one ‘4’, one ‘5’ and maybe a ‘2’ or two in the code.

<strong><em> </em></strong>

<h1>Detailed steps</h1>

<ol>

 <li>Create another method inside FirstAssignment, called calcSurfaceArea.

  <ul>

   <li>Declare two integer variables: height and diameter. Assign the literal values 5 to height and 4 to diameter.  (That will be your quota for ‘4’ and ‘5’ literals.)</li>

   <li>Create a new variable called radius that is one half the diameter. (One of the</li>

  </ul></li>

</ol>

‘2’s.)

<ol start="2">

 <li>Write a single statement to calculate the circumference of the cylinder, and assign the result to a new variable, appropriately named. Because π (pi) is required for any calculations involving circles, you will need to use a variable for pi.  Luckily, Java has one in its library, called PI, which provides an accurate value.</li>

 <li>Write a single statement to calculate the area of the rectangle that forms the wall of the cylinder with the given height and diameter. Assign the result to a new variable, appropriately named.</li>

 <li>Write a single statement to calculate the total area of a circle with the given diameter, and store the result in a new variable, appropriately named.

  <ul>

   <li>Computers are faster at adding than multiplying, and are faster at multiplying than calculating to a power, so most programmers will write radius*radius, instead of Math.pow(radius,2). You may use either.</li>

  </ul></li>

 <li>Write a final statement that stores the total surface area into a variable. It will sum the two circle areas and the wall area.</li>

 <li>Print the resulting value of the surface area to the console.</li>

 <li>Call calcSurfaceArea from the main</li>

 <li>Write, compile and run your program until your output looks similar to image on the following page…</li>

</ol>




<strong> </strong>

<strong> </strong>

<strong>How to hand it in:  </strong>

Submit the single file with your finished <em>source</em> code (FirstAssignment.java –NOT FirstAssignment.class) to the CSC110 conneX site as an attachment in the Assignment 1 page.

<strong> </strong>