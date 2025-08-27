
<!doctype html>
<html lang="ru">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>WAKA NEITRALO VIP — элитный каталог</title>
<meta name="description" content="WAKA NEITRALO VIP — премиум витрина одноразок. Реальные модели, реальные вкусы и цены в тенге. 18+." />
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg-1:#030312;
  --bg-2:#071026;
  --glass: rgba(255,255,255,0.03);
  --muted: #9aa3b2;
  --accent1: #7c5cff;
  --accent2: #33ffd1;
  --gold: linear-gradient(90deg,#ffd97d,#ff9f1c);
  --card-radius:16px;
}
*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0; font-family:Inter,system-ui,Arial,sans-serif; background:radial-gradient(800px 400px at 10% 10%, rgba(124,92,255,0.05), transparent),
  linear-gradient(180deg,var(--bg-1),var(--bg-2)); color:#e7eef8; -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale; overflow-x:hidden;
}

/* particles background */
.bg-canvas{position:fixed;inset:0;z-index:0;pointer-events:none;mix-blend-mode:screen;}

/* header / hero */
.header{position:relative; padding:48px 20px 24px; z-index:10; display:flex;align-items:center;justify-content:center;flex-direction:column;text-align:center}
.logo{font-family:"Playfair Display",serif;font-weight:700;font-size:34px;letter-spacing:2px;
  background:linear-gradient(90deg,#fff 0%, #d7d2ff 30%, #33ffd1 70%);
  -webkit-background-clip:text; -webkit-text-fill-color:transparent; text-transform:uppercase;}
.lead{color:var(--muted); margin-top:8px; max-width:860px}
.hero-orn{margin-top:18px; display:flex; gap:10px; align-items:center; justify-content:center}

/* VIP ribbon */
.ribbon{
  margin-top:18px; padding:8px 14px; border-radius:999px; font-weight:800; color:#081026;
  background: linear-gradient(90deg,#ffd97d,#ff9f1c);
  box-shadow:0 10px 30px rgba(255,170,90,.12), inset 0 -2px 0 rgba(255,255,255,.06);
}

/* layout */
.wrap{max-width:1200px;margin:0 auto;padding:18px}
.controls{display:flex;gap:10px;flex-wrap:wrap;align-items:center;justify-content:center;margin:20px 0 8px;z-index:10}
.input, select{background:var(--glass); border:1px solid rgba(255,255,255,.04); color:var(--muted); padding:10px 12px; border-radius:12px; min-width:160px; outline:none}
.btn{padding:10px 14px;border-radius:12px;border:none;cursor:pointer;font-weight:800;background:linear-gradient(135deg,var(--accent2),#a1ffdd);color:#031022; box-shadow:0 12px 30px rgba(51,255,209,.06)}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,.06); color:var(--muted)}

/* grid of cards */
.grid{display:grid; grid-template-columns: repeat(auto-fill,minmax(260px,1fr)); gap:18px; margin-top:18px; z-index:10}
.card{position:relative; overflow:hidden; border-radius:var(--card-radius);
  background: linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.007));
  border:1px solid rgba(255,255,255,.04); padding:14px; box-shadow:0 12px 40px rgba(3,6,10,.6);
  transition: transform .45s cubic-bezier(.2,.9,.2,1), box-shadow .45s, border-color .35s; transform:translateY(12px) scale(.995); opacity:0; }
.card.revealed{transform:none;opacity:1}
.card:hover{transform:translateY(-8px) scale(1.02); box-shadow:0 30px 80px rgba(124,92,255,.06); border-color: rgba(124,92,255,.18)}

/* top badge */
.badge-row{display:flex;justify-content:space-between;align-items:center;gap:8px}
.puffs{font-weight:800;background:linear-gradient(90deg,#ffffff08,#ffffff02);padding:6px 10px;border-radius:999px;color:var(--muted);font-size:13px}
.tags{display:flex;gap:6px;flex-wrap:wrap}
.tag{background:rgba(255,255,255,.03);padding:6px 8px;border-radius:999px;font-weight:700;font-size:12px;color:var(--muted);border:1px solid rgba(255,255,255,.03)}

/* title and price */
.title{font-weight:800;margin-top:10px;font-size:16px;display:flex;justify-content:space-between;align-items:center;gap:8px}
.price{font-weight:900;background:linear-gradient(90deg,#b3fff0,#7ce0ff); -webkit-background-clip:text; -webkit-text-fill-color:transparent; font-size:16px}

/* flavors */
.flavors{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.flavor{font-size:13px;padding:6px 8px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.01));border:1px solid rgba(255,255,255,.03);color:var(--muted)}

/* actions */
.actions{display:flex;gap:8px;align-items:center;margin-top:12px;justify-content:space-between}
.actions .left{display:flex;gap:8px;align-items:center}
.link-tg{background:linear-gradient(90deg,#5eead4,#a7f3d0);padding:9px 12px;border-radius:10px;font-weight:900;color:#041021;text-decoration:none;display:inline-flex;align-items:center;gap:8px}
.copy-btn{background:transparent;border:1px solid rgba(255,255,255,.05);padding:9px 12px;border-radius:10px;color:var(--muted);font-weight:800;cursor:pointer}

/* favorites star */
.fav{background:transparent;border:none;color:var(--muted);font-size:18px;cursor:pointer}
.fav.active{color:gold;text-shadow:0 6px 18px rgba(255,215,0,.12)}

/* footer */
.footer{padding:28px 20px;text-align:center;color:var(--muted)}

/* age modal */
.age{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,rgba(2,6,23,.88),rgba(2,6,23,.92));z-index:60;backdrop-filter: blur(6px)}
.modal{width:min(540px,92vw);background:linear-gradient(180deg,#071026,#0b1224);padding:22px;border-radius:14px;border:1px solid rgba(255,255,255,.04);text-align:center}
.modal h3{font-family:"Playfair Display",serif;margin:6px 0 8px}
.modal p{color:var(--muted)}

/* toast */
.toast{position:fixed;left:50%;transform:translateX(-50%);bottom:26px;background:#071028;padding:10px 14px;border-radius:10px;border:1px solid rgba(255,255,255,.06);opacity:0;transition:all .25s}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}

/* small responsive */
@media (max-width:640px){
  .controls{flex-direction:column;align-items:stretch}
  .title{font-size:15px}
}
</style>
</head>
<body>
<!-- SVG particles background -->
<div class="bg-canvas" aria-hidden="true">
  <svg width="100%" height="100%" viewBox="0 0 1600 900" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" style="position:fixed;left:0;top:0;z-index:0;opacity:.25;mix-blend-mode:screen">
    <defs>
      <radialGradient id="g" cx="50%" cy="20%"><stop offset="0" stop-color="#7c5cff"/><stop offset="1" stop-color="#33ffd1" stop-opacity="0"/></radialGradient>
    </defs>
    <rect width="1600" height="900" fill="url(#g)" />
    <g fill="#ffffff" opacity="0.06">
      <circle cx="200" cy="120" r="2"/><circle cx="400" cy="80" r="1.6"/><circle cx="900" cy="100" r="2.2"/>
      <circle cx="1200" cy="200" r="1.2"/><circle cx="520" cy="240" r="1.4"/>
    </g>
  </svg>
</div>

<header class="header">
  <div class="logo">WAKA NEITRALO VIP</div>
  <div class="lead">Эксклюзивная VIP‑витрина одноразок — реальные модели, реальные вкусы, аккуратные цены в тенге. Только для 18+.</div>
  <div class="hero-orn"><div class="ribbon">VIP • Альфа‑коллекция</div></div>
</header>

<main class="wrap" role="main">
  <div class="controls" role="search">
    <input id="q" class="input" placeholder="Поиск: модель или вкус (напр. арбуз, манго)">
    <select id="puffs" class="input">
      <option value="">Пыхи — все</option>
      <option value="<=1000">до 1000</option>
      <option value="1001-3000">1001–3000</option>
      <option value="3001-8000">3001–8000</option>
      <option value="8001-15000">8001–15000</option>
      <option value=">15000">больше 15000</option>
    </select>
    <select id="nic" class="input">
      <option value="">Никотин — любой</option>
      <option value="2%">2%</option>
      <option value="3%">3%</option>
      <option value="5%">5%</option>
      <option value="18mg">18mg</option>
      <option value="20mg">20mg</option>
    </select>
    <button class="btn" id="copyTag" data-copy="@neitralo">Скопировать тег @neitralo</button>
    <button class="btn ghost" id="themeToggle">Тема</button>
  </div>

  <section class="grid" id="grid" aria-live="polite"></section>

  <div class="footer">18+ Только для совершеннолетних. Telegram: <strong>@neitralo</strong></div>
</main>

<!-- age modal -->
<div class="age" id="age">
  <div class="modal">
    <h3>Вам уже исполнилось 18 лет?</h3>
    <p>На сайте информация о никотинсодержащей продукции. Подтвердите возраст, чтобы продолжить.</p>
    <div style="margin-top:12px">
      <button class="btn" id="ageYes">Да, мне 18+</button>
      <button class="btn ghost" id="ageNo">Нет</button>
    </div>
  </div>
</div>

<div class="toast" id="toast">Скопировано</div>

<script>
// Модели (с ценами в тенге)
const MODELS = [
  {name:"WAKA Solo 600", puffs:600, price:"3 000 ₸", flavors:["Клубника","Ваниль","Табак"], tags:["мини","компакт"]},
  {name:"WAKA Solo 1500", puffs:1500, price:"4 000 ₸", flavors:["Клубника лёд","Манго","Мята"], tags:["популярная"]},
  {name:"WAKA Solo 1800", puffs:1800, price:"4 500 ₸", flavors:["Ананас","Вишня","Свежая мята"], tags:["компакт"]},
  {name:"WAKA Solo 2500", puffs:2500, price:"5 000 ₸", flavors:["Манго апельсин","Клубника манго"], tags:[]},
  {name:"WAKA Smash 6000", puffs:6000, price:"7 500 ₸", flavors:["Арбуз лёд","Алоэ виноград","Клубника манго"], tags:["mesh","USB‑C"]},
  {name:"WAKA soPro PA7000", puffs:7000, price:"8 500 ₸", flavors:["Арбуз лёд","Черника-малина","Манго персик"], tags:["USB‑C","14 мл"]},
  {name:"WAKA soPro PA10000", puffs:10000, price:"10 500 ₸", flavors:["Клубника киви","Черника малина","Персиковый лёд"], tags:["USB‑C","18 мл"]},
  {name:"WAKA soPro 20000", puffs:20000, price:"15 500 ₸", flavors:["Манго смузи","Персик лёд","Киви пассион"], tags:["DualMesh","850 мАч"]},
  {name:"WAKA DUO 28000", puffs:28000, price:"12 000 ₸", flavors:["Двойной манго","Двойная ягода"], tags:["DUO"]},
  {name:"WAKA Heavy Hitter 30000", puffs:30000, price:"20 000 ₸", flavors:["Майами мята","Белый виноград","Тропический микс"], tags:["Heavy Hitter","DualMesh"]},
  {name:"WAKA ProMax 12000", puffs:12000, price:"11 000 ₸", flavors:["Манго апельсин","Капучино"], tags:["ProMax","USB‑C"]}
];

const grid = document.getElementById('grid');
const q = document.getElementById('q');
const puffs = document.getElementById('puffs');
const nic = document.getElementById('nic');
const toast = document.getElementById('toast');
const copyTagBtn = document.getElementById('copyTag');

function createCard(m, idx){
  const c = document.createElement('article');
  c.className = 'card';
  c.innerHTML = `
    <div class="badge-row">
      <div class="puffs">${m.puffs.toLocaleString()} пых</div>
      <div class="tags">${m.tags.map(t=>`<span class="tag">${t}</span>`).join('')}</div>
    </div>
    <div class="title"><span>${m.name}</span><span class="price">${m.price}</span></div>
    <div class="flavors">${m.flavors.map(f=>`<span class="flavor">${f}</span>`).join('')}</div>
    <div class="actions">
      <div class="left">
        <a class="link-tg" href="https://t.me/neitralo?text=${encodeURIComponent('Привет! Хочу '+m.name)}" target="_blank">Купить в Telegram</a>
        <button class="copy-btn" data-copy="@neitralo">Скопировать</button>
      </div>
      <div>
        <button class="fav" data-idx="${idx}" title="Избранное">☆</button>
      </div>
    </div>
  `;
  return c;
}

function render(){
  grid.innerHTML = '';
  const txt = q.value.trim().toLowerCase();
  const pr = puffs.value;
  const nr = nic.value;

  MODELS.filter(m=>{
    const matchTxt = !txt || m.name.toLowerCase().includes(txt) || m.flavors.some(f=>f.toLowerCase().includes(txt));
    const matchPuffs = !pr || (
      pr === '<=1000' && m.puffs <= 1000 ||
      pr === '1001-3000' && m.puffs>=1001 && m.puffs<=3000 ||
      pr === '3001-8000' && m.puffs>=3001 && m.puffs<=8000 ||
      pr === '8001-15000' && m.puffs>=8001 && m.puffs<=15000 ||
      pr === '>15000' && m.puffs>15000
    );
    const matchNic = !nr || m.nicotine?.some(n=>n.includes(nr));
    return matchTxt && matchPuffs && matchNic;
  }).forEach((m,i)=>{
    const card = createCard(m,i);
    grid.appendChild(card);
  });

  // reveal animation
  const io = new IntersectionObserver((entries)=>{
    entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('revealed'); io.unobserve(e.target); } });
  },{threshold:.12});
  document.querySelectorAll('.card').forEach(c=> io.observe(c));

  // copy handlers
  document.querySelectorAll('.copy-btn').forEach(b=> b.onclick = async ()=>{
    try{ await navigator.clipboard.writeText(b.dataset.copy); showToast('Скопировано: ' + b.dataset.copy); confetti(b) }catch{ showToast('Не удалось скопировать') }
  });

  // fav handlers
  document.querySelectorAll('.fav').forEach(btn=>{
    const idx = btn.dataset.idx;
    const favs = JSON.parse(localStorage.getItem('waka_vip_favs')||'{}');
    if(favs[idx]){ btn.classList.add('active'); btn.textContent='★'; } else btn.textContent='☆';
    btn.onclick = ()=>{
      const favs = JSON.parse(localStorage.getItem('waka_vip_favs')||'{}');
      if(favs[idx]){ delete favs[idx]; btn.classList.remove('active'); btn.textContent='☆'; showToast('Удалено из избранного') }
      else{ favs[idx]=true; btn.classList.add('active'); btn.textContent='★'; showToast('Добавлено в избранное') }
      localStorage.setItem('waka_vip_favs', JSON.stringify(favs));
    };
  });
}

// confetti effect
function confetti(el){
  try{
    const rect = el.getBoundingClientRect();
    for(let i=0;i<18;i++){
      const p = document.createElement('span');
      p.style.position='fixed'; p.style.left = (rect.left+rect.width/2)+'px'; p.style.top = (rect.top+rect.height/2)+'px';
      p.style.width='6px'; p.style.height='6px'; p.style.borderRadius='2px';
      p.style.background = ['#ffd97d','#7c5cff','#33ffd1','#b084ff'][i%4];
      p.style.zIndex=120; document.body.appendChild(p);
      const dx = (Math.random()*2-1)*140; const dy = -30 - Math.random()*160; const rot = Math.random()*360;
      p.animate([{transform:'translate(0,0) rotate(0deg)', opacity:1},{transform:`translate(${dx}px,${dy}px) rotate(${rot}deg)`, opacity:0}],{duration:600+Math.random()*600}).onfinish=()=>p.remove();
    }
  }catch(e){}
}

function showToast(t){ toast.textContent = t; toast.classList.add('show'); setTimeout(()=>toast.classList.remove('show'),1200); }

// age gate
const ageModal = document.getElementById('age');
const ageYes = document.getElementById('ageYes');
const ageNo = document.getElementById('ageNo');
ageYes.addEventListener('click', ()=>{ try{ localStorage.setItem('waka_vip_age','yes') }catch{}; ageModal.style.display='none'; showToast('Приятного просмотра') });
ageNo.addEventListener('click', ()=>{ alert('Доступ запрещён'); window.location.href='https://www.google.com' });
try{ if(localStorage.getItem('waka_vip_age')==='yes') ageModal.style.display='none' }catch{}

// copy tag main
copyTagBtn.addEventListener('click', async ()=>{ try{ await navigator.clipboard.writeText(copyTagBtn.dataset.copy); showToast('Скопировано: ' + copyTagBtn.dataset.copy); confetti(copyTagBtn) }catch{ showToast('Не удалось скопировать') } });

// theme toggle (soft)
document.getElementById('themeToggle').addEventListener('click', ()=>{
  const is = document.documentElement.classList.toggle('light');
  if(is){
    document.documentElement.style.setProperty('--bg-1','#f6f8ff');
    document.documentElement.style.setProperty('--bg-2','#eef2ff');
    document.documentElement.style.setProperty('--accent2','#06b6d4');
    document.body.style.color='#061025';
  } else {
    document.documentElement.style.removeProperty('--bg-1');
    document.documentElement.style.removeProperty('--bg-2');
    document.documentElement.style.removeProperty('--accent2');
    document.body.style.color='';
  }
});

// search + filters
q.addEventListener('input', render);
puffs.addEventListener('change', render);
nic.addEventListener('change', render);

render();

// pointer sparkle on hover for card covers
document.addEventListener('pointermove', e=>{
  const els = document.elementsFromPoint(e.clientX, e.clientY);
  const card = els.find(x=> x.classList && x.classList.contains('card'));
  document.querySelectorAll('.card').forEach(c=> c.style.boxShadow = '');
  if(card) card.style.boxShadow = '0 40px 100px rgba(124,92,255,.08)';
});
</script>
</body>
</html>
