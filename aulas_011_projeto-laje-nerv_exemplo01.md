---
title: Exemplo
layout: default
grand_parent: Aulas
parent: Projeto laje nervurada
nav_order: 1
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Exemplo - Dimensionamento da armadura seção Tê</h1>

<p align = "justify">Um sistema de laje pré-moldada (treliçada), com altura total de 12 cm (d = 10 cm) e capa de 4 cm. O vão efetivo do sistema estrutural é de 4,15 m e as cargas são: (a) Permanente: 2,0 kN/m²; e (b) Variável: 2,0 kN/m²</p>

<p align="justify">Dados:</p>
<ol type="1">
    <li>\(f_{ck} = 20 \, MPa\)</li>
    <li>\(f_{yk} = 500 \, MPa\)</li>
    <li>\(Cob = 2,50 \, cm\)</li>
    <li>\(b_w = 9,0 \, cm\)</li>
    <li>\(b_2 = 31,0 \, cm\)</li>
</ol>

<p align = "center"><b>Figura 1.</b> Bla bla bla </p>
<center><img src="assets\images\aula_011\fig_01.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 2.</b> Bla bla bla </p>
<center><img src="assets\images\aula_011\fig_02.png" width="80%"></center>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[b_1 \leq 
                \begin{cases} 
                    0,1 \cdot a \\ 
                    0,5 \cdot b_2 
                \end{cases}\]</td>
    </tr>
    <tr>
        <td>\[b_3 \leq 
                \begin{cases} 
                    0,1 \cdot a \\ 
                    b_4 
                \end{cases}\]</td>
    </tr>
</table>

<p align = "justify"> Temos \(a = 1 \cdot 1 = 1 \cdot 4 \, m \, = 4,0 \, m\) e \(b_2 = 31 \, cm\). Portanto:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[b_1 \leq 
                \begin{cases} 
                    0,1 \cdot 4 = 0,4 \, m \\ 
                    0,5 \cdot 0,31 = 0,155 \, m 
                \end{cases}\]</td>
    </tr>
</table>

<p align = "justify">Logo, \(b_1 = 0,155 \, m\).</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[b_f = b_w + 2 \cdot b_1 = 0,09 + 2 \cdot 0,155 = 0,40 \, m\]</td>
    </tr>
</table>

<p align = "justify">Repartição do esforço por nervura:</p>
<br><br>
Como toda laje pré fabricada é LA1d</p>

<p align = "justify">Como vão ser os esforços máximos:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[M_{max}' = \frac{P_{sd} \cdot l^2}{8} \rightarrow P_{sd} = (2,0 + 2,0) \cdot 1,40 = 5,60 \, kN/m²\]</td>
    </tr>
</table>

<p align = "justify">Como é nervurada, tudo deverá ser por nervura:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[M_{max} = b_f \cdot M_{max}' \rightarrow M_{max} = 0,40 \cdot 5,60 \cdot \frac{4,15^2}{8} = 4,82 \, kNm/nerv\]</td>