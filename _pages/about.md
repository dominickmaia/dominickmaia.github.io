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

<script>
  // Se o visitante ainda não escolheu um tema manualmente (não há nada
  // salvo no localStorage), força o modo claro como padrão em vez de
  // seguir a preferência do sistema operacional. Depois que a pessoa
  // clicar no botão de sol/lua, a escolha dela passa a valer normalmente.
  (function () {
    if (!localStorage.getItem("theme")) {
      localStorage.setItem("theme", "light");
      document.documentElement.setAttribute("data-theme", "light");
    }
  })();
</script>

<style>
  .tag-word{ padding: 1px 6px; border-radius: 5px; color: #2A2822; }
  .tag-badge{ position: static; display: inline; vertical-align: text-top; font-size: 9px; font-weight: 600; padding: 1px 4px; border-radius: 3px; margin-left: 2px; }

  .tw-noun{ background: #FFE4DA; } .tb-noun{ background: #FF6B47; color: #fff; }
  .tw-verb{ background: #E9E3FF; } .tb-verb{ background: #7C5CFC; color: #fff; }
  .tw-adj{ background: #D6F5F0; } .tb-adj{ background: #00A896; color: #fff; }
  .tw-adp{ background: #DCEAFA; } .tb-adp{ background: #4F86C6; color: #fff; }
  .tw-propn{ background: #FFDCEA; } .tb-propn{ background: #E0447A; color: #fff; }
  .tw-adv{ background: #FFF1C2; } .tb-adv{ background: #E0A200; color: #3D2E00; }
  .tw-cconj{ background: #E7E7EA; } .tb-cconj{ background: #6E6E76; color: #fff; }

  .tagged-hover{ position: relative; cursor: help; }
  .tagged-hover::after{
    content: attr(data-tag);
    position: absolute;
    left: 50%; bottom: calc(100% + 6px);
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
    left: 50%; bottom: calc(100% + 1px);
    transform: translateX(-50%);
    border: 5px solid transparent; border-top-color: #000;
    opacity: 0; transition: opacity 0.15s ease; z-index: 5;
  }
  .tagged-hover:hover::after{ opacity: 1; transform: translateX(-50%) translateY(0); }
  .tagged-hover:hover::before{ opacity: 1; }
</style>

<p>
  <span class="tagged-hover" data-tag="Gender=Fem|Number=Sing"><span class="tag-word tw-noun">Pesquisadora</span><span class="tag-badge tb-noun">NOUN</span></span>
  em <span class="tag-word tw-noun">Linguística</span><span class="tag-badge tb-noun">NOUN</span> <span class="tagged-hover" data-tag="Gender=Fem|Number=Sing"><span class="tag-word tw-adj">Computacional</span><span class="tag-badge tb-adj">ADJ</span></span>,
  <span class="tagged-hover" data-tag="VerbForm"><span class="tag-word tw-verb">trabalhando</span><span class="tag-badge tb-verb">VERB</span></span>
  no processamento automático de línguas <span class="tagged-hover" data-tag="Gender=Fem|Number=Plur"><span class="tag-word tw-adj">indígenas</span><span class="tag-badge tb-adj">ADJ</span></span> brasileiras. Doutoranda em <span class="tag-word tw-noun">Linguística</span><span class="tag-badge tb-noun">NOUN</span> (PPGLin/UFC), <span class="tag-word tw-adp">sob</span><span class="tag-badge tb-adp">ADP</span> orientação do Prof. <span class="tag-word tw-propn">Leonel</span><span class="tag-badge tb-propn">PROPN</span> F. de Alencar <a href="https://leoalenc.github.io/" target="_blank">↗</a>, com pesquisa <span class="tagged-hover" data-tag="Gender=Fem|Number=Sing|VerbForm=Part"><span class="tag-word tw-verb">voltada</span><span class="tag-badge tb-verb">VERB</span></span> à modelagem computacional do <span class="tag-word tw-propn">nheengatu</span><span class="tag-badge tb-propn">PROPN</span>.
</p>

<p>
  <span class="tag-word tw-adv">Profissionalmente</span><span class="tag-badge tb-adv">ADV</span>,
  <span class="tagged-hover" data-tag="Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin"><span class="tag-word tw-verb">atuo</span><span class="tag-badge tb-verb">VERB</span></span>
  com anotação <span class="tag-word tw-cconj">e</span><span class="tag-badge tb-cconj">CCONJ</span> análise de dados <span class="tagged-hover" data-tag="Gender=Masc|Number=Plur"><span class="tag-word tw-adj">linguísticos</span><span class="tag-badge tb-adj">ADJ</span></span>, desenvolvimento de <span class="tagged-hover" data-tag="Number=Plur"><span class="tag-word tw-noun">corpora</span><span class="tag-badge tb-noun">NOUN</span></span> e criação de <span class="tagged-hover" data-tag="Number=Plur"><span class="tag-word tw-noun">datasets</span><span class="tag-badge tb-noun">NOUN</span></span> <span class="tag-word tw-adp">para</span><span class="tag-badge tb-adp">ADP</span> treinamento e avaliação de modelos <span class="tag-word tw-adp">de</span><span class="tag-badge tb-adp">ADP</span> língua.
</p>