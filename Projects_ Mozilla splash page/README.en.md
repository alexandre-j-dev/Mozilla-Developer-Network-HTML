<span><i>Return to the previous</i> <a href="https://github.com/alexandre-j-dev/Mozilla-Developer-Network-HTML/tree/main/Projects_%20Mozilla%20splash%20page"> README</a></span>

<h1> Project brief </h1>

<p>In this assessment we have a mostly-finished Mozilla splash page, which aims to say something nice and interesting about what Mozilla stands for, and provide some links to further resources. Unfortunately, no images or video have been added yet — this is your job! You need to add some media to make the page look nice and make more sense. The following subsections detail what you need to do:</p>

<strong>Skills learned (used):</strong>
<ul>
<li>Responsive images</li>
<li>Resolution switching and Art direction problems</li>
<li>Raster and vector (svg) images</li>
<li>scrset e sizes atributes</li>
<li>&lt;picture&gt; element</li>
<li>Minimizing bandwidth consumption on images</li>
</ul>

<h2> Starting point: </h2>
<p>To start off this assessment, you need to grab the HTML and all the images available in the <a href="https://github.com/mdn/learning-area/tree/main/html/multimedia-and-embedding/mdn-splash-page-start"> mdn-splash-page-start </a> directory on github. Save the contents of <a href="https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/mdn-splash-page-start/index.html"> index.html </a>  in a file called index.html on your local drive, in a new directory. Then save <a href="https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/mdn-splash-page-start/pattern.png"> pattern.png </a> in the same directory (right click on the image to get an option to save it.)</p>

<p>Access the different images in the <a href="https://github.com/mdn/learning-area/tree/main/html/multimedia-and-embedding/mdn-splash-page-start/originals"> originals </a> directory and save them in the same way; you'll want to save them in a different directory for now, as you'll need to manipulate (some of) them using a graphics editor before they're ready to be used.</p>


<h2> Requirements: </h2>

<h3> Preparing images </h3>

<p>Using your favorite image editor, create 400px wide and 120px wide versions of:</p>

<ul> 
<li>firefox_logo-only_RGB.png</li>
<li>firefox-addons.jpg</li>
<li>mozilla-dinosaur-head.png</li>
</ul>

<p>Call them something sensible, e.g. firefoxlogo400.png and firefoxlogo120.png</p>
<p>Along with mdn.svg, these images will be your icons to link to further resources, inside the further-info area. You'll also link to the Firefox logo in the site header. Save copies of all these inside the same directory as index.html.</p>
<p>Next, create a 1200px wide landscape version of red-panda.jpg, and a 600px wide portrait version that shows the panda in more of a close up shot. Again, call them something sensible so you can easily identify them. Save a copy of both of these inside the same directory as index.html.</p>
<p>You should optimize your JPG and PNG images to make them as small as possible, while still looking OK. tinypng.com is a great service for doing this easily.</p>


<h3>Adding a logo to the header</h3>

<p>Inside the &lt;header&gt; element, add an &lt;img&gt; element that will embed the small version of the Firefox logo in the header.</p>

<h3>Adding a video to the main article content</h3>

<p>Just inside the &lt;article&gt; element (right below the opening tag), embed the YouTube video found at <a href="https://www.youtube.com/watch?v=ojcNcvb1olg">https://www.youtube.com/watch?v=ojcNcvb1olg</a>, using the appropriate YouTube tools to generate the code. The video should be 400px wide.</p>


<h3>Adding responsive images to the further info links</h3>

<p>Inside the &lt;div&gt; with the class of further-info you will find four &lt;a&gt; elements — each one linking to an interesting Mozilla-related page. To complete this section you'll need to insert an &lt;img&gt; element inside each one containing appropriate src, alt, srcset and sizes attributes.</p>
<p>In each case (except one — which one is inherently responsive?) we want the browser to serve the 120px wide version when the viewport width is 500px wide or less, or the 400px wide version otherwise.</p>
<p>Make sure you match the correct images with the correct links!</p>

<h3>Art direction of red panda</h3>

<p>Inside the &lt;div&gt; with the class of red-panda, we want to insert a &lt;picture&gt; element that serves the small portrait panda image if the viewport is 600px wide or less, and the large landscape image otherwise.</p>



<h2>Hints and tips</h2>
<ul>
<li>Use the W3C HTML Checker to validate your HTML and to catch unintended mistakes.</li>
<li>You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside the HTML document.</li>
</ul>

Example:
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page/wide-shot.png"> Mozilla splash page (done) </a></li> 
<li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page/narrow-shot.png"> Narrow ver. </a></li>
</ul>

Validator:
<a href="https://validator.w3.org">W3C HTML Checker</a>  <br><hr>

  
<strong>See it below</strong><br>
<a href="https://htmlpreview.github.io/?https://github.com/alexandre-j-dev/Mozilla-Developer-Network-HTML/blob/main/Projects_%20Mozilla%20splash%20page/index.html"> Render </a><br>

<strong>MDN conclusion projects</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page#starting_point"> Mozilla splash page </a>

<strong>Assessment on Mozilla Discourse</strong><br>
<a href="https://discourse.mozilla.org/t/assessment-wanted-for-html-marking-up-a-letter-exercise/106851/2">Link to assessment </a>
