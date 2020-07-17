# prevent-by-JS-in-Website

# This code for prevent right click in website using JS

 <script language="javascript" type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script><br/>
<script type="text/javascript" language="javascript"><br/>
$(function() {<br/>
  $(this).bind("contextmenu", function(e) {<br/>
    e.preventDefault();<br/>
  });<br/>
}); <br/>
</script><br/>

# This code for prevent F12 in website using JS

<script src="http://sibeeshpassion.com/content/scripts/jquery-1.11.1.min.js"></script><br/>
<script>  <br/>
document.onkeypress = function (event) {  <br/>
event = (event || window.event);  <br/>
if (event.keyCode == 123) {  <br/>
return false;  <br/>
}  <br/>
}  <br/>
document.onmousedown = function (event) {  <br/>
event = (event || window.event);  <br/>
if (event.keyCode == 123) {  <br/>
return false; <br/> 
}  <br/>
}  <br/>
document.onkeydown = function (event) {  <br/>
event = (event || window.event);  <br/>
if (event.keyCode == 123) {  <br/>
return false;  <br/>
}  <br/>
}  <br/>
</script>  <br/>
