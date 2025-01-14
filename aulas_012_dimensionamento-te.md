---
title: Dimensionamento seção tê
layout: default
parent: Aulas
nav_order: 10
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Dimensionamento seções tê</h1>

<br>

<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_1.png" width="60%"></center>

<br>

<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_2.png" width="60%"></center>

<br>

<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_3.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 4.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_4.png" width="80%"></center>

<br>

<p align="justify">A grande questão no <strong>cálculo da seção Tê</strong> é a <strong>definição desta largura de colaboração da mesa ou aba \((𝑏_𝑓\))</strong>. Essa definição de largura colaborante é complexa e depende de uma série de fatores como por exemplo, tipo de carregamento, tipo e afastamento entre apoios, rigidez da alma e da laje.
<br><br>
NBBR 6118 em seu item 14.6.2.2: 
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ b_1 \leq 
          \begin{cases} 
                0,1 \cdot a \\ 
                0,5 \cdot b_2
          \end{cases} \]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ b_1 \leq 
          \begin{cases} 
                0,1 \cdot a \\ 
                0,5 \cdot b_4
          \end{cases} \]</td>
    <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
  </tr>
</table>

<ol type = "a">
  <li>Viga simplesmente apoiada: \(𝑎 = 1,00 \cdot 𝑙\);</li>
  <li>Tramo com momento em uma só extremidade: \(𝑎 = 0,75 \cdot 𝑙\);</li>
  <li>Tramo com momentos nas duas extremidades: \(𝑎 = 0,60 \cdot 𝑙\);</li>
  <li>Tramo em balanço: \(𝑎 = 2,00 \cdot 𝑙\).</li>
</ol>

<br>

<p align = "center"><b>Figura 5.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_5.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 6.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_6.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 7.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_7.png" width="80%"></center>

<br>

<table border="0" style="width:100%">
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_012/fig_8.png" alt="Figura 6" width = "80%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig8">\(\lambda \cdot x \leq h_f\)</p>
            </center>
        </td>
    </tr>
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_012/fig_9.png" alt="Figura 7" width = "80%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig9">\(\lambda \cdot x > h_f\)</p>
            </center>
        </td>
    </tr>
</table>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ M_{1sd} = (b_f - b_w) \cdot h_f \cdot \alpha_c \cdot f_{cd} \cdot (d - 0,5 \cdot h_f) \]</td>
    <td style="width:10%"><p align = "right" id = "eq3">(3)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ M_{2sd} = M_{sd} - M_{1sd} \]</td>
    <td style="width:10%"><p align = "right" id = "eq4">(4)</p></td>
  </tr>
</table>

<br>

<p align = "center"><b>Figura 13.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_012\fig_13.png" width="80%"></center>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ A_{1st} = \frac{M_{1sd}}{f_{yd} \cdot (d - 0,5 \cdot h_f)} \]</td>
    <td style="width:10%"><p align = "right" id = "eq5">(5)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ A_{st} = A_{1st} + A_{2st} \]</td>
    <td style="width:10%"><p align = "right" id = "eq6">(6)</p></td>
  </tr>
</table>

<p align="justify">Onde:</p>
<ul>
    <li>\(A_{1st}\): Parcela de aço que advém da contribuição da mesa;</li>
    <li>\(A_{2st}\): Parcela de aço que advém da contribuição da nervura.</li>
</ul>