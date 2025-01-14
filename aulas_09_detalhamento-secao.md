---
title: Detalhamento seção retangular
layout: default
parent: Aulas
nav_order: 8
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Detalhamento da Seção Transversal</h1>

<br>

<p align = "center"><b>Tabela 1.</b> Bla bla bla </p>
<table>
    <thead>
        <tr>
            <th>Diâmetro (mm)</th>
            <th>Tipo </th>
            <th>Massa Linear (kg/m)</th>
            <th>Área (cm²)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>4,20</td>
            <td>CA 60</td>
            <td>0,109</td>
            <td>0,139</td>
        </tr>
        <tr>
            <td>5,00</td>
            <td>CA 60</td>
            <td>0,154</td>
            <td>0,196</td>
        </tr>
        <tr>
            <td>6,30</td>
            <td>CA 50</td>
            <td>0,245</td>
            <td>0,312</td>
        </tr>
        <tr>
            <td>8,00</td>
            <td>CA 50</td>
            <td>0,395</td>
            <td>0,503</td>
        </tr>
        <tr>
            <td>10,00</td>
            <td>CA 50</td>
            <td>0,617</td>
            <td>0,785</td>
        </tr>
        <tr>
            <td>12,50</td>
            <td>CA 50</td>
            <td>0,963</td>
            <td>1,227</td>
        </tr>
        <tr>
            <td>16,00</td>
            <td>CA 50</td>
            <td>1,578</td>
            <td>2,011</td>
        </tr>
        <tr>
            <td>20,00</td>
            <td>CA 50</td>
            <td>2,466</td>
            <td>3,142</td>
        </tr>
        <tr>
            <td>25,00</td>
            <td>CA 50</td>
            <td>3,853</td>
            <td>4,909</td>
        </tr>
        <tr>
            <td>32,00</td>
            <td>CA 50</td>
            <td>6,313</td>
            <td>8,042</td>
        </tr>
    </tbody>
</table>


<br>

<P align = "justify">Segundo Carvalho e Figueiredo Filho (2014) a <strong>armadura mínima deve ser colocada para evitar rupturas bruscas da seção</strong>, pois o aço faz com que ela apresente uma deformação razoável antes de entrar em ruína, <strong>já os valores máximos decorrem da necessidade de assegurar condições de ductilidade e de respeitar o campo de validade dos ensaios que deram origem as prescrições de funcionamento do conjunto  aço-concreto</strong>.
</p>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ M_{d, min} = 0,80 \cdot W_0 \cdot f_{ctm} \]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ f_{ctk, sup} = 1,30 \cdot f_{ctm}  \]</td>
    <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ f_{ctm} = 0,30 \cdot f_{ck}^{2/3}   \]</td>
    <td style="width:10%"><p align = "right" id = "eq3">(3)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Onde:</p>
<ul>
    <li>\(W_0\) = Módulo de resistência da seção transversal bruta de concreto, relativo à fibra mais tracionada</li>
    <li>\(f_{ctk, sup}\) = Resistência característica superior do concreto à tração</li>
    <li>\(f_{ctm}\) = Resistência característica média do concreto à tração</li>
</ul>

<br>

<p align = "center"><b>Tabela 2.</b> Bla bla bla </p>
<table>
        <caption>Valores de ρmín (As,min/Ac) %</caption>
        <thead>
            <tr>
                <th rowspan="2">Forma da Seção</th>
                <th colspan="11">Valores de ρmín (%)</th>
            </tr>
            <tr>
                <th>20</th>
                <th>25</th>
                <th>30</th>
                <th>35</th>
                <th>40</th>
                <th>45</th>
                <th>50</th>
                <th>55</th>
                <th>60</th>
                <th>65</th>
                <th>70</th>
                <th>75</th>
                <th>80</th>
                <th>85</th>
                <th>90</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Retangular</td>
                <td>0,150</td>
                <td>0,150</td>
                <td>0,150</td>
                <td>0,164</td>
                <td>0,179</td>
                <td>0,194</td>
                <td>0,208</td>
                <td>0,210</td>
                <td>0,219</td>
                <td>0,226</td>
                <td>0,233</td>
                <td>0,239</td>
                <td>0,245</td>
                <td>0,251</td>
                <td>0,256</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="16">
                    Os valores de ρmín estabelecidos nesta tabela pressupoem o uso de aço CA-50, d/h = 0,8 e γ<sub>c</sub> = 1,4 e γ<sub>s</sub> = 1,15. Caso esses fatores sejam diferentes, ρmín deve ser recalculado.
                </td>
            </tr>
        </tfoot>
    </table>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ \rho_{min} = \frac{A_{s, min}}{A_{c}} \]</td>
    <td style="width:10%"><p align = "right" id = "eq4">(4)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Para a armadura máxima o valor respeitado deve ser de no máximo 4% da área de concreto quando somadas todas as armaduras tracionadas e comprimidas da seção, calculada fora da região de emendas.
<br><br>
Segundo Carvalho (2014) as <strong>armaduras de pele</strong> tem função de <strong>mitigar efeitos decorrentes da fissuração, retração e variação da temperatura nas faces de vigas de concreto</strong>, servindo também para controlar melhor a abertura de fissuras em vigas. 
<br><br>
O critério de armadura de pele é aplicado para peças com altura maior ou igual a 60 cm, sendo que a ABNT NBR descreve suas caraterísticas no item 17.3.5.2.3. Sendo a armadura descrita pela equação a seguir:
</p>

<br>

<p align = "center"><b>Figura 1.</b> Bla bla bla </p>
<center><img src="assets\images\aula_09\fig_1.png" width="80%"></center>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ A_{s, face} = 0,10 \% \cdot A_{c, alma} = 0,0010 \% \cdot b_w \cdot h \]</td>
    <td style="width:10%"><p align = "right" id = "eq5">(5)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Segundo ABNT NBR 6118:2014 não é necessário uma armadura superior a 5 cm²/m por face do elemento.
<br><br>
Alguns projetistas recomendam o uso da armadura de pela para alturas superiores a 40 cm, melhorando assim o controle a fissuração. Bastos (2015) cita para altura maiores que 50 cm por exemplo.
<br><br>
O espaçamento disponível pode ser horizontal ou vertical, são dados através das seguintes equações:</p>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ a_h \geq 
                              \begin{cases} 
                              2 \, \text{cm} \\
                              \phi_l \\
                              1,20 \cdot d_{max, agre}
                              \end{cases} \]</td>
    <td style="width:10%"><p align = "right" id = "eq6">(6)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ a_v \geq 
                              \begin{cases} 
                              2 \, \text{cm} \\
                              \phi_l \\
                              0,50 \cdot d_{max, agre}
                              \end{cases} \]</td>
    <td style="width:10%"><p align = "right" id = "eq7">(7)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ b_{\text{disp}} = b_w - 2 \cdot (\text{cob} + \phi_e) \]</td>
    <td style="width:10%"><p align = "right" id = "eq8">(8)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ n_{\text{barras,max}} = \frac{(b_{\text{disp}} + a_h)}{\phi_l + a_h}\]</td>
    <td style="width:10%"><p align = "right" id = "eq9">(9)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ \phi_l = \phi + 0,04 \cdot \phi (\text{barra} + \text{mossa}) \]</td>
    <td style="width:10%"><p align = "right" id = "eq10">(10)</p></td>
  </tr>
</table>

<br>

<p align = "justify">Fusco (1995) recomenda o acréscimo de mossas no cálculo do diâmetro final das barras. Sendo mossa, as saliências da armadura nervurada (CA 50).</p>

<br>

<p align = "center"><b>Tabela 3.</b> Bla bla bla </p> 
<table>
    <thead>
        <tr>
            <th>Tipo de brita</th>
            <th>Diâmetro (mm) </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Brita 0</td>
            <td>4,8 a 9,5</td>
        </tr>
        <tr>
            <td>Brita 1</td>
            <td>9,5 a 19,0</td>
        </tr>
        <tr>
        <td>Brita 2</td>
        <td>19,0 a 25,0</td>
        </tr>
        <tr>
        <td>Brita 3</td>
        <td>25,0 a 38,0</td>
        </tr>
    </tbody>
</table>

<br>

<p align = "center"><b>Figura 2.</b> Espaçamento armaduras –Armadura simples. </p>
<center><img src="assets\images\aula_09\fig_2.png" width="80%"></center>
<p id="fig2"></p>

<br>

<p align = "center"><b>Figura 3.</b> Espaçamento entre feixes de armaduras . </p>
<center><img src="assets\images\aula_09\fig_3.png" width="80%"></center>

<br>

<p align = "justify">Segundo Carvalho (2014) os esforços na armadura só podem ser considerados concentrados no centro de gravidade das barras se a distância deste centro ao ponto de armadura mais afastado da linha neutra(\(𝑎_{𝑡𝑒𝑠𝑡𝑒}\)), medida formalmente a ela, for menor que 10% de h. Já para a armadura concentrada considera-se o cálculo abaixo: </p>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ y_{1\text{º barra}} = \text{cob} + \varphi_e + \frac{\varphi_l}{2} \]</td>
    <td style="width:10%"><p align = "right" id = "eq11">(11)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ y_{\text{cg}} = \frac{\sum A_i \cdot x_i}{\sum A_i} \]</td>
    <td style="width:10%"><p align = "right" id = "eq12">(12)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ d_{\text{real}} > d_{\text{calc}} \]</td>
    <td style="width:10%"><p align = "right" id = "eq13">(13)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ d_{\text{real}} < d_{\text{calc}} \quad \rightarrow \quad \text{recalcular } A_s \]</td>
    <td style="width:10%"><p align = "right" id = "eq14">(14)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ a_{\text{teste}} = y_{\text{cg}} - y^{1\text{ª barra}} \]</td>
    <td style="width:10%"><p align = "right" id = "eq15">(15)</p></td>
  </tr>
  <tr>
    <td style="width:90%">\[ < 10\% \cdot h \quad \rightarrow \quad \text{armadura pode ser concentrada} \]</td>
    <td style="width:10%"><p align = "right" id = "eq16">(16)</p></td>
  </tr>
</table>

<h2>Exemplo 01 - Cálculo de uma seção retangular com armadura simples</h2>

<p align = "justify">Dada uma seção retangular com os dados a seguir, determinar a armadura longitudinal necessária:</p>

\(M_{k,\text{mín}} = -10.000 \, \text{kN.cm}\)
\(\gamma_c = \gamma_r = 1,4 \quad ; \quad \gamma_s = 1,15\)
\(\text{concreto C20} \, (f_{ck} = 20 \, \text{MPa, Grupo I})\)
\(\text{aço CA-50}\)
\(\phi_l = 5 \, \text{mm} \, \text{(diâmetro do estribo)}\)
\(\text{concreto com brita 1 } (d_{\text{máx}} = 19 \, \text{mm}), \, \text{sem brita 2}\)
\(h = 50 \, \text{cm} \quad ; \quad b_w = 20 \, \text{cm}\)
\(d = 47 \, \text{cm} \, \text{(altura útil)} \quad ; \quad c = 2,0 \, \text{cm} \, \text{(cobrimento nominal)}\)
