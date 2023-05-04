Download Link: https://assignmentchef.com/product/solved-cse-522-assignment4-part-2-design-patterns
<br>
<h1></h1>

One of the most important design patterns is the Observer pattern, also known as the Model-ViewController (MVC) pattern, first introduced in the Smalltalk programming language.  In this part of the assignment, you are asked to make use of the Observer pattern so as to achieve a modular interaction between a model and its viewers.




Posted on Piazza: ResourcesàAssignments is a file ObserverPatternExample.java which defines the following classes:




<ol>

 <li>The “observer” classes Table, BarChart, and PieChart.   The classes BarChart and PieChart extend a class Chart, which factors the commonalities between these two classes.   The code for these classes is given to you in their entirety except for their respective update()</li>

</ol>




<ol start="2">

 <li>The “observable” class Sales, which records and updates sales data for five regions, called North, South, Central, East, and West. The class is given in its entirety except for the code that notifies the observers.</li>

</ol>




<ol start="3">

 <li>The class ObserverPatternExample is the top-level class containing the main() You are required to define the main method fully.</li>

</ol>




Complete the definitions of the above classes and run the program.   The amount of coding is very small and much of it is similar to what was presented in Lecture 18.   A correct implementation would enable you to see the table, bar-chart, and pie-chart.