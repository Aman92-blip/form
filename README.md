HELLO! বন্ধুরা আস্সলামুআলাইকুম। ASP এর ওয়েবসাইট টা দেখে মনে হলো যদি ACP আর্মিদের জন্যও একটা ওয়েবসাইট বানাই তাহলে কেমন হয়? ACP এর প্রাইভেট গ্রুপ তো আছেই পাশাপাশি একটা ওয়েবসাইটের সুযোগ সুবিধাই আলাদা। তো, এখানে আমরা Upcoming Exam এর TIME,ASSIGNMENT,NOTES,CHECKBOX ফিো আপ ও দেখতে পারবো।
BUTTON:
<form action="https://facebook.com/groups/272368833896163/">
    <input type="submit" value="Go to Google" />
</form>
                                      
                                      LET'S START THE COUNTDOWN 
                                      (function () {
  const second = 1000,
        minute = second * 60,
        hour = minute * 60,
        day = hour * 24;

  let birthday = "Sep 30, 2021 00:00:00",
      countDown = new Date(birthday).getTime(),
      x = setInterval(function() {    

        let now = new Date().getTime(),
            distance = countDown - now;

        document.getElementById("days").innerText = Math.floor(distance / (day)),
          document.getElementById("hours").innerText = Math.floor((distance % (day)) / (hour)),
          document.getElementById("minutes").innerText = Math.floor((distance % (hour)) / (minute)),
          document.getElementById("seconds").innerText = Math.floor((distance % (minute)) / second);

        //do something later when date is reached
        if (distance < 0) {
          let headline = document.getElementById("headline"),
              countdown = document.getElementById("countdown"),
              content = document.getElementById("content");

          headline.innerText = "It's my birthday!";
          countdown.style.display = "none";
          content.style.display = "block";

          clearInterval(x);
        }
        //seconds
      }, 0)
  }());





















 











  







