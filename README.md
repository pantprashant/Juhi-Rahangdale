# project

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Medicinal Plants | Juhi Rahangdale</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--green:#204b37;--lime:#91a95b;--paper:#f8f8f1;--line:#dfe5d9}
html{scroll-behavior:smooth;scroll-padding-top:80px}
body{font-family:"Segoe UI",Arial,sans-serif;background:var(--paper);color:#203a2d;line-height:1.7}
header{position:sticky;top:0;z-index:10;background:#fbfcf7;border-bottom:1px solid var(--line);padding:17px 7%;display:flex;justify-content:space-between;align-items:center}
.logo{font-weight:800;letter-spacing:2px;color:var(--green);text-decoration:none}
nav{display:flex;gap:20px}
nav a{color:#506456;text-decoration:none;font-size:12px;font-weight:700}
nav a:hover{color:var(--lime)}
.menu{display:none;background:none;border:0;font-size:25px;color:var(--green)}
.hero{background:#eaf0e3;padding:75px 9%;display:grid;grid-template-columns:1.2fr .8fr;align-items:center;gap:30px}
.eyebrow,.label{font-size:10px;letter-spacing:2px;font-weight:800;color:#819853}
h1,h2{font-family:Georgia,serif;line-height:1.2}
h1{font-size:clamp(38px,5vw,65px);margin:20px 0}
h1 em,h2 em{color:#829951}
.hero p{color:#64746a}
.student{margin:24px 0;font-size:12px}
.student strong{display:block;color:var(--green);letter-spacing:2px}
.btn{display:inline-block;background:var(--green);color:white;padding:12px 20px;text-decoration:none;border:0;cursor:pointer;font-weight:700;margin-top:10px}
.art{height:280px;width:280px;border-radius:50%;background:linear-gradient(140deg,#d8e7af,#a9c58d);display:grid;place-items:center;position:relative;margin:auto}
.art span{font-size:65px;position:absolute}
.art span:nth-child(1){top:20px;left:25px}
.art span:nth-child(2){right:15px;top:100px}
.art span:nth-child(3){bottom:15px;left:75px}
.art b{z-index:1;text-align:center;font:italic bold 27px Georgia;color:#294b35}
.hero-bottom{grid-column:1/-1;border-top:1px solid #cfdac7;padding-top:14px;font-size:9px;letter-spacing:2px;color:#788b78}
section.content{padding:75px 9%}
h2{font-size:clamp(32px,4vw,48px);margin:20px 0}
.two{display:grid;grid-template-columns:.85fr 1.15fr;gap:8%;margin-top:20px}
.lead{font-size:18px;margin-bottom:20px}
.info{border-top:1px solid var(--line);padding:16px 0;font-size:13px;color:#64746a}
.dark{background:var(--green);color:white;padding:65px 9%}
.dark .label{color:#c4dc96}
.dark h2 em{color:#c4dc96}
.objectives{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;border-top:1px solid #ffffff35;padding-top:20px}
.objectives div{font-size:13px;padding-right:15px}
.objectives span{display:block;color:#c4dc96;margin-bottom:12px}
.plant-heading{display:flex;justify-content:space-between;align-items:end}
.plant-heading p{color:#728176;font-size:13px}
.count{font:36px Georgia;border-left:1px solid var(--line);padding-left:20px}
.count small{display:block;font:9px Arial;letter-spacing:2px;color:#728176}
.filters{display:flex;gap:12px;margin:25px 0}
input,select{padding:13px;border:1px solid var(--line);background:white;font:12px Arial;min-width:0}
input{flex:1}
select{width:190px}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px}
.card{border:1px solid var(--line);background:white;cursor:pointer;text-align:left;color:#203a2d;transition:.2s;min-width:0}
.card:hover{transform:translateY(-4px);box-shadow:0 12px 25px #203a2d12}
.visual{height:135px;display:grid;place-items:center;position:relative;background:var(--bg)}
.visual:before{content:"";position:absolute;width:105px;height:105px;border:1px solid #617d4b40;border-radius:50%}
.emoji{font-size:58px;z-index:1}
.number{position:absolute;top:8px;left:10px;font-size:9px;letter-spacing:1px}
.arrow{position:absolute;right:10px;bottom:8px;background:white;border-radius:50%;padding:2px 9px}
.cardbody{padding:15px}
.card h3{font:20px Georgia;line-height:1.3}
.scientific{font-size:11px;font-style:italic;color:#849087;margin:5px 0 12px}
.compound-label{font-size:8px;letter-spacing:1px;color:#829454;font-weight:bold}
.compound{font-size:12px;font-weight:700;margin:5px 0 12px}
.chip{display:inline-block;background:#edf2e7;color:#607a4b;padding:5px 7px;font-size:10px;line-height:1.5}
.hint{text-align:center;font-size:11px;color:#728176;margin-top:20px}
.safety{margin:0 9% 45px;background:#f0ecd9;border-left:4px solid #b6a05b;padding:22px}
.safety h3{font:20px Georgia;margin-bottom:8px}
.safety p{font-size:12px;color:#706c56}
.conclusion p{border-bottom:1px solid var(--line);padding:14px 0;font-size:13px;color:#607166}
.thanks{text-align:center;padding:70px 20px;background:#eaf0e3}
.thanks .flower{font-size:35px;color:#829951}
.thanks h2{font-size:55px}
.thanks strong,.thanks small{display:block;letter-spacing:2px;font-size:11px}
.thanks small{color:#728176;margin-top:10px}
footer{padding:22px 7%;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap;font-size:9px;color:#728176}
footer a{color:var(--green);text-decoration:none}
.modal{position:fixed;inset:0;background:#10251ed9;z-index:30;display:grid;place-items:center;padding:18px}
.modal[hidden]{display:none}
.dialog{background:#fbfcf7;width:min(760px,100%);max-height:90vh;overflow:auto;display:grid;grid-template-columns:.7fr 1.3fr;position:relative}
.picture{background:#e6eddf;display:grid;place-items:center;min-height:300px;font-size:100px}
.details{padding:35px 25px}
.details h2{font-size:32px}
.close{position:absolute;right:10px;top:8px;border:0;border-radius:50%;background:white;font-size:25px;width:35px;height:35px;cursor:pointer}
.detail{border-top:1px solid var(--line);padding:12px 0}
.detail b{font-size:9px;letter-spacing:1px;color:#829454}
.detail p{font-size:12px;color:#526559;margin-top:5px}
@media(max-width:800px){
 .hero{padding:55px 6%}.content{padding:60px 6%!important}
 .grid{grid-template-columns:repeat(2,minmax(0,1fr))}
 .objectives{grid-template-columns:repeat(2,1fr)}
 .safety{margin-left:6%;margin-right:6%}
}
@media(max-width:600px){
 header{padding:15px 5%}.menu{display:block}
 nav{display:none;position:absolute;top:58px;left:0;right:0;background:#fbfcf7;padding:20px;flex-direction:column}
 nav.open{display:flex}
 .hero{grid-template-columns:1fr;padding:45px 7%}
 .hero h1{font-size:43px}
 .art{width:230px;height:230px}
 section.content,.dark{padding:55px 7%}
 .two{grid-template-columns:1fr;gap:20px}
 .filters{flex-direction:column}
 select{width:100%}
 .grid{gap:10px}
 .visual{height:110px}.emoji{font-size:45px}
 .cardbody{padding:10px}.card h3{font-size:17px}
 .compound{font-size:11px}
 .dialog{grid-template-columns:1fr}
 .picture{min-height:120px;font-size:65px}
 .details{padding:22px}
}
@media(max-width:370px){.grid{grid-template-columns:1fr}}
</style>
</head>

<body>
<header>
<a class="logo" href="#home">✿ HERBARIUM</a>
<button class="menu" id="menu">☰</button>
<nav id="nav">
<a href="#home">Home</a>
<a href="#intro">Introduction</a>
<a href="#objectives">Objectives</a>
<a href="#plants">Plants</a>
<a href="#conclusion">Conclusion</a>
</nav>
</header>

<section class="hero" id="home">
<div>
<p class="eyebrow">B.SC. PROJECT / ASSIGNMENT</p>
<h1>Medicinal Plants <em>& Medicines Made From Them</em></h1>
<p>Exploring medicinal plants, their active compounds and their contribution to healthcare.</p>
<div class="student">PREPARED BY <strong>JUHI RAHANGDALE</strong></div>
<a class="btn" href="#plants">Explore the Plants ↘</a>
</div>
<div class="art"><span>🌿</span><span>🍃</span><span>🌱</span><b>Nature's<br>Pharmacy</b></div>
<div class="hero-bottom">PLANTS • COMPOUNDS • MEDICAL USES</div>
</section>

<section class="content" id="intro">
<p class="label">01 / INTRODUCTION</p>
<div class="two">
<h2>Why medicinal <em>plants matter.</em></h2>
<div>
<p class="lead">Medicinal plants contain biologically active substances that can contribute to medicines and healthcare products.</p>
<p class="info">A — Useful compounds may be present in leaves, roots, bark, flowers, seeds, fruits or rhizomes.</p>
<p class="info">B — Some modern medicines were developed from plant-derived compounds, while others are manufactured synthetically or semi-synthetically.</p>
</div>
</div>
</section>

<section class="dark" id="objectives">
<p class="label">02 / OBJECTIVES</p>
<h2>What this project <em>covers.</em></h2>
<div class="objectives">
<div><span>01</span>To study important medicinal plants and their scientific names.</div>
<div><span>02</span>To identify important active compounds obtained from medicinal plants.</div>
<div><span>03</span>To understand major medical uses of selected plant-derived compounds.</div>
<div><span>04</span>To recognize scientific research, standardization and safe medical use.</div>
</div>
</section>

<section class="content" id="plants">
<p class="label">03 / PLANT COLLECTION</p>
<div class="plant-heading">
<div><h2>Meet the <em>plants.</em></h2><p>Explore all 24 medicinal plants in this educational project.</p></div>
<div class="count">24<small>PLANTS</small></div>
</div>
<div class="filters">
<input id="search" type="search" placeholder="Search plant, compound or medical use...">
<select id="filter">
<option value="">All medical uses</option>
<option value="malaria">Malaria</option>
<option value="skin">Skin and topical</option>
<option value="digestive">Digestive</option>
<option value="cancer">Cancer</option>
<option value="heart">Heart and cardiovascular</option>
<option value="pain">Pain and fever</option>
</select>
</div>
<div class="grid" id="grid"></div>
<p id="empty" class="hint" hidden>No matching plants found. Try another search.</p>
<p class="hint">✦ Click any plant card to read its details.</p>
</section>

<div class="safety">
<h3>Important Note on Safe Use</h3>
<p>Plant-based does not automatically mean safe. Some compounds listed here are potent or controlled medicines. Correct identification, dose, preparation and medical guidance are essential. This project is for educational purposes and is not a substitute for professional medical advice.</p>
</div>

<section class="content" id="conclusion">
<p class="label">04 / CONCLUSION</p>
<div class="two">
<h2>Key points from <em>the study.</em></h2>
<div class="conclusion">
<p>✓ Medicinal plants are important natural sources of biologically active compounds.</p>
<p>✓ Some plant-derived compounds are used in medicines; others help pharmaceutical research.</p>
<p>✓ Different plant parts can contain different active substances and require scientific processing and standardization.</p>
<p>✓ Safe use requires correct identification, dose, preparation and medical guidance.</p>
</div>
</div>
</section>

<section class="thanks">
<div class="flower">✿</div>
<p class="label">END OF PROJECT</p>
<h2>Thank <em>You!</em></h2>
<strong>JUHI RAHANGDALE</strong>
<small>B.Sc. Project / Assignment</small>
</section>

<footer><span>MEDICINAL PLANTS & MEDICINES</span><span>Prepared by Juhi Rahangdale</span><a href="#home">Back to top ↑</a></footer>

<div class="modal" id="modal" hidden>
<div class="dialog">
<button class="close" id="close" aria-label="Close">×</button>
<div class="picture" id="picture">🌿</div>
<div class="details">
<p class="label">MEDICINAL PLANT PROFILE</p>
<h2 id="dName"></h2>
<p class="scientific" id="dScientific"></p>
<div class="detail"><b>IMPORTANT COMPOUNDS</b><p id="dCompounds"></p></div>
<div class="detail"><b>PART USED</b><p id="dPart"></p></div>
<div class="detail"><b>MAIN MEDICAL USE</b><p id="dUse"></p></div>
<div class="detail"><b>DESCRIPTION</b><p id="dDescription"></p></div>
<button class="btn" id="next">Next Plant →</button>
</div>
</div>
</div>

<script>
const plants = [
{name:"Neem",scientific:"Azadirachta indica",compounds:"Nimbin, Azadirachtin",part:"Leaves, bark, seeds",use:"Antimicrobial and skin-related preparations",description:"Neem contains several biologically active compounds. It has a long history of traditional use in healthcare and topical preparations.",emoji:"🌿",color:"#e4eddd",category:"skin"},
{name:"Tulsi",scientific:"Ocimum tenuiflorum",compounds:"Eugenol and volatile compounds",part:"Leaves",use:"Traditional cold, cough and throat preparations",description:"Tulsi leaves contain aromatic compounds and are widely used in traditional Indian medicine.",emoji:"🍃",color:"#e1f0e9",category:"digestive"},
{name:"Aloe Vera",scientific:"Aloe vera",compounds:"Aloin and polysaccharides",part:"Leaf gel",use:"Skin-care and topical preparations",description:"The clear gel inside aloe leaves is used in topical products for skin soothing and moisturizing.",emoji:"🪴",color:"#e5eddf",category:"skin"},
{name:"Cinchona",scientific:"Cinchona spp.",compounds:"Quinine",part:"Bark",use:"Malaria treatment",description:"Cinchona bark is a historical source of quinine, an important antimalarial drug.",emoji:"🌳",color:"#e9edda",category:"malaria"},
{name:"Artemisia",scientific:"Artemisia annua",compounds:"Artemisinin",part:"Leaves and aerial parts",use:"Malaria treatment",description:"Artemisia annua provides artemisinin, a key compound used in artemisinin-based antimalarial medicines.",emoji:"🌱",color:"#e4eddd",category:"malaria"},
{name:"Digitalis / Foxglove",scientific:"Digitalis lanata",compounds:"Digoxin and cardiac glycosides",part:"Leaves",use:"Certain heart conditions",description:"Digitalis species contain cardiac glycosides. Digoxin is a potent medicine that requires medical supervision.",emoji:"🌸",color:"#f2e4e3",category:"heart"},
{name:"Periwinkle / Sadabahar",scientific:"Catharanthus roseus",compounds:"Vincristine, Vinblastine",part:"Leaves and aerial parts",use:"Certain cancers",description:"This plant provided important alkaloids used in cancer medicines, including vincristine and vinblastine.",emoji:"🌺",color:"#f2e4e3",category:"cancer"},
{name:"Willow",scientific:"Salix spp.",compounds:"Salicin",part:"Bark",use:"Pain and fever; historical role in aspirin development",description:"Willow bark contains salicin. Salicylate chemistry from natural sources contributed to modern pain-relieving medicines.",emoji:"🌿",color:"#e5eddf",category:"pain"},
{name:"Turmeric",scientific:"Curcuma longa",compounds:"Curcuminoids, including curcumin",part:"Rhizome",use:"Traditional anti-inflammatory preparations",description:"Turmeric rhizomes contain curcuminoids and have a long history in traditional medicine and food.",emoji:"🟠",color:"#f3ecd5",category:"pain"},
{name:"Ginger",scientific:"Zingiber officinale",compounds:"Gingerols and shogaols",part:"Rhizome",use:"Nausea and digestive preparations",description:"Ginger contains pungent compounds such as gingerols and is commonly used in preparations for nausea.",emoji:"🫚",color:"#f3ecd5",category:"digestive"},
{name:"Senna",scientific:"Senna alexandrina",compounds:"Sennosides",part:"Leaves and pods",use:"Constipation",description:"Sennosides are stimulant laxative compounds used for short-term relief of constipation.",emoji:"🌿",color:"#e4eddd",category:"digestive"},
{name:"Sarpagandha",scientific:"Rauvolfia serpentina",compounds:"Reserpine",part:"Roots",use:"Historically used for hypertension",description:"Rauvolfia roots contain reserpine, a compound with historical importance in cardiovascular medicine.",emoji:"🌱",color:"#e9edda",category:"heart"},
{name:"Opium Poppy",scientific:"Papaver somniferum",compounds:"Morphine, Codeine",part:"Latex and other plant material",use:"Severe pain and selected medical uses",description:"The opium poppy is a source of important alkaloids such as morphine and codeine, which are controlled medicines.",emoji:"🌷",color:"#f2e4e3",category:"pain"},
{name:"Belladonna",scientific:"Atropa belladonna",compounds:"Atropine and related alkaloids",part:"Leaves and berries",use:"Certain medical procedures and poisoning treatment",description:"Belladonna contains tropane alkaloids. Atropine is an important medicine used in specific clinical situations.",emoji:"🫐",color:"#ebe5f0",category:"pain"},
{name:"Yew",scientific:"Taxus spp.",compounds:"Taxane compounds, including paclitaxel source chemistry",part:"Bark/needles depending on species",use:"Certain cancers",description:"Yew species contributed compounds that led to taxane cancer medicines. Pharmaceutical production uses controlled processes.",emoji:"🌲",color:"#e4eddd",category:"cancer"},
{name:"Garlic",scientific:"Allium sativum",compounds:"Allicin and sulfur compounds",part:"Bulb",use:"Traditional cardiovascular and antimicrobial preparations",description:"Garlic contains sulfur compounds formed when the bulb is crushed. It has traditional uses and is studied for cardiovascular effects.",emoji:"🧄",color:"#f1eddf",category:"heart"},
{name:"Peppermint",scientific:"Mentha × piperita",compounds:"Menthol and menthone",part:"Leaves and oil",use:"Digestive and topical preparations",description:"Peppermint oil contains menthol and other compounds. It is used in selected digestive and topical products.",emoji:"🌿",color:"#e1f0e9",category:"digestive"},
{name:"Eucalyptus",scientific:"Eucalyptus globulus",compounds:"1,8-Cineole (eucalyptol)",part:"Leaves and oil",use:"Respiratory and topical preparations",description:"Eucalyptus leaves and oil contain eucalyptol, which is used in some topical and respiratory preparations.",emoji:"🍃",color:"#e5eddf",category:"skin"},
{name:"Liquorice / Mulethi",scientific:"Glycyrrhiza glabra",compounds:"Glycyrrhizin",part:"Roots",use:"Cough and digestive preparations",description:"Liquorice root contains glycyrrhizin and is used in traditional and some modern herbal preparations.",emoji:"🌱",color:"#f1eddf",category:"digestive"},
{name:"Clove",scientific:"Syzygium aromaticum",compounds:"Eugenol",part:"Flower buds",use:"Dental preparations and topical pain relief",description:"Clove oil is rich in eugenol, which is used in dental materials and topical preparations.",emoji:"🌺",color:"#f2e4e3",category:"pain"},
{name:"Tea Tree",scientific:"Melaleuca alternifolia",compounds:"Terpinen-4-ol",part:"Leaves and essential oil",use:"Topical antiseptic preparations",description:"Tea tree oil contains terpinen-4-ol and is used in some topical products for antimicrobial properties.",emoji:"🌿",color:"#e4eddd",category:"skin"},
{name:"Chamomile",scientific:"Matricaria chamomilla",compounds:"Apigenin and bisabolol",part:"Flower heads",use:"Herbal skin and digestive preparations",description:"Chamomile flowers contain bioactive compounds and are used in herbal teas and topical preparations.",emoji:"🌼",color:"#f3ecd5",category:"digestive"},
{name:"Ginkgo",scientific:"Ginkgo biloba",compounds:"Flavone glycosides and terpene lactones",part:"Leaves",use:"Standardized herbal preparations",description:"Standardized ginkgo leaf extracts contain characteristic flavone glycosides and terpene lactones.",emoji:"🍂",color:"#f3ecd5",category:"heart"},
{name:"Boswellia / Salai",scientific:"Boswellia serrata",compounds:"Boswellic acids",part:"Resin",use:"Traditional joint and inflammation-related preparations",description:"Boswellia resin contains boswellic acids and is studied for inflammation-related conditions.",emoji:"🌳",color:"#e9edda",category:"pain"}
];

const grid=document.getElementById("grid");
const search=document.getElementById("search");
const filter=document.getElementById("filter");
const modal=document.getElementById("modal");
let active=0;

function render(){
 const q=search.value.trim().toLowerCase();
 const f=filter.value;
 grid.innerHTML="";
 let total=0;

 plants.forEach((p,i)=>{
  const all=[p.name,p.scientific,p.compounds,p.part,p.use,p.description].join(" ").toLowerCase();
  if(!all.includes(q)||(f&&p.category!==f))return;
  total++;

  const card=document.createElement("button");
  card.className="card";
  card.type="button";
  card.setAttribute("aria-label","View "+p.name+" details");

  const visual=document.createElement("div");
  visual.className="visual";
  visual.style.setProperty("--bg",p.color);

  const num=document.createElement("span");
  num.className="number";
  num.textContent=String(i+1).padStart(2,"0")+" / 24";

  const emoji=document.createElement("span");
  emoji.className="emoji";
  emoji.textContent=p.emoji;

  const arrow=document.createElement("span");
  arrow.className="arrow";
  arrow.textContent="↗";

  visual.append(num,emoji,arrow);

  const body=document.createElement("div");
  body.className="cardbody";

  const title=document.createElement("h3");
  title.textContent=p.name;

  const sci=document.createElement("p");
  sci.className="scientific";
  sci.textContent=p.scientific;

  const label=document.createElement("span");
  label.className="compound-label";
  label.textContent="KEY COMPOUND(S)";

  const comp=document.createElement("p");
  comp.className="compound";
  comp.textContent=p.compounds;

  const use=document.createElement("span");
  use.className="chip";
  use.textContent=p.use;

  body.append(title,sci,label,comp,use);
  card.append(visual,body);
  card.addEventListener("click",()=>openPlant(i));
  grid.appendChild(card);
 });

 document.getElementById("empty").hidden=total!==0;
}

function openPlant(i){
 active=i;
 const p=plants[i];
 document.getElementById("dName").textContent=p.name;
 document.getElementById("dScientific").textContent=p.scientific;
 document.getElementById("dCompounds").textContent=p.compounds;
 document.getElementById("dPart").textContent=p.part;
 document.getElementById("dUse").textContent=p.use;
 document.getElementById("dDescription").textContent=p.description;
 document.getElementById("picture").textContent=p.emoji;
 document.getElementById("picture").style.background=p.color;
 document.getElementById("next").disabled=i===plants.length-1;
 modal.hidden=false;
 document.body.style.overflow="hidden";
 document.getElementById("close").focus();
}
function closeModal(){
 modal.hidden=true;
 document.body.style.overflow="";
}
search.addEventListener("input",render);
filter.addEventListener("change",render);
document.getElementById("close").addEventListener("click",closeModal);
modal.addEventListener("click",e=>{if(e.target===modal)closeModal()});
document.getElementById("next").addEventListener("click",()=>{
 if(active<plants.length-1)openPlant(active+1);
});
document.addEventListener("keydown",e=>{
 if(e.key==="Escape"&&!modal.hidden)closeModal();
});
document.getElementById("menu").addEventListener("click",()=>{
 document.getElementById("nav").classList.toggle("open");
});
document.querySelectorAll("nav a").forEach(a=>{
 a.addEventListener("click",()=>document.getElementById("nav").classList.remove("open"));
});
render();
</script>
</body>
</html>
