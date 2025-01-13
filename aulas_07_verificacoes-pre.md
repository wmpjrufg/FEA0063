---
title: Verificações preliminares
layout: default
parent: Aulas
nav_order: 6
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->



<h1>Verificaçoes preliminares do Sistema Estrutural</h1><br>

<p align = "justify">Antes de começar o detalhamento de uma estrutura é essencial que o projetista já tenha uma planta de fôrma pré-executiva para que na fase final do projeto não sejam necessárias grandes modificações.</p>
<ul>
  <li>Verificações de cisalhamento;
  <li>Verificações de flecha;
  <li>Verificações de estabilidade.
</ul>

<br>

<h2>Verificação de cisalhamento para lajes sem armaduras</h2>

<p align = "justify">Para \(V_{sd} \leq V_{Rd1}\):</p> 
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[V_{Rd1} = \left[ \tau_{Rd} \cdot k \cdot (1,2 + 40 \cdot \rho_{1}) + 0,15 \cdot \sigma_{cp} \right] \cdot b_{w} \cdot d\]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<br>

<h2>Verificação de Flexa</h2>

<p align = "justify">Para \(M_{a} \leq M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[I_{eq} = I_{c}\]</td>
    <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
  </tr>
</table>

<p align = "justify">Para \(M_{a} > M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[I_{eq} = 0,30 \cdot I_{c}\]</td>
    <td style="width:10%"><p align = "right" id = "eq3">(3)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Para \(M_{a} > M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[a_{(t=\infty)} = a_{(t=0)} \cdot (1 + \alpha_{f})\]</td>
    <td style="width:10%"><p align = "right" id = "eq4">(4)</p></td>
  </tr>
</table>

<br>

<h2>Verificação de Estabilidade Global</h2>

<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_1.png" width="100%"></center>

<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_2.png" width="100%"></center>

<br>

<h3>Parâmetro alfa</h3>

<p align  = "justify">O termômetro da análise de 2º ordem</p>

<br>

<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_3.png" width="100%"></center>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[E \cdot I_{eq} = \frac{p \cdot H^4}{8 \cdot a_k} \] </td>
    <td style="width:10%"><p align = "right" id = "eq5">(5)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[\alpha = H_{tot} \cdot \sqrt{\frac{N_{k}}{E_{CS} \cdot I_c}}\]</td>
    <td style="width:10%"><p align = "right" id = "eq6">(6)</p></td>
  </tr>
</table>

<br>

<h3>Coeficiente \(\gamma_Z\)</h3>

<p align = "justify">Quantifica os esforços de 2º ordem que ocorrem na estrutura
</p>


<br>

<h2>Limitações de Deslocamento</h2>


<p id="fig4"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> [colocar]
<br><br><br>

<p id="fig5"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> [colocar]
<br><br><br>