<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday My Kuchupuchu ❤️</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
text-align:center;
background: linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
overflow:hidden;
}

h1{
margin-top:40px;
font-size:42px;
}

.date{
font-size:22px;
margin-bottom:20px;
}

.letter{
max-width:700px;
margin:40px auto;
background:rgba(255,255,255,0.15);
padding:30px;
border-radius:20px;
font-size:18px;
line-height:1.6;
}

button{
padding:12px 25px;
border:none;
border-radius:30px;
background:white;
color:#ff4b7d;
font-size:16px;
cursor:pointer;
}

.heart{
position:fixed;
top:-10px;
color:#fff;
font-size:20px;
animation:fall linear infinite;
}

@keyframes fall{
to{
transform:translateY(100vh);
}
}

</style>
</head>

<body>

<h1>Happy Birthday My Kuchupuchu 🎂❤️</h1>
<div class="date">Today is your special day</div>

<button onclick="playMusic()">Play Our Song 🎵</button>

<audio id="song" autoplay loop>
<source src="madeinjapan.mp3" type="audio/mpeg">
</audio>

<div class="letter">

<h2>A Letter For You 💌</h2>

<p>My dearest Kuchupuchu,</p>

<p>
Happy Birthday to the most beautiful and special person in my life.
Today is all about celebrating you and the happiness you bring into my world.
</p>

<p>
Every moment with you is precious to me. Your smile makes my day brighter,
your voice calms my heart, and your love makes my life complete.
</p>

<p>
I am so lucky to have you in my life. No matter what happens,
I promise to always be there for you, support you, and make you smile.
</p>

<p>
I hope your birthday is full of love, laughter, and beautiful memories.
You deserve all the happiness in the world.
</p>

<p>
I love you so much ❤️  
Happy Birthday again my Kuchupuchu.
</p>

<p>— From your love</p>

</div>

<script>

function playMusic(){
document.getElementById("song").play();
}

function createHeart(){
const heart=document.createElement("div");
heart.classList.add("heart");
heart.innerHTML="❤️";
heart.style.left=Math.random()*100+"vw";
heart.style.animationDuration=(Math.random()*3+2)+"s";
document.body.appendChild(heart);

setTimeout(()=>{
heart.remove();
},5000);
}

setInterval(createHeart,300);

</script>

</body>
</html>

