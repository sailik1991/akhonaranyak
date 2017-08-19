---
layout: post
title:  "Gratitude To Our Readers For Making Our Exhibition a Success"
date:   2017-08-08 16:30:00
categories: activities
---

Thank you for joining us and making the event a huge success! We were glad to have press and media coverage from reputed media houses:

Video summarizing the event by [Calcalling](https://www.youtube.com/watch?v=EHrfh34fd6k).

Article in [Sholoana Bangaliana](http://sholoanabangaliana.in/blog/2017/08/02/photography-exhibition-on-international-tiger-day-organized-an-initiative-of-akhon-aranyak/) that backs our initiative to create awareness on International Tiger Day.

<p id="open"></p>
<script>
// Set the date we're counting down to
var countDownDate = new Date("Sep 5, 2017 23:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get todays date and time
  var now = new Date().getTime();

  // Find the distance between now an the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("open").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("open").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

