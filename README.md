#Cabin CSS Framework

Cabin is a lean, modular and unobtrusive CSS framework. Cabin helps your projects get going quicker by eliminating the need for you to write basic CSS styles yourself.

##What's in the core file?

The core <code>cabin.css</code> file is supposed to be as simple (yet supportive) as possible—perfect for smaller websites and applications. 

###What is covered

<code>html, body, .wrapper, .left, .right, .nomargin, .box, .cf, h1, h2, h3, h4, h5, h6, p, q, i, em, cite, b, strong, s, del, mark, abbr, small, hr, blockqupte, a, code, pre, .codecomment, ::selection, ul, ol, dl, img, embed, object, video</code>

It also includes 3 basic menu styles:
<ul>
<li>Horizontal menu by adding <code>class="horizontal"</code> to your menu &lt;ul&gt;</li>
<li>Horizontal center aligned menu by adding <code>class="centered"</code> to your menu &lt;ul&gt;</li>
<li>Vertical menu by adding <code>class="vertical"</code> to your menu &lt;ul&gt;</li>
</ul>

###What isn't covered

The core file does not include predefined styles for elements associated with:

<ul>
<li>forms</li>
<li>tables</li>
</ul>

Grids have now been completely removed from Cabin as there are much better systems available.

##Cabin's extensions

Cabin's extension CSS files allow you to add additional predefined styles to the framework as you need them. Inclusion in your project is as simple as downloading the desired CSS file and including it in your project. There are 2 easy ways of going about this, the first uses @import found at the top of the cabin.css file

<pre><code>@charset "UTF-8";
@import url("reset.cabin.css");
/*==================================================*/
/*  Cabin CSS Framework by Adam Whitcroft           */
/*  hello[at]adamwhitcroft[dot]com                  */
/*  @adamwhitcroft                                  */
/*==================================================*/
</code></pre>

Or if you prefer, you can add a <code>&lt;link /&gt;</code> inside the <code>&lt;head&gt;</code> of your page <strong>after</strong> the core <code>cabin.css</code> link.

<pre><code>&lt;!DOCTYPE html&gt;
&lt;head&gt;
  &lt;title&gt;Let's hug kittens!&lt;title&gt;
  <span class="codecomment">&lt;!-- Core Cabin .css file --&gt;</span>
  &lt;link rel="stylesheet" href="cabin.css" /&gt;
  <span class="codecomment">&lt;!-- Cabin extension .css file --&gt;</span>
  &lt;link rel="stylesheet" href="reset.cabin.css" /&gt;
&lt;/head&gt;
</code></pre>

##Feedback &amp; Suggestions

Cabin CSS Framework and it's extensions are available to you freely on an "as is" basis. This means you can use it when you like, where you like and how you like without fear of reprimand. Neat huh?

All I ask is that if you do choose Cabin let me know—it would make me a happy chappy. Tweet [@adamwhitcroft](http://www.twitter.com/adamwhitcroft) with your feedback, suggestions or just to let me know how you've gotten on with it.