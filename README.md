# prevent-by-JS-in-Website

# This code for prevent right click in website using JS

 <script language="javascript" type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
<script type="text/javascript" language="javascript">
$(function() {
  $(this).bind("contextmenu", function(e) {
    e.preventDefault();
  });
}); 
</script>

# This code for prevent F12 in website using JS

<script src="http://sibeeshpassion.com/content/scripts/jquery-1.11.1.min.js"></script>
<script>  
document.onkeypress = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
document.onmousedown = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
document.onkeydown = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
</script>  
