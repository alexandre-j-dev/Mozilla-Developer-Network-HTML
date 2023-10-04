<span><i>Return to the previous</i> <a href="https://github.com/alexandre-j-dev/Mozilla-Developer-Network-HTML/tree/main/Projects_%20Marking%20up%20a%20letter"> README</a></span>

<h1> Project brief </h1>

<p>For this project, your task is to mark up a letter that needs to be hosted on a university intranet. The letter is a response from a research fellow to a prospective PhD student concerning their application to the university.</p>

<strong>Skills learned (used):</strong>
<ul>
<li>!DOCTYPE, lang, meta tags, utf-8, author, name, content </li>
<li>Using semantic heading</li>
<li>Unordered list and ordered list</li>
<li>Description lists</li>
<li>&lt;address&gt; element</li>
<li>&lt;pre&gt; element</li>
<li>Markup appropriate words with strong and emphasis</li>
<li>Semantically machine-readable dates with &lt;time&gt;</li>
<li>&lt;abbr&gt; element for abbreviations and acronyms</li> 
<li>Subscript and superscript on text</li>
<li>Create hyperlinks</li>
<li>Good pratices on link names</li>  
<li>&lt;cite&gt; element for quotes</li>
</ul>

<h2> Starting point: </h2>

<p>Create a new .html file using your text editor of preference or use an online tool, them copy the <a href="https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/marking-up-a-letter-start/letter-text.txt">raw text</a> for the project and link with the <a href="https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/marking-up-a-letter-start/css.txt">stylesheet</a>.</p>


<h2> Requirements: </h2>

<h3> Block/structural semantics </h3>

<ul>
<li>Use appropriate document structure including doctype, and &lt;html&gt;, &lt;head&gt; and &lt;body&gt; elements.</li>
<li>In general, the letter should be marked up as an organization of headings and paragraphs, with the following exception. There is one top level heading (the "Re:" line) and three second level headings.</li>
<li>Use an appropriate list type to mark up the semester start dates, study subjects, and exotic dances.</li>
<li>Put the two addresses inside &lt;address&gt; elements. Each line of the address should sit on a new line, but not be in a new paragraph.</li>
</ul>

<h3>Inline semantics</h3>

<ul>
<li>The names of the sender and receiver (and Tel and Email) should be marked up with strong importance.</li>
<li>The four dates in the document should have appropriate elements containing machine-readable dates.</li>
<li>The first address and first date in the letter should have a class attribute value of sender-column. The CSS you'll add later will cause these to be right aligned, as it should be in the case in a classic letter layout.</li>
<li>Mark up the following five acronyms/abbreviations in the main text of the letter — "PhD," "HTML," "CSS," "BC," and "Esq." — to provide expansions of each one.</li>
<li>The six sub/superscripts should be marked up appropriately — in the chemical formulae, and the numbers 103 and 104 (they should be 10 to the power of 3 and 4, respectively).</li>
<li>Try to mark up at least two appropriate words in the text with strong importance/emphasis.</li>
<li>There are two places where the letter should have a hyperlink. Add appropriate links with titles. For the location that the links point to, you may use http://example.com as the URL.</li>
<li>Mark up the university motto quote and citation with appropriate elements.</li>
</ul>


<h2>Hints and tips</h2>

<ul>
<li>Use the W3C HTML Checker to validate your HTML and to catch unintended mistakes.</li>
<li>You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside the HTML document.</li>
</ul>

Example:
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter/letter-update.png"> Marking up a letter (done) </a>

Validator:
<a href="https://validator.w3.org">W3C HTML Checker</a>  <br><hr>
  
<strong>See it below</strong><br>
<a href="https://htmlpreview.github.io/?https://github.com/alexandre-j-dev/Mozilla-Developer-Network-HTML/blob/HTML/Projects_%20Marking%20up%20a%20letter/index.html"> Render </a><br>

<strong>MDN conclusion projects</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter"> Marking up a letter </a>

<strong>Assessment on Mozilla Discourse</strong><br>
<a href="https://discourse.mozilla.org/t/assessment-wanted-for-html-marking-up-a-letter-exercise/106851/2">Link to assessment </a>
