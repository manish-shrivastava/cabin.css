#Cabin CSS Framework

Cabin is a lean, modular and unobtrusive CSS framework. Cabin helps your projects get going quicker by eliminating the need for you to write basic CSS styles yourself.

##What does the core file cover?

The core <code>cabin.css</code> file is supposed to be as simple (yet supportive) as possible—perfect for smaller websites and applications. With this in mind, the core file <em>does not</em> include predefined styles for elements associated with forms,tables or grids as these are not always necessary. Adding support for these elements is incredibly easy thanks to Cabin's modular nature.

It also includes 3 basic menu presets:
<ul>
<li>Horizontal menu by adding <code>class="horizontal"</code> to your menu &lt;ul&gt;</li>
<li>Horizontal center aligned menu by adding <code>class="centered"</code> to your menu &lt;ul&gt;</li>
<li>Vertical menu by adding <code>class="vertical"</code> to your menu &lt;ul&gt;</li>
</ul>

Cabin makes it easy for you to keep CSS bloat at bay by providing a solid yet simple core file, with extension files providing additional styles that you can add when/if you need to. 

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
  &lt;link rel="stylesheet" href="css/cabin.css" /&gt;
  <span class="codecomment">&lt;!-- Cabin extension .css file --&gt;</span>
  &lt;link rel="stylesheet" href="css/reset.cabin.css" /&gt;
&lt;/head&gt;
</code></pre>

##Feedback &amp; Suggestions

Once you've had a crack at Cabin, let me know about it! Tweet [@adamwhitcroft](http://www.twitter.com/adamwhitcroft) with your feedback, 
suggestions or just to let me know you are using Cabin.

I welcome feedback and would love to hear if I have left out something you think should be
included in the next release or if I have made a terrible mistake somewhere (I am only human after all).