---
title: Exemplo 1
layout: default
grand_parent: Aulas
parent: Modelo estrutural e esforços
nav_order: 1
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Exemplo 1 - Determinação dos esforços em lajes de concreto</h1>

<p align="justify">Dado a planta de fôrma na figura a seguir determinar os esforços internos, flecha e fazer a verificação de cisalhamento para as lajes do exemplo. Para este exemplo considerar a carga permanente total de 4,05 kN/m² (já levada em consideração do peso próprio da peça [h = 10 cm e d = 8,50 cm]) e de 1,5 kN/m² para carga variável. 
<br><br>
Além destes dados considerar que as lajes (fim residencial) tem a mesma espessura e estão no mesmo nível neste pavimento em particular. As distâncias apresentadas em plantas já são efetivas, considere um fck de 25 MPa (agregado de granito) e retirada de escoras aos 28 dias.
</p>

<p align = "center"><b>Figura 1.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig011.png" width="80%"></center>

<br>

<h2>Solução</h2>

<p align="justify">Vamos determinar os segmentos: </p>

<p align = "center"><b>Figura 2.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig012.png" width="80%"></center>

<br>

<p align="justify">Exemplificando a laje L2:</p>

<p align = "center"><b>Figura 3.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig013.png" width="60%"></center>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[\lambda = \frac{l_y}{l_x} = \frac{4}{3} = 1,33\]</td>
    </tr>
</table>

<p align="justify">Como \(\lambda < 2\): LAZD</p>

<br>

<p align = "center"><b>Figura 4.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig014.png" width="80%"></center>

<br>

<p align="justify">Dado \(\rho = 4,05 \, \text{kN/m²}\) e \(l_x = 3 \, \text{m}\), temos:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[ m = \frac{m \cdot \rho \cdot l_x²}{100} = \frac{4,05 \cdot 3²}{100} = 0,36 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[ m_x = 0,36 \cdot 3,46 = 1,25 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[ m_x' = 0,36 \cdot 7,65 = 2,79 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[ m_y = 0,36 \cdot 1,58 = 0,58 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[ m_y' = 0,36 \cdot 5,75 = 2,10\, kN/m\]</td>
    </tr>
</table>

<p align = "center"><b>Figura 5.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig015.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 6.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig016.png" width="80%"></center>

<br>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[V_{AZ} = \frac{4,05 \cdot 1,30}{3} = 1,76 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[V_{A3} = \frac{4,05 \cdot 2,25}{3} = 3,04 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[V_{A1} = \frac{4,05 \cdot 4,23}{4} = 5,71 \, kN/m\]</td>
    </tr>
</table>

<p align = "center"><b>Figura 7.</b> Bla bla bla </p>
<center><img src="assets\images\aula_06\fig017.png" width="80%"></center>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
  <thead>
    <tr>
      <th></th>
      <th>G</th>
      <th>Q</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>\(R_x'\)</th>
      <td>5,71 </td>
      <td>1,59 </td>
    </tr>
    <tr>
      <th>\(R_y\)</th>
      <td>1,76 </td>
      <td>0,65 </td>
    </tr>
    <tr>
      <th>\(R_y'\)</th>
      <td>3,04 </td>
      <td>1,13 </td>
    </tr>
  </tbody>
</table>

<p align="justify">Valore de cálculo par cisaalhamento:</p>

<table border="0" style="width:100%; border-collapse:collapse; text-align:center;">
    <tr>
        <td>\[V_{x'd} = R_{x'l} = 5,71 \cdot 1,4 + 1,59 \cdot 1,4 = 10,22 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[V_{yd} = R_{yd} = 1,76 \cdot 1,4 + 0,65 \cdot 1,4 = 3,37 \, kN/m\]</td>
    </tr>
    <tr>
        <td>\[V_{y'd} = R_{y'd} = 3,04 \cdot 1,4 + 1,13 \cdot 1,4 = 5,84 \, kN/m\]</td>
    </tr>
</table>