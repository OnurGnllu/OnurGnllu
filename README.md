### Hi there 👋

$('#go').click(function(event){
var email =  $('#email').val();
if(email)
window.location.href = 'https://mail.google.com/mail/?view=cm&fs=1&to='+email;
else
alert('please enter your email');
})
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<span>Please Enter Your Email And Go</span>
<br />
<input id="onur95rt@gmail.com" />

<button id="go">Go!</button>
