HELLO! বন্ধুরা আস্সলামুআলাইকুম। ASP এর ওয়েবসাইট টা দেখে মনে হলো যদি ACP আর্মিদের জন্যও একটা ওয়েবসাইট বানাই তাহলে কেমন হয়? ACP এর প্রাইভেট গ্রুপ তো আছেই পাশাপাশি একটা ওয়েবসাইটের সুযোগ সুবিধাই আলাদা। তো, এখানে আমরা Upcoming Exam এর TIME,ASSIGNMENT,NOTES,CHECKBOX ফিল আপ ও দেখতে পারবো।
BUTTON:
<form action="https://facebook.com/groups/272368833896163/">
    <input type="submit" value="ACP-22 FACEBOOK GROUP" />
</form>
                                      
                                      LET'S START THE COUNTDOWN 



    REMAINING TIME TO START NEXT CHELLENGE...
    

<html> 
<head> 
<style> 
p { 
  text-align: center; 
  font-size: 20px; 
  font-colour:red
} 
</style> 
</head> 
<body> 
<p id="demo"></p> 
<script> 
var deadline = new Date("Feb 7, 2021 11:00:00").getTime(); 
var x = setInterval(function() { 
var now = new Date().getTime(); 
var t = deadline - now; 
var days = Math.floor(t / (1000 * 60 * 60 * 24)); 
var hours = Math.floor((t%(1000 * 60 * 60 * 24))/(1000 * 60 * 60)); 
var minutes = Math.floor((t % (1000 * 60 * 60)) / (1000 * 60)); 
var seconds = Math.floor((t % (1000 * 60)) / 1000); 
document.getElementById("demo").innerHTML = days + "d "  
+ hours + "h " + minutes + "m " + seconds + "s "; 
    if (t < 0) { 
        clearInterval(x); 
        document.getElementById("demo").innerHTML = "EXPIRED"; 
    } 
}, 1000); 
</script> 
  
</body> 
</html> 

Routine:
<form action="https://docs.google.com/spreadsheets/d/1L-sQ5AE6sxePEgZII7Rybxp-dsJdYfmqhm3Lf4FqhtA/edit?usp=drivesdk/">
<input type="submit" value="BATCH22-ROUTINE" />
</form>

upcoming:Play list,Checkbox,Assignment,Notes
Colors are not developed.



© goes to MIAH MOHAMMED AMAN(batch-22)--😍


<        <span class="bottom-back">
          <span>0</span>
        </span>          
      </div>

      <div class="figure sec sec-2">
        <span class="top">0</span>
        <span class="top-back">
          <span>0</span>
        </span>
        <span class="bottom">0</span>
        <span class="bottom-back">
          <span>0</span>
        </span>
      </div>
    </div>
  </div>
</div>



top cycle" the function stopCycle(), which start and stop the timer respectiveley.

The timer executes function changeColor which was designed to see which colour the "indicator" paragraph was showing, therefore recolouring the "title" division to the next colour in the list.

I guess I could have detected the actual colour of the "title" division instead of creating a new paragraph. That and a whole bunch of stuff I could have improved.

I even bet that I have done many wrong things here.

Thanks in advance for sparing your time!

UPDATE: I finally got it to work. view full code here:

<button type="button" onclick="startCycle()">Start/Resume cycle</button>
<button type="button" onclick="stopCycle()">Stop cycle</button>
<div id="title">Colormatic!</div>
It is currently
<span id="indicator">blue</span>

<script>

var timerId;

var ind = document.getElementById("indicator");
var tit = document.getElementById("title");
var color = ["red"]

function startCycle() {
    timerId = setInterval(changeColor, 500);
}

function stopCycle() {
    clearInterval(timerId);
    timerId = null;
}

function changeColor() {
    if (ind.innerHTML == 'blue') {
        tit.style.color = 'green';
        ind.innerHTML = 'green';
    }

    else if (ind.innerHTML == "green") {
        tit.style.color = 'yellow';
        ind.innerHTML = "yellow";
    }

    else {
        tit.style.color = 'blue';
        ind.innerHTML = "blue";
    }
}

</script>

<body style="background-color:#FF0000;">
</body>











 











  







