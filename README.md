<!DOCTYPE html>

<html lang="tr"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">

<title>Fadişim ❤️</title>

<style>

*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif}

body{min-height:100vh;overflow:hidden;background:linear-gradient(135deg,#ffd1e6,#ff8fbc,#ff6ca5);display:flex;justify-content:center;align-items:center}

.top{position:fixed;top:18px;left:18px;right:18px;background:rgba(255,255,255,.28);backdrop-filter:blur(10px);border-radius:18px;padding:14px 20px;display:flex;justify-content:space-between;color:#fff;font-weight:bold;box-shadow:0 8px 25px rgba(0,0,0,.15)}

.right{display:flex;gap:10px;align-items:center}

.right button,#btn{border:none;border-radius:12px;padding:9px 16px;background:#ff2d6f;color:#fff;cursor:pointer}

.center{display:flex;flex-direction:column;align-items:center;gap:24px;margin-top:40px}

.heart{position:relative;width:150px;height:150px;background:#ff174f;transform:rotate(-45deg);animation:beat 1.2s infinite}

.heart:before,.heart:after{content:"";position:absolute;width:150px;height:150px;background:#ff174f;border-radius:50%}

.heart:before{top:-75px}.heart:after{left:75px}

.name{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%) rotate(45deg);z-index:2;color:#fff;font-size:24px;font-weight:bold}

@keyframes beat{50%{transform:rotate(-45deg) scale(1.08)}}

#msg{display:none;max-width:520px;background:#fff;border-radius:18px;padding:20px;color:#d81b60;line-height:1.7;text-align:center;animation:up .4s}

@keyframes up{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:none}}

.float{position:absolute;bottom:-30px;color:#e60039;animation:fly linear infinite}

@keyframes fly{to{transform:translateY(-120vh);opacity:0}}

</style></head>

<body>

<div class="top"><div>02/07/2026 - ∞</div><div class="right">🎵 Seyre Dursun Aşk <button onclick="toggle()">▶ / ⏸</button></div></div>

<div class="center">

<div class="heart"><div class="name">Fadişim</div></div>

<button id="btn" onclick="showMsg()">Bas</button>

<div id="msg">Seninle tanışmak benim için çok büyük bir mutluluk oldu. İyi ki o gün o gruba girmişim ve seninle karşılaşmışım.<br><br>Seni çok seviyorum hayatımmm. ❤️<br>İyi ki varsın.</div>

</div>

<audio id="music">

    <source src="Gulsen-Seyre-Dursun-Ask-[AudioTrimmer.com].mp3" type="audio/mpeg">

</audio>

<script>

const a=document.getElementById('music');

function toggle(){a.paused?a.play():a.pause();}

function showMsg(){let m=document.getElementById('msg');m.style.display=m.style.display==='block'?'none':'block';}

for(let i=0;i<30;i++){let s=document.createElement('div');s.className='float';s.innerHTML='❤️';s.style.left=Math.random()*100+'vw';s.style.fontSize=(15+Math.random()*18)+'px';s.style.animationDuration=(6+Math.random()*6)+'s';s.style.animationDelay=(-Math.random()*8)+'s';document.body.appendChild(s);}

</script>

</body></html>



bana bu kodları alt alta yazabilir misin
