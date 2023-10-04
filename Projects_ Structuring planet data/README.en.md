<span><i>Return to the previous</i> <a href="https://github.com/alexandre-j-dev/MDN-Mozilla-Developer-Network/tree/HTML/Projects_%20Structuring%20planet%20data"> README</a></span>

<h1> Project brief </h1>

<p>You are working at a school; currently your students are studying the planets of our solar system, and you want to provide them with an easy-to-follow set of data to look up facts and figures about the planets. An HTML data table would be ideal — you need to take the raw data you have available and turn it into a table, following the steps below.</p>

<strong>Skills learned (used):</strong>
<ul>
<li>Creating HTML Tables</li>
<li>Semantics and structuring properly Tables</li>
<li>Associating columns and rows data with scope, id and headers atributes</li>
<li>Adding captions to tables with &lt;caption&gt; element</li>
<li>Adding styles to tables using &lt;colgroup&gt; element and CSS</li>
</ul>

<h2> Starting point: </h2>
<p>To start the project, make local copies of <a href="https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/blank-template.html"> blank-template.html </a> <a href="https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/minimal-table.css"> minimal-table.css </a> and <a href="https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/planets-data.txt"> planets-data.txt </a>  in a new directory in your local computer. </p>


<h2> Requirements: </h2> 

<p>The following steps describe what you need to do to complete the table example. All the data you'll need is contained in the planets-data.txt file. If you have trouble visualizing the data, look at the live example below, or try drawing a diagram.</p>

<ol> 
<li>Open your copy of blank-template.html, and start the table off by giving it an outer container, a table header, and a table body. You don't need a table footer for this example.</li>
<li>Add a row to the table header containing all the column headers.</li>
<li>Create all the content rows inside the table body, remembering to make all the row headings into headings semantically.</li>
<li>Ensure all the content is placed into the right cells — in the raw data, each row of planet data is shown next to its associated planet.</li>
<li>Add attributes to make the row and column headers unambiguously associated with the rows, columns, or rowgroups that they act as headings for.</li>
<li>Add a black border just around the column that contains all the planet name row headers.</li>
</ol>


<h2>Hints and tips</h2>
<ul>
<li>Use the W3C HTML Checker to validate your HTML and to catch unintended mistakes.</li>
<li>You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside the HTML document.</li>
<li>The first cell of the header row needs to be blank, and span two columns.</li>
<li>The group row headings (e.g. Jovian planets) that sit to the left of the planet name row headings (e.g. Saturn) are a little tricky to sort out — you need to make sure each one spans the correct number of rows and columns.</li>
<li>One way of associating headers with their rows/columns is a lot easier than the other way.</li>
</ul>

Example:
<a href="https://mdn.github.io/learning-area/html/tables/assessment-finished/planets-data.html"> 
Structuring planet data (done) </a>


Validator:
<a href="https://validator.w3.org">W3C HTML Checker</a>  <br><hr>
  
<strong>See it below</strong><br>
<a href="https://htmlpreview.github.io/?https://github.com/alexandre-j-dev/MDN-Mozilla-Developer-Network/blob/HTML/Projects_%20Structuring%20planet%20data/index.html"> Render </a><br>

<strong>MDN conclusion projects</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data"> Structuring planet data </a>

<strong>Assessment on Mozilla Discourse</strong><br>
<a href="">Link to assessment </a>
