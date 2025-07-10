# Hirst-Panting-Python
<h2>To generate a grid of randomly colored dots using turtle graphics, simulating a modern art piece.</h2>

<h2><Modules Used:</h2>
<h3>turtle – For drawing the graphics (built-in)</h3>
<h3>random – For randomly selecting a color for each dot (built-in)</h3>

<h2>working of code:</h2>
<h3>setup:</h3>
<p>The screen color mode is set to RGB (0–255).<br>
A turtle is created, hidden, and moved to the starting position.</p>

<h3>Color List:</h3>
<p>A hardcoded list of 26 color tuples in RGB format.<br>
These were likely extracted from an image using the colorgram module.</p>

<h3>Dot Painting Logic:</h3>
<p>The turtle draws 100 dots in a 10×10 grid.</p>

<h3>For each dot:</h3>
<p>A random color is picked.<br>
A dot of size 10 is drawn.<br>
After 10 dots in a row, the turtle moves up and starts the next row from the left.</p>

