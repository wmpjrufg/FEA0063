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
  <li>Verificações de cisalhamento;</li>
  <li>Verificações de flecha;</li>
  <li>Verificações de estabilidade.</li>
</ul>

<h2>Verificação de cisalhamento para lajes sem armaduras</h2>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ V_{sd} \leq V_{Rd1} \]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<p align = "justify">Sendo:</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[V_{Rd1} = \left[ \tau_{Rd} \cdot k \cdot (1,2 + 40 \cdot \rho_{1}) + 0,15 \cdot \sigma_{cp} \right] \cdot b_{w} \cdot d\]</td>
    <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
  </tr>
</table>

<h2>Verificação de Flexa</h2>

<br>

<p align = "justify">Para \(M_{a} \leq M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[I_{eq} = I_{c}\]</td>
    <td style="width:10%"><p align = "right" id = "eq3">(3)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Para \(M_{a} > M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[I_{eq} = 0,30 \cdot I_{c}\]</td>
    <td style="width:10%"><p align = "right" id = "eq4">(4)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Para \(M_{a} > M_{r}\):</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[a_{(t=\infty)} = a_{(t=0)} \cdot (1 + \alpha_{f})\]</td>
    <td style="width:10%"><p align = "right" id = "eq5">(5)</p></td>
  </tr>
</table>

<br>

<h2>Verificação de Estabilidade Global</h2>

<br>

<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_1.png" width="100%"></center>

<br>

<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_2.png" width="100%"></center>

<br>

<h3>Parâmetro alfa</h3>

<br>

<p align  = "justify">O termômetro da análise de 2º ordem</p>

<br>

<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_3.png" width="100%"></center>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[E \cdot I_{eq} = \frac{p \cdot H^4}{8 \cdot a_k} \] </td>
    <td style="width:10%"><p align = "right" id = "eq6">(6)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[\alpha = H_{tot} \cdot \sqrt{\frac{N_{k}}{E_{CS} \cdot I_c}}\]</td>
    <td style="width:10%"><p align = "right" id = "eq7">(7)</p></td>
  </tr>
</table>

<br>

<h3>Coeficiente \(\gamma_Z\)</h3>

<br>

<p align = "justify">Quantifica os esforços de 2º ordem que ocorrem na estrutura
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ \gamma_Z = \frac{1}{1 - \frac{\Delta M_{tot, d}}{M_{1, tot, d}}} \]</td>
    <td style="width:10%"><p align = "right" id = "eq8">(8)</p></td>
  </tr>
</table>

<p align = "justify">Onde:</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ \Delta M_{tot, d} = \sum (F_{V d, i \cdot a_{i}}) \]</td>
  </tr>
  <tr>
    <td style="width:90%">\[M_{1, tot, d} = \sum (F_{H d, i \cdot Z_{i}}) \]</td>
  </tr>
</table>

<br>

<h2>Limitações de Deslocamento</h2>

<br>

<p align = "center"><b>Figura 4.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_4.png" width="100%"></center>

<p align = "center"><b>Figura 5.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_07\fig_5.png" width="80%"></center>

<h2>Verificação de lajes ao cisalhamento</h2>

<br>

<p align="justify">Conforme Carvalho (2014), afirma que as lajes, quando comparadas com vigas, demonstram um comportamento diferente destas no que diz respeito aos esforços cortantes, de modo que, conforme sua configuração, amenize os efeitos ao esforço cortante com auxílio do concreto para resisti-lo, (fazendo emprego de armadura em condições especiais).
<br><br>
Conforme o item 19.4 da NBR 6118 (2014), são estabelecidas as relações que se baseiam na verificação do efeito da força cortante, sendo divididas em laje se armadura para força cortante e laje com armadura para força cortante:
</p>

<h3>Laje sem armadura para força cortante</h3>

<p align="justify">Segundo o item 19.4.1 da NBR 6118 (2014), lajes maciças ou nervuradas podem prescindir de armadura transversal para combater os esforços cortantes, quando a força cortante de cálculo obedecer à expressão:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ V_{sd} \leq V_{Rd1} \]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<p align = "justify">Sendo:</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[V_{Rd1} = \left[ \tau_{Rd} \cdot k \cdot (1,2 + 40 \cdot \rho_{1}) + 0,15 \cdot \sigma_{cp} \right] \cdot b_{w} \cdot d\]</td>
    <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
  </tr>
</table>

<p align="justify">Onde:</p>
<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\(\tau_{Rd} = 0,25 f_{ctd}\) (Tensão resistente de cálculo do concreto ao cisalhamento);</td>
  </tr>
  <tr>
    <td style="width:90%">\(f_{ctd} = \frac{f_{ctk, inf}}{\gamma_c}\), não maior que [0,02], ( \(𝐴_𝑠1\) sendo a área de armadura de tração que se estende até não menos que \(𝑑 + 𝑙_{𝑏,𝑛𝑒c}\) além da seção considerada, com \(𝑙_{𝑏,𝑛𝑒𝑐}\) definido em 9.4.2.5 e na figura 19.1 da NBR 6118:2014);</td>
  </tr>
  <tr>
    <td style="width:90%">\(b_w\) é a largura mínima da seção ao longo da altura útil \(d\);</td>
  </tr>
  <tr>
    <td style="width:90%">\(\rho_{cp} = \frac{N_{Sd}}{A_c}\) (\(N_{Sd}\)) sendo a força longitudinal na seção devida à protensão ou carregamento (a compressão é considerada com sinal positivo);</td>
  </tr>
  <tr>
    <td style="width:90%">\(k\) Coeficiente com os seguntes valores:
    <ul>
        <li>Para elementos menores que 50 % da armadura inferior não chega até o apoio: \(𝑘 = |1|\); </li>
        <li>Para os demais casos, \(𝑘 = |1,6 - d|\), não menor que |1|, com \(𝑑\) em metros;</li>
    </ul>
        </td>
  </tr>
</table>

<br>

<p align = "center"><b>Figura 6.</b> Comprimento de ancoragem necessária.</p>
<center><img src="assets\images\aula_07\fig_6.png" width="100%"></center>

<h3>Laje com armadura para força cortante</h3>

<p align="justify">Conforme é estabelecido na NBR 6118:2014, deve-se aplicar os critérios estabelecidos no item 17.4.2, e mais, conforme especificações do item 19.4.2, a resistência dos estribos pode ser considerada com os valores máximos, sendo permitida a interpolação linear. </p>
<ul>
    <li>250 MPa, para laje com espessura até 15 cm;</li>
    <li>435 MPa \(𝑓_{𝑦𝑤𝑑}\), para lajes com espessura maior que 35 cm.</li>
</ul>   

<br>

<p align = "center"><b>Figura 7.</b> Reações de apoio características (kN/m) das lajes nas vigas de borda.</p>
<center><img src="assets\images\aula_07\fig_7.png" width="80%"></center>

<br>

<p align = "justify">Conforme exemplo extraído do Bastos (2015), para verificação da força cortante, temos as lajes \(L_1\) e \(L_4\).</p>

<h3>Laje \(L_1\)</h3>

<br>

<p align="justify">A laje \(L_1\) apresenta espessura de \(h = 11 cm\), e reação de apoio característica de \(12,41 \text{kN/m}\).
<br><br>
Aplicando na equação <a href="#eq1">(1)</a>, nota-se:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ V_{sd} = \gamma_f \cdot V_k = 1,4 \cdot 12,41 = 17,4 \text{kN/m} \]</td>
  </tr>
</table>

<p align="justify">Através da equação <a href="#eq2">(2)</a>, tem-se:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[V_{Rd1} = \left[ \tau_{Rd} \cdot k \cdot (1,2 + 40 \cdot \rho_{1}) + 0,15 \cdot \sigma_{cp} \right] \cdot b_{w} \cdot d\]</td>
  </tr>
  <tr>
    <td style="width:90%">\[\tau_{Rd} = 0.25 \cdot f_{ctd} = \frac{f_{ctk,inf}}{\gamma_c} = 0.25 \left( \frac{0.7 \cdot 0.3 \sqrt[3]{25^2}}{1.4} \right) = 0.3206 \, \text{MPa} = 0.03206 \, \text{kN/cm}^2\] </td>
  </tr>
</table>

<p align="justify">Fazendo para área de armadura negativa, para laje \(L_1\), o diâmetro da armadura tal como \(\phi=8 cm\) c/8 cm, corresponde à 6,25 cm². Para altura útil da armadura negativa, faz-se \(d=h-2=11-2=9 cm\). \(b_w=100 cm\).
<br><br>
Logo:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ \rho_1 = \frac{A_s}{b_w \cdot d} \leq 0,02 \rightarrow \rho_1 = \frac{A_s1}{b_w \cdot d} = \frac{6,25}{100 \cdot 9} = 0,0069 \leq 0,02 \rightarrow \text{OK!} \] </td>
  </tr>
</table>

<h3>Laje \(L_4\)</h3>

<br>

<p align="justify">A laje \(L_4\) apresenta espessura de \(h=9 cm\), e reação de apoio característica de \(12,78 \text{kN/m}\). Visto que há a consideração do trecho que tem parede apoiada na laje. Aplicando, analogamente, a metodologia utilizada na laje \(L_1\), faz-se:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ V_{sd} = \gamma_f \cdot V_k = 1,4 \cdot 12,78 = 17,9 \text{kN/m} \]</td>
  </tr>
  <tr>
    <td style="width:90%">\[\tau_{Rd} = 0.03206 \, \text{kN/cm}^2\] </td>
  </tr>
</table>

<p align="justify">Fazendo para área de armadura positiva, para laje \(L_4\), o diâmetro da armadura tal como \(\phi=5 cm\) c/9 cm, corresponde à 2,22 cm². Para altura útil da armadura positiva, faz-se \(d=h-2,5=9-2,5=6,5 cm\). \(b_w=100 cm\).
<br><br>
Logo:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ \rho_1 = \frac{A_s}{b_w \cdot d} \leq 0,02 \rightarrow \rho_1 = \frac{A_s1}{b_w \cdot d} = \frac{2,22}{100 \cdot 6,5} = 0,0034 \leq 0,02 \rightarrow \text{OK!} \] </td>
  </tr>
</table>

<br>

<p align = "justify">Se considerarmos 100% da armadura positiva chega até a viga de apoio, tem-se que:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ k = |1,6 - d| = |1,6 - 0,065| = 1,535 > 1 \rightarrow \text{OK!} \] </td>
  </tr>
</table>

<p align = "justify">Então, aplicando na equação <a href="#eq2">(2)</a>:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ V_{Rd1} = \left[ \tau_{Rd} \cdot k \cdot (1,2 + 40 \cdot \rho_{1}) + 0,15 \cdot \sigma_{cp} \right] \cdot b_{w} \cdot d = [0,0326 \cdot 1,535(1,2 + 40 \cdot 0,0034)] \cdot 100 \cdot 6,5 \] </td>
  </tr>
  <tr>
    <td style="width:90%">\[ V_{Rd1} = 42,7 \text{kN/m} \] </td>
  </tr>
</table>

<p align = "justify">Visto que, \(V_{sd} = 17,9 \text{kN/m} < V_{Rd1} = 42,7 \text{kN/m}\) significa que não haverá necessidade de disposição de armadura transversal na laje \(L_4\).</p>


