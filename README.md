Inpage
======

<h2>What is Inpage.js?</h2>
<p>
<b>Inpage.js</b> is a jQuery powered tool for dynamically generating links to key content in the current webpage being viewed, and for enabling the visitor to smoothly scroll to those elements when the Inpage link is clicked.
</p>

<br />
<hr />
<br />

<h2>What do I need to use Inpage.js?</h2>
<p>
<ul>
<li>jQuery</li>
<li>A basic knowledge of HTML</li>
<li>An HTML 5 page</li>
</ul>
</p>

<br />
<hr />
<br />

<h2>What browsers can run Inpage.js?</h2>
<p>
So far Inpage.js has been tested and works great on IE 7/8/9/10/11, Chrome, and Safari.
</p>

<br />
<hr />
<br />

<h2>How do I use Inpage.js?</h2>
<div>
<p>Very simply.  First just include the script file as shown:</p>
<code>&lt;script src=&quot;/js/inpage.js&quot;&gt;&lt;/script&gt;</code>
<p>Then create the wrappers for your menu as shown below.  You can place them anywhere on your page and can style them however you want with CSS (horizontal, vertical, etc.).  Just <strong>don't change the ID's of the elements shown below</strong></p>


<code>
&lt;div id=&#39;submenu_wrapper&#39;&gt;
	&lt;nav id=&quot;submenu&quot;&gt;
		&lt;ul id=&quot;submenulist&quot; &gt;&lt;/ul&gt;
    &lt;/nav&gt;
&lt;/div&gt;
</code>


<p>You may have observed that the "submenulist" UL element is empty.  It will be filled automatically by inpage.js when the page loads with links to any elements on the page with a "data-inpage" attribute.  Here's an example of a heading that has the tag:</p>
<p><code>&lt;h1 data-inpage=&quot;FAQ&quot;&gt;Frequently asked questions&lt;/h1&gt;</code></p>
<p>In our example the inpage.js generated menu would display a link with the text "FAQ" which would, when clicked, initiate a smooth scroll down to the chosen element</p>

<br />
<hr />
<br />

<div>
<p>And it's that easy.</p>
</div>

<div>
<h2>Stuff to add in the future</h2>
<p>
<ul>
<li>Scrolling speed customization</li>
<li>A blur effect option (maybe)</li>
</ul>
</p>
</div>