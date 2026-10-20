# MK-candell-
mk candell sell website
<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>MK Candles – Light Up Your Moments | Handmade Candles India</title>
<meta name="description" content="Shop handmade scented, decorative, flower and gift candles from MK Candles. Order easily on WhatsApp.">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--cream:#FAF5EE;--beige:#E8D8C3;--brown:#3B2A20;--gold:#C8A96B;--white:#fff;--sh:0 8px 28px rgba(59,42,32,.12)}
*{box-sizing:border-box;margin:0}html{scroll-behavior:smooth;scroll-padding-top:72px}
body{font-family:Inter,sans-serif;background:var(--cream);color:var(--brown);line-height:1.6}
h1,h2,h3,.logo{font-family:'Cormorant Garamond',Georgia,serif;line-height:1.15}
img{max-width:100%;display:block}button,input,select,textarea{font:inherit;color:inherit}
button{cursor:pointer}a{color:inherit}
:focus-visible{outline:2px solid var(--gold);outline-offset:2px}
section{padding:72px 5%}.wrap{max-width:1200px;margin:auto}
h2{font-size:clamp(30px,4vw,44px);text-align:center;margin-bottom:8px}
.sub{text-align:center;opacity:.75;margin-bottom:36px;max-width:620px;margin-inline:auto}
.btn{background:var(--brown);color:var(--cream);border:0;padding:12px 24px;border-radius:30px;font-weight:600;text-decoration:none;display:inline-block;transition:.25s}
.btn:hover{background:var(--gold);color:var(--brown);transform:translateY(-2px)}
.btn.gold{background:var(--gold);color:var(--brown)}.btn.gold:hover{background:var(--white)}
.btn.out{background:transparent;border:1.5px solid currentColor;color:inherit}
.btn.sm{padding:9px 16px;font-size:14px}
nav{position:sticky;top:0;z-index:50;background:rgba(250,245,238,.95);backdrop-filter:blur(8px);border-bottom:1px solid var(--beige);display:flex;align-items:center;gap:20px;padding:12px 5%}
.logo{font-size:26px;font-weight:700;text-decoration:none;margin-right:auto}.logo span{color:var(--gold)}
.links{display:flex;gap:22px}.links a{text-decoration:none;font-size:15px}.links a:hover{color:var(--gold)}
.ib{background:none;border:0;font-size:20px;position:relative;padding:4px 6px}
.cnt{position:absolute;top:-6px;right:-6px;background:var(--gold);color:var(--brown);font-size:11px;font-weight:700;border-radius:50%;min-width:18px;height:18px;display:grid;place-items:center}
#burger{display:none}
#sbar{display:none;padding:10px 5%;background:var(--white);position:sticky;top:60px;z-index:49;border-bottom:1px solid var(--beige)}
#sbar input{width:100%;padding:10px 16px;border-radius:30px;border:1px solid var(--beige)}
@media(max-width:860px){#burger{display:block}.links{display:none;position:absolute;top:100%;left:0;right:0;background:var(--cream);flex-direction:column;padding:16px 5%;box-shadow:var(--sh)}.links.open{display:flex}}
.hero{height:88vh;min-height:520px;position:relative;display:grid;place-items:center;text-align:center;color:#fff;padding:0 6%;overflow:hidden;background:linear-gradient(135deg,#6b4a35,#3B2A20)}
.hero .bg{position:absolute;inset:0;background-size:cover;background-position:center;opacity:0;transition:opacity 1.2s}.hero .bg.on{opacity:1}
.hero:after{content:"";position:absolute;inset:0;background:linear-gradient(rgba(59,42,32,.5),rgba(59,42,32,.62))}
.hero div.in{position:relative;z-index:2;max-width:760px;animation:up .9s}
.hero h1{font-size:clamp(40px,7vw,72px);margin-bottom:16px}.hero p{font-size:18px;margin-bottom:28px}.hero .btn{margin:6px}
@keyframes up{from{opacity:0;transform:translateY(24px)}}
.fbar{text-align:center;margin-bottom:16px;font-size:14px}.fbar button{background:none;border:0;color:var(--gold);text-decoration:underline}
.cwrap{position:relative}
.track{display:flex;gap:20px;overflow-x:auto;scroll-snap-type:x mandatory;scroll-behavior:smooth;padding:8px 4px 24px;scrollbar-width:none}
.track::-webkit-scrollbar{display:none}
.card{flex:0 0 280px;scroll-snap-align:start;background:var(--white);border-radius:20px;box-shadow:var(--sh);overflow:hidden;display:flex;flex-direction:column;transition:.3s}
.card:hover{transform:translateY(-4px)}
.ph{position:relative;aspect-ratio:1;background:linear-gradient(135deg,var(--beige),var(--cream));cursor:pointer;overflow:hidden}
.ph img{width:100%;height:100%;object-fit:cover}
.badge{position:absolute;top:12px;left:12px;background:var(--gold);color:var(--brown);font-size:12px;font-weight:700;padding:3px 10px;border-radius:20px}
.demo{position:absolute;bottom:8px;left:8px;background:rgba(255,255,255,.85);font-size:10px;padding:2px 8px;border-radius:10px}
.wl{position:absolute;top:8px;right:8px;background:#fff;border:0;border-radius:50%;width:36px;height:36px;font-size:18px;box-shadow:var(--sh)}
.wl.on{color:#c0392b}
.cb{padding:16px;display:flex;flex-direction:column;gap:6px;flex:1}.cb h3{font-size:22px}
.cb p{font-size:14px;opacity:.75;flex:1}.meta{font-size:13px;color:#8a6d3b}
.price{font-weight:600;font-size:18px}.price s{font-size:13px;opacity:.5;font-weight:400;margin-left:6px}
.row{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.qty{display:inline-flex;align-items:center;border:1px solid var(--beige);border-radius:30px}
.qty button{background:none;border:0;width:30px;height:30px;font-size:18px}.qty span{min-width:24px;text-align:center}
.arr{position:absolute;top:40%;background:var(--white);border:0;width:44px;height:44px;border-radius:50%;box-shadow:var(--sh);font-size:20px;z-index:3}
.arr.l{left:-14px}.arr.r{right:-14px}@media(max-width:700px){.arr{display:none}}
.cols{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:18px}
.col{position:relative;height:200px;border-radius:20px;overflow:hidden;border:0;background:linear-gradient(135deg,var(--beige),var(--gold));color:#fff;font-family:'Cormorant Garamond',serif;font-size:26px;font-weight:700;text-shadow:0 2px 8px rgba(0,0,0,.5)}
.col img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;transition:.5s}.col:hover img{transform:scale(1.08)}
.col:after{content:"";position:absolute;inset:0;background:rgba(59,42,32,.35)}.col b{position:relative;z-index:2}
.gift{background:var(--brown);color:var(--cream)}.gift h2{color:var(--cream)}
.gift .card{color:var(--brown)}.gift .sub{opacity:.85}
.feat{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:20px}
.ft{background:var(--white);padding:28px;border-radius:20px;text-align:center;box-shadow:var(--sh)}.ft i{font-size:36px;font-style:normal}.ft h3{margin:8px 0;font-size:24px}.ft p{font-size:14px;opacity:.8}
.about{display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:center}
.about img,.about .ph2{border-radius:20px;box-shadow:var(--sh);width:100%;aspect-ratio:4/3;object-fit:cover;background:var(--beige)}
.about h2{text-align:left}@media(max-width:760px){.about{grid-template-columns:1fr}}
.rev{background:var(--white);padding:24px;border-radius:20px;box-shadow:var(--sh);font-size:14px}.tag{font-size:11px;background:var(--beige);padding:2px 10px;border-radius:12px;display:inline-block;margin-bottom:8px}
.ig{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:10px;margin-bottom:28px}
.ig img{aspect-ratio:1;object-fit:cover;width:100%;border-radius:14px;background:var(--beige);transition:.3s}.ig img:hover{transform:scale(1.04)}
.cont{display:grid;grid-template-columns:1fr 1fr;gap:40px}@media(max-width:760px){.cont{grid-template-columns:1fr}}
label{display:block;font-size:14px;font-weight:500;margin:10px 0 4px}
.in,input.in,textarea.in,select.in{width:100%;padding:11px 14px;border:1px solid var(--beige);border-radius:12px;background:var(--white)}
.err{color:#b03a2e;font-size:12px;min-height:16px}.note{font-size:13px;margin-top:10px}
footer{background:var(--brown);color:var(--beige);padding:48px 5% 24px}
.fg{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:28px;max-width:1200px;margin:auto}
footer a,footer button.lk{display:block;color:var(--beige);background:none;border:0;padding:3px 0;text-align:left;text-decoration:none;font-size:14px}footer a:hover,footer button.lk:hover{color:var(--gold)}
footer h4{color:var(--gold);margin-bottom:8px}.copy{text-align:center;font-size:13px;margin-top:32px;opacity:.7}
.ov{position:fixed;inset:0;background:rgba(59,42,32,.55);z-index:100;display:none;align-items:center;justify-content:center;padding:16px}.ov.on{display:flex}
.md{background:var(--cream);border-radius:22px;max-width:900px;width:100%;max-height:92vh;overflow:auto;padding:28px;position:relative}
.x{position:absolute;top:12px;right:16px;background:none;border:0;font-size:28px}
.dg{display:grid;grid-template-columns:1fr 1fr;gap:28px}@media(max-width:700px){.dg{grid-template-columns:1fr}}
.th{display:flex;gap:8px;margin-top:8px}.th img{width:64px;height:64px;object-fit:cover;border-radius:10px;cursor:pointer;border:2px solid transparent;background:var(--beige)}.th img.on{border-color:var(--gold)}
.drawer{position:fixed;top:0;right:0;bottom:0;width:min(420px,100%);background:var(--cream);z-index:101;transform:translateX(100%);transition:.35s;display:flex;flex-direction:column;box-shadow:var(--sh)}.drawer.on{transform:none}
.drawer header{padding:18px 20px;border-bottom:1px solid var(--beige);display:flex;justify-content:space-between;align-items:center}
.items{flex:1;overflow:auto;padding:16px 20px}.it{display:flex;gap:12px;margin-bottom:16px;font-size:14px}.it img{width:70px;height:70px;border-radius:12px;object-fit:cover;background:var(--beige)}
.drawer footer{background:var(--white);color:var(--brown);padding:16px 20px}
.sm2{font-size:13px;display:flex;justify-content:space-between}.tot{font-weight:700;font-size:18px}
.toast{position:fixed;bottom:24px;left:50%;transform:translate(-50%,100px);background:var(--brown);color:#fff;padding:12px 22px;border-radius:30px;z-index:200;transition:.3s}.toast.on{transform:translate(-50%,0)}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style></head><body>
 
<nav>
<a class="logo" href="#home">MK <span>Candles</span></a>
<div class="links" id="links">
<a href="#home">Home</a><a href="#shop">Shop Candles</a><a href="#collections">Collections</a><a href="#best">Best Sellers</a><a href="#about">About Us</a><a href="#contact">Contact</a></div>
<button class="ib" id="sb" aria-label="Search">🔍</button>
<button class="ib" id="wb" aria-label="Wishlist">♡<span class="cnt" id="wc">0</span></button>
<button class="ib" id="cb" aria-label="Open cart">🛒<span class="cnt" id="cc">0</span></button>
<button class="ib" id="burger" aria-label="Menu">☰</button>
</nav>
<div id="sbar"><input id="q" type="search" placeholder="Search candles, fragrances…" aria-label="Search products"></div>
 
<header class="hero" id="home">
<div class="in"><h1>Light Up Your Moments with MK Candles</h1>
<p>Handcrafted with love. Designed to bring warmth, fragrance, and beautiful moments into your home.</p>
<a class="btn gold" href="#shop">Shop Candles</a><a class="btn out" href="#collections">Explore Our Collection</a></div></header>
 
<section id="shop"><div class="wrap">
<h2>Our Candles</h2><p class="sub">Sample products shown as demo data — prices and details will be replaced with MK Candles' real range.</p>
<div class="fbar" id="fbar"></div>
<div class="cwrap"><button class="arr l" aria-label="Previous" onclick="slide(-1)">‹</button>
<div class="track" id="track" aria-live="polite"></div>
<button class="arr r" aria-label="Next" onclick="slide(1)">›</button></div></div></section>
 
<section id="collections" style="background:var(--white)"><div class="wrap">
<h2>Collections</h2><p class="sub">Choose a collection to filter the candles above.</p><div class="cols" id="cols"></div></div></section>
 
<section id="best"><div class="wrap"><h2>Best Sellers</h2><p class="sub">Sample favourites (demo selection).</p><div class="cols" id="bests" style="grid-template-columns:repeat(auto-fill,minmax(260px,1fr))"></div></div></section>
 
<section class="gift" id="gifts"><div class="wrap">
<h2>Make Every Moment Special</h2><p class="sub">Discover thoughtful candle gifts for birthdays, celebrations, festivals, and everyday moments.</p>
<div class="cols" id="giftgrid" style="grid-template-columns:repeat(auto-fill,minmax(260px,1fr))"></div>
<p style="text-align:center;margin-top:28px"><button class="btn gold" onclick="filt('Gift Sets')">Shop Gifts</button></p></div></section>
 
<section><div class="wrap"><h2>Why Choose MK Candles?</h2><p class="sub"></p>
<div class="feat">
<div class="ft"><i>🕯️</i><h3>Handcrafted Designs</h3><p>Candles shaped with attention to detail and a handmade touch.</p></div>
<div class="ft"><i>🌸</i><h3>Beautiful Fragrance Options</h3><p>A range of scents to suit every mood and space.</p></div>
<div class="ft"><i>🎁</i><h3>Thoughtful Gifting</h3><p>Gift sets and personalised options for special occasions.</p></div>
<div class="ft"><i>📦</i><h3>Careful Packaging</h3><p>Packed with care so your candles arrive ready to enjoy.</p></div></div></div></section>
 
<section id="about" style="background:var(--white)"><div class="wrap about">
<img id="aboutimg" alt="MK Candles handmade candles" loading="lazy">
<div><h2>About MK Candles</h2>
<p id="abouttext">At MK Candles, we believe that small details can make everyday moments special. Explore our collection of decorative candles, fragrant favorites, and thoughtful gifts designed to bring warmth and beauty to your space.</p>
<p class="note">✏️ Edit this text in <code>index.html</code> (id="abouttext") to add your real story.</p></div></div></section>
 
<section><div class="wrap"><h2>Customer Reviews</h2><p class="sub">Placeholder layout only. Real customer reviews will appear here once collected.</p>
<div class="feat" id="revs"></div></div></section>
 
<section style="background:var(--white)"><div class="wrap"><h2>Discover MK Candles on Instagram</h2><p class="sub">Placeholder images until real photos are added.</p>
<div class="ig" id="ig"></div><p style="text-align:center"><a class="btn" id="igbtn" target="_blank" rel="noopener">Follow Us on Instagram</a></p></div></section>
 
<section id="contact"><div class="wrap"><h2>Contact Us</h2><p class="sub"></p>
<div class="cont"><div><h3>MK Candles</h3><p style="margin-top:10px">📧 <a id="em"></a><br>💬 <a id="wa" target="_blank" rel="noopener"></a><br>📷 <a id="ig2" target="_blank" rel="noopener">Instagram</a></p></div>
<form id="cf" novalidate><label for="cn">Name</label><input class="in" id="cn"><div class="err" id="e1"></div>
<label for="ce">Email</label><input class="in" id="ce" type="email"><div class="err" id="e2"></div>
<label for="cm">Message</label><textarea class="in" id="cm" rows="4"></textarea><div class="err" id="e3"></div>
<button class="btn" type="submit">Send Message</button><p class="note" id="cmsg" role="status"></p></form></div></div></section>
 
<footer><div class="fg">
<div><div class="logo" style="font-size:28px;color:#fff">MK <span>Candles</span></div><p style="font-style:italic;margin-top:6px">Light Up Your Moments</p></div>
<div><h4>Explore</h4><a href="#collections">Shop Collections</a><a href="#best">Best Sellers</a><a href="#about">About Us</a><a href="#contact">Contact Us</a><a id="ig3" target="_blank" rel="noopener">Instagram</a></div>
<div><h4>Policies</h4><button class="lk" data-pol="Shipping Policy">Shipping Policy</button><button class="lk" data-pol="Return and Refund Policy">Return and Refund Policy</button><button class="lk" data-pol="Privacy Policy">Privacy Policy</button><button class="lk" data-pol="Terms and Conditions">Terms and Conditions</button></div></div>
<div class="copy">© <span id="yr"></span> MK Candles. All rights reserved.</div></footer>
 
<div class="ov" id="ov"><div class="md" id="md" role="dialog" aria-modal="true"></div></div>
<div class="drawer" id="dr" aria-label="Shopping cart"><header><h3>Your Cart</h3><button class="x" style="position:static" onclick="cart(0)" aria-label="Close cart">×</button></header>
<div class="items" id="items"></div>
<footer id="cf2"></footer></div>
<div class="toast" id="toast" role="status"></div>
 
<script>
/* ===== CONFIG: edit these ===== */
const CFG={brand:"MK Candles",wa:"919302844154" /* country code + number, no + */,email:"monikakorram0802@gmail.com",
ig:"https://www.instagram.com/mk_candles.8?dlrf=ZnByYmxmMG13YjF6",shipFee:60,freeShipAbove:999,
// Future: orderApi:"https://your-backend/orders", razorpayKey:""
orderApi:"",razorpayKey:""};
const IMGS=["https://i.ibb.co/1JTRYzWK/Whats-App-Image-2026-10-20-at-2-29-59-AM.jpg","https://i.ibb.co/CK9x2FKp/Whats-App-Image-2026-10-20-at-2-29-58-AM.jpg","https://i.ibb.co/wNDr7nDg/Whats-App-Image-2026-10-20-at-2-29-58-AM.jpg"];
const CATS=["Scented","Decorative","Flower","Pillar","Gift Sets","Birthday","Festive","Personalized"];
/* ===== PRODUCT DATA (DEMO) — replace names, prices, images (img:[...urls]) ===== */
const S=[["Small (100g)",0],["Medium (200g)",150]];
const P=[
{id:1,n:"Vanilla Scented Candle",c:"Scented",d:"A warm, comforting vanilla fragrance for cozy evenings.",p:349,m:449,sc:["Vanilla"],sz:S,bs:1},
{id:2,n:"Rose Aroma Candle",c:"Scented",d:"A soft floral rose fragrance in an elegant finish.",p:379,sc:["Rose"],sz:S,bs:1},
{id:3,n:"Lavender Relaxing Candle",c:"Scented",d:"A calming lavender scent to help you unwind.",p:369,sc:["Lavender"],sz:S},
{id:4,n:"Classic White Pillar Candle",c:"Pillar",d:"A timeless pillar candle for dining tables and décor.",p:249,sz:[["3 inch",0],["6 inch",120]],cl:["White","Ivory"]},
{id:5,n:"Decorative Flower Candle",c:"Flower",d:"A flower-shaped candle that doubles as a display piece.",p:299,m:399,sz:[["Single",0],["Set of 3",450]],cl:["Pink","White","Peach"],bs:1},
{id:6,n:"Bubble Cube Candle",c:"Decorative",d:"A trendy bubble-textured cube for modern spaces.",p:279,sz:[["Standard",0]],cl:["Cream","Pink","Beige"]},
{id:7,n:"Luxury Gift Candle Set",c:"Gift Sets",d:"A curated set of candles presented as a gift.",p:899,m:1099,sz:[["Set of 3",0],["Set of 5",600]],sc:["Assorted"],bs:1},
{id:8,n:"Birthday Celebration Candle",c:"Birthday",d:"A festive candle to make birthday moments memorable.",p:199,sz:[["Standard",0]],cl:["Pink","Gold","Blue"]},
{id:9,n:"Festive Candle Collection",c:"Festive",d:"Celebration candles to brighten festivals and gatherings.",p:649,sz:[["Set of 4",0],["Set of 8",500]],cl:["Gold","Red"]},
{id:10,n:"Personalized Gift Candle",c:"Personalized",d:"A candle personalised with a name or message (details confirmed on order).",p:499,sz:[["Standard",0]],sc:["Vanilla","Rose","Lavender"]}
];
P.forEach((x,i)=>x.img=[IMGS[i%3],IMGS[(i+1)%3],IMGS[(i+2)%3]]);
const POL={"Shipping Policy":"DRAFT – edit before publishing. Orders are confirmed on WhatsApp. Delivery time and shipping charges depend on location and will be shared at confirmation. Shipping within India only.","Return and Refund Policy":"DRAFT – edit before publishing. Please contact us within [X] days of delivery if your candle arrives damaged, with photos. Resolution (replacement/refund) at the seller's discretion.","Privacy Policy":"DRAFT – edit before publishing. We collect name, phone, address and order details only to process and deliver your order. We do not sell your information.","Terms and Conditions":"DRAFT – edit before publishing. Prices are in INR and may change. Orders are confirmed only after we reply on WhatsApp. Candles must never be left burning unattended."};
/* ===== helpers ===== */
const $=s=>document.querySelector(s),inr=n=>new Intl.NumberFormat('en-IN',{style:'currency',currency:'INR',maximumFractionDigits:0}).format(n);
const ld=(k,d)=>{try{return JSON.parse(localStorage.getItem(k))||d}catch(e){return d}};
const sv=(k,v)=>{try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}};
let C=ld('mk_cart',[]),W=ld('mk_wish',[]),cat=null,qs='';
const im=(u,a)=>`<img src="${u}" alt="${a}" loading="lazy" onerror="this.style.display='none'">`;
function toast(t){const e=$('#toast');e.textContent=t;e.classList.add('on');setTimeout(()=>e.classList.remove('on'),2000)}
function unit(p,sz){return p.p+((p.sz.find(s=>s[0]==sz)||[0,0])[1])}
/* ===== render ===== */
function card(p){const off=p.m?Math.round((1-p.p/p.m)*100):0;
return `<article class="card"><div class="ph" onclick="det(${p.id})">${im(p.img[0],p.n)}${off?`<span class="badge">${off}% off (sample)</span>`:''}<span class="demo">Demo item</span>
<button class="wl ${W.includes(p.id)?'on':''}" aria-label="Wishlist" onclick="event.stopPropagation();wish(${p.id})">${W.includes(p.id)?'♥':'♡'}</button></div>
<div class="cb"><h3>${p.n}</h3><p>${p.d}</p><div class="meta">${p.sz[0][0]}${p.sc?' · '+p.sc[0]:''}</div>
<div class="price">${inr(p.p)}${p.m?`<s>${inr(p.m)}</s>`:''}</div>
<div class="row"><div class="qty"><button aria-label="Less" onclick="qd(${p.id},-1)">−</button><span id="q${p.id}">1</span><button aria-label="More" onclick="qd(${p.id},1)">+</button></div>
<button class="btn sm" onclick="add(${p.id},document.getElementById('q${p.id}').textContent*1)">Add to Cart</button></div>
<button class="btn sm out" style="margin-top:4px" onclick="det(${p.id})">View Details</button></div></article>`}
function qd(id,d){const e=$('#q'+id);e.textContent=Math.max(1,e.textContent*1+d)}
function list(){return P.filter(p=>(!cat||p.c==cat)&&(!qs||(p.n+p.d+p.c+(p.sc||[]).join()).toLowerCase().includes(qs)))}
function render(){const l=list();
$('#track').innerHTML=l.length?l.map(card).join(''):'<p style="padding:30px;text-align:center;width:100%">No candles match your search. Try another term or clear the filter.</p>';
$('#fbar').innerHTML=(cat||qs)?`Showing ${l.length} result(s)${cat?' in <b>'+cat+'</b>':''} <button onclick="cat=null;qs='';$('#q').value='';render()">Clear filter</button>`:'';
$('#wc').textContent=W.length;$('#cc').textContent=C.reduce((a,b)=>a+b.q,0)}
function mini(l,t){return l.map(p=>`<div class="card" style="flex:none"><div class="ph" onclick="det(${p.id})">${im(p.img[0],p.n)}<span class="demo">Demo item</span></div><div class="cb"><h3>${p.n}</h3><div class="price">${inr(p.p)}</div><button class="btn sm" onclick="det(${p.id})">View Details</button></div></div>`).join('')}
function filt(c){cat=c;render();$('#shop').scrollIntoView();$('#track').scrollLeft=0}
function slide(d){$('#track').scrollBy({left:d*300,behavior:'smooth'})}
/* ===== wishlist ===== */
function wish(id){W=W.includes(id)?W.filter(x=>x!=id):[...W,id];sv('mk_wish',W);render();toast(W.includes(id)?'Added to wishlist':'Removed from wishlist')}
/* ===== modal ===== */
function open(h){$('#md').innerHTML=`<button class="x" onclick="closeM()" aria-label="Close">×</button>`+h;$('#ov').classList.add('on')}
function closeM(){$('#ov').classList.remove('on')}
$('#ov').onclick=e=>{if(e.target.id=='ov')closeM()};
document.addEventListener('keydown',e=>{if(e.key=='Escape'){closeM();cart(0)}});
function det(id){const p=P.find(x=>x.id==id);
const rel=P.filter(x=>x.c==p.c&&x.id!=id).concat(P.filter(x=>x.c!=p.c)).slice(0,3);
open(`<div class="dg"><div><div class="ph" id="big" style="border-radius:16px">${im(p.img[0],p.n)}</div><div class="th">${p.img.map((u,i)=>`<img src="${u}" alt="View ${i+1}" class="${i?'':'on'}" onclick="$('#big').innerHTML=im('${u}','${p.n}');document.querySelectorAll('.th img').forEach(t=>t.classList.remove('on'));this.classList.add('on')">`).join('')}</div></div>
<div><span class="tag">Demo product</span><h2 style="text-align:left">${p.n}</h2><div class="price" id="dp" style="font-size:24px">${inr(p.p)}</div><p style="margin:10px 0">${p.d}</p>
<label for="ds">Size</label><select class="in" id="ds" onchange="$('#dp').textContent=inr(unit(P.find(x=>x.id==${id}),this.value))">${p.sz.map(s=>`<option>${s[0]}</option>`).join('')}</select>
${p.sc?`<label for="dsc">Scent</label><select class="in" id="dsc">${p.sc.map(s=>`<option>${s}</option>`).join('')}</select>`:''}
${p.cl?`<label for="dcl">Colour</label><select class="in" id="dcl">${p.cl.map(s=>`<option>${s}</option>`).join('')}</select>`:''}
<label>Quantity</label><div class="qty"><button onclick="qd('d',-1)">−</button><span id="qd">1</span><button onclick="qd('d',1)">+</button></div>
<p style="margin-top:14px"><button class="btn" onclick="add(${id},$('#qd').textContent*1,$('#ds').value,($('#dsc')||{}).value,($('#dcl')||{}).value);closeM()">Add to Cart</button></p>
<p class="note"><b>Delivery:</b> [Placeholder] Delivery time and charges to be confirmed.<br><b>Care & safety:</b> Never leave a burning candle unattended. Keep away from children, pets and flammable items. Trim the wick before lighting and place on a heat-safe surface.</p></div></div>
<h3 style="margin:22px 0 10px">You may also like</h3><div class="cols" style="grid-template-columns:repeat(3,1fr)">${rel.map(r=>`<div class="card" style="cursor:pointer" onclick="det(${r.id})"><div class="ph">${im(r.img[0],r.n)}</div><div class="cb"><b style="font-size:14px">${r.n}</b><span class="price" style="font-size:14px">${inr(r.p)}</span></div></div>`).join('')}</div>`)}
/* ===== cart ===== */
function add(id,q,sz,sc,cl){const p=P.find(x=>x.id==id);sz=sz||p.sz[0][0];sc=sc||(p.sc||[])[0]||'';cl=cl||(p.cl||[])[0]||'';
const k=[id,sz,sc,cl].join('|'),e=C.find(x=>x.k==k);e?e.q+=q:C.push({k,id,sz,sc,cl,q});save();toast('Added to cart')}
function save(){sv('mk_cart',C);render();drawCart()}
function chg(k,d){const e=C.find(x=>x.k==k);e.q+=d;if(e.q<1)C=C.filter(x=>x.k!=k);save()}
function rm(k){C=C.filter(x=>x.k!=k);save()}
function ship(sub){return !sub||sub>=CFG.freeShipAbove?0:CFG.shipFee}
function tots(){const sub=C.reduce((a,x)=>a+unit(P.find(p=>p.id==x.id),x.sz)*x.q,0);return{sub,sh:ship(sub),t:sub+ship(sub)}}
function drawCart(){const el=$('#items');
if(!C.length){el.innerHTML='<p style="text-align:center;margin-top:40px">Your cart is empty.</p>';$('#cf2').innerHTML='<button class="btn" style="width:100%" onclick="cart(0);filt(null)">Continue Shopping</button>';return}
el.innerHTML=C.map(x=>{const p=P.find(a=>a.id==x.id);return `<div class="it">${im(p.img[0],p.n)}<div style="flex:1"><b>${p.n}</b><div style="opacity:.7">${[x.sz,x.sc,x.cl].filter(Boolean).join(' · ')}</div><div>${inr(unit(p,x.sz))}</div>
<div class="row"><div class="qty"><button aria-label="Decrease" onclick="chg('${x.k}',-1)">−</button><span>${x.q}</span><button aria-label="Increase" onclick="chg('${x.k}',1)">+</button></div><button class="ib" style="font-size:13px;text-decoration:underline" onclick="rm('${x.k}')">Remove</button></div></div></div>`}).join('');
const t=tots();$('#cf2').innerHTML=`<div class="sm2"><span>Subtotal</span><span>${inr(t.sub)}</span></div><div class="sm2"><span>Shipping (sample)</span><span>${t.sh?inr(t.sh):'Free'}</span></div><div class="sm2 tot"><span>Total</span><span>${inr(t.t)}</span></div>
<button class="btn" style="width:100%;margin-top:10px" onclick="checkout()">Proceed to Checkout</button><button class="btn out" style="width:100%;margin-top:8px" onclick="cart(0)">Continue Shopping</button>`}
function cart(o){$('#dr').classList.toggle('on',o);if(o)drawCart()}
/* ===== checkout ===== */
const F=[["nm","Full name",1],["mb","Mobile number",1],["em","Email (optional)",0],["ad","Full delivery address",1],["ct","City",1],["st","State",1],["pn","PIN code",1],["nt","Order notes (optional)",0]];
function checkout(){if(!C.length)return;cart(0);const t=tots();
open(`<h2 style="text-align:left">Checkout</h2><div class="dg"><form id="ckf" novalidate>${F.map(f=>`<label for="k${f[0]}">${f[1]}</label>${f[0]=='ad'||f[0]=='nt'?`<textarea class="in" id="k${f[0]}" rows="2"></textarea>`:`<input class="in" id="k${f[0]}">`}<div class="err" id="r${f[0]}"></div>`).join('')}</form>
<div><h3>Order summary</h3>${C.map(x=>{const p=P.find(a=>a.id==x.id);return `<div class="sm2" style="margin:6px 0"><span>${p.n} (${x.sz}) × ${x.q}</span><span>${inr(unit(p,x.sz)*x.q)}</span></div>`}).join('')}<hr style="margin:10px 0;border-color:var(--beige)">
<div class="sm2"><span>Subtotal</span><span>${inr(t.sub)}</span></div><div class="sm2"><span>Shipping</span><span>${t.sh?inr(t.sh):'Free'}</span></div><div class="sm2 tot"><span>Payable</span><span>${inr(t.t)}</span></div>
<button class="btn gold" style="width:100%;margin-top:14px" onclick="place()">Place Order (WhatsApp)</button>
<button class="btn out" style="width:100%;margin-top:8px" onclick="place()">Order on WhatsApp</button>
<button class="btn out" style="width:100%;margin-top:8px;opacity:.5" disabled>Pay online (not configured)</button>
<p class="note">Your order is sent to us on WhatsApp and is confirmed only after we reply. Online payment/backend: not connected yet (see CFG).</p></div></div>`)}
function place(){let ok=1;const v=id=>$('#k'+id).value.trim();
const chk={nm:v('nm').length>1,mb:/^[6-9]\d{9}$/.test(v('mb').replace(/\D/g,'').slice(-10))&&v('mb').replace(/\D/g,'').length>=10,em:!v('em')||/^\S+@\S+\.\S+$/.test(v('em')),ad:v('ad').length>5,ct:!!v('ct'),st:!!v('st'),pn:/^\d{6}$/.test(v('pn'))};
const msg={nm:'Enter your name',mb:'Enter a valid 10-digit Indian mobile number',em:'Enter a valid email',ad:'Enter your full address',ct:'Enter city',st:'Enter state',pn:'Enter a 6-digit PIN code'};
for(const k in chk){$('#r'+k).textContent=chk[k]?'':msg[k];if(!chk[k])ok=0}if(!ok)return;
const t=tots();let m=`*New Order – ${CFG.brand}*\n\n`+C.map((x,i)=>{const p=P.find(a=>a.id==x.id);return `${i+1}. ${p.n} (${[x.sz,x.sc,x.cl].filter(Boolean).join(', ')}) × ${x.q} = ${inr(unit(p,x.sz)*x.q)}`}).join('\n')+
`\n\nSubtotal: ${inr(t.sub)}\nShipping: ${t.sh?inr(t.sh):'Free'}\n*Total: ${inr(t.t)}*\n\n*Customer*\nName: ${v('nm')}\nMobile: ${v('mb')}\n${v('em')?'Email: '+v('em')+'\n':''}Address: ${v('ad')}, ${v('ct')}, ${v('st')} – ${v('pn')}\n${v('nt')?'Notes: '+v('nt'):''}\n\n(Demo catalogue prices – please confirm.)`;
window.open(`https://wa.me/${CFG.wa}?text=${encodeURIComponent(m)}`,'_blank')}
/* ===== init ===== */
$('#cols').innerHTML=CATS.map((c,i)=>`<button class="col" onclick="filt('${c}')">${im(IMGS[i%3],c)}<b>${c} Candles</b></button>`).join('');
$('#bests').innerHTML=mini(P.filter(p=>p.bs));
$('#giftgrid').innerHTML=mini(P.filter(p=>["Gift Sets","Festive","Birthday","Personalized"].includes(p.c)));
$('#revs').innerHTML=[1,2,3].map(()=>`<div class="rev"><span class="tag">Placeholder – not a real review</span><p>Your genuine customer review will appear here.</p><p><b>Customer name</b></p></div>`).join('');
$('#ig').innerHTML=Array.from({length:6},(_,i)=>im(IMGS[i%3],'MK Candles photo '+(i+1))).join('');
$('#aboutimg').src=IMGS[1];
['igbtn','ig2','ig3'].forEach(i=>$('#'+i).href=CFG.ig);
$('#em').href='mailto:'+CFG.email;$('#em').textContent=CFG.email;
$('#wa').href='https://wa.me/'+CFG.wa;$('#wa').textContent='WhatsApp: +'+CFG.wa;
$('#yr').textContent=new Date().getFullYear();
document.querySelectorAll('[data-pol]').forEach(b=>b.onclick=()=>open(`<h2 style="text-align:left">${b.dataset.pol}</h2><p style="margin-top:12px">${POL[b.dataset.pol]}</p>`));
$('#burger').onclick=()=>$('#links').classList.toggle('open');
$('#links').onclick=()=>$('#links').classList.remove('open');
$('#sb').onclick=()=>{const b=$('#sbar');b.style.display=b.style.display=='block'?'none':'block';$('#q').focus()};
$('#q').oninput=e=>{qs=e.target.value.toLowerCase().trim();render()};
$('#wb').onclick=()=>{const l=P.filter(p=>W.includes(p.id));open(`<h2 style="text-align:left">Wishlist</h2>${l.length?'<div class="cols" style="margin-top:14px;grid-template-columns:repeat(auto-fill,minmax(220px,1fr))">'+mini(l)+'</div>':'<p style="margin-top:12px">Your wishlist is empty.</p>'}`)};
$('#cb').onclick=()=>cart(1);
$('#cf').onsubmit=e=>{e.preventDefault();const n=$('#cn').value.trim(),m=$('#ce').value.trim(),t=$('#cm').value.trim();
$('#e1').textContent=n?'':'Please enter your name';$('#e2').textContent=/^\S+@\S+\.\S+$/.test(m)?'':'Enter a valid email';$('#e3').textContent=t.length>4?'':'Please enter a message';
if(!n||!/^\S+@\S+\.\S+$/.test(m)||t.length<5)return;
$('#cmsg').textContent='No server is connected, so your email app will open with this message ready to send. It is not sent until you press Send there.';
location.href=`mailto:${CFG.email}?subject=${encodeURIComponent('Enquiry from '+n)}&body=${encodeURIComponent(t+'\n\nFrom: '+n+' ('+m+')')}`};
/* hero slideshow + carousel autoplay (pauses on interaction) */
const hero=$('.hero');IMGS.forEach((u,i)=>{const d=document.createElement('div');d.className='bg'+(i?'':' on');d.style.backgroundImage=`url(${u})`;hero.prepend(d)});
let hi=0;setInterval(()=>{const b=hero.querySelectorAll('.bg');b[hi].classList.remove('on');hi=(hi+1)%b.length;b[hi].classList.add('on')},5000);
let hold=0;const tk=$('#track');['pointerenter','touchstart','focusin'].forEach(e=>tk.addEventListener(e,()=>hold=1));['pointerleave','touchend','focusout'].forEach(e=>tk.addEventListener(e,()=>hold=0));
setInterval(()=>{if(hold||matchMedia('(prefers-reduced-motion:reduce)').matches)return;tk.scrollLeft+tk.clientWidth>=tk.scrollWidth-10?tk.scrollTo({left:0,behavior:'smooth'}):slide(1)},4500);
render();drawCart();
</script></body></html>
 
