---
title: 03. Fundamentos de Express
parent: Aula 05 - Criando páginas dinâmicas modernas
nav_order: 3
youtubeId: KfxbZWjXpPs
youtubeId2: Ay6pjWQ_iE8
next: 04-template-engine
---

{% assign title = page.title | split: "." %}

## {{ title | slice: 1 }}

{% comment %}
### Recurso
{% endcomment %}

<!--
<span class="fs-3">
  <a href="{{site.baseurl}}/assets/downloads/08-Fundamentos-de-TyoeScript.pdf" class="btn" target="_blank">Notas de aula</a>
  <a href="https://www.icloud.com/keynote/0GDTVZX4m6lppt1uxjntVY2Yg#07-JavaScript-na-web" class="btn" target="_blank">Notas de aula com animações</a>
</span>
-->

{% include youtubePlayer.html id=page.youtubeId %}


{% include youtubePlayer.html id=page.youtubeId2 %}

<span class="fs-3 float-right">
[Próxima aulas]({{page.next}}){: .btn }
</span>

