Download Link: https://assignmentchef.com/product/solved-ct5132-ct5148-lab-week-01
<br>






<ol>

 <li>Have you installed Anaconda (or a different method of Python installation, if you are confident)?</li>

 <li>Are you able to run Python code in the following scenarios?</li>

</ol>

<ul>

 <li>Spyder</li>

 <li>Jupyter Notebook</li>

 <li>IPython</li>

 <li>Command-line (Powershell, Terminal, …)</li>

</ul>

<ol start="3">

 <li>In the <strong>Grid Driving </strong>notebook, we have <em>doctests </em>for <sub>simulate() </sub>and plan(). Can you run the doctests and observe that they fail?</li>

 <li>Let’s work on <sub>simulate()</sub>. We need to track <em>how many </em>cells have been visited. But to do that, we need to track <em><sub>which </sub></em>cells have been visited. Why? What data structure might we use to track <em><sub>which </sub></em>cells have been visited? Why? Write out a complete implementation for <sub>simulate()</sub>. When you think you have it right, try the doctests.</li>

 <li>Write an extra function <sub>draw </sub>which outputs a simple text-based diagram of the cells visited by a car. Hint: the following code shows how to create an <em><sub>empty </sub></em>city grid <sub>g </sub>and then “visit” a particular cell, and then print the grid. Don’t worry if you don’t understand it all yet.</li>

</ol>

xsize = 10 ysize = 10 g = [[0 <strong>for </strong>_ <strong>in </strong>range(xsize)] <strong>for </strong>_ <strong>in </strong>range(ysize)] g[4][6] = 1

<strong>for </strong>line <strong>in </strong>reversed(g): print(line)

<ol start="6">

 <li>Write out an implementation of <sub>plan()</sub>, check it with the doctests, and feed its output to draw() and to simulate().</li>

</ol>

1