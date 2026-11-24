
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Feliz cumpleaños Susej 💗</title>
<style>
:root{--pink:#ff168f;--pink2:#ff69bd}
*{box-sizing:border-box}
html,body{margin:0;min-height:100%;background:#070108;color:white;font-family:Georgia,serif}
body{overflow-x:hidden}
#backdrop{position:fixed;inset:0;z-index:-2;background:radial-gradient(circle at 10% 15%,#ff168f99 0 2px,transparent 4px),radial-gradient(circle at 80% 25%,#ff5bbd77 0 3px,transparent 6px),radial-gradient(ellipse at 50% 0%,#bd0876,#5c073d 27%,#18051a 65%,#030106)}
.heart-bg{position:fixed;z-index:-1;color:#ff8acb;opacity:.17;font-size:80px;animation:drift 14s infinite}
.h1{top:5%;left:4%}.h2{top:30%;right:5%}.h3{bottom:7%;left:10%}.h4{bottom:20%;right:12%}
@keyframes drift{50%{transform:translateY(-25px) rotate(12deg);opacity:.35}}
.brand{height:72px;display:grid;place-items:center;text-align:center;font:20px Arial;letter-spacing:3px;text-shadow:0 0 12px #ff8acb}
.brand span{display:block;font-size:10px;letter-spacing:5px;color:#ffd1eb}
main{width:min(900px,96vw);margin:0 auto 60px}
.stage{height:min(690px,76vh);min-height:520px;position:relative;overflow:hidden;border-radius:32px;background:#020104;border:1px solid #ff6dbb55;box-shadow:0 0 45px #ff168f44}
#space{position:absolute;inset:0;width:100%;height:100%}
.screen{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;padding:22px;transition:opacity .8s,transform .8s}
.screen.off{opacity:0;pointer-events:none;transform:scale(.92)}
.intro-card{width:min(430px,92%);padding:38px 26px;text-align:center;background:linear-gradient(145deg,#160711ee,#080308f5);border:1px solid #ff7ac355;border-radius:19px;box-shadow:0 0 35px #ff168f22}
h1{font-size:clamp(34px,6vw,54px);line-height:1.1;margin:0 0 20px;text-shadow:0 0 16px #ffb5df66}
.bunny{font-size:68px;display:block;margin:18px 0 22px;filter:drop-shadow(0 0 14px #ff69bd);animation:bob 3s infinite}
@keyframes bob{50%{transform:translateY(-9px)}}
.kicker{font:10px Arial;letter-spacing:4px;color:#ffacd9;text-transform:uppercase}
.smallline{font:11px Arial;letter-spacing:3px;color:#f3c4df;margin:0 0 20px}
button{font:bold 10px Arial;letter-spacing:2px;color:white;border:1px solid #ffadd9;border-radius:30px;padding:14px 24px;background:linear-gradient(90deg,#d30b7a,#ff65b7);box-shadow:0 0 22px #ff168f66;cursor:pointer;transition:.25s}
button:hover{transform:scale(1.05);box-shadow:0 0 30px #ff168f}
.galaxy-screen{display:block;opacity:0;pointer-events:none;transition:opacity 1.2s}
.galaxy-screen.on{opacity:1;pointer-events:auto}
.galaxy-title{position:absolute;top:22px;left:0;right:0;text-align:center;font:11px Arial;letter-spacing:5px;color:#ffc5e6}
.orbit-words{position:absolute;inset:0;pointer-events:none}
.orbit-words span{position:absolute;color:#ff9bd0;font:bold clamp(10px,2vw,17px) Arial;letter-spacing:2px;text-shadow:0 0 12px #ff168f;white-space:nowrap;animation:wordGlow 2.5s infinite alternate}
.orbit-words span:nth-child(1){top:24%;left:5%;transform:rotate(-12deg)}
.orbit-words span:nth-child(2){top:34%;right:4%;transform:rotate(12deg)}
.orbit-words span:nth-child(3){bottom:28%;left:9%;transform:rotate(8deg)}
.orbit-words span:nth-child(4){bottom:16%;right:7%;transform:rotate(-9deg)}
@keyframes wordGlow{to{text-shadow:0 0 22px #ff7acb,0 0 35px #ff168f}}
.heart-core{position:absolute;left:50%;top:48%;transform:translate(-50%,-50%);font-size:clamp(100px,24vw,190px);color:#ff4eae;filter:drop-shadow(0 0 18px #ff168f) drop-shadow(0 0 45px #ff168f);animation:heartBeat 2s infinite}
@keyframes heartBeat{0%,100%{transform:translate(-50%,-50%) scale(1)}50%{transform:translate(-50%,-50%) scale(1.09)}}
.galaxy-caption{position:absolute;bottom:25px;left:0;right:0;text-align:center;color:#ff9bd0;font:bold 12px Arial;letter-spacing:3px}
.floating-note{position:absolute;z-index:3;border:1px solid #ff80c655;background:#120711dd;color:white;border-radius:50%;width:38px;height:38px;padding:0;font-size:17px;display:grid;place-items:center;animation:floatNote 4s infinite}
.note1{top:19%;left:17%}.note2{top:57%;right:14%}.note3{bottom:18%;left:23%}
@keyframes floatNote{50%{transform:translateY(-12px)}}
.modal{position:absolute;z-index:5;inset:0;display:grid;place-items:center;padding:20px;background:#0009;opacity:0;pointer-events:none;transition:.35s}
.modal.show{opacity:1;pointer-events:auto}
.note-card{width:min(360px,94%);padding:20px;text-align:center;background:#100711;border:1px solid #ff8acb66;border-radius:18px;box-shadow:0 0 35px #ff168f55}
.note-art{height:145px;border-radius:10px;background:radial-gradient(circle,#ff9bd344,#170813 65%);display:grid;place-items:center;font-size:66px;margin-bottom:18px}
.note-card h2{font-size:27px;margin:0 0 12px}
.note-card p{font:13px/1.7 Arial;color:#f2cce2}
.close{margin-top:8px;padding:10px 20px}
.footer{margin:18px auto 0;text-align:center;color:#ffadd9;font:10px Arial;letter-spacing:3px}
@media(max-width:520px){.brand{height:60px}.stage{min-height:560px;height:76vh;border-radius:23px}.intro-card{padding:32px 20px}.orbit-words span{font-size:9px;letter-spacing:1px}.orbit-words span:nth-child(1){left:2%}.orbit-words span:nth-child(2){right:2%}}
</style>
</head>
<body>
<div id="backdrop"></div>
<div class="heart-bg h1">♡</div>
<div class="heart-bg h2">♡</div>
<div class="heart-bg h3">♡</div>
<div class="heart-bg h4">♡</div>

<header class="brand">
SUSEJ
<span>✦ UN UNIVERSO HECHO PARA TI ✦</span>
</header>

<main>
<section class="stage">
<canvas id="space"></canvas>

<!-- PORTADA -->
<div class="screen" id="intro">
<div class="intro-card">
<div class="kicker">Un detalle especial para ti</div>
<h1>Una Galaxia de<br><span style="color:#ff8acb">Cumpleaños</span></h1>
<div class="bunny">🐰💗🐻</div>
<p class="smallline">FELIZ CUMPLEAÑOS, SUSEJ</p>
<button onclick="enterGalaxy()">ENTRAR A TU UNIVERSO ✦</button>
</div>
</div>

<!-- GALAXIA -->
<div class="screen galaxy-screen" id="galaxy">
<div class="galaxy-title">✦ PARA UNA PRIMA INCREÍBLE ✦</div>

<div class="orbit-words">
<span>FELIZ CUMPLEAÑOS ♡</span>
<span>ERES MUY ESPECIAL</span>
<span>QUE SE CUMPLAN TUS SUEÑOS</span>
<span>TE QUIERO, PRIMA ♡</span>
</div>

<div class="heart-core">♥</div>

<div class="galaxy-caption">
HOY EL UNIVERSO CELEBRA A SUSEJ ✦
</div>

<button class="floating-note note1" onclick="openNote(0)">♡</button>
<button class="floating-note note2" onclick="openNote(1)">♥</button>
<button class="floating-note note3" onclick="openNote(2)">✧</button>
</div>

<!-- TARJETAS -->
<div class="modal" id="modal" onclick="if(event.target===this)closeNote()">
<div class="note-card">
<div class="note-art" id="noteArt">💗🐰</div>
<h2 id="noteTitle">Para ti</h2>
<p id="noteText"></p>
<button class="close" onclick="closeNote()">VOLVER ♡</button>
</div>
</div>

</section>

<div class="footer">
HECHO CON CARIÑO PARA SUSEJ · FELIZ CUMPLEAÑOS ♡
</div>
</main>

<script>
const canvas=document.getElementById('space');
const ctx=canvas.getContext('2d');

let w,h,stars=[],dust=[],heartPoints=[];

function resize(){
const r=canvas.getBoundingClientRect();
const d=devicePixelRatio||1;

w=r.width;
h=r.height;

canvas.width=w*d;
canvas.height=h*d;
ctx.setTransform(d,0,0,d,0,0);

stars=Array.from({length:Math.floor(w*h/1900)},()=>({
x:Math.random()*w,
y:Math.random()*h,
r:Math.random()*1.5+.2,
a:Math.random(),
v:Math.random()*.018+.003
}));

dust=Array.from({length:650},()=>({
a:Math.random()*Math.PI*2,
rad:Math.random()*.48+.08,
size:Math.random()*1.7+.3,
phase:Math.random()*6
}));

heartPoints=[];

for(let t=0;t<Math.PI*2;t+=.025){
const x=16*Math.pow(Math.sin(t),3);
const y=13*Math.cos(t)-5*Math.cos(2*t)-2*Math.cos(3*t)-Math.cos(4*t);
heartPoints.push({x,y});
}
}

function draw(){
ctx.clearRect(0,0,w,h);

stars.forEach(s=>{
s.a+=s.v;
if(s.a>1||s.a<.12)s.v*=-1;
ctx.fillStyle=`rgba(255,210,238,${s.a})`;
ctx.beginPath();
ctx.arc(s.x,s.y,s.r,0,7);
ctx.fill();
});

if(document.getElementById('galaxy').classList.contains('on')){

const cx=w/2;
const cy=h*.48;
const scale=Math.min(w,h)*.012;
const tm=Date.now()*.00025;

// GALAXIA ESPIRAL
dust.forEach(p=>{
let a=p.a+tm*(1.4-p.rad);
let r=p.rad*Math.min(w,h)*.56;
let x=cx+Math.cos(a)*r;
let y=cy+Math.sin(a)*r*.48;

ctx.fillStyle=`rgba(255,${90+Math.floor(100*(1-p.rad))},${175+Math.floor(70*(1-p.rad))},${.18+.65*Math.abs(Math.sin(p.phase+tm*4))})`;

ctx.beginPath();
ctx.arc(x,y,p.size,0,Math.PI*2);
ctx.fill();
});

// CORAZÓN DE PARTÍCULAS
heartPoints.forEach((p,i)=>{
let x=cx+p.x*scale*1.85;
let y=cy-p.y*scale*1.85;
let tw=.55+.45*Math.sin(tm*8+i*.4);

ctx.fillStyle=`rgba(255,${70+Math.floor(tw*90)},${160+Math.floor(tw*90)},${.55+tw*.4})`;

ctx.shadowBlur=8;
ctx.shadowColor='#ff168f';
ctx.beginPath();
ctx.arc(x,y,1.1+tw*1.2,0,Math.PI*2);
ctx.fill();
ctx.shadowBlur=0;
});

ctx.fillStyle='#ffb3dc';
ctx.shadowBlur=24;
ctx.shadowColor='#ff168f';
ctx.beginPath();
ctx.arc(cx,cy+Math.min(w,h)*.19,4,0,7);
ctx.fill();
ctx.shadowBlur=0;
}

requestAnimationFrame(draw);
}

// ENTRAR A LA GALAXIA
function enterGalaxy(){
document.getElementById('intro').classList.add('off');
document.getElementById('galaxy').classList.add('on');
}

// DEDICATORIAS PARA SUSEJ
const notes=[
{
art:'🐰💗🐻',
title:'Para mi prima',
text:'Susej, que la vida te regale muchísimas razones para sonreír. Que cada sueño que guardas en tu corazón encuentre su camino para hacerse realidad. ¡Te mereces cosas preciosas!'
},
{
art:'🎂✨💖',
title:'Un día para celebrar',
text:'Hoy celebramos tu vida, tu alegría y la persona tan especial que eres. Que este nuevo año venga lleno de aventuras bonitas, amor, salud y momentos inolvidables.'
},
{
art:'🌷💝',
title:'Con mucho cariño',
text:'Gracias por ser parte de mi vida y de nuestra familia. Nunca olvides lo valiosa que eres. ¡Que tu brillo nunca se apague, Susej! Feliz cumpleaños.'
}
];

// ABRIR MENSAJES
function openNote(i){
const n=notes[i];

document.getElementById('noteArt').textContent=n.art;
document.getElementById('noteTitle').textContent=n.title;
document.getElementById('noteText').textContent=n.text;

document.getElementById('modal').classList.add('show');
}

// CERRAR MENSAJES
function closeNote(){
document.getElementById('modal').classList.remove('show');
}

addEventListener('resize',resize);
resize();
draw();
</script>

</body>
</html>
