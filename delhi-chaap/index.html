<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>For You ❤️</title>
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&display=swap" rel="stylesheet">
<style>
:root{color-scheme:dark;--bg1:#3a0b25;--bg2:#12030c;--blush:#ffe3ea;--rose:#e8a0b4;--gold:#e9c28f;--wine:#8c1237;--card:rgba(30,6,20,.5);box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{-webkit-tap-highlight-color:transparent}
html,body{height:100%;margin:0;overflow:hidden;background:radial-gradient(ellipse at 50% 25%,var(--bg1),var(--bg2) 75%);color:var(--blush);font-family:'Cormorant Garamond','Noto Serif Devanagari',Georgia,serif}
canvas{position:fixed;inset:0;width:100%;height:100%;display:block}
#title{position:fixed;top:calc(18px + env(safe-area-inset-top,0px));left:0;right:0;text-align:center;font-family:'Great Vibes',cursive;font-size:clamp(2rem,8vw,3.2rem);color:var(--gold);text-shadow:0 0 24px rgba(233,194,143,.45);pointer-events:none}
#ui{position:fixed;left:0;right:0;bottom:0;padding:0 16px calc(22px + env(safe-area-inset-bottom,0px));display:flex;justify-content:center;pointer-events:none}
.card{pointer-events:auto;max-width:440px;width:100%;background:var(--card);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border:1px solid rgba(233,194,143,.45);border-radius:20px;padding:22px 20px 18px;text-align:center;box-shadow:0 10px 50px rgba(0,0,0,.5),inset 0 0 30px rgba(232,160,180,.08)}
#msg{font-size:1.45rem;line-height:1.45;min-height:4.4em;margin:0 0 12px;font-style:italic;font-weight:500;display:flex;align-items:center;justify-content:center}
button{font-family:inherit;font-size:1.15rem;font-weight:600;letter-spacing:.04em;border:1px solid rgba(255,227,234,.4);border-radius:999px;padding:10px 28px;margin:4px;color:#fff;background:linear-gradient(135deg,#b01650,#7a0f33);cursor:pointer;box-shadow:0 6px 22px rgba(176,22,80,.45)}
button.ghost{background:rgba(255,255,255,.08);box-shadow:none;color:var(--blush);touch-action:none;user-select:none}
#no{position:fixed;left:0;top:0;z-index:4;transition:left .35s cubic-bezier(.2,.9,.3,1.25),top .35s cubic-bezier(.2,.9,.3,1.25),transform .35s}
.hide{display:none!important}
#intro{position:fixed;inset:0;z-index:5;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:18px;background:radial-gradient(ellipse at 50% 40%,#4a0f2d,#12030c 80%);transition:opacity 1s;text-align:center;padding:24px}
#intro h1{font-family:'Great Vibes',cursive;font-weight:400;font-size:clamp(2.6rem,12vw,4.4rem);margin:0;color:var(--gold);text-shadow:0 0 30px rgba(233,194,143,.4)}
#intro p{margin:0;font-style:italic;font-size:1.3rem;color:var(--rose)}
.env{font-size:4rem;animation:fl 2.4s ease-in-out infinite}
@keyframes fl{50%{transform:translateY(-10px) scale(1.06)}}
</style>
</head>
<body>
<canvas id="c"></canvas>
<div id="title">For You, My Love</div>
<div id="ui"><div class="card">
  <p id="msg"></p>
  <div id="next"><button id="nb">Continue ♡</button></div>
  <div id="ask" class="hide"><button id="yes">Yes, I forgive you ❤️</button></div>
</div></div>
<button class="ghost hide" id="no">No 💔</button>
<div id="intro"><div class="env">💌</div><h1>I wrote you something</h1><p>Open it, please?</p><button id="open">Open ♡</button></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
const lines=[
"Hey you… this is only for you.",
"Yesterday I was stressed and frustrated with work, and I took it out on you.",
"Your prank was just you being playful, and I shouldn't have snapped at you. I'm truly sorry.",
"I won't do that again. No matter how busy I get, you matter the most to me.",
"I love you, my baby. More than any website could ever say. ❤️",
"So… will you forgive me? 🥹"
];
const msg=document.getElementById('msg');let i=0,tw=null;
function type(t){msg.style.transition='opacity .35s';msg.style.opacity=0;setTimeout(()=>{msg.textContent=t;msg.style.opacity=1},300)}
document.getElementById('open').onclick=()=>{const el=document.getElementById('intro');el.style.opacity=0;setTimeout(()=>el.remove(),1000);type(lines[0])};
document.getElementById('nb').onclick=()=>{i++;type(lines[i]);if(i===lines.length-1){document.getElementById('next').classList.add('hide');document.getElementById('ask').classList.remove('hide');placeNo()}};

/* three.js */
const canvas=document.getElementById('c');
const renderer=new THREE.WebGLRenderer({canvas,antialias:true,alpha:true});
renderer.setPixelRatio(Math.min(devicePixelRatio,2));
const scene=new THREE.Scene();
const cam=new THREE.PerspectiveCamera(55,1,.1,100);cam.position.z=10;
scene.add(new THREE.AmbientLight(0xffc9d6,.55));
const k1=new THREE.PointLight(0xfff0e0,1.6,60);k1.position.set(5,6,9);scene.add(k1);
const k2=new THREE.PointLight(0xff5c8a,1.3,60);k2.position.set(-7,-4,6);scene.add(k2);
const sh=new THREE.Shape();
sh.moveTo(0,0);sh.bezierCurveTo(0,.6,-.9,1,-1.4,.4);sh.bezierCurveTo(-1.9,-.3,-1,-1.2,0,-2);
sh.bezierCurveTo(1,-1.2,1.9,-.3,1.4,.4);sh.bezierCurveTo(.9,1,0,.6,0,0);
const geo=new THREE.ExtrudeGeometry(sh,{depth:.6,bevelEnabled:true,bevelSize:.2,bevelThickness:.25,bevelSegments:10,curveSegments:24});
geo.center();
const main=new THREE.Mesh(geo,new THREE.MeshPhysicalMaterial({color:0xb3123f,roughness:.18,metalness:.25,clearcoat:1,clearcoatRoughness:.1,emissive:0x3d0010}));
main.position.y=1.6;scene.add(main);
const pal=[0xe8a0b4,0xf4c6d0,0xe9c28f,0xc2185b,0xffd9e0];
const small=[];
for(let n=0;n<55;n++){
  const m=new THREE.Mesh(geo,new THREE.MeshStandardMaterial({color:pal[n%pal.length],roughness:.35,metalness:.3,transparent:true,opacity:.85}));
  m.scale.setScalar(.08+Math.random()*.16);
  m.position.set((Math.random()-.5)*20,(Math.random()-.5)*16,(Math.random()-.5)*10-3);
  m.userData={v:.25+Math.random()*.5,r:(Math.random()-.5)*1.5};
  scene.add(m);small.push(m);
}
/* sparkles */
const c2=document.createElement('canvas');c2.width=c2.height=64;const g=c2.getContext('2d');
const gr=g.createRadialGradient(32,32,0,32,32,32);gr.addColorStop(0,'rgba(255,240,215,1)');gr.addColorStop(.4,'rgba(233,194,143,.5)');gr.addColorStop(1,'rgba(233,194,143,0)');
g.fillStyle=gr;g.fillRect(0,0,64,64);
const N=220,pp=new Float32Array(N*3);
for(let n=0;n<N;n++){pp[n*3]=(Math.random()-.5)*26;pp[n*3+1]=(Math.random()-.5)*18;pp[n*3+2]=(Math.random()-.5)*14}
const pg=new THREE.BufferGeometry();pg.setAttribute('position',new THREE.BufferAttribute(pp,3));
const stars=new THREE.Points(pg,new THREE.PointsMaterial({size:.22,map:new THREE.CanvasTexture(c2),transparent:true,depthWrite:false,blending:THREE.AdditiveBlending}));
scene.add(stars);
/* burst */
const bursts=[];
function burst(){
  for(let n=0;n<90;n++){
    const m=new THREE.Mesh(geo,new THREE.MeshStandardMaterial({color:pal[n%pal.length],roughness:.3,metalness:.3}));
    const s=.1+Math.random()*.18;m.scale.setScalar(s);m.position.set(0,1.6,0);
    const a=Math.random()*Math.PI*2,sp=3+Math.random()*6;
    m.userData={vx:Math.cos(a)*sp,vy:Math.sin(a)*sp+2,vz:(Math.random()-.2)*4,s,life:2.8+Math.random()};
    scene.add(m);bursts.push(m);
  }
}
let mx=0,my=0,boost=1;
addEventListener('pointermove',e=>{mx=e.clientX/innerWidth-.5;my=e.clientY/innerHeight-.5;nearNo(e.clientX,e.clientY)});
function resize(){renderer.setSize(innerWidth,innerHeight,false);cam.aspect=innerWidth/innerHeight;cam.updateProjectionMatrix();main.scale.setScalar(innerWidth<600?1.15:1.5)}
addEventListener('resize',resize);resize();
let last=performance.now();
function loop(now){
  const dt=Math.min((now-last)/1000,.05);last=now;const t=now/1000;
  main.rotation.y=Math.sin(t*.7)*.9;
  const base=innerWidth<600?1.15:1.5,beat=1+.07*Math.max(0,Math.sin(t*3));
  main.scale.setScalar(base*beat*(boost>1?1.2:1));
  cam.position.x+=(mx*2.5-cam.position.x)*.05;cam.position.y+=(-my*1.5-cam.position.y)*.05;cam.lookAt(0,0,0);
  small.forEach(m=>{m.position.y+=m.userData.v*dt*boost;m.rotation.y+=m.userData.r*dt*boost;if(m.position.y>9)m.position.y=-9});
  stars.rotation.y=t*.02*boost;stars.position.y=Math.sin(t*.4)*.2;
  for(let b=bursts.length-1;b>=0;b--){const m=bursts[b],u=m.userData;u.life-=dt;m.position.x+=u.vx*dt;m.position.y+=u.vy*dt;m.position.z+=u.vz*dt;u.vy-=3*dt;m.rotation.y+=dt*3;m.scale.setScalar(Math.max(.001,u.s*Math.min(1,u.life)));if(u.life<=0){scene.remove(m);bursts.splice(b,1)}}
  renderer.render(scene,cam);requestAnimationFrame(loop);
}
requestAnimationFrame(loop);

/* The "No" button can never be clicked */
const no=document.getElementById('no');
const labels=["Nope 😜","Nice try 😏","Catch me 🏃","Too slow 😂","Try again 🙈","Not today 😝","Oops 🫣","Almost! 😆"];
let li=0,cool=0;
function hits(x,y,w,h){return [document.querySelector('.card'),document.getElementById('yes')].some(e=>{const r=e.getBoundingClientRect();return x<r.right+10&&x+w>r.left-10&&y<r.bottom+10&&y+h>r.top-10})}
function placeNo(){
  no.classList.remove('hide');
  const r=document.querySelector('.card').getBoundingClientRect();
  no.style.left=Math.max(12,innerWidth/2+30)+'px';no.style.top=Math.max(80,r.top-64)+'px';
}
function moveNo(){
  const now=performance.now();if(now<cool)return;cool=now+380;
  const w=no.offsetWidth||110,h=no.offsetHeight||46;
  const goTop=(parseFloat(no.style.top)||0)>innerHeight*.45;
  let x=0,y=0;
  for(let t=0;t<80;t++){
    x=12+Math.random()*(innerWidth-w-24);
    if(t<40){y=goTop?70+Math.random()*(innerHeight*.35-h):innerHeight*.5+Math.random()*(innerHeight*.5-h-12)}
    else{y=70+Math.random()*(innerHeight-h-90)}
    if(!hits(x,y,w,h))break;
  }
  no.style.left=x+'px';no.style.top=y+'px';
  no.style.transform='rotate('+((Math.random()-.5)*26)+'deg)';
  no.textContent=labels[li++%labels.length];
}
function nearNo(px,py){
  if(no.classList.contains('hide'))return;
  const r=no.getBoundingClientRect();
  if(Math.hypot(r.left+r.width/2-px,r.top+r.height/2-py)<90)moveNo();
}
['pointerdown','pointerenter','touchstart','mousedown','click'].forEach(ev=>no.addEventListener(ev,e=>{e.preventDefault();e.stopPropagation();moveNo()},{passive:false}));
addEventListener('touchmove',e=>{const t=e.touches[0];if(t)nearNo(t.clientX,t.clientY)},{passive:true});

document.getElementById('yes').onclick=()=>{
  boost=5;setTimeout(()=>boost=1.8,3000);burst();setTimeout(burst,700);no.classList.add('hide');
  document.getElementById('ask').classList.add('hide');
  document.getElementById('title').textContent='Thank you, my love';
  type("You just made me the happiest. From today, double the love, half the fights. I love you so much ❤️");
};
</script>
</body>
</html>
