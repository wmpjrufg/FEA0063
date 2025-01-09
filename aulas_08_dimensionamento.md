---
title: Hipóteses básicas e dimensionamento
layout: default
parent: Aulas
nav_order: 7
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<p align="justify">Elementos lineares de concreto armado, conforme a NBR 6118, <strong>são dimensionados considerando flexão normal simples</strong>, uma vez que o plano do momento fletor está em um dos eixos principais da seção transversal e acompanha as ações de força cortante. No entanto, esta mesma norma estabelece que o <strong>dimensionamento de peças submetidas a flexão normal simples deve ser feito de maneira separada</strong> (dimensionamento devido ao momento fletor e dimensionamento devido à força cortante).

<center><img src="assets\images\aula_08\fig_1.png" width="100%"></center>
<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>

<center><img src="assets\images\aula_08\fig_2.png" width="100%"></center>
<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>

<center><img src="assets\images\aula_08\fig_3.png" width="100%"></center>
<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>

<p align="justify">Estádios:</p>
<ol type = "a">
  <li><strong>Estádio I:</strong> Esse estágio inicial de linearidade na respsota experiemntal;</li>
  <li><strong>Estádio II:</strong> Uma certa redução da inclinação da curva marcando o início do trecho de não linearidade;</li>
  <li><strong>Estádio III:</strong> Plastificação da armadura e/ou plastificação do concreto.</li>
</ol>

<center><img src="assets\images\aula_08\fig_4.png" width="100%"></center>
<p align = "center"><b>Figura 4.</b> Bla bla bla.</p>

<p align="justify">Para o <strong>Estádio I</strong> são válidas algumas hipóteses, são elas:</p>
<ul>
    <li><strong>A região de concreto tracionado, abaixo da linha neutra</strong> (\(h – x\)), <strong>está íntegra</strong> (não há fissuras) devido à pequena intensidade das <strong>tensões normais de tração</strong>, as quais <strong>são menores que a tensão resistente do concreto</strong> (fct);</li>
    <li>As <strong>tensões na região comprimida são proporcionais às deformações</strong>, correspondendo ao trecho linear elástico do diagrama tensão-deformação do concreto;</li>
    <li>O diagrama de <strong>tensão normal ao longo da seção é linear</strong> (Ia) – exceto quando o <strong>concreto está na iminência da ruptura devido à tração</strong> (Ib), em que se tem um diagrama plastificado na região de tração do concreto (Ver Figura 1.8).</li>
</ul>

<center><img src="assets\images\aula_08\fig_5.png" width="100%"></center>
<p align = "center"><b>Figura 5.</b> Bla bla bla.</p>

<br>

$$
\begin{align*}
  &A_h = b_f \cdot h_f + b_w \cdot h + A_s \cdot (\alpha - 1)\\
  &y_h = \frac{b_f \cdot \left(\frac{h_f²}{2}\right) + b_w \cdot \frac{h²}{2} + A_s \cdot (\alpha - 1) \cdot d}{A_h}\\
  &I_h = \frac{b_f \cdot h_f³}{12} + \frac{b_w \cdot h³}{12} + b_f \cdot h_f \cdot \left(y{cg} - \frac{h_f}{2}\right)² + b_w \cdot h \cdot \left(y{cg} - \frac{h}{2}\right)² + A_s \cdot (\alpha - 1) \cdot d \cdot (y_h - d)²
\end{align*}
$$

<p align="justify">No <strong>Estádio II</strong> ocorre um <strong>aumento da intensidade do momento fletor solicitante</strong>, o que <strong>produz uma tensão de tração</strong> na maioria dos pontos abaixo da Linha Neutra (L.N.) que <strong>supera a tensão resistente do concreto à tração</strong>, o que resulta nos seguintes comportamentos:</p>
<ul>
    <li>O <strong>momento fletor solicitante supera o momento de fissuração</strong>, o que provoca o aparecimento das fissuras na região de concreto tracionado, abaixo da linha neutra (\(h – x\)). Devido a esse fato, considera-se que apenas o aço resiste aos esforços de tração (despreza-se o concreto tracionado);</li>
    <li>Admite-se que a <strong>tensão de compressão no concreto continue linear</strong>;</li>
    <li>As <strong>fissuras de tração</strong> na flexão do concreto <strong>são visíveis</strong>.
<ul>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets\images\aula_08\fig_6.png" width = "80%"></center></td>
    <td><center><p align = "justify" id = "fig1">Seção sem armadura</td>
  </tr>
  <tr>
    <td><center><img src = "assets\images\aula_08\fig_7.png" width = "80%"></center></td>
    <td><center><p align = "justify" id = "fig1">Seção com armadura</td>
  </tr>
</table>