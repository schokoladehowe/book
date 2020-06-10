# cyber bird project.
<head>
<style>
body{background:#000;font-family:Oswald,sans-serif;font-style:italic}
.glitch,.glow{color:#dfbfbf;position:relative;font-size:150px;margin:15% 17%;animation:glitch 5s 5s infinite}
.glitch::before,.glow::before{content:attr(data-text);position:absolute;left:-2px;text-shadow:-5px 0 #ff00ff;background:#000;overflow:hidden;top:0;animation:noise-1 3s linear infinite alternate-reverse,glitch 5s 5.05s infinite}
.glitch::after,.glow::after{content:attr(data-text);position:absolute;left:2px;text-shadow:-5px 0 #90ee90;background:#000;overflow:hidden;top:0;animation:noise-2 3s linear infinite alternate-reverse,glitch 5s 5s infinite}
@keyframes glitch{1%{transform:rotateX(5deg) skewX(40deg)}
2%{transform:rotateX(0deg) skewX(0deg)}}
@keyframes noise-1{3.3333333333%{clip-path:inset(35px 0 27px 0)}
6.6666666667%{clip-path:inset(85px 0 14px 0)}
10%{clip-path:inset(91px 0 3px 0)}
13.3333333333%{clip-path:inset(63px 0 22px 0)}
16.6666666667%{clip-path:inset(60px 0 8px 0)}
20%{clip-path:inset(27px 0 64px 0)}
23.3333333333%{clip-path:inset(68px 0 15px 0)}
26.6666666667%{clip-path:inset(75px 0 16px 0)}
30%{clip-path:inset(91px 0 5px 0)}
33.3333333333%{clip-path:inset(85px 0 6px 0)}
36.6666666667%{clip-path:inset(22px 0 66px 0)}
40%{clip-path:inset(72px 0 12px 0)}
43.3333333333%{clip-path:inset(4px 0 55px 0)}
46.6666666667%{clip-path:inset(79px 0 7px 0)}
50%{clip-path:inset(89px 0 2px 0)}
53.3333333333%{clip-path:inset(7px 0 28px 0)}
56.6666666667%{clip-path:inset(61px 0 8px 0)}
60%{clip-path:inset(87px 0 4px 0)}
63.3333333333%{clip-path:inset(34px 0 14px 0)}
66.6666666667%{clip-path:inset(42px 0 7px 0)}
70%{clip-path:inset(3px 0 42px 0)}
73.3333333333%{clip-path:inset(11px 0 81px 0)}
76.6666666667%{clip-path:inset(21px 0 69px 0)}
80%{clip-path:inset(94px 0 4px 0)}
83.3333333333%{clip-path:inset(62px 0 1px 0)}
86.6666666667%{clip-path:inset(78px 0 5px 0)}
90%{clip-path:inset(14px 0 49px 0)}
93.3333333333%{clip-path:inset(72px 0 4px 0)}
96.6666666667%{clip-path:inset(78px 0 8px 0)}
100%{clip-path:inset(1px 0 93px 0)}}
@keyframes noise-2{0%{clip-path:inset(24px 0 16px 0)}
3.3333333333%{clip-path:inset(30px 0 29px 0)}
6.6666666667%{clip-path:inset(30px 0 17px 0)}
10%,13.3333333333%{clip-path:inset(70px 0 11px 0)}
16.6666666667%{clip-path:inset(16px 0 32px 0)}
20%{clip-path:inset(41px 0 35px 0)}
23.3333333333%{clip-path:inset(84px 0 17px 0)}
26.6666666667%{clip-path:inset(37px 0 61px 0)}
30%{clip-path:inset(13px 0 67px 0)}
33.3333333333%{clip-path:inset(42px 0 18px 0)}
36.6666666667%{clip-path:inset(28px 0 70px 0)}
40%{clip-path:inset(31px 0 43px 0)}
43.3333333333%{clip-path:inset(18px 0 39px 0)}
46.6666666667%{clip-path:inset(25px 0 45px 0)}
50%{clip-path:inset(58px 0 23px 0)}
53.3333333333%{clip-path:inset(4px 0 32px 0)}
56.6666666667%{clip-path:inset(81px 0 6px 0)}
60%{clip-path:inset(24px 0 5px 0)}
63.3333333333%{clip-path:inset(94px 0 4px 0)}
66.6666666667%{clip-path:inset(29px 0 27px 0)}
70%{clip-path:inset(61px 0 22px 0)}
73.3333333333%{clip-path:inset(58px 0 29px 0)}
76.6666666667%{clip-path:inset(48px 0 53px 0)}
80%{clip-path:inset(7px 0 21px 0)}
83.3333333333%{clip-path:inset(9px 0 75px 0)}
86.6666666667%{clip-path:inset(32px 0 53px 0)}
90%{clip-path:inset(10px 0 37px 0)}
93.3333333333%{clip-path:inset(27px 0 38px 0)}
96.6666666667%{clip-path:inset(82px 0 11px 0)}
100%{clip-path:inset(33px 0 57px 0)}}
.scanlines{overflow:hidden;mix-blend-mode:difference}
.scanlines::before{content:"";position:absolute;width:100%;height:100%;top:0;left:0;background:repeating-linear-gradient(to bottom,transparent 0,rgba(255,255,255,.05) .5%,transparent 1%);animation:fudge 7s ease-in-out alternate infinite}
@keyframes fudge{from{transform:translate(0px,0)}
to{transform:translate(0px,2%)}}
.glow{text-shadow:0 0 1000px #dfbfbf;color:transparent;margin-top:-30%}
.subtitle{font-family:Arial,Helvetica,sans-serif;font-weight:100;color:rgba(165,141,141,.4);text-transform:uppercase;letter-spacing:1em;text-align:center;margin-top:-15%;animation:glitch-2 5s 5.02s infinite}
@keyframes glitch-2{1%{transform:rotateX(10deg) skewX(70deg)}
2%{transform:rotateX(0deg) skewX(0deg)}}



</style></head> 

<font size="4">
<h1> <div class="glitch" data-text="CYBER BIRD">CYBER BIRD</div>
<div class="glow">CYBER BIRD</div>
<p class="subtitle">I never make the same mistake twice... I make about five times, just to make sure it's wrong!</p>
<div class="scanlines"></div> </h1>
  
<p>Note to self: Never get drunk & listen to this. It gives you an emotional high on memories past.</p>

[![CYBER BIRD](https://images.genius.com/0e0e5fb1292b4a8ff6504d2164741625.600x600x1.png)](https://youtu.be/79w0T1jmgoQ "CYBER BIRD")


