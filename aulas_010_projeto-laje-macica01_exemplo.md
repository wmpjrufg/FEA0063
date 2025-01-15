---
title: Exemplo
layout: default
grand_parent: Aulas
parent: Projeto laje maciça
nav_order: 1
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Exemplo 1 - Cálculo da área de aço em uma seção de laje</h1>

<p align="justify">Considere o painel de lajes maciças abaixo para determinação da área de aço necessária para laje L2.</p>

<p align = "center"><b>Figura 1.</b> Bla bla bla </p>
<center><img src="assets\images\aula_010\fig_01.png" width="80%"></center>

<br>

<p align="justify">Dados:</p>
<ol type="1">
    <li>\(f_{ck} = 20 \, MPa\)</li>
    <li>\(f_{yk} = 500 \, MPa\)</li>
    <li>\(Cob = 2,50 \, cm\)</li>
    <li>\(h = 12,0 \, cm\)</li>
    <li>\(d^+ = 8,0 \, cm\)</li>
    <li>\(d^- = 9,0 \, cm\)</li>
</ol>

<p align="justify">Vamos fazer o exemplo:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[M_{sdx}^+ \rightarrow 4,28 \, kN \cdot 1,4\]</td>
    </tr>
</table>

<p align="justify">\(b_w = 100 \, cm \rightarrow \text{fixo laje maciçã} = 5,99 \, KN\)
<br><br>
Para \(f_{ck} \leq 50 \, MPa\):
</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[M_{lim} = 0,45 \cdot b_w \cdot \lambda \cdot d² \cdot \alpha_c \cdot f_{cd} (1 - 0,255 \cdot \lambda)\]</td>
    </tr>
    <tr>
        <td>\[M_{lim} = 22,94 \, KN \cdot m\]</td>
    </tr>
</table>

<p align="justify">Se Armadura simples: </p>
<ol type="1">
    <li>\(A_{sc} = 0 \)</li>
    <li>\(x = ? \)</li>
    <li>\(A_{st} = ? \)</li>
</ol>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
  <tr>
    <td rowspan="2" style="width:70%;">
      \[
      x_{III} = \frac{d \pm \sqrt{d^2 - 2 \cdot \left(\frac{M_{sd}}{b_w \cdot \alpha_c \cdot f_{cd}}\right)}}{\lambda}
      \]
    </td>
    <td style="width:30%;">
      \[
      x^+ = 0,19 \, \text{m}
      \]
    </td>
  </tr>
  <tr>
    <td>
      \[
      x^- = 0,008 \, \text{m}
      \]
    </td>
  </tr>
</table>

<br>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[A_{st} = \frac{M_{sd}}{f_{yd} \cdot (d - 0,50 \cdot \lambda \cdot x_{III})} = 0,000179 \, m² \rightarrow 1,79 \, cm²\]</td>
    </tr>
    <tr>
        <td>\[A_{smin} = \frac{0,15}{100} \cdot 12 \cdot 100 = 0,018 \, m² \rightarrow 1,8 \, cm²\]</td>
    </tr>
    <tr>
        <td>\[A_{smax} = \frac{0,04}{100} \cdot 12 \cdot 100 = 0,048 \, m² \rightarrow 4,8 \, cm²\]</td>
    </tr>
</table>

<p align = "center"><b>Figura 2.</b> Bla bla bla </p>
<center><img src="assets\images\aula_010\fig_02.png" width="80%"></center>

<p align="justify">Dado \(\phi l = 10 \, mm\ \rightarrow \phi = 1,0 \, cm\):</p> 

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[y_{cg} = y_{1com} = 12 - 2,5 - \frac{\phi l}{2} - \phi l \]</td>
    </tr>
    <tr>
        <td>\[y_{cg} = 12 - 2,5 - \frac{1}{2} - 1 = 9 \, cm\]</td>
    </tr>
</table>

<p align="justify">\(d_{calc} = 8 \, cm\) e \(d_{real} = 9 \, cm \rightarrow \text{OK}\)</p>