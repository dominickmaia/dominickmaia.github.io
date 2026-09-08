---
layout: about
title: about
permalink: /
subtitle: <a href='http://dgp.cnpq.br/dgp/espelhogrupo/2542059310124116' target='_blank'>CompLin</a> · <a href='https://www.ufc.br/pt' target='_blank'>Universidade Federal do Ceará</a>

profile:
  align: right
  image: Image100827.png
  image_circular: false
  more_info: >

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: true
  scrollable: true
  limit: 3
---

<style>
  .tagged{
    position: relative;
    display: inline-flex;
    flex-direction: column;
    align-items: center;
    padding: 1px 9px 3px;
    border-radius: 7px;
    color: #2A2822;
    font-weight: 400;
    margin: 0 2px;
    line-height: 1.3;
  }
  .tagged .tag-label{
    position: absolute;
    bottom: -17px;
    font-family: monospace;
    font-size: 9.5px;
    font-weight: 600;
    letter-spacing: 0.04em;
    padding: 1px 6px;
    border-radius: 4px;
    white-space: nowrap;
  }
  .tagged--noun{ background: #FFE4DA; }
  .tagged--noun .tag-label{ background: #FF6B47; color: #fff; }
  .tagged--verb{ background: #E9E3FF; }
  .tagged--verb .tag-label{ background: #7C5CFC; color: #fff; }
  .tagged--adj{ background: #D6F5F0; }
  .tagged--adj .tag-label{ background: #00A896; color: #fff; }
  .tagged--adp{ background: #DCEAFA; }
  .tagged--adp .tag-label{ background: #4F86C6; color: #fff; }
  .tagged--propn{ background: #FFDCEA; }
  .tagged--propn .tag-label{ background: #E0447A; color: #fff; }
  .tagged--adv{ background: #FFF1C2; }
  .tagged--adv .tag-label{ background: #E0A200; color: #3D2E00; }
  .tagged--cconj{ background: #E7E7EA; }
  .tagged--cconj .tag-label{ background: #6E6E76; color: #fff; }

  .tagged-hover{ cursor: help; }
  .tagged-hover::after{
    content: attr(data-tag);
    position: absolute;
    left: 50%; bottom: calc(100% + 8px);
    transform: translateX(-50%) translateY(4px);
    background: #000; color: #fff;
    font-family: monospace; font-size: 11px; font-weight: 500;
    padding: 6px 10px; border-radius: 6px; white-space: nowrap;
    opacity: 0; pointer-events: none;
    transition: opacity 0.15s ease, transform 0.15s ease;
    z-index: 5;
  }
  .tagged-hover::before{
    content: "";
    position: absolute;
    left: 50%; bottom: calc(100% + 2px);
    transform: translateX(-50%);
    border: 5px solid transparent; border-top-color: #000;
    opacity: 0; transition: opacity 0.15s ease; z-index: 5;
  }
  .tagged-hover:hover::after{ opacity: 1; transform: translateX(-50%) translateY(0); }
  .tagged-hover:hover::before{ opacity: 1; }

  .bio-tagged-line{ line-height: 2.5; }
</style>

<p class="bio-tagged-line">
  <span class="tagged tagged--noun tagged-hover" data-tag="Gender=Fem|Number=Sing">Pesquisadora<span class="tag-label">NOUN</span></span>
  em <span class="tagged tagged--noun">Linguística<span class="tag-label">NOUN</span></span> <span class="tagged tagged--adj tagged-hover" data-tag="Gender=Fem|Number=Sing">Computacional<span class="tag-label">ADJ</span></span>,
  <span class="tagged tagged--verb tagged-hover" data-tag="VerbForm">trabalhando<span class="tag-label">VERB</span></span>
  no processamento automático de línguas <span class="tagged tagged--adj tagged-hover" data-tag="Gender=Fem|Number=Plur">indígenas<span class="tag-label">ADJ</span></span> brasileiras. Doutoranda em <span class="tagged tagged--noun">Linguística<span class="tag-label">NOUN</span></span> (PPGLin/UFC), <span class="tagged tagged--adp">sob<span class="tag-label">ADP</span></span> orientação do Prof. <span class="tagged tagged--propn">Leonel<span class="tag-label">PROPN</span></span> F. de Alencar [↗](https://leoalenc.github.io/){:target="_blank"}, com pesquisa <span class="tagged tagged--verb tagged-hover" data-tag="Gender=Fem|Number=Sing|VerbForm=Part">voltada<span class="tag-label">VERB</span></span> à modelagem computacional do <span class="tagged tagged--propn">nheengatu<span class="tag-label">PROPN</span></span>.
</p>

<p class="bio-tagged-line">
  <span class="tagged tagged--adv">Profissionalmente<span class="tag-label">ADV</span></span>,
  <span class="tagged tagged--verb tagged-hover" data-tag="Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin">atuo<span class="tag-label">VERB</span></span>
  com anotação <span class="tagged tagged--cconj">e<span class="tag-label">CCONJ</span></span> análise de dados <span class="tagged tagged--adj tagged-hover" data-tag="Gender=Masc|Number=Plur">linguísticos<span class="tag-label">ADJ</span></span>, desenvolvimento de <span class="tagged tagged--noun tagged-hover" data-tag="Number=Plur">corpora<span class="tag-label">NOUN</span></span> e criação de <span class="tagged tagged--noun tagged-hover" data-tag="Number=Plur">datasets<span class="tag-label">NOUN</span></span> <span class="tagged tagged--adp">para<span class="tag-label">ADP</span></span> treinamento e avaliação de modelos <span class="tagged tagged--adp">de<span class="tag-label">ADP</span></span> língua.
</p>
