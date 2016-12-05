---
layout: page
title: Flair and Badges
permalink: /flair
banner_image_alt: Flair
---

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>



## Stack Exchange

<div align="center">
<a href="http://stackexchange.com/users/4468619">
<img src="http://stackexchange.com/users/flair/4468619.png" width="208" height="58" alt="profile for Jonathan Wheeler on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Jonathan Wheeler on Stack Exchange, a network of free, community-driven Q&amp;A sites">
</a>
</div>

## Github

<div align="center">
<iframe src="http://githubbadge.appspot.com/jondoesntgit" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder="0"></iframe>
</div>


## Code Wars

<div align="center">
<a href="https://www.codewars.com/users/jamwheeler">
<img src="https://www.codewars.com/users/jamwheeler/badges/small">
</a>
</div>

## Duolingo

<div align="center">
<a href="https://www.duolingo.com/jamwheeler">
<img class="flag" src="https://b.thumbs.redditmedia.com/tkqJtyXcZ-OYmLaY.png" /><span class="duo duo-de">9</span>&nbsp;
<img class="flag" src="https://b.thumbs.redditmedia.com/6jE2_QPc5iNeleRI.png" /><span class="duo duo-es">7</span>&nbsp;
<img class="flag" src="https://b.thumbs.redditmedia.com/Hs0JAtSwNYtsmcYi.png" /><span class="duo duo-fr">5</span>&nbsp;
<img class="flag" src="https://b.thumbs.redditmedia.com/WyqRvFdxGGp96ME_YS9tyru2RsJ1HlBuWSUm3KB1CAc.png" />4<span class="duo duo-ru"></span>&nbsp;
</a>
</div>

<script>
$('.flag').css('display', 'inline-block')
$('.flag').css('vertical-align', 'middle')
$('.duo').css('padding', '2px')
$.get("http://www.duolingo.com/users/jamwheeler", function(data){
    duolingo = data;
    duolingo.languages.forEach(function (element) {
        if ((!element.learning)) {return;}
        console.log(element)
        console.log('.duo-' + element.language)
        $('.duo-' + element.language ).text(element.level);
    })
})
</script>

<div align="center">
(Had to script this one myself)
</div>

