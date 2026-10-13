

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

<div><h2>Meet the <em>plants.</em></h2><p>Explore all 36 medicinal plants in this educational project.</p></div>

<div class="count" id="plantCount">36<small>PLANTS</small></div>

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

<div class="detail"><b>HABITAT AND GROWING CONDITIONS</b><p id="dHabitat"></p></div>

<div class="detail"><b>TRADITIONAL USES</b><p id="dTraditional"></p></div>

<div class="detail"><b>SCIENTIFIC EVIDENCE</b><p id="dEvidence"></p></div>

<div class="detail"><b>SAFETY AND PRECAUTIONS</b><p id="dCaution"></p></div>

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

{name:"Boswellia / Salai",scientific:"Boswellia serrata",compounds:"Boswellic acids",part:"Resin",use:"Traditional joint and inflammation-related preparations",description:"Boswellia resin contains boswellic acids and is studied for inflammation-related conditions.",emoji:"🌳",color:"#e9edda",category:"pain"},

{"name":"Ashwagandha","scientific":"Withania somnifera","compounds":"Withanolides","part":"Roots; some products use leaves","use":"Traditional stress and vitality preparations","description":"An Ayurvedic shrub studied for stress and sleep outcomes. Results vary by product and study.","emoji":"🌱","color":"#e4eddd","category":"pain","habitat":"A hardy shrub grown in dry regions of India and South Asia.","traditional":"Root preparations are traditionally associated with strength, vitality and coping with stress.","evidence":"Some small studies suggest possible effects on stress or sleep, but evidence is limited and products are not interchangeable.","caution":"May interact with medicines and has been linked to rare liver injury. Avoid during pregnancy; consult a clinician, especially with thyroid or liver conditions."},

{"name":"Brahmi","scientific":"Bacopa monnieri","compounds":"Bacosides","part":"Whole aerial parts","use":"Traditional memory and learning preparations","description":"A creeping herb used in Ayurveda and researched for selected memory and cognitive outcomes.","emoji":"🍃","color":"#e1f0e9","category":"digestive","habitat":"Often grows in wet, marshy or damp places in tropical and subtropical climates.","traditional":"Used in traditional formulations associated with memory and concentration.","evidence":"Some trials report changes in selected memory measures, but findings are mixed and do not establish treatment for cognitive disorders.","caution":"May cause gastrointestinal upset and interact with medicines. Seek advice before using concentrated extracts."},

{"name":"Amla / Indian Gooseberry","scientific":"Phyllanthus emblica","compounds":"Polyphenols and hydrolysable tannins","part":"Fruit","use":"Nutrition and traditional wellness preparations","description":"A sour fruit eaten fresh or dried and used in traditional preparations; it contains vitamin C and polyphenols.","emoji":"🟢","color":"#e4eddd","category":"digestive","habitat":"A deciduous tree cultivated widely in India, including dry and semi-arid areas.","traditional":"The fruit is eaten fresh, dried or prepared in powders and preserves.","evidence":"Amla is a food, but claims that supplements prevent or treat specific diseases require stronger clinical evidence.","caution":"Concentrated supplements may interact with medicines affecting blood sugar or clotting. Food use differs from supplement doses."},

{"name":"Shatavari","scientific":"Asparagus racemosus","compounds":"Steroidal saponins, including shatavarins","part":"Roots","use":"Traditional reproductive and digestive health preparations","description":"A climbing or scrambling plant whose roots are used in Ayurvedic preparations.","emoji":"🌿","color":"#e5eddf","category":"digestive","habitat":"Found in parts of South Asia in woodland and scrub; also cultivated for its roots.","traditional":"Root preparations have traditional associations with digestive and reproductive health.","evidence":"Clinical evidence for many advertised benefits remains limited; traditional use alone does not prove effectiveness.","caution":"Consult a clinician before concentrated products, particularly during pregnancy or breastfeeding or with hormone-sensitive conditions."},

{"name":"Vasaka / Adulsa","scientific":"Justicia adhatoda","compounds":"Vasicine and vasicinone","part":"Leaves","use":"Traditional cough and respiratory preparations","description":"A South Asian shrub known for its use in traditional respiratory formulations.","emoji":"🍃","color":"#e1f0e9","category":"digestive","habitat":"An evergreen shrub found across South Asia and commonly grown in gardens.","traditional":"Leaves are used in traditional preparations for cough and respiratory discomfort.","evidence":"Traditional-use and laboratory evidence exists, but strong clinical evidence for specific conditions is limited.","caution":"Not a substitute for assessment of breathing difficulty or persistent fever. Safety in pregnancy is a concern."},

{"name":"Guduchi / Giloy","scientific":"Tinospora cordifolia","compounds":"Diterpenoid lactones and alkaloids","part":"Stems","use":"Traditional fever and wellness preparations","description":"A climbing plant used in traditional medicine; its chemistry and commercial products vary.","emoji":"🌿","color":"#e4eddd","category":"pain","habitat":"A vine native to the Indian subcontinent, often growing over trees or supports.","traditional":"Stem-based preparations are used traditionally for several complaints, including fever.","evidence":"Evidence for many claimed benefits is insufficient, and some products have been associated with liver injury.","caution":"Avoid self-treatment, particularly with liver disease or autoimmune conditions; discuss use with a qualified clinician."},

{"name":"Bael","scientific":"Aegle marmelos","compounds":"Marmelosin and other coumarins","part":"Fruit; leaves and bark in some traditional preparations","use":"Traditional digestive preparations","description":"A fruit-bearing tree valued as food and in traditional medicine; ripe fruit is also consumed as food.","emoji":"🌳","color":"#e9edda","category":"digestive","habitat":"Native to the Indian subcontinent and tolerant of hot, relatively dry conditions.","traditional":"Fruit preparations have a long history in traditional digestive practices.","evidence":"Most medicinal claims lack strong clinical trials, and evidence varies by plant part and preparation.","caution":"Concentrated products may not suit everyone. Seek medical advice for persistent digestive symptoms."},

{"name":"Isabgol / Psyllium","scientific":"Plantago ovata","compounds":"Mucilage-forming soluble fibre","part":"Seed husk","use":"Constipation and fibre supplementation","description":"Psyllium husk absorbs water and forms a gel. It is used as a bulk-forming fibre supplement.","emoji":"🌾","color":"#f3ecd5","category":"digestive","habitat":"An annual herb cultivated in India and other dry regions for its seeds.","traditional":"The husk is mixed with sufficient liquid and used as a fibre supplement.","evidence":"Clinical evidence supports psyllium for constipation and suggests it can help lower LDL cholesterol as part of an appropriate diet.","caution":"Take with plenty of water and follow the label. It may affect medicine absorption; avoid without medical advice if swallowing is difficult."},

{"name":"Moringa / Drumstick Tree","scientific":"Moringa oleifera","compounds":"Glucosinolates, isothiocyanates and polyphenols","part":"Leaves and pods as food","use":"Nutrition and traditional wellness","description":"A fast-growing tree whose leaves and pods are widely eaten; leaves provide nutrients depending on preparation.","emoji":"🌳","color":"#e4eddd","category":"heart","habitat":"Grows in warm climates and is widely cultivated in Indian gardens and farms.","traditional":"Leaves and pods are eaten as vegetables; leaves are also dried and powdered.","evidence":"Food value is well established, but evidence that supplements treat chronic diseases is not conclusive.","caution":"Food portions differ from concentrated extracts. Root and bark products raise additional safety concerns."},

{"name":"Bhringraj","scientific":"Eclipta prostrata","compounds":"Wedelolactone and related coumestans","part":"Whole plant","use":"Traditional hair and scalp preparations","description":"A small herb used in traditional hair oils and other formulations.","emoji":"🌱","color":"#e1f0e9","category":"skin","habitat":"A low-growing herb commonly found in moist areas across tropical regions.","traditional":"Plant extracts and infused oils are traditionally applied to hair and scalp.","evidence":"Evidence for hair-growth claims in humans is limited; laboratory or animal findings do not prove clinical benefit.","caution":"Topical products may irritate skin or cause allergy. Avoid eyes and broken skin."},

{"name":"Kalmegh","scientific":"Andrographis paniculata","compounds":"Andrographolide","part":"Leaves and aerial parts","use":"Traditional fever and respiratory preparations","description":"A bitter herb used in traditional medicine and studied for its diterpenoid compounds.","emoji":"🍃","color":"#e4eddd","category":"pain","habitat":"An annual herb cultivated in South and Southeast Asia in warm conditions.","traditional":"Aerial parts are used in traditional preparations for fever and seasonal complaints.","evidence":"Studies of respiratory symptoms show mixed results and vary by formulation; it is not a substitute for proven treatment.","caution":"May cause allergic reactions and interact with medicines. Avoid during pregnancy unless directed by a clinician."},

{"name":"Fenugreek / Methi","scientific":"Trigonella foenum-graecum","compounds":"Trigonelline, saponins and galactomannan fibre","part":"Seeds and leaves","use":"Food and study of digestive and blood-sugar effects","description":"A culinary legume whose leaves and seeds are common in Indian cooking; seeds contain fibre and bioactive compounds.","emoji":"🌿","color":"#f1eddf","category":"digestive","habitat":"An annual crop grown in India and other regions with suitable cool-season conditions.","traditional":"Leaves are eaten as a vegetable and seeds are used as a spice and in traditional preparations.","evidence":"Some studies investigate blood-sugar and lipid effects, but findings are variable and do not replace standard diabetes care.","caution":"Supplemental amounts may lower blood sugar, interact with anticoagulants and cause digestive symptoms. Allergy is possible."}

];




const extraByCategory = {
  skin: {
    habitat:"Growing conditions vary by species; this plant is cultivated or collected in regions suited to its climate.",
    traditional:"Used in selected traditional or topical preparations; the exact preparation and plant part matter.",
    evidence:"Evidence differs by preparation. Traditional use or laboratory findings do not by themselves prove that a product treats a disease.",
    caution:"Topical products can irritate skin or cause allergy. Do not ingest essential oils or concentrated extracts unless a qualified clinician specifically advises it."
  },
  digestive: {
    habitat:"This species is cultivated or grows naturally in suitable tropical or subtropical environments; growing conditions depend on the species.",
    traditional:"Used in traditional food, digestive or herbal preparations, but the purpose and preparation vary by culture and plant part.",
    evidence:"Evidence ranges from established uses for some standardized products to limited evidence for traditional claims. Product quality and dose matter.",
    caution:"May cause side effects or interact with medicines. Persistent digestive symptoms, severe pain or dehydration need medical assessment."
  },
  malaria: {
    habitat:"These plants grow in particular ecological regions and are cultivated or harvested as sources of compounds used in antimalarial medicines.",
    traditional:"The plant is historically important in the discovery or development of antimalarial treatment.",
    evidence:"Plant-derived compounds have contributed to modern malaria medicines, but treatment requires approved regimens and professional guidance.",
    caution:"Do not self-treat suspected malaria with plant material or herbal products. Prompt testing and approved treatment are essential."
  },
  cancer: {
    habitat:"Species and growing conditions vary; pharmaceutical compounds are obtained through controlled cultivation, extraction or manufacturing.",
    traditional:"The plant is notable mainly because it contributed compounds to modern cancer drug research.",
    evidence:"A plant-derived compound may be used in a standardized prescription medicine; this does not mean the raw plant treats cancer.",
    caution:"Some compounds are highly toxic. Never consume the plant or use herbal products in place of oncology care."
  },
  heart: {
    habitat:"Growing conditions vary by species; some are cultivated for food while others are grown or harvested for pharmaceutical research.",
    traditional:"Has a history of traditional use or scientific study related to cardiovascular health.",
    evidence:"Evidence depends on the specific compound and preparation. Traditional use does not establish that a plant prevents or treats heart disease.",
    caution:"Can interact with heart, blood-pressure or blood-thinning medicines. Do not replace prescribed treatment with a plant product."
  },
  pain: {
    habitat:"This species grows or is cultivated in regions suited to its climate; the plant part and preparation affect its chemistry.",
    traditional:"Used traditionally or studied for pain, fever or inflammation-related purposes, depending on the species.",
    evidence:"Evidence varies substantially between plants and products; laboratory findings do not necessarily translate into clinical benefit.",
    caution:"Some plant compounds are potent or toxic. Seek medical advice before medicinal use, especially with pregnancy or regular medication."
  }
};
const detailedProfiles = {
"Neem": {habitat:"An evergreen tree native to the Indian subcontinent, adapted to hot climates and relatively dry conditions. It is commonly planted along roads and around homes.", traditional:"Leaves, bark and seed oil appear in different traditional preparations. Neem oil is also widely used in agriculture; these uses should not be confused with proven medical treatment.", evidence:"Neem extracts show antimicrobial activity in some laboratory studies, but reliable human evidence for treating infections or skin disease is limited and depends on the preparation.", caution:"Neem oil can be poisonous if swallowed, particularly by children. Avoid ingesting neem products; concentrated products may cause irritation or other adverse effects."},
"Tulsi": {habitat:"An aromatic herb commonly grown in household gardens across India. It prefers warmth, sunlight and well-drained soil.", traditional:"Leaves are used in teas and household preparations for coughs, colds and general wellness. They are also used in religious and cultural practices.", evidence:"Laboratory studies identify aromatic compounds such as eugenol. Human studies are limited and do not establish tulsi as a replacement for treatment of respiratory infections.", caution:"Concentrated extracts may interact with medicines, including those affecting blood sugar or clotting. Seek advice during pregnancy or before surgery."},
"Aloe Vera": {habitat:"A succulent plant suited to warm, sunny climates and well-drained soil. It stores water in its thick leaves and is often grown in pots.", traditional:"The clear inner gel is applied to skin in some soothing and moisturizing products. The yellow latex beneath the leaf skin is chemically different from the gel.", evidence:"Some topical aloe products may help selected minor skin problems, but evidence varies by condition and formulation. Benefits should not be generalized to every product.", caution:"Do not confuse inner gel with aloe latex, which can cause cramps and severe diarrhoea. Oral aloe products may interact with medicines; stop topical use if irritation occurs."},
"Cinchona": {habitat:"Cinchona trees originate in the Andean region of South America and are cultivated in some tropical highland regions.", traditional:"The bark became historically important because quinine was isolated from it and used in antimalarial treatment.", evidence:"Quinine is an established medicine for specific clinical situations, but it is administered in measured pharmaceutical doses rather than by using raw bark.", caution:"Quinine can cause serious adverse effects and interactions. Suspected malaria requires prompt testing and approved treatment; do not prepare bark remedies at home."},
"Artemisia": {habitat:"Artemisia annua is an annual aromatic herb originally associated with Asia and now cultivated in different regions. It grows best in suitable sunny conditions.", traditional:"The plant has a history in traditional Chinese medicine and became globally important after artemisinin was identified from it.", evidence:"Artemisinin derivatives are central to recommended combination treatments for malaria. The raw plant or unstandardized tea is not an appropriate substitute for these medicines.", caution:"Do not self-treat malaria with Artemisia tea or supplements. Incomplete or unsuitable treatment can be dangerous and may contribute to treatment failure."},
"Digitalis / Foxglove": {habitat:"Digitalis species are flowering plants grown in temperate climates. The species used for pharmaceutical production are cultivated and processed under controlled conditions.", traditional:"Foxglove's medical importance comes from cardiac glycosides developed into medicines for selected heart conditions.", evidence:"Digoxin has specific clinical uses and a narrow safety margin; clinicians monitor dosing and sometimes blood concentrations and kidney function.", caution:"All parts of foxglove can be highly poisonous. Never ingest the plant or use homemade preparations. Digoxin toxicity can cause dangerous heart rhythms."},
"Periwinkle / Sadabahar": {habitat:"A flowering evergreen plant native to Madagascar and widely grown in warm regions, including Indian gardens.", traditional:"Although commonly grown as an ornamental plant, it is especially important as the source of alkaloids that led to medicines used in oncology.", evidence:"Vincristine and vinblastine are prescription chemotherapy drugs derived from research on this plant. This does not mean the raw plant treats cancer.", caution:"The plant contains toxic alkaloids. Do not consume it or make home remedies; cancer treatment must be managed by oncology professionals."},
"Willow": {habitat:"Willows are trees and shrubs often found in temperate regions near rivers, wetlands and moist soils. The genus contains many species.", traditional:"Willow bark has a long history of use for aches and fever and contributed to the history of salicylate-based medicines.", evidence:"Evidence for willow bark products varies by formulation. Salicin is related to salicylates, but willow bark is not identical to aspirin and should not be treated as interchangeable.", caution:"May increase bleeding risk and can cause stomach problems. Avoid in children and teenagers with viral illness, and seek advice with ulcers, kidney disease, pregnancy or blood-thinning medicines."},
"Turmeric": {habitat:"A tropical rhizomatous plant cultivated widely in India. It needs warm conditions, moisture and a suitable growing season.", traditional:"The rhizome is used as a spice, colouring agent and in traditional food and topical preparations.", evidence:"Curcumin has been studied for inflammation-related outcomes, but absorption is low and clinical results vary. Evidence for a supplement does not automatically apply to turmeric in food.", caution:"High-dose supplements may cause digestive effects and interact with anticoagulants. Some enhanced-bioavailability products have been linked to liver injury; seek advice if taking medicines."},
"Ginger": {habitat:"A tropical plant grown from underground rhizomes in warm, humid conditions. The rhizome is harvested for cooking and herbal products.", traditional:"Ginger is used as a culinary spice and in drinks or preparations for nausea and digestive discomfort.", evidence:"Some clinical evidence supports ginger for certain types of nausea, including pregnancy-related nausea, but suitability and dose vary. It is not a treatment for every digestive condition.", caution:"May cause heartburn or stomach upset and may interact with blood-thinning or blood-sugar medicines. Ask a clinician about concentrated supplements during pregnancy."},
"Senna": {habitat:"Senna alexandrina is a shrub grown in warm, relatively dry regions. Leaves and pods contain stimulant laxative compounds.", traditional:"Senna preparations have been used for short-term relief of constipation and are present in some regulated laxative products.", evidence:"Standardized senna medicines can be effective for short-term constipation when used according to product directions.", caution:"Excessive or prolonged use can cause cramps, diarrhoea, dehydration and electrolyte imbalance. Persistent constipation or severe abdominal pain requires medical assessment."},
"Sarpagandha": {habitat:"Rauvolfia serpentina is a perennial shrub native to South and Southeast Asia, growing in warm climates and partly shaded habitats.", traditional:"Its roots have a history in South Asian medicine. Reserpine was later isolated and used historically to lower blood pressure.", evidence:"Reserpine has established pharmacological effects but is now used less often because of adverse effects and availability of alternatives.", caution:"The root is potent and should never be self-administered. Reserpine can cause low blood pressure, slow heart rate, depression and important drug interactions."},
"Opium Poppy": {habitat:"Papaver somniferum is an annual plant grown in temperate and subtropical regions. Cultivation and processing are subject to legal controls in many countries.", traditional:"The plant is historically important because its alkaloids include morphine and codeine, which have medical uses under strict regulation.", evidence:"Pharmaceutical opioids can be effective for selected types of severe pain, but require individualized prescribing and monitoring.", caution:"The plant and its products can contain potent opioids. Unsupervised use risks overdose, dependence and fatal respiratory depression; legal restrictions apply."},
"Belladonna": {habitat:"Atropa belladonna is a perennial herb native to parts of Europe, North Africa and western Asia, typically associated with woodland edges and shaded habitats.", traditional:"The plant's tropane alkaloids have influenced medicine; purified atropine is used in carefully defined clinical settings.", evidence:"Atropine is an established medicine when prescribed and administered for specific indications. This does not make belladonna plant material medically safe.", caution:"All parts, especially berries, are poisonous. Poisoning can cause delirium, rapid heartbeat, overheating and seizures. Suspected exposure requires urgent medical or poison-control help."},
"Yew": {habitat:"Yew is a group of evergreen trees and shrubs found in temperate regions. Species differ, and pharmaceutical taxanes are obtained through controlled supply chains.", traditional:"Its modern medical significance is linked to taxane compounds that contributed to the development of chemotherapy medicines.", evidence:"Paclitaxel and related taxanes are used in oncology under specialist supervision. Raw yew is not a cancer treatment.", caution:"Many parts of yew contain highly toxic compounds that can cause fatal heart disturbances. Never ingest yew material or prepare home remedies."},
"Garlic": {habitat:"Garlic is a bulb-forming plant cultivated globally in cool to mild growing seasons and used extensively in cooking.", traditional:"The bulb is eaten as food and used in traditional preparations. Crushing garlic produces allicin-related sulfur compounds.", evidence:"Studies have examined garlic supplements for blood pressure and cholesterol, but effects are variable and generally modest; garlic is not a substitute for prescribed cardiovascular care.", caution:"Concentrated supplements can increase bleeding risk and affect some medicines. Food use is different from supplement use; seek advice before surgery or when taking anticoagulants."},
"Peppermint": {habitat:"Peppermint is a cultivated aromatic hybrid of spearmint and watermint, usually grown in moist soil with adequate sunlight.", traditional:"Leaves are used in teas and flavourings, while peppermint oil is included in selected digestive and topical products.", evidence:"Enteric-coated peppermint oil may help some adults with irritable bowel syndrome symptoms, but it does not suit everyone and evidence depends on formulation.", caution:"Peppermint oil can worsen reflux or heartburn and concentrated oil can be harmful if swallowed incorrectly. Keep essential oils away from children and eyes."},
"Eucalyptus": {habitat:"Eucalyptus globulus is an evergreen tree native to Australia and cultivated in many warm regions. Its leaves contain volatile oils.", traditional:"Leaf-derived preparations and vapours are used in some topical and respiratory products, while the tree is also grown for timber and essential oil.", evidence:"Eucalyptol is present in certain standardized products, but evidence depends on the formulation and condition. Steam or oil should not replace medical care for breathing problems.", caution:"Eucalyptus oil is toxic if swallowed and can cause seizures or other severe effects. Avoid applying concentrated oil to the face of young children."},
"Liquorice / Mulethi": {habitat:"Glycyrrhiza glabra is a perennial legume grown in parts of Europe and Asia; its sweet-tasting roots are harvested for food and herbal products.", traditional:"The root is used in some cough, throat and digestive preparations and as a flavouring ingredient.", evidence:"Evidence for particular liquorice preparations varies. Glycyrrhizin has biological effects, but traditional use does not establish that all products are effective.", caution:"Regular or high intake of glycyrrhizin can raise blood pressure, lower potassium and cause dangerous heart rhythm problems. Extra caution is needed with heart, kidney or blood-pressure conditions."},
"Clove": {habitat:"Clove is an evergreen tropical tree. The dried unopened flower buds are harvested and used as a spice and source of essential oil.", traditional:"Clove oil has been used in dental preparations because eugenol can provide local soothing effects and is used in some dental materials.", evidence:"Eugenol has recognized uses in certain dental materials, but clove oil is not a substitute for diagnosing or treating dental infection.", caution:"Undiluted clove oil can burn or irritate tissue. Swallowing large amounts can cause serious toxicity, especially in children; seek dental care for persistent pain."},
"Tea Tree": {habitat:"Melaleuca alternifolia is native to Australia and grows in moist environments. Its leaves are distilled to produce tea tree essential oil.", traditional:"The oil is used in some topical products for skin concerns, but it is intended for external use only.", evidence:"Some small studies suggest benefit for selected mild skin problems, but the evidence is limited and products vary in concentration.", caution:"Tea tree oil is poisonous if swallowed and can cause skin allergy, especially after oxidation. Do not ingest it or apply it near eyes or to pets."},
"Chamomile": {habitat:"German chamomile is an annual flowering herb cultivated in temperate regions and grown for its daisy-like flower heads.", traditional:"Flowers are used in herbal teas and topical preparations associated with relaxation, digestive comfort and skin care.", evidence:"Evidence for specific uses is limited or mixed and varies by product. Chamomile should not be presented as a proven treatment for chronic disease.", caution:"People allergic to ragweed or related plants may react. It may interact with anticoagulants or sedatives; seek advice during pregnancy or before using concentrated extracts."},
"Ginkgo": {habitat:"Ginkgo biloba is a long-lived tree native to China and cultivated worldwide as an ornamental tree. Standardized medicinal extracts are made from leaves.", traditional:"Leaf extracts have been marketed for circulation and memory, while the seeds have different chemistry and safety concerns.", evidence:"Research on memory and dementia has produced mixed results; it is not proven to prevent dementia or reliably improve cognition in healthy people.", caution:"Ginkgo supplements may increase bleeding risk and interact with medicines. Raw seeds can be toxic; do not use seeds as a home remedy."},
"Boswellia / Salai": {habitat:"Boswellia serrata is a tree found in dry forests and rocky areas of India. Its resin is collected from cuts in the bark.", traditional:"The resin, often called salai guggul, is used in some traditional preparations for joint discomfort and inflammation-related complaints.", evidence:"Boswellic acids are being studied, including for osteoarthritis symptoms, but trials vary in quality and extracts are not interchangeable.", caution:"May cause digestive symptoms or interact with medicines. Consult a healthcare professional before use, especially during pregnancy or alongside regular medication."}
};

plants.forEach(p => {
  const extra = extraByCategory[p.category] || extraByCategory.digestive;
  p.habitat = p.habitat || extra.habitat;
  p.traditional = p.traditional || extra.traditional;
  p.evidence = p.evidence || extra.evidence;
  p.caution = p.caution || extra.caution;
  const specific = detailedProfiles[p.name];
  if (specific) Object.assign(p, specific);
});

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

  const all=[p.name,p.scientific,p.compounds,p.part,p.use,p.description,p.habitat,p.traditional,p.evidence,p.caution].join(" ").toLowerCase();

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

  num.textContent=String(i+1).padStart(2,"0")+" / "+plants.length;



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
  document.getElementById("dHabitat").textContent=p.habitat;
  document.getElementById("dTraditional").textContent=p.traditional;
  document.getElementById("dEvidence").textContent=p.evidence;
  document.getElementById("dCaution").textContent=p.caution;

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
