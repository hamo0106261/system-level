<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>System</title>

<style>
*{box-sizing:border-box}

body{
margin:0;
min-height:100vh;
font-family:Arial,sans-serif;
background:#01050d;
color:white;
display:flex;
align-items:center;
justify-content:center;
overflow:hidden;
}

body:before{
content:"";
position:fixed;
width:600px;
height:600px;
background:#008cff;
filter:blur(180px);
opacity:.16;
border-radius:50%;
}

.system{
width:92%;
max-width:650px;
padding:30px;
background:rgba(0,100,255,.08);
border:1px solid rgba(0,160,255,.7);
border-radius:20px;
backdrop-filter:blur(20px);
-webkit-backdrop-filter:blur(20px);
box-shadow:0 0 30px rgba(0,140,255,.2);
}

.title{
text-align:center;
font-size:32px;
letter-spacing:5px;
color:#69caff;
text-shadow:0 0 15px #008cff;
margin-bottom:28px;
}

.player{
padding:20px;
background:rgba(0,120,255,.06);
border:1px solid rgba(0,153,255,.3);
border-radius:15px;
}

.player-name{
font-size:20px;
color:#8ed7ff;
margin-bottom:18px;
}

.info{
display:flex;
justify-content:space-between;
padding:10px 0;
border-bottom:1px solid rgba(0,153,255,.12);
}

.info:last-child{border-bottom:0}

.label{color:#8aa7c4}

.value{
font-weight:bold;
color:white;
text-shadow:0 0 8px #008cff;
}

.xp{
margin-top:18px;
}

.xp-top{
display:flex;
justify-content:space-between;
color:#a9c8e5;
margin-bottom:7px;
}

.xp-bar{
height:10px;
background:rgba(255,255,255,.08);
border-radius:20px;
overflow:hidden;
}

.xp-fill{
width:35%;
height:100%;
background:linear-gradient(90deg,#006eff,#00c8ff);
box-shadow:0 0 15px #008cff;
}

.stats{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:12px;
margin-top:20px;
}

.stat{
padding:15px;
text-align:center;
background:rgba(0,120,255,.06);
border:1px solid rgba(0,153,255,.25);
border-radius:12px;
}

.stat-name{
font-size:13px;
color:#7899b8;
}

.stat-value{
font-size:22px;
color:#65c8ff;
margin-top:5px;
text-shadow:0 0 10px #008cff;
}

.buttons{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:10px;
margin-top:22px;
}

button{
padding:13px 8px;
color:#8ed7ff;
background:rgba(0,110,255,.08);
border:1px solid rgba(0,153,255,.4);
border-radius:10px;
cursor:pointer;
}

button:hover{
background:rgba(0,130,255,.2);
box-shadow:0 0 15px rgba(0,153,255,.4);
}

.message{
margin-top:22px;
padding:13px;
text-align:center;
color:#79d0ff;
background:rgba(0,120,255,.06);
border:1px solid rgba(0,153,255,.25);
border-radius:10px;
text-shadow:0 0 8px #008cff;
}

@media(max-width:600px){
.system{width:94%;padding:20px}
.title{font-size:25px}
.buttons{grid-template-columns:1fr}
}
</style>
</head>

<body>

<div class="system">

<div class="title">SYSTEM</div>

<div class="player">

<div class="player-name">PLAYER</div>

<div class="info">
<span class="label">LEVEL</span>
<span class="value">01</span>
</div>

<div class="info">
<span class="label">RANK</span>
<span class="value">E</span>
</div>

<div class="info">
<span class="label">COINS</span>
<span class="value">0</span>
</div>

<div class="xp">

<div class="xp-top">
<span>XP</span>
<span>35 / 100</span>
</div>

<div class="xp-bar">
<div class="xp-fill"></div>
</div>

</div>

</div>

<div class="stats">

<div class="stat">
<div class="stat-name">STRENGTH</div>
<div class="stat-value">10</div>
</div>

<div class="stat">
<div class="stat-name">AGILITY</div>
<div class="stat-value">10</div>
</div>

<div class="stat">
<div class="stat-name">VITALITY</div>
<div class="stat-value">10</div>
</div>

<div class="stat">
<div class="stat-name">INTELLIGENCE</div>
<div class="stat-value">10</div>
</div>

</div>

<div class="buttons">
<button>STATUS</button>
<button>QUESTS</button>
<button>REWARDS</button>
</div>

<div class="message">
SYSTEM ONLINE
</div>

</div>

</body>
</html>
