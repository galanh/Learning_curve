---
layout: post
title:  "Dos puntos en multivariable"
permalink: dos-puntos-en-multivariable
---

## Dos cosas para entender y recordar
{% include katex_import.html %} 

{% raw %}

<h3> Primero, un buen punto de partida es: </h3>

<div class="equation" data-expr="\displaystyle \nabla \times F = 0"></div>
<ol type = "1">
<li> Un campo sin rotación </li>
<li> Por definición diferencial: <div class="equation" data-expr="\oint_C F \cdot dl = 0"></div> </li>
<li> Podemos describir F mediante una energía potencial V: <div class="equation" data-expr="\displaystyle F = - \nabla \cdot V"></div> </li>
</ol>

<br>                                                                                    

<ol type = "1">
<h3> Segundo, la forma más difícil de decir que para un campo F, lo que entra es igual a lo que sale: </h3>

<div class="equation" data-expr="\displaystyle \nabla \cdot F = 0"></div>
<li> Según el teorema de la divergencia: <div class="equation" data-expr="\displaystyle \int \limits_{V} \nabla \cdot F \, dV = 0 = \int_S F \cdot dA"></div> </li>
<li> Lo que entra por la superficie es igual a lo que sale por ella: <div class="equation" data-expr="\int_S F \cdot dA = 0"></div> </li>
</ol>

{% endraw %}

{% include katex_render.html %} 

