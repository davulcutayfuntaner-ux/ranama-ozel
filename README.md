# ranama-ozel
Yavrum için hazırladığım özel anılar ve sevgi sayfası
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bebeğimm Rana ❤️</title>
<style>
body{margin:0;padding:20px;background:#fff2f6;color:#462331;font-family:Georgia,serif;text-align:center}
.card{max-width:650px;margin:25px auto;padding:30px 20px;background:white;border-radius:25px;box-shadow:0 8px 30px #d9a8b8}
h1{color:#bd5475;font-size:38px}
h2{color:#bd5475}
.box{background:#ffe1eb;padding:22px;border-radius:18px;margin:20px 0;line-height:1.8}
button{background:#bd5475;color:white;border:0;border-radius:30px;padding:14px 22px;font-size:16px;margin:8px;cursor:pointer}
#secret,#surprise{display:none;margin-top:18px;line-height:1.9}
a{color:white;text-decoration:none}
</style>
</head>
<body>
<div class="card">
<p>11 Mayıs'tan beri, sadece sana özel</p>
<h1>Bebeğimm Rana ❤️</h1>
<p>Tanıştığımız günden bugüne, bizim küçük ve özel hikâyemiz...</p>

<div class="box">
Bazen sana ne kadar değer verdiğimi kelimelere dökmek zor oluyor. Ama şunu bilmeni istiyorum: iyi ki varsın bebeğimm, iyi ki varsın yavrumm. 11 Mayıs'ta başlayan hikâyemizin, 7 Ağustos'ta daha da güzelleşmesi benim için çok özel. Gülüşün, konuşman ve hayatımda olman benim için çok değerli. 🥹❤️
</div>

<div class="box">
<h2>RANA ❤️</h2>
<p><b>R</b>uhumun en güzel yerinde sen varsın.</p>
<p><b>A</b>klıma geldiğinde yüzümde bir gülümseme oluşuyor.</p>
<p><b>N</b>e olursa olsun, seni tanıdığıma çok mutluyum.</p>
<p><b>A</b>şkım, iyi ki benim hayatımdasın bebeğimm. ❤️</p>
</div>

<div class="box">
<h2>Bizim hikâyemiz 🗓️</h2>
11 Mayıs — Tanıştığımız gün ✨<br>
7 Ağustos — Sevgili olduğumuz gün ❤️
</div>

<div class="box">
7 Ağustos'tan beri beraberiz ❤️
<h2 id="counter">Hesaplanıyor...</h2>
</div>

<div class="box">
<h2>İlk tanışmamız 🌸</h2>
11 Mayıs'ta başlayan bu güzel hikâyenin nereye kadar gideceğini belki o gün bilmiyorduk. Ama şimdi dönüp baktığımda, hayatıma giren en güzel insanlardan birinin sen olduğunu biliyorum bebeğimm. ❤️
</div>

<div class="box">
<h2>Birlikte hayallerimiz ✨</h2>
♡ Birlikte daha çok güzel anı biriktirmek<br>
♡ Zor günlerde de birbirimizin yanında olmak<br>
♡ Kahkahalarımızın hiç eksilmemesi<br>
♡ Daha nice 11 Mayısları ve 7 Ağustosları birlikte görmek ❤️<br>
♡ Bir gün evlenip kendi güzel ailemizi kurmak 🥹💍
</div>

<h2>Sana özel şarkım 🎵</h2>
<button><a href="https://open.spotify.com/track/6y5yE3OMAerCpKIGPih0j0?si=pDMTtYGqSA2Ra-5R6qxPeg&utm_source=copy-link" target="_blank">Bizim şarkımızı dinle 🎶❤️</a></button>

<br>
<button onclick="surprise()">Rana ne kadar seviliyor? 🥹❤️</button>
<p id="surprise"></p>

<button onclick="secret()">Sana mesajım var bebeğimm 💌</button>
<div class="box" id="secret">
BEBEĞİMMM HAYATIMMM GÜZELİMMMM YAVRUMMM KARICIMMM SEVGİLİMMMM KALBİMMM KAHVE GÖZLÜMMM… İYİ Kİ SEN HAYATIMAA GİRDİN. BENİ SEVEN BİR YAVRUM VAR DİYE MUTLU OLUYORUMM. BAZEN MORALSİZ OLUYORUM, SANA YANSITTIĞIM İÇİN ÖZÜR DİLERİMMMM. SENİİİ ÇOKKK SEVİYORUMMM. NE OLURSA OLSUNN YANINDA OLCAMM. BAŞARACAĞINA HER ZAMAN İNANIYORUM. DENEMEDEE BAŞARILARR! SENİİİ ÇOKKK SEVİYORUMMM BEBEĞİMMMM 😍🥹💝
</div>

<p>Senin için, sevgiyle yapıldı. ♡</p>
</div>

<script>
function secret(){
let x=document.getElementById("secret");
x.style.display=x.style.display==="block"?"none":"block";
}
function surprise(){
let x=document.getElementById("surprise");
x.style.display="block";
x.innerHTML="Çok seviliyor Rana! Kahve gözlüm, dünyanın en güzel sürprizisin! ❤️";
}
function counter(){
let start=new Date(2026,7,7);
let days=Math.max(0,Math.floor((new Date()-start)/86400000));
document.getElementById("counter").innerText=days+" gündür birlikteyiz ❤️";
}
counter();
</script>
</body>
</html>
