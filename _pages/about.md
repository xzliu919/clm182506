---
layout: about
title: Linmei Chen — PhD Student, Zhejiang University
permalink: /
subtitle:
profile:
  enabled: false
social: false
selected_papers: false
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=Inter:wght@400;500;600&display=swap');

:root{
  --clm-bg:#121615; --clm-panel:#1A201E; --clm-text:#E6EBE9; --clm-muted:#9FB0AB;
  --clm-teal:#5CC4B2; --clm-orange:#E79A62; --clm-line:rgba(255,255,255,.08);
}
/* ---- hide al-folio theme chrome, take over the page ---- */
html,body{background:var(--clm-bg)!important;color:var(--clm-text)!important;}
#navbar,footer.fixed-bottom,.progress{display:none!important;}
body.fixed-top-nav{padding-top:0!important;}
#main{display:none!important;}
.container{max-width:none!important;width:auto!important;padding:0!important;margin:0!important;}
.post,.post-header,.post-title{background:transparent!important;border:0!important;padding:0!important;margin:0!important;}
.post-title{display:none!important;}
article,main{background:transparent!important;}
a{color:var(--clm-teal);text-decoration:none;}
a:hover{text-decoration:underline;}

/* ---- layout ---- */
#clm{font-family:Inter,-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif;
  color:var(--clm-text);background:var(--clm-bg);line-height:1.65;font-size:16px;}
#clm .wrap{max-width:1080px;margin:0 auto;padding:0 24px;}
#clm h1,#clm h2,#clm h3{font-family:Fraunces,Georgia,"Times New Roman",serif;font-weight:600;color:var(--clm-text);letter-spacing:.2px;}
#clm h1{font-size:48px;line-height:1.1;margin:6px 0 14px;}
#clm h2{font-size:32px;margin:0 0 22px;}
#clm h3{font-size:19px;margin:0 0 8px;}
#clm section{padding:56px 0;border-top:1px solid var(--clm-line);}
#clm p{margin:0 0 14px;color:var(--clm-muted);}
#clm strong{color:var(--clm-text);}

/* ---- nav ---- */
#clm .nav{position:sticky;top:0;z-index:50;background:rgba(18,22,21,.86);backdrop-filter:blur(10px);
  border-bottom:1px solid var(--clm-line);}
#clm .nav .wrap{display:flex;align-items:center;gap:22px;height:60px;}
#clm .brand{font-family:Fraunces,serif;font-size:19px;color:var(--clm-text);font-weight:600;}
#clm .nav .links{margin-left:auto;display:flex;align-items:center;gap:20px;}
#clm .nav .links a{color:var(--clm-muted);font-size:14.5px;}
#clm .nav .links a:hover{color:var(--clm-text);text-decoration:none;}
#lang-toggle{cursor:pointer;font:inherit;font-size:14px;color:var(--clm-text);background:var(--clm-panel);
  border:1px solid var(--clm-line);border-radius:999px;padding:6px 14px;}
#lang-toggle:hover{border-color:var(--clm-teal);}

/* ---- hero ---- */
#clm .hero{display:flex;gap:36px;align-items:flex-start;padding-top:56px;border-top:0;}
#clm .portrait{width:210px;height:210px;object-fit:cover;border-radius:16px;flex:0 0 auto;background:var(--clm-panel);}
#clm .eyebrow{color:var(--clm-orange);text-transform:uppercase;letter-spacing:.12em;font-size:12.5px;font-weight:600;margin:2px 0 10px;}
#clm .affil{color:var(--clm-muted);margin:0 0 6px;font-size:15.5px;}
#clm .pills{list-style:none;display:flex;flex-wrap:wrap;gap:10px;padding:0;margin:18px 0 0;}
#clm .pill{display:inline-block;padding:8px 16px;border-radius:999px;font-size:14px;background:var(--clm-panel);
  border:1px solid var(--clm-line);color:var(--clm-text);}
#clm .pill:hover{text-decoration:none;border-color:var(--clm-teal);}
#clm .pill.primary{background:var(--clm-teal);color:#121615;border-color:var(--clm-teal);font-weight:600;}

/* ---- research cards ---- */
#clm .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;}
#clm .card{background:var(--clm-panel);border:1px solid var(--clm-line);border-radius:14px;padding:22px;}
#clm .card .num{font-family:Fraunces,serif;color:var(--clm-orange);font-size:15px;font-weight:600;margin-bottom:10px;}
#clm .card p{margin:0;font-size:14.5px;}

/* ---- news ---- */
#clm .news{list-style:none;padding:0;margin:0;}
#clm .news li{display:flex;gap:16px;padding:12px 0;border-bottom:1px solid var(--clm-line);}
#clm .news time{color:var(--clm-orange);font-variant-numeric:tabular-nums;flex:0 0 64px;font-size:14.5px;}
#clm .news span{color:var(--clm-muted);font-size:15px;}

/* ---- publications ---- */
#clm .pubs{list-style:none;padding:0;margin:0;counter-reset:p;}
#clm .pubs li{position:relative;padding:16px 0 16px 44px;border-bottom:1px solid var(--clm-line);}
#clm .pubs li:before{counter-increment:p;content:counter(p);position:absolute;left:0;top:16px;
  font-family:Fraunces,serif;color:var(--clm-orange);font-size:15px;font-weight:600;}
#clm .pubs .title{color:var(--clm-text);font-weight:500;}
#clm .pubs .meta{color:var(--clm-muted);font-size:14.5px;}

/* ---- simple lists ---- */
#clm .rows{list-style:none;padding:0;margin:0;}
#clm .rows li{display:flex;gap:18px;padding:12px 0;border-bottom:1px solid var(--clm-line);}
#clm .rows .when{color:var(--clm-orange);flex:0 0 132px;font-variant-numeric:tabular-nums;font-size:14.5px;}
#clm .rows .what{color:var(--clm-muted);font-size:15px;}

#clm footer{padding:40px 0 60px;color:var(--clm-muted);font-size:13.5px;border-top:1px solid var(--clm-line);}

@media(max-width:820px){
  #clm .cards{grid-template-columns:1fr;}
  #clm .hero{flex-direction:column;}
  #clm .nav .links{display:none;}
  #clm h1{font-size:38px;}
}
/* language switching: default English */
.lang-zh{display:none;}
html[data-lang="zh"] .lang-en{display:none;}
html[data-lang="zh"] .lang-zh{display:block;}
html[data-lang="zh"] #clm .lang-zh{display:block;}
</style>

<div id="clm">

<header class="nav">
  <div class="wrap">
    <a class="brand" href="#top">Linmei Chen</a>
    <div class="links">
      <a href="#research"><span class="lang-en">Research</span><span class="lang-zh">研究方向</span></a>
      <a href="#news"><span class="lang-en">News</span><span class="lang-zh">动态</span></a>
      <a href="#publications"><span class="lang-en">Publications</span><span class="lang-zh">论文</span></a>
      <a href="#honors"><span class="lang-en">Honors</span><span class="lang-zh">荣誉</span></a>
      <a href="#education"><span class="lang-en">Education</span><span class="lang-zh">教育</span></a>
      <button id="lang-toggle" type="button">中文</button>
    </div>
  </div>
</header>

<section class="hero wrap" id="top">
  <img class="portrait" src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Linmei Chen">
  <div>
    <p class="eyebrow"><span class="lang-en">PhD Student · Zhejiang University</span><span class="lang-zh">博士研究生 · 浙江大学</span></p>
    <h1><span class="lang-en">Linmei Chen</span><span class="lang-zh">陈林妹</span></h1>
    <p class="affil lang-en">Institute of Vegetable Science, Zhejiang University<br>Hangzhou, China</p>
    <p class="affil lang-zh">浙江大学 蔬菜学<br>中国 · 杭州</p>
    <p class="lang-en">I am a PhD student in Vegetable Science at Zhejiang University. My research explores the molecular mechanisms underlying ornamental and stress-responsive traits in horticultural crops — from flower pigmentation and abiotic stress tolerance in <em>Rosa</em>, to stress tolerance in Cucurbitaceae crops.</p>
    <p class="lang-zh">我是浙江大学蔬菜学博士研究生，主要研究园艺作物观赏性状与抗逆性状的分子机制——涵盖蔷薇科（月季/蔷薇）的花色与抗逆，以及葫芦科作物的抗逆机制。</p>
    <ul class="pills">
      <li><a class="pill primary" href="mailto:clm182506@zju.edu.cn">clm182506@zju.edu.cn</a></li>
      <li><a class="pill" href="https://orcid.org/0009-0002-6347-5196">ORCID</a></li>
      <li><a class="pill" href="https://github.com/xzliu919">GitHub</a></li>
    </ul>
  </div>
</section>

<section class="wrap" id="research">
  <h2><span class="lang-en">Research</span><span class="lang-zh">研究方向</span></h2>
  <div class="cards">
    <article class="card">
      <div class="num">01</div>
      <h3><span class="lang-en">Floral Ornamental Traits</span><span class="lang-zh">花卉观赏性状</span></h3>
      <p class="lang-en">Transcriptional regulation of anthocyanin and proanthocyanidin biosynthesis in rose, e.g. the RhMYB1–RhMYB123 positive feedback loop.</p>
      <p class="lang-zh">月季花青素与原花青素合成的转录调控，如 RhMYB1–RhMYB123 正反馈调控环。</p>
    </article>
    <article class="card">
      <div class="num">02</div>
      <h3><span class="lang-en">Stress Tolerance in Rosa</span><span class="lang-zh">蔷薇科抗逆</span></h3>
      <p class="lang-en">Cold, salt and drought tolerance mediated by transcription factors and ROS homeostasis (ERF54, RmZAT10, RmNHX2, RcDREB1E–RcMYB28).</p>
      <p class="lang-zh">由转录因子与 ROS 稳态介导的低温、盐、干旱耐受（ERF54、RmZAT10、RmNHX2、RcDREB1E–RcMYB28）。</p>
    </article>
    <article class="card">
      <div class="num">03</div>
      <h3><span class="lang-en">Cucurbitaceae Stress Biology</span><span class="lang-zh">葫芦科抗逆</span></h3>
      <p class="lang-en">Molecular mechanisms of stress tolerance in cucurbit crops (cucumber, melon, pumpkin, watermelon).</p>
      <p class="lang-zh">葫芦科作物（黄瓜、甜瓜、南瓜、西瓜等）抗逆性状的分子机制。</p>
    </article>
  </div>
</section>

<section class="wrap" id="news">
  <h2><span class="lang-en">News</span><span class="lang-zh">动态</span></h2>
  <ul class="news">
    <li><time>2024</time><span class="lang-en">Paper published in <em>Plant, Cell &amp; Environment</em> — ERF54 regulates cold tolerance in <em>Rosa multiflora</em>.</span><span class="lang-zh">论文发表于 <em>Plant, Cell &amp; Environment</em> —— ERF54 调控白花野蔷薇抗寒性。</span></li>
    <li><time>2024</time><span class="lang-en">Paper published in <em>Horticultural Plant Journal</em> — RhMYB114–RhMYB16 feedback loop.</span><span class="lang-zh">论文发表于 <em>Horticultural Plant Journal</em> —— RhMYB114–RhMYB16 调控环。</span></li>
    <li><time>2023</time><span class="lang-en">Awarded the Zhejiang Provincial Excellent Master's Thesis.</span><span class="lang-zh">获评浙江省优秀硕士学位论文。</span></li>
    <li><time>2023</time><span class="lang-en">Papers published in <em>Industrial Crops and Products</em> and <em>Horticulturae</em>.</span><span class="lang-zh">论文发表于 <em>Industrial Crops and Products</em> 与 <em>Horticulturae</em>。</span></li>
  </ul>
</section>

<section class="wrap" id="publications">
  <h2><span class="lang-en">Publications</span><span class="lang-zh">代表性论文</span></h2>
  <ol class="pubs">
    <li>
      <span class="title">Zhou Y<sup>†</sup>, <strong>Chen L</strong><sup>†</sup>, Zhang H<sup>†</sup>, Chen Y, Xin J, Chen W, Cui Y, Shen Y*, Luo P*. The RcDREB1E–RcMYB28 module improves drought tolerance in <em>Rosa chinensis</em> via RcLAR/RcCORA1-mediated proanthocyanidin biosynthesis and stress responses.</span>
      <div class="meta">The Plant Journal, 2026, 128: e71169.</div>
    </li>
    <li>
      <span class="title"><strong>Chen L</strong>, Chen Y, Zhang H, Shen Y, Cui Y*, Luo P*. ERF54 regulates cold tolerance in <em>Rosa multiflora</em> through DREB/COR signalling pathways.</span>
      <div class="meta">Plant, Cell &amp; Environment, 2024. <a href="https://doi.org/10.1111/pce.14796">doi:10.1111/pce.14796</a></div>
    </li>
    <li>
      <span class="title">Chen Y, Shao G, <strong>Chen L</strong>, Zhang H, Cui Y, Luo P*. A feedback loop comprising RhMYB114 and RhMYB16 regulates anthocyanin accumulation and tissue acidification in <em>Rosa hybrida</em>.</span>
      <div class="meta">Horticultural Plant Journal, 2024. <a href="https://doi.org/10.1016/j.hpj.2024.07.004">doi:10.1016/j.hpj.2024.07.004</a></div>
    </li>
    <li>
      <span class="title"><strong>Chen L</strong>, Chen Y, Shen Y, Wen X, Cui Y*, Luo P*. RhMYB1 and RhMYB123 form a positive feedback loop to regulate the proanthocyanidin biosynthesis in rose.</span>
      <div class="meta">Industrial Crops and Products, 2023, 196: 116792. <a href="https://doi.org/10.1016/j.indcrop.2023.116492">doi:10.1016/j.indcrop.2023.116492</a></div>
    </li>
    <li>
      <span class="title">Luo H<sup>†</sup>, Shen Y<sup>†</sup>, <strong>Chen L</strong>, Cui Y, Luo P*. A Na<sup>+</sup>/H<sup>+</sup> antiporter gene from <em>Rosa multiflora</em> (RmNHX2) functions in salt tolerance via modulating ROS levels and ion homeostasis.</span>
      <div class="meta">Horticulturae, 2023, 9: 290. <a href="https://doi.org/10.3390/horticulturae9030290">doi:10.3390/horticulturae9030290</a></div>
    </li>
    <li>
      <span class="title">Luo P*<sup>#</sup>, <strong>Chen L</strong><sup>#</sup>, Chen Y, Shen Y, Cui Y*. RmZAT10, a novel Cys2/His2 zinc finger transcription factor of <em>Rosa multiflora</em>, functions in cold tolerance through modulation of proline biosynthesis and ROS homeostasis.</span>
      <div class="meta">Environmental and Experimental Botany, 2022, 198: 104845. <a href="https://doi.org/10.1016/j.envexpbot.2022.104845">doi:10.1016/j.envexpbot.2022.104845</a></div>
    </li>
  </ol>
</section>

<section class="wrap" id="honors">
  <h2><span class="lang-en">Honors</span><span class="lang-zh">荣誉</span></h2>
  <ul class="rows">
    <li><span class="when">2023</span><span class="what lang-en">Zhejiang Provincial Excellent Master's Thesis (浙江省优秀硕士学位论文)</span><span class="what lang-zh">浙江省优秀硕士学位论文</span></li>
  </ul>
</section>

<section class="wrap" id="education">
  <h2><span class="lang-en">Education</span><span class="lang-zh">教育经历</span></h2>
  <ul class="rows">
    <li><span class="when">2023.9 – 2027.6</span><span class="what lang-en">PhD in Vegetable Science, Zhejiang University</span><span class="what lang-zh">博士 · 蔬菜学 · 浙江大学</span></li>
    <li><span class="when">2020.9 – 2023.6</span><span class="what lang-en">MSc in Horticulture, Zhejiang A&amp;F University</span><span class="what lang-zh">硕士 · 园艺学 · 浙江农林大学</span></li>
    <li><span class="when">2016.9 – 2020.7</span><span class="what lang-en">BSc in Plant Science and Technology, Shandong Agricultural University</span><span class="what lang-zh">本科 · 植物科学与技术 · 山东农业大学</span></li>
  </ul>
</section>

<footer class="wrap">
  <span class="lang-en">© <span id="yr">2026</span> Linmei Chen · Built with al-folio &amp; GitHub Pages</span>
  <span class="lang-zh">© <span>2026</span> 陈林妹 · 基于 al-folio 与 GitHub Pages 构建</span>
</footer>

</div>

<script>
(function(){
  try{ if((localStorage.getItem('clm-lang')||'')==='zh'){document.documentElement.setAttribute('data-lang','zh');} }catch(e){}
  function init(){
    var btn=document.getElementById('lang-toggle'); if(!btn) return;
    function cur(){ return document.documentElement.getAttribute('data-lang')==='zh'?'zh':'en'; }
    function upd(){ btn.textContent = cur()==='zh' ? 'EN' : '中文'; document.documentElement.lang = cur()==='zh'?'zh':'en'; }
    upd();
    btn.addEventListener('click',function(){
      var n = cur()==='zh' ? 'en' : 'zh';
      if(n==='zh'){document.documentElement.setAttribute('data-lang','zh');}
      else{document.documentElement.removeAttribute('data-lang');}
      try{ localStorage.setItem('clm-lang', n); }catch(e){}
      upd();
    });
  }
  if(document.readyState!=='loading') init(); else document.addEventListener('DOMContentLoaded',init);
})();
</script>
---
layout: about
title:
permalink: /
subtitle:
profile:
  enabled: false
social: false
selected_papers: false
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=Inter:wght@400;500;600&display=swap');

:root{
  --clm-bg:#121615; --clm-panel:#1A201E; --clm-text:#E6EBE9; --clm-muted:#9FB0AB;
  --clm-teal:#5CC4B2; --clm-orange:#E79A62; --clm-line:rgba(255,255,255,.08);
}
/* ---- hide al-folio theme chrome, take over the page ---- */
html,body{background:var(--clm-bg)!important;color:var(--clm-text)!important;}
#navbar,footer.fixed-bottom,.progress{display:none!important;}
body.fixed-top-nav{padding-top:0!important;}
#main{display:none!important;}
.container{max-width:none!important;width:auto!important;padding:0!important;margin:0!important;}
.post,.post-header,.post-title{background:transparent!important;border:0!important;padding:0!important;margin:0!important;}
.post-title{display:none!important;}
article,main{background:transparent!important;}
a{color:var(--clm-teal);text-decoration:none;}
a:hover{text-decoration:underline;}

/* ---- layout ---- */
#clm{font-family:Inter,-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif;
  color:var(--clm-text);background:var(--clm-bg);line-height:1.65;font-size:16px;}
#clm .wrap{max-width:1080px;margin:0 auto;padding:0 24px;}
#clm h1,#clm h2,#clm h3{font-family:Fraunces,Georgia,"Times New Roman",serif;font-weight:600;color:var(--clm-text);letter-spacing:.2px;}
#clm h1{font-size:48px;line-height:1.1;margin:6px 0 14px;}
#clm h2{font-size:32px;margin:0 0 22px;}
#clm h3{font-size:19px;margin:0 0 8px;}
#clm section{padding:56px 0;border-top:1px solid var(--clm-line);}
#clm p{margin:0 0 14px;color:var(--clm-muted);}
#clm strong{color:var(--clm-text);}

/* ---- nav ---- */
#clm .nav{position:sticky;top:0;z-index:50;background:rgba(18,22,21,.86);backdrop-filter:blur(10px);
  border-bottom:1px solid var(--clm-line);}
#clm .nav .wrap{display:flex;align-items:center;gap:22px;height:60px;}
#clm .brand{font-family:Fraunces,serif;font-size:19px;color:var(--clm-text);font-weight:600;}
#clm .nav .links{margin-left:auto;display:flex;align-items:center;gap:20px;}
#clm .nav .links a{color:var(--clm-muted);font-size:14.5px;}
#clm .nav .links a:hover{color:var(--clm-text);text-decoration:none;}
#lang-toggle{cursor:pointer;font:inherit;font-size:14px;color:var(--clm-text);background:var(--clm-panel);
  border:1px solid var(--clm-line);border-radius:999px;padding:6px 14px;}
#lang-toggle:hover{border-color:var(--clm-teal);}

/* ---- hero ---- */
#clm .hero{display:flex;gap:36px;align-items:flex-start;padding-top:56px;border-top:0;}
#clm .portrait{width:210px;height:210px;object-fit:cover;border-radius:16px;flex:0 0 auto;background:var(--clm-panel);}
#clm .eyebrow{color:var(--clm-orange);text-transform:uppercase;letter-spacing:.12em;font-size:12.5px;font-weight:600;margin:2px 0 10px;}
#clm .affil{color:var(--clm-muted);margin:0 0 6px;font-size:15.5px;}
#clm .pills{list-style:none;display:flex;flex-wrap:wrap;gap:10px;padding:0;margin:18px 0 0;}
#clm .pill{display:inline-block;padding:8px 16px;border-radius:999px;font-size:14px;background:var(--clm-panel);
  border:1px solid var(--clm-line);color:var(--clm-text);}
#clm .pill:hover{text-decoration:none;border-color:var(--clm-teal);}
#clm .pill.primary{background:var(--clm-teal);color:#121615;border-color:var(--clm-teal);font-weight:600;}

/* ---- research cards ---- */
#clm .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;}
#clm .card{background:var(--clm-panel);border:1px solid var(--clm-line);border-radius:14px;padding:22px;}
#clm .card .num{font-family:Fraunces,serif;color:var(--clm-orange);font-size:15px;font-weight:600;margin-bottom:10px;}
#clm .card p{margin:0;font-size:14.5px;}

/* ---- news ---- */
#clm .news{list-style:none;padding:0;margin:0;}
#clm .news li{display:flex;gap:16px;padding:12px 0;border-bottom:1px solid var(--clm-line);}
#clm .news time{color:var(--clm-orange);font-variant-numeric:tabular-nums;flex:0 0 64px;font-size:14.5px;}
#clm .news span{color:var(--clm-muted);font-size:15px;}

/* ---- publications ---- */
#clm .pubs{list-style:none;padding:0;margin:0;counter-reset:p;}
#clm .pubs li{position:relative;padding:16px 0 16px 44px;border-bottom:1px solid var(--clm-line);}
#clm .pubs li:before{counter-increment:p;content:counter(p);position:absolute;left:0;top:16px;
  font-family:Fraunces,serif;color:var(--clm-orange);font-size:15px;font-weight:600;}
#clm .pubs .title{color:var(--clm-text);font-weight:500;}
#clm .pubs .meta{color:var(--clm-muted);font-size:14.5px;}

/* ---- simple lists ---- */
#clm .rows{list-style:none;padding:0;margin:0;}
#clm .rows li{display:flex;gap:18px;padding:12px 0;border-bottom:1px solid var(--clm-line);}
#clm .rows .when{color:var(--clm-orange);flex:0 0 132px;font-variant-numeric:tabular-nums;font-size:14.5px;}
#clm .rows .what{color:var(--clm-muted);font-size:15px;}

#clm footer{padding:40px 0 60px;color:var(--clm-muted);font-size:13.5px;border-top:1px solid var(--clm-line);}

@media(max-width:820px){
  #clm .cards{grid-template-columns:1fr;}
  #clm .hero{flex-direction:column;}
  #clm .nav .links{display:none;}
  #clm h1{font-size:38px;}
}
/* language switching: default English */
.lang-zh{display:none;}
html[data-lang="zh"] .lang-en{display:none;}
html[data-lang="zh"] .lang-zh{display:block;}
html[data-lang="zh"] #clm .lang-zh{display:block;}
</style>

<div id="clm">

<header class="nav">
  <div class="wrap">
    <a class="brand" href="#top">Linmei Chen</a>
    <div class="links">
      <a href="#research"><span class="lang-en">Research</span><span class="lang-zh">研究方向</span></a>
      <a href="#news"><span class="lang-en">News</span><span class="lang-zh">动态</span></a>
      <a href="#publications"><span class="lang-en">Publications</span><span class="lang-zh">论文</span></a>
      <a href="#honors"><span class="lang-en">Honors</span><span class="lang-zh">荣誉</span></a>
      <a href="#education"><span class="lang-en">Education</span><span class="lang-zh">教育</span></a>
      <button id="lang-toggle" type="button">中文</button>
    </div>
  </div>
</header>

<section class="hero wrap" id="top">
  <img class="portrait" src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Linmei Chen">
  <div>
    <p class="eyebrow"><span class="lang-en">PhD Student · Zhejiang University</span><span class="lang-zh">博士研究生 · 浙江大学</span></p>
    <h1><span class="lang-en">Linmei Chen</span><span class="lang-zh">陈林妹</span></h1>
    <p class="affil lang-en">Institute of Vegetable Science, Zhejiang University<br>Hangzhou, China</p>
    <p class="affil lang-zh">浙江大学 蔬菜学<br>中国 · 杭州</p>
    <p class="lang-en">I am a PhD student in Vegetable Science at Zhejiang University. My research explores the molecular mechanisms underlying ornamental and stress-responsive traits in horticultural crops — from flower pigmentation and abiotic stress tolerance in <em>Rosa</em>, to stress tolerance in Cucurbitaceae crops.</p>
    <p class="lang-zh">我是浙江大学蔬菜学博士研究生，主要研究园艺作物观赏性状与抗逆性状的分子机制——涵盖蔷薇科（月季/蔷薇）的花色与抗逆，以及葫芦科作物的抗逆机制。</p>
    <ul class="pills">
      <li><a class="pill primary" href="mailto:clm182506@zju.edu.cn">clm182506@zju.edu.cn</a></li>
      <li><a class="pill" href="https://orcid.org/0009-0002-6347-5196">ORCID</a></li>
      <li><a class="pill" href="https://github.com/xzliu919">GitHub</a></li>
    </ul>
  </div>
</section>

<section class="wrap" id="research">
  <h2><span class="lang-en">Research</span><span class="lang-zh">研究方向</span></h2>
  <div class="cards">
    <article class="card">
      <div class="num">01</div>
      <h3><span class="lang-en">Floral Ornamental Traits</span><span class="lang-zh">花卉观赏性状</span></h3>
      <p class="lang-en">Transcriptional regulation of anthocyanin and proanthocyanidin biosynthesis in rose, e.g. the RhMYB1–RhMYB123 positive feedback loop.</p>
      <p class="lang-zh">月季花青素与原花青素合成的转录调控，如 RhMYB1–RhMYB123 正反馈调控环。</p>
    </article>
    <article class="card">
      <div class="num">02</div>
      <h3><span class="lang-en">Stress Tolerance in Rosa</span><span class="lang-zh">蔷薇科抗逆</span></h3>
      <p class="lang-en">Cold, salt and drought tolerance mediated by transcription factors and ROS homeostasis (ERF54, RmZAT10, RmNHX2, RcDREB1E–RcMYB28).</p>
      <p class="lang-zh">由转录因子与 ROS 稳态介导的低温、盐、干旱耐受（ERF54、RmZAT10、RmNHX2、RcDREB1E–RcMYB28）。</p>
    </article>
    <article class="card">
      <div class="num">03</div>
      <h3><span class="lang-en">Cucurbitaceae Stress Biology</span><span class="lang-zh">葫芦科抗逆</span></h3>
      <p class="lang-en">Molecular mechanisms of stress tolerance in cucurbit crops (cucumber, melon, pumpkin, watermelon).</p>
      <p class="lang-zh">葫芦科作物（黄瓜、甜瓜、南瓜、西瓜等）抗逆性状的分子机制。</p>
    </article>
  </div>
</section>

<section class="wrap" id="news">
  <h2><span class="lang-en">News</span><span class="lang-zh">动态</span></h2>
  <ul class="news">
    <li><time>2024</time><span class="lang-en">Paper published in <em>Plant, Cell &amp; Environment</em> — ERF54 regulates cold tolerance in <em>Rosa multiflora</em>.</span><span class="lang-zh">论文发表于 <em>Plant, Cell &amp; Environment</em> —— ERF54 调控白花野蔷薇抗寒性。</span></li>
    <li><time>2024</time><span class="lang-en">Paper published in <em>Horticultural Plant Journal</em> — RhMYB114–RhMYB16 feedback loop.</span><span class="lang-zh">论文发表于 <em>Horticultural Plant Journal</em> —— RhMYB114–RhMYB16 调控环。</span></li>
    <li><time>2023</time><span class="lang-en">Awarded the Zhejiang Provincial Excellent Master's Thesis.</span><span class="lang-zh">获评浙江省优秀硕士学位论文。</span></li>
    <li><time>2023</time><span class="lang-en">Papers published in <em>Industrial Crops and Products</em> and <em>Horticulturae</em>.</span><span class="lang-zh">论文发表于 <em>Industrial Crops and Products</em> 与 <em>Horticulturae</em>。</span></li>
  </ul>
</section>

<section class="wrap" id="publications">
  <h2><span class="lang-en">Publications</span><span class="lang-zh">代表性论文</span></h2>
  <ol class="pubs">
    <li>
      <span class="title">Zhou Y<sup>†</sup>, <strong>Chen L</strong><sup>†</sup>, Zhang H<sup>†</sup>, Chen Y, Xin J, Chen W, Cui Y, Shen Y*, Luo P*. The RcDREB1E–RcMYB28 module improves drought tolerance in <em>Rosa chinensis</em> via RcLAR/RcCORA1-mediated proanthocyanidin biosynthesis and stress responses.</span>
      <div class="meta">The Plant Journal, 2026, 128: e71169.</div>
    </li>
    <li>
      <span class="title"><strong>Chen L</strong>, Chen Y, Zhang H, Shen Y, Cui Y*, Luo P*. ERF54 regulates cold tolerance in <em>Rosa multiflora</em> through DREB/COR signalling pathways.</span>
      <div class="meta">Plant, Cell &amp; Environment, 2024. <a href="https://doi.org/10.1111/pce.14796">doi:10.1111/pce.14796</a></div>
    </li>
    <li>
      <span class="title">Chen Y, Shao G, <strong>Chen L</strong>, Zhang H, Cui Y, Luo P*. A feedback loop comprising RhMYB114 and RhMYB16 regulates anthocyanin accumulation and tissue acidification in <em>Rosa hybrida</em>.</span>
      <div class="meta">Horticultural Plant Journal, 2024. <a href="https://doi.org/10.1016/j.hpj.2024.07.004">doi:10.1016/j.hpj.2024.07.004</a></div>
    </li>
    <li>
      <span class="title"><strong>Chen L</strong>, Chen Y, Shen Y, Wen X, Cui Y*, Luo P*. RhMYB1 and RhMYB123 form a positive feedback loop to regulate the proanthocyanidin biosynthesis in rose.</span>
      <div class="meta">Industrial Crops and Products, 2023, 196: 116792. <a href="https://doi.org/10.1016/j.indcrop.2023.116492">doi:10.1016/j.indcrop.2023.116492</a></div>
    </li>
    <li>
      <span class="title">Luo H<sup>†</sup>, Shen Y<sup>†</sup>, <strong>Chen L</strong>, Cui Y, Luo P*. A Na<sup>+</sup>/H<sup>+</sup> antiporter gene from <em>Rosa multiflora</em> (RmNHX2) functions in salt tolerance via modulating ROS levels and ion homeostasis.</span>
      <div class="meta">Horticulturae, 2023, 9: 290. <a href="https://doi.org/10.3390/horticulturae9030290">doi:10.3390/horticulturae9030290</a></div>
    </li>
    <li>
      <span class="title">Luo P*<sup>#</sup>, <strong>Chen L</strong><sup>#</sup>, Chen Y, Shen Y, Cui Y*. RmZAT10, a novel Cys2/His2 zinc finger transcription factor of <em>Rosa multiflora</em>, functions in cold tolerance through modulation of proline biosynthesis and ROS homeostasis.</span>
      <div class="meta">Environmental and Experimental Botany, 2022, 198: 104845. <a href="https://doi.org/10.1016/j.envexpbot.2022.104845">doi:10.1016/j.envexpbot.2022.104845</a></div>
    </li>
  </ol>
</section>

<section class="wrap" id="honors">
  <h2><span class="lang-en">Honors</span><span class="lang-zh">荣誉</span></h2>
  <ul class="rows">
    <li><span class="when">2023</span><span class="what lang-en">Zhejiang Provincial Excellent Master's Thesis (浙江省优秀硕士学位论文)</span><span class="what lang-zh">浙江省优秀硕士学位论文</span></li>
  </ul>
</section>

<section class="wrap" id="education">
  <h2><span class="lang-en">Education</span><span class="lang-zh">教育经历</span></h2>
  <ul class="rows">
    <li><span class="when">2023.9 – 2027.6</span><span class="what lang-en">PhD in Vegetable Science, Zhejiang University</span><span class="what lang-zh">博士 · 蔬菜学 · 浙江大学</span></li>
    <li><span class="when">2020.9 – 2023.6</span><span class="what lang-en">MSc in Horticulture, Zhejiang A&amp;F University</span><span class="what lang-zh">硕士 · 园艺学 · 浙江农林大学</span></li>
    <li><span class="when">2016.9 – 2020.7</span><span class="what lang-en">BSc in Plant Science and Technology, Shandong Agricultural University</span><span class="what lang-zh">本科 · 植物科学与技术 · 山东农业大学</span></li>
  </ul>
</section>

<footer class="wrap">
  <span class="lang-en">© <span id="yr">2026</span> Linmei Chen · Built with al-folio &amp; GitHub Pages</span>
  <span class="lang-zh">© <span>2026</span> 陈林妹 · 基于 al-folio 与 GitHub Pages 构建</span>
</footer>

</div>

<script>
(function(){
  try{ if((localStorage.getItem('clm-lang')||'')==='zh'){document.documentElement.setAttribute('data-lang','zh');} }catch(e){}
  function init(){
    var btn=document.getElementById('lang-toggle'); if(!btn) return;
    function cur(){ return document.documentElement.getAttribute('data-lang')==='zh'?'zh':'en'; }
    function upd(){ btn.textContent = cur()==='zh' ? 'EN' : '中文'; document.documentElement.lang = cur()==='zh'?'zh':'en'; }
    upd();
    btn.addEventListener('click',function(){
      var n = cur()==='zh' ? 'en' : 'zh';
      if(n==='zh'){document.documentElement.setAttribute('data-lang','zh');}
      else{document.documentElement.removeAttribute('data-lang');}
      try{ localStorage.setItem('clm-lang', n); }catch(e){}
      upd();
    });
  }
  if(document.readyState!=='loading') init(); else document.addEventListener('DOMContentLoaded',init);
})();
</script>
