<!doctype html>
<html lang="uz">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta http-equiv="Content-Security-Policy" content="default-src 'none';script-src 'unsafe-inline';style-src 'unsafe-inline' https://fonts.googleapis.com;font-src https://fonts.gstatic.com;connect-src 'self' https://*.supabase.co;img-src data: https://*.supabase.co;media-src https://*.supabase.co">
<title>Noveluz — o‘zbek tilida o‘qish platformasi</title>
<meta name="description" content="Noveluz: o‘zbek tilidagi romanlar, manga, manhwa va shaxsiy rivojlanish kitoblari">
<meta name="theme-color" content="#0A0716">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='.9em' font-size='90'%3E📖%3C/text%3E%3C/svg%3E">
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;800&family=Literata:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#0A0716;--sf:#141026;--sf2:#1D1838;--tx:#EEEAFB;--mu:#9A94B8;--ac:#8B5CF6;--ln:#2A2350;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:dark}
:root[data-theme="light"]{--bg:#F7F5F0;--sf:#FFFFFF;--sf2:#ECE8DD;--tx:#1B2430;--mu:#66707C;--ac:#A56E0A;--ln:#DDD6C6;color-scheme:light}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;color:var(--tx);font:400 15px/1.5 Manrope,system-ui,sans-serif;background:radial-gradient(80% 28% at 75% -4%,rgba(139,92,246,.30),transparent 62%),radial-gradient(60% 30% at 0% 30%,rgba(236,72,153,.08),transparent 60%),var(--bg)}
:root[data-theme="light"] body{background:var(--bg)}
a{color:inherit;text-decoration:none}
.wrap{max-width:760px;margin:0 auto;padding:0 16px 110px}
header{display:flex;gap:8px;align-items:center;padding:12px;max-width:760px;margin:0 auto}
.logo{display:flex;align-items:center;gap:9px;line-height:1.1;font-weight:800;font-size:20px;letter-spacing:-.02em}
.logo b{color:var(--ac)}
.logo small{display:block;font:500 10px Manrope,sans-serif;color:var(--mu);margin-top:2px;letter-spacing:0}
.lm{width:34px;height:34px;border-radius:10px;background:linear-gradient(135deg,#8B5CF6,#EC4899);display:grid;place-items:center;box-shadow:0 4px 14px rgba(139,92,246,.5)}
.lm svg{width:20px;height:20px}
#q{flex:0 1 150px;min-width:0;margin-left:auto;height:34px;padding:0 12px 0 34px;border-radius:99px;font:inherit;font-size:13px;color:var(--tx);border:1px solid var(--ln);background:var(--sf) url(data:image/svg+xml,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%2024%2024%22%20fill=%22none%22%20stroke=%22%238B9BAB%22%20stroke-width=%222%22%20stroke-linecap=%22round%22%3E%3Ccircle%20cx=%2211%22%20cy=%2211%22%20r=%227%22/%3E%3Cpath%20d=%22M20%2020l-3.5-3.5%22/%3E%3C/svg%3E) no-repeat 11px center/15px}
#q:focus,button:focus-visible,a:focus-visible{outline:2px solid var(--ac);outline-offset:2px}
#bl,#av{flex:none;width:36px;height:36px;border-radius:50%;display:grid;place-items:center;color:var(--tx);background:none;border:0;cursor:pointer}
#bl svg{width:23px;height:23px}
#av{background:linear-gradient(135deg,#8B5CF6,#EC4899);color:#fff}#av svg{width:20px;height:20px}
#bk{background:var(--sf);border:1px solid var(--ln);color:var(--tx);width:36px;height:36px;border-radius:10px;font-size:18px;cursor:pointer;flex:none}
h2{display:flex;align-items:center;gap:9px;font-size:16px;letter-spacing:.01em;margin:26px 0 12px;font-weight:800}
h2:before{content:"";width:3px;height:15px;border-radius:2px;background:var(--ac)}
h2:empty{display:none}
.mu,small{color:var(--mu)}
.chips,.row,.tabs{display:flex;gap:8px;overflow-x:auto;padding-bottom:4px;scrollbar-width:none}
.chips.w{flex-wrap:wrap}
.chip{flex:none;border:1px solid var(--ln);background:var(--sf);color:var(--tx);padding:7px 13px;border-radius:99px;font:600 13px Manrope,sans-serif;cursor:pointer}
.chip.on{background:var(--ac);color:#fff;border-color:var(--ac)}
.tabs{margin:2px 0 14px}
.tabs button{flex:none;display:flex;align-items:center;gap:7px;padding:9px 15px;border:1px solid transparent;background:none;border-radius:99px;color:var(--tx);font:600 14px Manrope,sans-serif;cursor:pointer}
.tabs button svg{width:18px;height:18px}
.tabs button.on{background:var(--ac);color:#fff;box-shadow:0 6px 18px rgba(139,92,246,.45)}
.cv{flex:none;width:118px;display:block}
.cv i{display:flex;flex-direction:column;justify-content:space-between;aspect-ratio:3/4;border-radius:8px;padding:10px;position:relative;color:#fff;font-style:normal;box-shadow:0 8px 18px rgba(0,0,0,.35),inset 0 0 0 1px rgba(255,255,255,.08)}
.cv i:before{content:"";position:absolute;left:10px;right:10px;top:27px;height:1px;background:rgba(255,255,255,.16)}
.cv i em{font:700 9px Manrope,sans-serif;letter-spacing:.14em;text-transform:uppercase;opacity:.8;font-style:normal}
.cv i s{text-decoration:none;font:600 15px/1.15 Literata,Georgia,serif}
.cv i s b{display:block;margin-top:5px;font:700 10px Manrope,sans-serif;color:#F5C660;letter-spacing:.04em}
.cv i.ci em,.cv i.ci s,.cv i.ci:before{display:none}
.cv span{display:block;margin-top:6px;font-size:13px;font-weight:600;line-height:1.3}
.cv span small{display:block;font-weight:500;font-size:11px;margin-top:1px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px 10px}.grid .cv{width:auto}
.item{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:14px 2px;border-bottom:1px solid var(--ln)}
.hero{display:flex;gap:16px;margin:8px 0 18px}.hero .cv{width:130px}
.btn{display:inline-block;color:#fff;background:linear-gradient(135deg,#8B5CF6,#6D28D9);font-weight:800;font-size:15px;padding:11px 18px;border-radius:12px;border:0;cursor:pointer;box-shadow:0 4px 14px rgba(0,0,0,.25)}
.btn.alt{background:var(--sf2);color:var(--tx);box-shadow:inset 0 0 0 1px var(--ln)}
.chs{display:grid;grid-template-columns:repeat(auto-fill,minmax(88px,1fr));gap:8px}
.chs a{background:var(--sf);border:1px solid var(--ln);border-radius:8px;padding:9px;text-align:center;font-size:13px;font-weight:600}
.bar{display:flex;gap:8px;align-items:center;justify-content:space-between;margin:6px 0 18px}
.rd{font:400 var(--fs,18px)/1.75 Literata,Georgia,serif}.rd p{margin:0 0 1.1em}
.nav{display:flex;gap:10px;margin-top:26px}.nav .btn{flex:1;text-align:center}
.cont,.box,.wk,.note{background:linear-gradient(160deg,var(--sf),color-mix(in srgb,var(--sf) 70%,var(--bg)));border:1px solid var(--ln)}
.note{margin:0 0 12px;padding:12px;border-radius:10px;color:var(--mu);font-size:13px}
.cont{position:relative;display:flex;gap:14px;align-items:center;border-radius:14px;padding:14px;margin-bottom:14px}
.cont .cv{width:70px}.cont>div{flex:1;min-width:0}.cont .btn{padding:7px 14px;font-size:13px;margin-top:8px}
.pb{height:6px;border-radius:9px;background:var(--sf2);margin:8px 0 3px}.pb u{display:block;height:100%;border-radius:9px;background:var(--ac)}
.x{position:absolute;top:-4px;right:-4px;width:24px;height:24px;font-size:18px;line-height:1;padding:0;display:grid;place-items:center;background:var(--bg);border:1px solid var(--ln);border-radius:50%;color:var(--mu);cursor:pointer}
.act{display:flex;gap:14px;align-items:center}
.ring{flex:none;width:130px;height:130px;border-radius:50%;display:grid;place-items:center}
.ring>div{width:102px;height:102px;border-radius:50%;background:var(--bg);display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center}
.st{flex:1;display:grid;gap:10px}
.box{border-radius:12px;padding:10px 12px}.box small,.ring small{display:block}.box b{font-size:20px}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.wk{display:flex;justify-content:space-between;border-radius:14px;padding:12px 8px;margin:14px 0 8px}
.dy{display:flex;flex-direction:column;align-items:center;gap:6px}
.dy b{width:34px;height:34px;border-radius:50%;display:grid;place-items:center;background:var(--sf2);font-size:13px;color:var(--tx)}
.dy.ok b{background:#7BC043;color:#10151c}.dy.td b{box-shadow:0 0 0 2px var(--ac)}
.tl{position:relative;margin:10px 0 0 8px;padding-left:22px;border-left:2px solid var(--ln)}
.tl>a{display:block;position:relative;padding:0 0 22px}
.tl>a:before{content:"";position:absolute;left:-30px;top:3px;width:12px;height:12px;border-radius:50%;background:var(--ac);box-shadow:0 0 0 4px var(--bg)}
.em{text-align:center;color:var(--mu);padding:34px 10px}.em svg{width:48px;height:48px;opacity:.5}
.ph{display:flex;align-items:center;gap:14px;border-radius:16px;padding:18px 16px;color:#fff;margin:6px 0 4px}
.ph svg{width:40px;height:40px;flex:none}.ph b{display:block;font-size:20px}.ph small{color:rgba(255,255,255,.88)}
.fi{display:block;width:100%;background:var(--bg);border:1px solid var(--ln);color:var(--tx);border-radius:10px;padding:10px 12px;font:inherit;margin:8px 0}
.sh{display:flex;align-items:center;gap:9px;margin:26px 0 12px}.sh svg{width:22px;height:22px;color:var(--ac)}.sh b{flex:1;font-size:17px}.sh a{color:var(--ac);font-size:13px;font-weight:600}
.qr{display:flex;gap:8px;margin:2px 0 4px;overflow-x:auto;scrollbar-width:none}
.qa{flex:1 0 78px;background:var(--sf);border:1px solid var(--ln);border-radius:16px;padding:12px 2px 10px;color:var(--tx);font:700 11.5px/1.15 Manrope,sans-serif;display:flex;flex-direction:column;align-items:center;gap:6px;text-align:center;cursor:pointer}
.qa i{width:52px;height:52px;border-radius:14px;display:grid;place-items:center;color:#fff;box-shadow:inset 0 0 0 1px rgba(255,255,255,.14)}
.qa svg{width:27px;height:27px}
.hero2{position:relative;overflow:hidden;border-radius:22px;padding:14px 16px 32px;min-height:150px;border:1px solid var(--ln);background:radial-gradient(70% 90% at 92% 8%,hsl(var(--h) 80% 48% / .55),transparent 65%),linear-gradient(160deg,hsl(var(--h) 45% 18%),#0A0716);display:flex;flex-direction:column;align-items:flex-start;justify-content:flex-end;gap:4px;color:#fff;margin:12px 0}
.hero2 .moon{position:absolute;right:-26px;top:-26px;width:130px;height:130px;border-radius:50%;background:radial-gradient(circle at 35% 35%,rgba(255,255,255,.4),rgba(255,255,255,.04) 70%)}
.pill{display:inline-flex;align-items:center;gap:6px;background:rgba(255,255,255,.14);padding:5px 11px;border-radius:99px;font:700 12px Manrope,sans-serif;position:relative}
.pill svg{width:15px;height:15px;color:#F5C660}
.hero2 h1{position:relative;margin:2px 0 0;max-width:80%;font:italic 700 27px/1.02 Literata,Georgia,serif;background:linear-gradient(180deg,#fff,#B9A4FF);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero2 p{position:relative;margin:0 0 4px;max-width:80%;opacity:.88;font-size:13px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.hero2 .btn{padding:8px 14px;font-size:13px}
.dots{position:absolute;left:16px;bottom:12px;display:flex;gap:7px}
.dots button{width:7px;height:7px;padding:0;border:0;border-radius:6px;background:rgba(255,255,255,.35);cursor:pointer}.dots button.on{width:24px;background:var(--ac)}
.cr{position:relative;display:flex;align-items:center;gap:12px;background:var(--sf);border:1px solid var(--ln);border-radius:18px;padding:10px 12px 10px 10px}
.cth{flex:none;width:62px;height:62px;border-radius:12px}
.cm{flex:1;min-width:0}.cm b{display:block;font-size:16px}
.pcp{font-size:13px;font-weight:700;color:var(--mu);align-self:flex-end;padding-bottom:6px}
.play{flex:none;width:46px;height:46px;border-radius:50%;display:grid;place-items:center;background:var(--ac);color:#fff;box-shadow:0 6px 16px rgba(139,92,246,.5)}.play svg{width:20px;height:20px}
#bn{position:fixed;z-index:60;left:10px;right:10px;bottom:10px;display:flex;background:color-mix(in srgb,var(--sf) 90%,transparent);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border:1px solid var(--ln);border-radius:22px;padding:2px 4px calc(2px + env(safe-area-inset-bottom,0px));box-shadow:0 10px 30px rgba(0,0,0,.45)}
#bn a{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px;padding:8px 0;min-height:54px;font:700 11px Manrope,sans-serif;color:var(--mu);touch-action:manipulation;-webkit-tap-highlight-color:transparent}
#bn a i{display:grid;place-items:center}#bn svg{width:22px;height:22px}
#bn a.on{color:var(--ac)}
#bn a.on i{background:var(--ac);color:#fff;width:42px;height:42px;border-radius:50%;margin-top:-16px;box-shadow:0 6px 16px rgba(139,92,246,.5)}
#toast{position:fixed;left:50%;bottom:96px;transform:translateX(-50%);background:var(--tx);color:var(--bg);padding:10px 16px;border-radius:99px;font-weight:700;opacity:0;pointer-events:none;transition:opacity .2s;z-index:70;max-width:90%;text-align:center}
#toast.on{opacity:1}
</style>
</head>
<body>
<header>
  <button id="bk" hidden aria-label="Orqaga">←</button><a class="logo" href="#"><span class="lm"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M6 19V5l12 14V5"/></svg></span><span>Novel<b>uz</b><small>Cheksiz o‘qish olami</small></span></a>
  <input id="q" type="search" placeholder="Qidirish" aria-label="Asar qidirish"><button id="bl" aria-label="Xabarnomalar"></button><a id="av" href="#profil" aria-label="Profil"></a>
</header>
<main class="wrap" id="app"><p class="mu">Yuklanmoqda…</p></main>
<nav id="bn"></nav>
<div id="toast" role="status"></div>
<script>
(function(){
// ===== SOZLAMA: Supabase loyihangiz ma'lumotlarini shu yerga yozing (anon kalit ochiq bo'lishi mo'ljallangan; service_role kalitini HECH QACHON yozmang) =====
var CFG={url:"",key:""};
var K=["Novel","Manga","Manhwa","Manhua","Rivojlanish","Fanfic"],TBS=["Bosh sahifa"].concat(K),TIC=["home","book","lib","img","star","spark","fire"];
var app=document.getElementById("app"),qi=document.getElementById("q"),root=document.documentElement;
var D={works:[],cfg:{a:"",c:"",m:false}},TB="Bosh sahifa",GF="Hammasi",Q="",HI=0,hc=0,gb=false;
var S={lib:[],int:[],prog:{},log:{},seen:{},hist:{},name:"",th:"dark",fs:18,last:null,hide:0,goals:[],sec:{},hr:{},done:{},cl:{},rs:{f:0,l:1,w:0,b:0}};
try{var j=JSON.parse(localStorage.getItem("nu")||"{}");if(j&&typeof j=="object")for(var k in j)if(k in S)S[k]=j[k]}catch(e){}
function fix(){["lib","int","goals"].forEach(function(n){if(!Array.isArray(S[n]))S[n]=[]});["prog","log","seen","hist","sec","hr","done","cl"].forEach(function(n){if(!S[n]||typeof S[n]!="object"||Array.isArray(S[n]))S[n]={}});S.name=String(S.name||"").slice(0,30);S.fs=Math.min(30,Math.max(14,+S.fs||18));S.th=S.th=="light"?"light":"dark";if(!S.rs||typeof S.rs!="object")S.rs={f:0,l:1,w:0,b:0}}
fix();root.setAttribute("data-theme",S.th);
function sv(){try{localStorage.setItem("nu",JSON.stringify(S))}catch(e){}}
function esc(s){return String(s==null?"":s).replace(/[&<>"']/g,function(c){return{"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]})}
function toast(m){var t=document.getElementById("toast");t.textContent=m;t.className="on";clearTimeout(toast.h);toast.h=setTimeout(function(){t.className=""},2200)}
function dk(d){return d.getFullYear()+"-"+(d.getMonth()+1)+"-"+d.getDate()}
function dv(s){var p=String(s).split("-");return new Date(p[0],p[1]-1,p[2]).getTime()||0}
function fd(s){var p=String(s).split("-");return p[2]+"."+p[1]+"."+p[0]}
var IC={home:'<path d="M4 11l8-7 8 7v9h-5v-6H9v6H4v-9z"/>',book:'<path d="M3 5c3-1 6-1 9 1 3-2 6-2 9-1v13c-3-1-6-1-9 1-3-2-6-2-9-1V5z"/><path d="M12 6v13"/>',lib:'<path d="M5 4h4v16H5zM11 4h4v16h-4z"/><path d="M17.5 5.5l3 1-3.2 13.5-3-1z"/>',img:'<rect x="4" y="5" width="16" height="14" rx="2"/><circle cx="9" cy="10" r="1.5"/><path d="M4 17l5-4 4 3 3-2 4 3"/>',star:'<path d="M12 3l2.6 5.6 6 .7-4.5 4.1 1.2 6L12 16.5 6.7 19.4l1.2-6L3.4 9.3l6-.7L12 3z"/>',spark:'<path d="M12 3l2 6 6 2-6 2-2 6-2-6-6-2 6-2 2-6z"/>',user:'<circle cx="12" cy="8" r="4"/><path d="M4 21c0-4 4-6 8-6s8 2 8 6"/>',crown:'<path d="M4 8l4 4 4-7 4 7 4-4-2 11H6L4 8z"/>',bell:'<path d="M6 16v-5a6 6 0 0 1 12 0v5l2 2H4l2-2zM10 21h4"/>',trophy:'<path d="M8 4h8v5a4 4 0 0 1-8 0V4z"/><path d="M8 6H5a3 3 0 0 0 3 4M16 6h3a3 3 0 0 1-3 4M12 13v4M9 20h6"/>',gift:'<rect x="3" y="9" width="18" height="12" rx="2"/><path d="M12 9v12M3 14h18M12 9c-2-4-6-4-5-1.5.6 1.5 5 1.5 5 1.5zM12 9c2-4 6-4 5-1.5-.6 1.5-5 1.5-5 1.5z"/>',gem:'<path d="M6 4h12l3 5-9 11L3 9l3-5z"/><path d="M3 9h18M9 4L7 9l5 11M15 4l2 5-5 11"/>',chart:'<path d="M5 20V10M12 20V4M19 20v-7"/>',mark:'<path d="M7 4h10v17l-5-4-5 4V4z"/>',play:'<path d="M8 5v14l11-7L8 5z" fill="currentColor"/>',clock:'<circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/>',fire:'<path d="M12 3c1 4 5 5 5 10a5 5 0 0 1-10 0c0-2 1-3 2-4 0 2 1 3 2 3 0-3-1-5 1-9z"/>',rank:'<path d="M12 3l7 4v10l-7 4-7-4V7l7-4z"/><path d="M12 8l1.3 2.6 2.9.4-2.1 2 .5 2.9-2.6-1.4-2.6 1.4.5-2.9-2.1-2 2.9-.4L12 8z"/>',bio:'<path d="M5 4h11a3 3 0 0 1 3 3v13H8a3 3 0 0 1-3-3V4z"/><path d="M9 9h6M9 13h6"/>'};
function ic(n){return'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">'+IC[n]+'</svg>'}
document.getElementById("bl").innerHTML=ic("bell");document.getElementById("av").innerHTML=ic("user");
document.getElementById("bn").innerHTML=[["#","Bosh sahifa","home"],["#kutubxona","Kutubxona","lib"],["#tavsiya","Tavsiya","spark"],["#statistika","Statistika","chart"],["#profil","Profil","user"]].map(function(a){return'<a href="'+a[0]+'"><i>'+ic(a[2])+'</i>'+a[1]+'</a>'}).join("");
function clean(d){var o={works:[],cfg:{a:"",c:"",m:false}};if(!d||typeof d!="object")return o;
(Array.isArray(d.works)?d.works:[]).forEach(function(w){if(!w||!/^[a-z0-9]{1,20}$/.test(w.id)||w.s=="q")return;o.works.push({id:w.id,t:String(w.t||"").slice(0,120),k:K.indexOf(w.k)>-1?w.k:"Novel",g:String(w.g||"").slice(0,40),d:String(w.d||"").slice(0,1000),p:!!w.p,st:w.st=="completed"?"completed":"ongoing",cv:/^data:image\/jpeg;base64,[A-Za-z0-9+\/=]{1,400000}$/.test(w.cv||"")?w.cv:"",ch:(Array.isArray(w.ch)?w.ch:[]).map(String)})});
var c=d.cfg||{};o.cfg={a:String(c.a||"").slice(0,300),c:/^https:\/\/(t\.me|telegram\.me)\/[\w\/.-]*$/.test(c.c)?c.c:"",m:!!c.m};return o}
function W(id){for(var i=0;i<D.works.length;i++)if(D.works[i].id==id)return D.works[i]}
function hue(s){var h=0;for(var i=0;i<s.length;i++)h=(h*31+s.charCodeAt(i))%360;return h}
function pct(w,k){return w.ch.length?Math.round(k/w.ch.length*100):0}
function mi(w){return S.int.indexOf(w.g)>-1||S.int.indexOf(w.k)>-1}
function bg(w){var h=240+hue(w.id)%90;return"radial-gradient(120% 80% at 85% 0%,hsl("+((h+30)%360)+" 70% 45% / .6),transparent 60%),linear-gradient(165deg,hsl("+h+" 45% 22%),hsl("+((h+40)%360)+" 50% 8%))"}
function bi(w){return w.cv?"linear-gradient(180deg,rgba(0,0,0,.1) 35%,rgba(0,0,0,.85)),url('"+w.cv+"') center/cover":bg(w)}
function cv(w,big){return'<a class="cv" href="#asar/'+w.id+'"><i class="'+(w.cv?"ci":"")+'" style="background:'+bi(w)+'"><em>'+esc(w.k)+'</em><s>'+esc(w.t)+'<b>Yangi</b></s></i>'+(big?"":'<span>'+esc(w.t)+'<small>'+esc(w.g)+(w.au?' · '+esc(w.au):'')+'</small></span>')+'</a>'}
function row(l){return'<div class="row">'+l.map(function(w){return cv(w)}).join("")+'</div>'}
function sh(n,t,h){return'<div class="sh">'+ic(n)+'<b>'+t+'</b>'+(h?'<a href="'+h+'">Barchasi →</a>':"")+'</div>'}
function em(n,t){return'<div class="em">'+ic(n)+'<p>'+t+'</p></div>'}
function streak(){var d=new Date(),n=0;if(!S.log[dk(d)])d.setDate(d.getDate()-1);while(S.log[dk(d)]){n++;d.setDate(d.getDate()-1)}return n}
function track(w,k){var d=dk(new Date()),key=w.id+":"+k;S.hide=0;S.last={id:w.id,k:k,p:(S.last&&S.last.id==w.id&&S.last.k==k)?(S.last.p||0):0};if(k>=w.ch.length)S.done[w.id]=d;var hr=new Date().getHours();S.hr[hr]=(S.hr[hr]||0)+1;S.prog[w.id]=Math.max(S.prog[w.id]||0,k);if(!S.hist[w.id])S.hist[w.id]={s:d};S.hist[w.id].l=d;if(!S.seen[key]){S.seen[key]=1;S.log[d]=(S.log[d]||0)+1}sv()}
function smart(){var gs={},ts={};Object.keys(S.prog).forEach(function(i){var w=W(i);if(w){gs[w.g]=(gs[w.g]||0)+1;ts[w.k]=(ts[w.k]||0)+1}});
return D.works.filter(function
