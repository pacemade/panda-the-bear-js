
1.
var portrait = document.querySelector('img');
portrait.src = 'images/pikachu-drawing.jpg';

1.2
var sky = document.querySelector('.photography');
sky
<img src=​"images/​clouds-man.jpg" alt=​"Man Walking on Ice" title=​"Man Walking on Ice" class=​"photography">​
sky.src = 'https://appamatix.com/wp-content/uploads/2016/05/04-450x427.jpg'
"https://appamatix.com/wp-content/uploads/2016/05/04-450x427.jpg"

2.
var title = document.querySelector('h1.highlight');
title
<h1 class=​"highlight">​Panda The Bear​</h1>​
title.innerText = 'Potato The potato'

3.
var poopoo = document.querySelectorAll('h3.info-title');
var poopoo = poopoo[1];
<h3 class=​"info-title">​<i class=​"icon-suitcase">​…​</i>​"poopoo"</h3>​
poopoo.innerText = "Try this";

4.
var body = document.querySelector('body');
body.style.backgroundColor = 'red';

5.
var highlight = document.querySelectorAll('.highlight')
for (var i = 0; i < highlight.length; i++){ highlight[i].style.color = 'purple'}

6.
var h1 = document.querySelector('h1');
h1.style.fontFamily = 'monospace';

7.
var icon = document.querySelectorAll('.action-icon-bg');
for (var i = 0; i < icon.length; i++) { icon[i].style.backgroundColor = 'orange'};

8.
var texty = document.querySelector('textarea');
texty.placeholder = 'STATE YOUR BUSINESS';

9.
var nemesis = document.querySelector('.contact-info');
nemesis.value = 'This is your nemesis';

10.
var email = document.querySelector('#email');
email.value = 'hooguugoo@bfabdfk.com';

11.
var button = document.querySelector('#submit');
button.setAttribute('disabled', 'disabled');

12.
var profile = document.querySelectorAll('.bio-info-value');
for (var i = 0; i < profile.length; i++) {
    profile[i].innerText = '';}
