Download Link: https://assignmentchef.com/product/solved-csci1300-homework-1-algorithm-and-pseudocode
<br>
<h1></h1>

In your algorithms, <strong>use</strong>​<strong> indentation</strong> to show that a line in the algorithm is inside of a loop or a conditional.

For example:

<strong>if x equals y        output(x) </strong>

The line output(x) only executes if x equals y is true. As a result output(x) is indented under the if statement.​

Note: <strong><em> </em></strong>

<ol>

 <li>Please make sure that what you submit is not code in any language (cpp, python, etc).</li>

</ol>

Merely produce pseudocode using algorithm rules.

<ol start="2">

 <li>Examples of good pseudocode are found <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45682">her</a><u>​ </u><a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45682">e</a><a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45682">.</a><u>​</u></li>

 <li>Your work should be <strong>typed</strong>​ .​ Submit your assignment as a <strong>PDF</strong>​ to <a href="https://moodle.cs.colorado.edu/mod/assign/view.php?id=45657">Homewor</a>​ <a href="https://moodle.cs.colorado.edu/mod/assign/view.php?id=45657">k</a> <a href="https://moodle.cs.colorado.edu/mod/assign/view.php?id=45657">1</a> on Moodle.</li>

</ol>

<h1>Problem Set</h1>

<ol>

 <li>The​S. Census provides information about the current U.S. population as well as approximate rates of change. Using those rates and the current US population, write an algorithm to calculate the U.S. population in exactly one year (365 days).</li>

</ol>

Your algorithm should output the result of your calculations. Three rates of change are provided:

<ol>

 <li>There is a birth every 8 seconds</li>

 <li>There is a death every 12 seconds</li>

 <li>There is a new immigrant every 27 seconds</li>

</ol>

Current U.S. population: 328,441,687

<ol start="2">

 <li><strong> </strong>A​ day has 86,400 seconds (24⨉60⨉60). Given a number of seconds in the range of 0 to 1,000,000 seconds, output the time as days, hours, minutes, and seconds for a 24 ​ hour clock. For example, 70,000 seconds is 0 days, 19 hours, 26 minutes, and 40 seconds. Your program should have user input that is the number of seconds to convert, and then use that number in your calculations. If your results are W, X, Y, and Z, then your output should be displayed as : The time is W days, X hours, Y minutes, and Z seconds.</li>

 <li>The​ Zootopia Police Department is recruiting new officers and has come up with an innovative equation to hire. They define hireScore​ as a weighted sum of agility​ ,​ strength, and ​ speed​ .​ hireScore = 1.8 * ​ agility​ + 2.16 * ​ strength ​ +​24 * speed​</li>

</ol>

The candidate for this hiring season are foxes, bunnies, and sloths. Chief Bogo has requested you to write a program that takes in these attributes and process a higreScore​ for the candidate.

The program should provide a menu to choose the anthropomorphic animal. The menu should have the following options:

<ol>

 <li>Fox</li>

 <li>Bunny</li>

 <li>Sloth</li>

 <li>Quit</li>

</ol>

Once an animal is selected, the program should ask the two of the characteristics based on the animal

<ol>

 <li>For fox, take input for agility​ and ​     strength​</li>

 <li>For bunny, take input for agility​ and ​     speed​</li>

 <li>For Sloth, take input for strength​ and ​     speed​</li>

</ol>

Write an algorithm to compute the hireScore​ ​ based on the inputs using the weighted sum formula. When you compute the hireScore, the third characteristic would be 0. The computed hireScore​ should​ be displayed on the screen. The menu will run in a loop, continually offering Bogo four options until he chooses to quit.

<ul>

 <li><strong> </strong>A​ bank account has an initial deposit of $10,000. Every month $500 is withdrawn to meet college expenses. After the money is withdrawn, an interest is computed at the rate of 6 percent per annum (0.5 percent per month). This interest is compounded monthly. Write an algorithm to find how many years it takes for the account balance to become $0.</li>

</ul>

<em>Hint: </em>​Create a table with money that is getting compounded and the money that is withdrawn and calculate by hand what happens in the first 5 months. Then use the pattern to help you figure out the algorithm.

<ul>

 <li><strong> </strong>Make​ changes to the algorithm to ask the user to input the values for principal, rate and monthly expenditure. Is there a scenario where the algorithm will not terminate (maybe enter an infinite loop)? If so, make changes to the algorithm so that it always terminates.</li>

</ul>

<ol start="5">

 <li><strong> </strong>Write​ an algorithm that will ask the user to enter 10 characters. Letters ‘a’, ‘e’, ‘i’, ‘o’, ‘u’ in the English alphabet are vowels. The algorithm should then <strong>count</strong>​ and​<strong> display</strong> the total number of vowels among the 10 characters entered by the user.</li>

 <li><strong> </strong>In​ science, the temperature is always described in Celsius, but in the U.S. we tend to use Fahrenheit. Write an algorithm that takes user input for Fahrenheit and converts it into Celsius. The formula is:</li>

</ol>

<em>Celsius</em> = <u><sup>5</sup></u><sub>9</sub> (<em>Fahrenheit</em> − 32)

<ol start="7">

 <li><strong> </strong>Punith​ is a student in CSCI 1300 in this semester. He’s writing a program that prints “Hello​ 1300!”,​ but it’s not working well. Describe two compile-time errors and one run-time error and how to fix them. (<a href="https://moodle.cs.colorado.edu/pluginfile.php/203348/mod_assign/introattachment/0/hmwk1_debugging.cpp">The cpp file is available on Moodl</a>​ <a href="https://moodle.cs.colorado.edu/pluginfile.php/203348/mod_assign/introattachment/0/hmwk1_debugging.cpp">e</a><a href="https://moodle.cs.colorado.edu/pluginfile.php/203348/mod_assign/introattachment/0/hmwk1_debugging.cpp">.</a><u>​</u> Try to run it by yourself)</li>

</ol>