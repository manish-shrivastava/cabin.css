#What is Cabin?

Cabin is a super lean, super modular CSS framework focused on providing you with unobtrusive predefined styles, perfect to help you get
the nitty gritty out the way when starting a new project.

The core cabin.css file includes an <b>almighty</b> reset and has predefined styles for:
<code>html, body, .wrapper, .clear, .h1, .h2, .h3, .h4, .h5, .h6, p, .nomargin, .center, i, em, cite, b, strong, del, small, a, a:hover, blockquote, cite, pre, code, .codecomment, ::selection, hr, ul, ol, ul ul, ul ol, ol ol, ol ul, li, dl, dt, dd, #logo, img</code>

It also includes 3 basic menu presets:
<ul>
<li>Horizontal menu by adding <code>class="nav-hor"</code> to your menu &lt;ul&gt;</li>
<li>Horizontal center aligned menu by adding <code>class="nav-cen"</code> to your menu &lt;ul&gt;</li>
<li>Vertical menu by adding <code>class="nav-ver"</code> to your menu &lt;ul&gt;</li>
</ul>

Do you need predefined styles outside of the ones covered by the core cabin.css file? Cabin makes it easy for you to keep CSS bloat at bay by providing a solid yet simple core file, with extension files providing additional styles that you can add when/if you need to. 

##Cabin's extensions

Adding extensions to your Cabin project couldn't be easier &mdash; simply add an additional stylesheet link in the <code>&lt;head&gt;</code> of your HTML document (see <b>How to use</b>). Additional extensions are in the works.


###12 column grid
This extensions adds support for a 12 column 960px wide grid based on the wildly popular 960gs. The extensions also features width based media queries which will resize the grids according to thewidth of the viewing screen.

[View grid12.cabin.css](https://github.com/Cabincss/Cabin-Extensions/tree/master/12%20Col)

###16 column grid
This extensions adds support for a 16 column 960px wide grid based on the wildly popular 960gs.
The extensions also features width based media queries which will resize the grids according to the
width of the viewing screen.

[View grid16.cabin.css](https://github.com/Cabincss/Cabin-Extensions/tree/master/16%20Col)

###Forms
This extensions adds support for basic forms. It has predefined styles for <code>fieldset, labels, inputs, textareas, .button</code> and includes some styles for useful form-related messages:

[View forms.cabin.css](https://github.com/Cabincss/Cabin-Extensions/tree/master/Forms)

###Tables
This extension adds support for basic tables. It has predefined styles for <code>table, th, td, colspan, rowspan</code>

[View tables.cabin.css](https://github.com/Cabincss/Cabin-Extensions/tree/master/Tables)

###Debugging
This extension has some pretty nifty features. It checks the links and images in your page for common errors and outlines them for you. <b>Note:</b> ONLY use this extension if your project is set to offline or you are developing locally.

[View debug.cabin.css](https://github.com/Cabincss/Cabin-Extensions/tree/master/Debug)

##How to use

Open up your HTML document and add the following in the <code>&lt;head&gt;</code> section:
<pre><code>&lt;head&gt;
	&lt;!-- Cabin core --&gt;
	&lt;link rel="stylesheet" href="/css/cabin.css" type="text/css" /&gt;
	&lt;!-- Cabin extension --&gt;
	&lt;link rel="stylesheet" href="/css/&lt;extension&gt;.cabin.css" type="text/css" /&gt;
&lt;/head&gt;
</code></pre>

##Feedback &amp; Suggestions

Once you've had a crack at Cabin, let me know about it! Tweet [@adamwhitcroft](http://www.twitter.com/adamwhitcroft) with your feedback, 
suggestions or just to let me know you are using Cabin.

I welcome feedback and would love to hear if I have left out something you think should be
included in the next release or if I have made a terrible mistake somewhere (I am only human after all).