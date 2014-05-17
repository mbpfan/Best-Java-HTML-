Best-Java-HTML-
===============

Java HTML 
<!DOCTYPE html>
<html lang="en">
<head>
<style>
body { background-color: Darkgray; }
p { color: white; }
</style>
<meta charset="utf-8" />
<title>Second edit</title>
<meta name="generator" content="BBEdit 10.1" />
<style>
p { padding-left: 45px; border: 1px solid black; }
h2 { padding-top: 80px; border: 1px solid black; }
ul { padding: 25px; border: 1px solid black; }
</style>
</head>
<body>
<input type="button" onClick="alert('Hey, remember to tell your friends about Quackit.com!');" value="Click Me!" />
<h2>Internal CSS</h2>
<p>This page uses internal CSS.  Using the style tag we are able to modify
the appearance of HTML elements.</p>
<p> Cheek out my favorite HTML website. <a href="http://www.w3schools.com"> Visit W3Schools.com!</a></p>
<p align="center"><a href="http://www.tizag.com/" target="_blank" >Tizag Home</a></p>
<p>Java script below.</p>
<script type="text/javascript">
<!--
document.write("<i>Java script goes here.</i>");HTML Quiz
//-->
</script>
<hr>
<p style="background: blue; color: white;">A new background and
 font color with inline CSS</p>
 <pre>
Roses are Red,
     Violets are blue,
I may sound crazy,
     But I love you!
</pre><hr>
<em>Emphasized text</em><br />
<strong>Strong text</strong><br />
<dfn>Definition term</dfn><br />
<code>Computer code text</code><br />
<samp>Sample computer code text</samp><br />
<kbd>Keyboard text</kbd><br />
<var>Variable</var><br />
<cite>Citation</cite> 
<code><a href="http://www.html.net/">Here is a link to HTML.net</a></code>
<hr>
<p style="font-size:20px;">This is typed in size 20px</p>
<p style="font-family:courier;">This is typed in Courier</p>
<hr>
<p style="color:green;">Green Java script text below.</p>
<script type="text/javascript">
var c=0;
var t;
var timer_is_on=0;
function timedCount()
{
document.getElementById('txt').value=c;
c=c+1;
t=setTimeout("timedCount()",1000);
}

function doTimer()
{
if (!timer_is_on)
{
timer_is_on=1;
  timedCount();
}
}
</script> 
<form>
<input type="button" value="Start count!" onClick="doTimer()">
<input type="text" id="txt">
</form>
<p>Click on the button above. The input field will count forever, starting at 0.</p>
<div style="color:#00FF00">
<h3>This is a heading</h3>
<p>This is a paragraph.</p>
</div>
<h2>CSS Padding</h2>
<p>The header has a top padding of 45px and this paragraph has a padding-left of 80px.  This gives
a nice indendation to the paragraph.</p>
<ul>
<li>This list has a uniform</li>
<li>25 pixel margin</li>
<li>Padding is useful for creating necessary white space.</li>
</ul>
</body>
</html>

