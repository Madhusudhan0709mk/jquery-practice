<h1>j Query Notes</h1>

What is jQuery?
jQuery is a lightweight, "write less, do more", JavaScript library.

<h4>Features of jQuery</h4>
<br>
<p>
The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities
</p>
<h4>Companies use jQuery</h4>

<h1>Starting with jQuery</h1>

<p>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js">
</script>
Add this in html head section
</head>
</p>

<h3>jQuery Syntax</h3>
<p>
Basic syntax is: $(selector).action()

A $ sign to define/access jQuery
A (selector) to "query (or find)" HTML elements
A jQuery action() to be performed on the element(s)
Examples:

$(this).hide() - hides the current element.

$("p").hide() - hides all <p> elements.

$(".test").hide() - hides all elements with class="test".

$("#test").hide() - hides the element with id="test".
</p>

<h2>Document Ready Event</h2>

<div>
 jQuery methods in our examples, are inside a document ready event:

    $(document).ready(function(){

    });
</div>

<h2> element selector</h2>


    $(document).ready(function(){
    $("button").click(function(){
        $("p").hide();
    });
        });
