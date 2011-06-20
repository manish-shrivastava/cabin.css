#What is Cabin?
Cabin is a super lightweight extensible and expandable CSS framework focused on providing you with predefined and unobtrusive styles.

Cabin makes it easy for you to keep CSS bloat at bay by providing a solid yet simple core file, with extensions providing additional styles that you can add when/if you need them. 

The core cabin.css file has defined styles for:

<ul>
	<li>Body and a wrapper class</li>
	<li>Headings &mdash; h1, h2, h3, h4, h5, h6</li>
	<li>Paragraphs, incl. the following tags: <code>&lt;i&gt;, &lt;em&gt;, &lt;b&gt;, &lt;strong&gt;, &lt;strikethrough&gt;, &lt;small&gt;, &lt;acronym&gt;</code></li>
	<li>Blockquotes</li>
	<li>Code &amp; Pre</li>
	<li>Lists &mdash; ol, ul and dl</li>
	<li>3 Menus &mdash; horizontal, horizontal center aligned &amp; vertical</li>
</ul>

Need more style support? Not a problem, take a look at Cabin's extensions below.

##Cabin's extensions

Cabin is as powerful as you choose to make it. Adding extensions to your Cabin project couldn't be easier &mdash; simply add an additional stylesheet link in the <code>&lt;head&gt;</code> of your HTML document (see <i>How to use</i>).

<code>reset.cabin.css</code> &mdash; a small yet effective CSS reset file
<br/>
<code>grid12.cabin.css</code> &mdash; a 12 column grid, based on 960.gs which includes width based media queries
<br/>
<code>fluid-grid12.cabin.css</code> &mdash; a 12 column fully fluid grid, based 960.gs
<br/>
<code>grid16.cabin.css</code> &mdash; a 16 column grid, based on 960.gs which includes width based media queries
<br/>
<code>fluid-grid16.cabin.css</code> &mdash; a 16 column fully fluid grid, based 960.gs
<br/>
<code>tables.cabin.css</code> &mdash; basic styles for tables
<br/>
<code>forms.cabin.css</code> &mdash; basic styles for forms
<br/>
<code>m-query.cabin.css</code> &mdash; adds width based media queries to your project
<br/>
<code>debug.cabin.css</code> &mdash; a useful Log for debugging your project

##How to use

Download the <code>cabin.css</code> file and place it in your <code>/css</code> folder.

Open up your HTML document and add the following in the <code>&lt;head&gt;</code> section:
<code>&lt;head&gt;</code> section:
<pre><code>&lt;head&gt;
	&lt;!-- Cabin reset --&gt;
	&lt;link rel="stylesheet" href="/css/reset.cabin.css" type="text/css" /&gt;
	&lt;!-- Cabin core --&gt;
	&lt;link rel="stylesheet" href="/css/cabin.css" type="text/css" /&gt;
	&lt;!-- Cabin extension --&gt;
	&lt;link rel="stylesheet" href="/css/&lt;extension&gt;.cabin.css" type="text/css" /&gt;
&lt;/head&gt;
</code></pre>