<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#050914">
<title>LIXERA TOP UP</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#050914;color:#f4f8ff;font-family:Arial,sans-serif}
header{padding:18px;background:#081326;border-bottom:1px solid #168cff;position:sticky;top:0;z-index:5}
.wrap{max-width:1100px;margin:auto;padding:0 14px}
.logo{font-size:25px;font-weight:900;color:#43d9ff}
.logo small{display:block;font-size:10px;letter-spacing:4px;color:white}
.hero{padding:35px 0}
.hero h1{font-size:42px;margin:8px 0}
.hero h1 span{color:#43d9ff}
p,.muted{color:#9fb1cb;line-height:1.6}
.search{width:100%;padding:14px;border:1px solid #24476c;border-radius:10px;background:#0b1426;color:white;margin:10px 0}
.filters{display:flex;gap:8px;overflow:auto;padding:8px 0 16px}
.filters button{white-space:nowrap;background:#10213a;color:white;border:1px solid #24476c;padding:10px;border-radius:20px}
.filters button.active{background:#168cff}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
.card{background:#0b1426;border:1px solid #203956;border-radius:14px;padding:14px;min-width:0}
.card h3{color:#43d9ff;margin-top:0}
.item{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:10px 0;border-bottom:1px solid #203047;font-size:12px}
.price{display:block;color:#43d9ff;font-weight:bold;margin-top:4px}
button{cursor:pointer}
.buy{background:#12365c;color:white;border:1px solid #168cff;border-radius:7px;padding:8px;font-weight:bold}
.buy:hover{background:#168cff}
.notice{padding:16px;background:#0b1426;border:1px solid #24476c;border-radius:12px;margin:25px 0;color:#b6cbe3;font-size:12px;line-height:1.7}
footer{padding:25px 0;color:#8299b7;border-top:1px solid #203956;margin-top:30px}
.overlay{display:none;position:fixed;inset:0;background:#000d;z-index:10;overflow:auto;padding:12px;align-items:center;justify-content:center}
.overlay.show{display:flex}
.modal{background:#0b1426;border:1px solid #168cff;border-radius:16px;padding:18px;width:min(550px,100%);max-height:95vh;overflow:auto}
.modalhead{display:flex;justify-content:space-between;align-items:center}
.modal input,.modal select{width:100%;padding:12px;background:#050914;border:1px solid #24476c;border-radius:8px;color:white}
.field{margin:12px 0}
.field label{display:block;font-size:12px;color:#b6cbe3;margin-bottom:6px}
.formgrid{display:grid;grid-template-columns:1fr 1fr;gap:0 12px}
.full{grid-column:1/-1}
.chosen,.paybox{padding:13px;border-radius:10px;background:#10213a;margin:12px 0}
.chosen span{display:block;color:#43d9ff;font-weight:bold;margin-top:7px}
.paybox img{display:block;width:100%;max-width:220px;margin:12px auto;border-radius:8px;background:white}
.primary{width:100%;padding:14px;border:0;border-radius:9px;background:linear-gradient(90deg,#168cff,#43d9ff);font-weight:bold;color:#04101f}
.close{padding:8px;background:#172942;color:white;border:1px solid #34506f;border-radius:7px}
.tiny{font-size:10px;color:#9fb1cb;line-height:1.6}
.total{display:flex;justify-content:space-between;font-weight:bold;margin:15px 0}
.total span:last-child{color:#43d9ff}
@media(max-width:750px){.grid{grid-template-columns:repeat(2,minmax(0,1fr))}.hero h1{font-size:35px}}
@media(max-width:480px){.grid{grid-template-columns:1fr}.formgrid{grid-template-columns:1fr}.full{grid-column:auto}}
</style>
</head>
<body>
<header><div class="wrap">
<div class="logo">LX LIXERA<small>TOP UP • DIGITAL GAMING</small></div>
</div></header>

<main class="wrap">
<section class="hero">
<div style="color:#43d9ff;font-size:11px;letter-spacing:3px">YOUR DIGITAL GAME PARTNER</div>
<h1>TOP UP GAME.<br><span>LEVEL UP.</span></h1>
<p>Top up game favoritmu di LIXERA. Pilih game, pilih paket, isi data akun, lalu konfirmasi pesanan ke WhatsApp admin.</p>
<p>⚡ Praktis • Harga jelas • Konfirmasi admin</p>
</section>

<h2>Katalog Top Up</h2>
<input class="search" id="search" placeholder="Cari game atau paket...">
<div class="filters" id="filters"></div>
<div class="grid" id="catalog"></div>
<p id="empty" style="display:none;text-align:center">Paket tidak ditemukan.</p>

<div class="notice">
<strong>INFORMASI PENTING</strong><br>
Pastikan Player ID dan server benar sebelum memesan. Jangan pernah memberikan password atau kode OTP akun. Pembayaran diverifikasi manual oleh admin. Harga dan ketersediaan paket dapat berubah.
</div>
</main>

<footer><div class="wrap">LIXERA TOP UP — Kebutuhan Digital Gaming<br>© <span id="year"></span> LIXERA</div></footer>

<div class="overlay" id="overlay">
<div class="modal">
<div class="modalhead"><h2>Form Pesanan</h2><button class="close" id="close">Tutup ✕</button></div>
<p class="muted">Pastikan data pesanan benar sebelum melanjutkan.</p>
<div class="chosen"><strong id="chosenName"></strong><span id="chosenPrice"></span></div>

<form id="orderForm">
<div class="formgrid">
<div class="field"><label>Player ID / User ID *</label><input id="playerId" required placeholder="ID pemain"></div>
<div class="field"><label>Server / Zone ID</label><input id="server" placeholder="Jika diperlukan"></div>
<div class="field"><label>Nama pemesan *</label><input id="buyerName" required placeholder="Nama kamu"></div>
<div class="field"><label>Nomor WhatsApp *</label><input id="buyerWa" required inputmode="tel" placeholder="08xxxxxxxxxx"></div>
<div class="field full"><label>Metode pembayaran *</label>
<select id="payment" required>
<option value="">Pilih pembayaran</option>
<option>QRIS</option><option>DANA</option><option>GoPay</option>
</select></div>
<div class="field full"><label>Catatan (opsional)</label><input id="note" placeholder="Catatan tambahan"></div>
</div>

<div class="paybox">
<strong>Informasi Pembayaran</strong>
<p id="payText">Pilih metode pembayaran.</p>
<img id="qris" src="./IMG-20261010-WA0017.jpg" alt="QRIS LIXERA" hidden>
<p>DANA: 083165700636</p>
<p>GoPay: 083165700636</p>
<p>Nama pembayaran: YAXXX</p>
<p class="tiny">Untuk QRIS, upload gambar bernama IMG-20261010-WA0017.jpg ke folder yang sama dengan index.html. Pastikan tujuan dan nominal pembayaran benar.</p>
</div>

<div class="total"><span>Total pesanan</span><span id="totalPrice"></span></div>
<button class="primary" type="submit">KONFIRMASI VIA WHATSAPP ↗</button>
<p class="tiny">Pesanan belum diproses sampai pembayaran diverifikasi admin.</p>
</form>
</div>
</div>

<script>
const ADMINS=["573123253419","628818238317"];
const P=[
{game:"Mobile Legends",icon:"ML",items:[
["5 DM",2000],["12 DM",4000],["19 DM",6500],["28 DM",9500],["44 DM",14000],["59 DM",18500],["85 DM",26500],["110 DM",37500],["170 DM",48000],["240 DM",74000],["296 DM",91000],["344 DM",96000],["408 DM",115000],["425 DM",120000],["514 DM",145000],["568 DM",165000],["706 DM",185000],["716 DM",200000],["875 DM",250000],["1.000 DM",290000],["1.135 DM",340000],["1.500 DM",440000],["2.010 DM",545000],["3.000 DM",850000],["4.830 DM",1300000],["WDP 1×",32000],["WDP 2×",65000],["WDP 3×",98000],["WDP 4×",131000],["WDP 5×",164000],["Weekly Elite Bundle",18000],["Monthly Epic Bundle",85000],["Twilight Pass",170000],["Starlight Member — Cek Harga",null],["Starlight Member Plus — Cek Harga",null]]},
{game:"Free Fire",icon:"FF",items:[
["5 DM",1500],["10 DM",2500],["12 DM",2500],["20 DM",4500],["25 DM",5500],["30 DM",6500],["50 DM",8000],["55 DM",9000],["70 DM",10000],["75 DM",11500],["80 DM",12000],["100 DM",15000],["120 DM",19000],["140 DM",21000],["150 DM",23000],["170 DM",27000],["190 DM",29000],["200 DM",31000],["210 DM",31000],["280 DM",41000],["355 DM",51000],["405 DM",60000],["500 DM",67000],["510 DM",70000],["635 DM",84000],["720 DM",94000],["800 DM",105000],["930 DM",122000],["1.000 DM",133000],["1.050 DM",140000],["1.080 DM",144000],["1.450 DM",193000],["2.180 DM",285000],["2.200 DM",290000],["3.640 DM",480000],["Member Mingguan",30000],["Member Mingguan ×2",62000],["Member Bulanan",90000],["Level Up Pass Lv. 6",6000],["Level Up Pass Lv. 10",10000],["Level Up Pass Lv. 15",10000],["Level Up Pass Lv. 20",10000],["Level Up Pass Lv. 25",10000],["Level Up Pass Lv. 30",15000],["BP Card",46000]]},
{game:"Roblox",icon:"RB",items:[
["80 Robux",20000],["100 Robux",25000],["160 Robux",40000],["200 Robux",50000],["250 Robux",62000],["320 Robux",80000],["400 Robux",100000],["500 Robux",125000],["600 Robux",150000],["800 Robux",200000],["1.000 Robux",250000],["1.200 Robux",300000],["1.500 Robux",375000],["1.700 Robux",425000],["2.000 Robux",500000],["2.500 Robux",625000],["3.000 Robux",750000],["4.000 Robux",1000000],["5.000 Robux",1250000]]},
{game:"PUBG Mobile",icon:"PUBG",items:[
["60 UC",16000],["120 UC",30000],["180 UC",45000],["240 UC",59000],["325 UC",75000],["385 UC",89000],["445 UC",105000],["505 UC",119000],["565 UC",135000],["660 UC",149000],["720 UC",165000],["780 UC",179000],["840 UC",195000],["900 UC",209000],["985 UC",225000],["1.200 UC",269000],["1.500 UC",329000],["1.800 UC",399000],["2.000 UC",449000],["2.400 UC",529000],["3.000 UC",659000],["4.000 UC",879000],["6.000 UC",1299000],["8.000 UC",1699000],["Prime — Cek Harga",null],["Prime Plus — Cek Harga",null],["Royale Pass — Cek Harga",null],["Elite Pass — Cek Harga",null]]},
{game:"Honor of Kings",icon:"HOK",items:[
["8 Tokens",2000],["16 Tokens",4000],["23 Tokens",5000],["38 Tokens",8000],["48 Tokens",10000],["80 Tokens",16000],["96 Tokens",19000],["160 Tokens",31000],["240 Tokens",46000],["400 Tokens",76000],["480 Tokens",91000],["800 Tokens",150000],["1.200 Tokens",225000],["2.000 Tokens",375000],["4.000 Tokens",740000],["8.000 Tokens",1470000]]},
{game:"Genshin Impact",icon:"GI",items:[
["60 Crystals",17000],["300 + 30 Crystals",80000],["980 + 110 Crystals",250000],["1.980 + 260 Crystals",485000],["3.280 + 600 Crystals",800000],["6.480 + 1.600 Crystals",1600000],["Welkin Moon 1×",80000],["Welkin Moon 2×",125000],["Welkin Moon 3×",185000],["Welkin Moon 4×",250000],["Welkin Moon 5×",300000]]},
{game:"Call of Duty Mobile",icon:"COD",items:[
["31 CP",5000],["62 CP",10000],["93 CP",15000],["127 CP",20000],["190 CP",30000],["320 CP",50000],["645 CP",100000],["800 CP",120000],["1.300 CP",200000],["2.000 CP",300000],["2.400 CP",350000],["4.000 CP",600000],["5.000 CP",750000],["8.000 CP",1200000]]},
{game:"FC Mobile",icon:"FC",items:[
["40 FC Points",5000],["100 FC Points",12000],["520 FC Points",55000],["1.070 FC Points",105000],["2.200 FC Points",205000],["5.750 FC Points",510000],["12.000 FC Points",1000000],["40.000 Coins",5000],["100.000 Coins",10000],["250.000 Coins",25000],["500.000 Coins",50000],["1.000.000 Coins",100000]]},
{game:"Delta Force",icon:"DF",items:[
["60 Delta Coins",5000],["300 Delta Coins",15000],["420 Delta Coins",20000],["680 Delta Coins",30000],["1.280 Delta Coins",55000],["1.960 Delta Coins",80000],["3.300 Delta Coins",130000],["6.480 Delta Coins",250000],["12.800 Delta Coins",490000]]},
{game:"Magic Chess",icon:"MC",items:[
["8 Diamonds",2000],["16 Diamonds",4000],["24 Diamonds",6000],["40 Diamonds",10000],["56 Diamonds",14000],["80 Diamonds",19000],["120 Diamonds",29000],["168 Diamonds",39000],["240 Diamonds",55000],["328 Diamonds",75000],["408 Diamonds",95000],["568 Diamonds",129000],["648 Diamonds",149000],["808 Diamonds",185000],["1.088 Diamonds",249000],["1.368 Diamonds",309000],["1.688 Diamonds",379000],["2.048 Diamonds",459000],["3.288 Diamonds",729000]]}
];

const rupiah=n=>"Rp"+Number(n).toLocaleString("id-ID");
let selectedGame="Semua",selectedItem=null;
const catalog=document.getElementById("catalog");
const search=document.getElementById("search");
const filters=document.getElementById("filters");

function makeFilters(){
 filters.innerHTML="";
 ["Semua",...P.map(x=>x.game)].forEach(g=>{
  const b=document.createElement("button");
  b.textContent=g;b.className=g===selectedGame?"active":"";
  b.onclick=()=>{selectedGame=g;makeFilters();render()};
  filters.appendChild(b);
 });
}

function render(){
 catalog.innerHTML="";
 const q=search.value.toLowerCase().trim();
 let count=0;
 P.forEach(game=>{
  if(selectedGame!=="Semua"&&selectedGame!==game.game)return;
  const items=game.items.filter(x=>(game.game+" "+x[0]).toLowerCase().includes(q));
  if(!items.length)return;
  count++;
  const card=document.createElement("article");
  card.className="card";
  const title=document.createElement("h3");
  title.textContent=game.icon+" | "+game.game;
  card.appendChild(title);
  items.forEach(item=>{
   const row=document.createElement("div");row.className="item";
   const info=document.createElement("div");
   info.textContent=item[0];
   const price=document.createElement("span");price.className="price";
   price.textContent=item[1]===null?"Cek Harga":rupiah(item[1]);
   info.appendChild(price);row.appendChild(info);
   const b=document.createElement("button");b.className="buy";
   b.textContent=item[1]===null?"Tanya":"Pesan";
   b.onclick=()=>item[1]===null?askAdmin(game.game,item[0]):openOrder(game,item);
   row.appendChild(b);card.appendChild(row);
  });
  catalog.appendChild(card);
 });
 document.getElementById("empty").style.display=count?"none":"block";
}

function askAdmin(game,item){
 const msg=`Halo admin LIXERA, saya mau cek harga ${item} untuk ${game}.`;
 location.href=`https://wa.me/${ADMINS[0]}?text=${encodeURIComponent(msg)}`;
}

const overlay=document.getElementById("overlay");
function openOrder(game,item){
 selectedItem={game:game.game,name:item[0],price:item[1]};
 document.getElementById("chosenName").textContent=game.game+" • "+item[0];
 document.getElementById("chosenPrice").textContent=rupiah(item[1]);
 document.getElementById("totalPrice").textContent=rupiah(item[1]);
 document.getElementById("orderForm").reset();
 document.getElementById("payText").textContent="Pilih metode pembayaran.";
 document.getElementById("qris").hidden=true;
 overlay.classList.add("show");
}
document.getElementById("close").onclick=()=>overlay.classList.remove("show");
overlay.addEventListener("click",e=>{if(e.target===overlay)overlay.classList.remove("show")});

document.getElementById("payment").addEventListener("change",e=>{
 const method=e.target.value;
 document.getElementById("qris").hidden=method!=="QRIS";
 document.getElementById("payText").textContent=
 method==="QRIS"?"Scan QRIS setelah admin mengonfirmasi pesanan.":
 method?`${method}: 083165700636 • a.n. YAXXX`:"Pilih metode pembayaran.";
});

document.getElementById("orderForm").addEventListener("submit",e=>{
 e.preventDefault();
 if(!selectedItem)return;
 const method=document.getElementById("payment").value;
 const id=document.getElementById("playerId").value.trim();
 const server=document.getElementById("server").value.trim();
 const name=document.getElementById("buyerName").value.trim();
 const wa=document.getElementById("buyerWa").value.trim();
 const note=document.getElementById("note").value.trim();
 if(!method){alert("Pilih metode pembayaran.");return}
 const msg=`HALO ADMIN LIXERA TOP UP

Saya ingin memesan:
Game: ${selectedItem.game}
Paket: ${selectedItem.name}
Harga: ${rupiah(selectedItem.price)}
Player/User ID: ${id}
Server/Zone ID: ${server||"-"}
Nama pemesan: ${name}
WhatsApp pemesan: ${wa}
Pembayaran: ${method}
Catatan: ${note||"-"}

Mohon konfirmasi pesanan dan pembayaran saya.`;
 location.href=`https://wa.me/${ADMINS[0]}?text=${encodeURIComponent(msg)}`;
});

search.addEventListener("input",render);
document.getElementById("year").textContent=new Date().getFullYear();
makeFilters();render();
</script>
</body>
</html>
