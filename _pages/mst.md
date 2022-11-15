---
layout: single
title: Mastodon
permalink: /mst/
---
<p>Hey there! This is a page to prove that I, Stefan Bocken, am the owner of the account <a rel="me" href="https://mastodon.social/@stefanbckn">https://mastodon.social/@stefanbckn</a>.</p>
<p align="center"><a href="https://www.bckn.be" class="btn btn--info">Click here to continue to my website, bckn.be</a></p>
<p align="center">This page will automatically redirect you in <span id="seconds">5</span> seconds.</p>
<p align="center">Hey daar! Dit is een pagina om te bewijzen dat ik, Stefan, eigenaar ben van de account <a rel="me" href="https://mastodon.social/@stefanbckn">https://mastodon.social/@stefanbckn</a>.</p>


<script type="text/javascript">
var seconds = 5; // seconds for HTML
var foo; // variable for clearInterval() function

function redirect() {
    document.location.href = 'https://www.bckn.be';
}

function updateSecs() {
    document.getElementById("seconds").innerHTML = seconds;
    seconds--;
    if (seconds == -1) {
        clearInterval(foo);
        redirect();
    }
}

function countdownTimer() {
    foo = setInterval(function () {
        updateSecs()
    }, 1000);
}

countdownTimer();
</script>