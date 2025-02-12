---
title: Projeto laje nervurada
layout: default
parent: Aulas
nav_order: 11
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

{: .important-title }
> O que é concreto?
>
> Adjetivo para exprimir algo que é sólido ou um **substantivo masculino** que designa uma **mistura de cimento, água, areia e brita em determinadas proporções**, que se coloca em uma **fôrma** para que **endureça** e atinja **“grande resistência”**.

<ol>
  <li>Levantamento dos elementos na laje</li>
  <li>Cálculo da carga permanente e variável da laje</li>
  <li>Determinação das áreas de influência das lajes</li>
  <li>Cálculo do peso próprio das vigas</li>
  <li>Cálculo das cargas totais nas vigas</li>
</ol>

<h2>1. Levantamento dos elementos na laje</h2>  

<p align = "justify">
  Para a determionação das ações atuantes na estrutura, mostra-se necessário consultar os procedimentos apresentados na ABNT NBR 6120. Logo, deve-se fazer um levantamento dos elementos presentes na laje, de forma a obter sua carga total na estrutura. Desta forma, para o presente projeto exemplo, tem-se a presença de contrapiso, impermeabilizante, proteção e o peso devido a própria laje, logo consultando-se a norma citada, tem-se que:
</p>

<p>
  \[\gamma_{cp} = 19 \, \text{kN/m³}\]

  \[\gamma_{prot} = 19 \, \text{kN/m³}\]
  
  \[\gamma_{Laje} = 25 \, \text{kN/m³}\]
</p>


<p align = "justify">
  Já para o impermeabilizante, tem-se que a carga em kN/m² para a espessura de 0,3 cm é de:
</p>

<p>
  \[\gamma_{imp} = 0,08 \, \text{kN/m²}\]
</p>

<h2>2. Cálculo da carga permanente e variável da laje</h2>  

<p align = "justify">
  Em seguida, pode-se calcular a carga superficial devido a cada elemento, considerando-se a espessura que cada um representa na estrutura por meio da equação <a href="#eq1">(1)</a>, que representa a parcela de carga permanente \(g\).
</p>

<table>
  <tr>
    <td align = "left">\[G_{x} = \gamma_{x} \cdot e_{x}\]</td>
    <td><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<p align = "justify">
  Portanto, aplicando-se a equação <a href="#eq1">(1)</a> e aplicando as respectivas espessuras, tem-se que:
</p>

<table>
  <thead align="center">
    <tr>
      <th>Elemento</th>
      <th>\(e \, (cm)\)</th>
      <th>\(\gamma \, (kN/m³)\)</th>
      <th>\(G \, (kN/m²)\)</th>
    </tr>
  </thead>
  <tbody align="center">
    <tr>
      <td>Contrapiso</td>
      <td>0,5</td>
      <td>19</td>
      <td>0,095</td>
    </tr>
    <tr>
      <td>impermeabilizante</td>
      <td>0,3</td>
      <td>-</td>
      <td>0,08</td>
    </tr>
    <tr>
      <td>Proteção</td>
      <td>2,5</td>
      <td>19</td>
      <td>0,475</td>
    </tr>
    <tr>
      <td>Laje</td>
      <td>10</td>
      <td>25</td>
      <td>2,5</td>
    </tr>
    <tr>
      <td><b>Total (g)</b></td>
      <td><b>-</b></td>
      <td><b>-</b></td>
      <td><b>3,15</b></td>
    </tr>
  </tbody>
  </table>

<p align = "justify">
  Já para a parcela de carga variável na laje, foi adotada a carga dada para uma cobertura, logo:
</p>

<p>
  \[q = 1,5 \, \text{kN/m²}\]
</p>

<h2>3. Determinação das áreas de influência das lajes</h2>  

<p align = "justify">
  Nesta etapa, define-se as áreas de influência da laje, visto que o carregamento atuante é transferido para as vigas. Logo, com o auxílio do AutoCAD, pode-se obter as seguintes áreas de influência:
<br>
<img src="https://i.imgur.com/k5k475q.png" alt="A1">
<br>
<img src="https://i.imgur.com/oglZZfH.png" alt="A2 e A3">
</p>

<p>
  \[A1 = 54509,62 \, \text{cm²}\]
  \[A2 = 16875,00 \, \text{cm²}\]
  \[A3 = 16875,00 \, \text{cm²}\]
</p>

<h2>4. Cálculo do peso próprio das vigas</h2>  

<p align = "justify">
  Para o cálculo do peso próprio das vigas, deve-se considerar a área da seção transversal de cada viga, logo calcula-se por meio da equação <a href="#eq2">(2)</a>.
</p>

<table>
  <tr>
    <td align = "left">\[G_{viga} = \gamma_{CA} \cdot A_{viga}\]</td>
    <td><p align = "right" id = "eq2">(2)</p></td>
  </tr>
</table>

<p align = "justify">
  Portanto, aplicando-se a equação <a href="#eq3">(3)</a>, considerando as dimensões de cada viga e \(\gamma_{CA} = 25 \, \text{kN/m³}\), constroi-se a seguinte tabela:
</p>

<table>
  <thead align="center">
    <tr>
      <th>Viga</th>
      <th>\(bw \, (m)\)</th>
      <th>\(h \, (m)\)</th>
      <th>\(A \, (m²)\)</th>
      <th>\(g_{viga} \, (kN/m)\)</th>
    </tr>
  </thead>
  <tbody align="center">
    <tr>
      <td>V1</td>
      <td>0,14</td>
      <td>0,45</td>
      <td>0,063</td>
      <td>1,57</td>
    </tr>
    <tr>
      <td>V2</td>
      <td>0,14</td>
      <td>0,30</td>
      <td>0,042</td>
      <td>1,05</td>
    </tr>
    <tr>
      <td>V3</td>
      <td>0,14</td>
      <td>0,30</td>
      <td>0,042</td>
      <td>1,05</td>
    </tr>
  </tbody>
</table>

<h2>5. Cálculo das cargas totais nas vigas</h2>  

<p align = "justify">
  Com tais resultados em mãos, e com o auxílio da relação apresentada pelas equações <a href="#eq3">(3)</a>, <a href="#eq4">(4)</a>, <a href="#eq5">(5)</a> e <a href="#eq6">(6)</a>, pode-se calcular as cargas totais em cada viga.
</p>

<table>
  <tr>
    <td align = "left">\[P_{g_{Laje}} = g_{Laje} \cdot A_{i}\]</td>
    <td><p align = "right" id = "eq3">(3)</p></td>
  </tr>
  <tr>
    <td align = "left">\[Q_{g_{TOTAL}} = \frac{P_{g_{Laje}}}{l_{i}} + g_{viga}\]</td>
    <td><p align = "right" id = "eq4">(4)</p></td>
  </tr>
  <tr>
    <td align = "left">\[P_{q_{Laje}} = q_{Laje} \cdot A_{i}\]</td>
    <td><p align = "right" id = "eq5">(5)</p></td>
  </tr>
  <tr>
    <td align = "left">\[Q_{q} = \frac{P_{q_{Laje}}}{l_{i}}\]</td>
    <td><p align = "right" id = "eq6">(6)</p></td>
  </tr>
</table>

<table>
  <thead align="center">
    <tr>
      <th>Viga</th>
      <th>\(l_{i} \, (m)\)</th>
      <th>\(Ai \, (m²)\)</th>
      <th>\(g_{viga} \, (kN/m)\)</th>
      <th>\(g_{Laje} \, (kN/m²)\)</th>
      <th>\(q_{Laje} \, (kN/m²)\)</th>
      <th>\(P_{g_{Laje}} \, (kN)\)</th>
      <th>\(P_{q_{Laje}} \, (kN)\)</th>
      <th>\(Q_{g_{TOTAL}} \, (kN/m)\)</th>
      <th>\(Q_{q} \, (kN/m)\)</th>
    </tr>
  </thead>
  <tbody align="center">
    <tr>
      <td>V1</td>
      <td>4,50</td>
      <td>5,45</td>
      <td>1,57</td>
      <td>3,15</td>
      <td>1,50</td>
      <td>17,17</td>
      <td>8,18</td>
      <td>5,39</td>
      <td>1,82</td>
    </tr>
    <tr>
      <td>V2</td>
      <td>1,50</td>
      <td>1,69</td>
      <td>1,05</td>
      <td>3,15</td>
      <td>1,50</td>
      <td>5,32</td>
      <td>2,53</td>
      <td>4,59</td>
      <td>1,69</td>
    </tr>
    <tr>
      <td>V3</td>
      <td>1,50</td>
      <td>1,69</td>
      <td>1,05</td>
      <td>3,15</td>
      <td>1,50</td>
      <td>5,32</td>
      <td>2,53</td>
      <td>4,59</td>
      <td>1,69</td>
    </tr>
  </tbody>
</table>
