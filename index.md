---
title: "Accueil"
order: 0
in_menu: true
---
<p class="encart"> Let s Rétro</p> 

Article Sur cette astronaute française qui brille

[Le Monde](https://www.lemonde.fr/sciences/article/2022/11/23/l-astronaute-francaise-sophie-adenot-integre-la-nouvelle-promotion-de-l-agence-spatiale-europeenne_6151278_1650684.html) 
<aside>
  S'abonner via le <a href="{{ '/feed.xml' | relative_url }}">flux RSS</a>
  (<a href="https://flus.fr/carnet/a-quoi-servent-les-flux.html">c'est quoi ?</a>)
</aside>

{% for post in site.posts %}
<article class="Sophie Adenot">
  <h2>
    <a href="{https://www.lemonde.fr/sciences/article/2022/11/23/l-astronaute-francaise-sophie-adenot-integre-la-nouvelle-promotion-de-l-agence-spatiale-europeenne_6151278_1650684.html}"> {l-astronaute-francaise-sophie-adenot-integre-la-nouvelle-promotion-de-l-agence-spatiale-europeenne} </a>
  </h2>

  <a href="{{post.url | relative_url}}"> Lire l'article ➞ </a>
</article>
<hr />
{% endfor %} 