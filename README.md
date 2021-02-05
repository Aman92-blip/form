HELLO! বন্ধুরা আস্সলামুআলাইকুম। ASP এর ওয়েবসাইট টা দেখে মনে হলো যদি ACP আর্মিদের জন্যও একটা ওয়েবসাইট বানাই তাহলে কেমন হয়? ACP এর প্রাইভেট গ্রুপ তো আছেই পাশাপাশি একটা ওয়েবসাইটের সুযোগ সুবিধাই আলাদা। তো, এখানে আমরা Upcoming Exam এর TIME,ASSIGNMENT,NOTES,CHECKBOX ফিো আপ ও দেখতে পারবো।









<html>
<head>
<title>Countdown</title>
<script type="text/javascript">
 // set minutes
var mins = 1;

 // calculate the seconds (don't change this! unless time progresses at a         different speed for you...)
var secs = mins * 60;
var timeout;

function countdown() {
  timeout = setTimeout('Decrement()', 1000);
}

function Decrement() {
  if (document.getElementById) {
    minutes = document.getElementById("minutes");
    seconds = document.getElementById("seconds");
    // if less than a minute remaining
    if (seconds < 59) {
      seconds.value = secs;
    } else {
      minutes.value = getminutes();
      seconds.value = getseconds();
    }
    secs--;
    if (secs < 0) {
      clearTimeout(timeout);
      return;
    }
    countdown();
  }
}

function getminutes() {
  // minutes is seconds divided by 60, rounded down
  mins = Math.floor(secs / 60);
  return ("0" + mins).substr(-2);
}

function getseconds() {
  // take mins remaining (as seconds) away from total seconds remaining
  return ("0" + (secs - Math.round(mins * 60))).substr(-2);
}

</script>
</head>
<body>

<div id="timer">
This is only valid for the next <input id="minutes" type="text"   style="width: 60px; border: none; background-color:none; font-size: 50px; font-weight: bold;"> : <input id="seconds" type="text" style="width: 60px; border: none; background-color:none; font-size: 50px; font-weight: bold;"> 
 </div>
<script>
countdown();
</script>

FB GROUP:<!DOCTYPE HTML> 
<html> 
<head>  
<title> 
example of onclick button
</title> 
<script> 
function welcome() { 
window.open(https://facebook.com/groups/272368833896163/");
} 
</script> 
</head> 
<body style = "text-align:center"> 
<button onclick="welcome()"> Welcome to our website </button>         
</body> 
</html>

BUTTON:<button onclick="https://facebook.com/groups/272368833896163/">Continue</button>

BUTTON:
<form action="https://facebook.com/groups/272368833896163/">
    <input type="submit" value="Go to Google" />
</form>


<!DOCTYPE HTML>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
p {
  text-align: center;
  font-size: 60px;
  margin-top: 0px;
}
</style>
</head>
<body>

<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Feb 7, 2021 11:13:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

</body>
</html>
 











  







