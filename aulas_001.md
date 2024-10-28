---
title: aula 001 - bla bla
parent: Aulas
layout: home
nav_order: 1
---

<!--Don't delete ths script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete ths script-->

<ol type="a">
    <li><p align="justify">Vigas (elementos lineares): O item 14.4.1.1 da NBR 6118 [4] define viga como um elemento linear em que a flexão é preponderante;</p></li>
    <li><p align="justify">Pilares (elementos lineares): O item 14.4.1.2 da NBR 6118 [4] define pilar como um elemento linear de eixo reto, usualmente dispostos na vertical, em que as forças normais de compressão são preponderantes;</p></li>
    <li><p align="justify">Lajes (elemento de superfície): O item 14.4.2.1 da NBR 6118 [4] define laje como um elemento de superfície plana, sujeitos principalmente a ações normais a seu plano.</p></li>
</ol>

<h2>Vigas</h2>
<p align="justify">
    A seção transversal das vigas não pode apresentar largura inferior a 12 cm e em uma viga parede a largura não deve ser inferior a 15 cm.
    <br><br>
    Estes limites podem ser reduzidos, respeitando-se um mínimo absoluto de 10 cm em casos excepcionais, sendo obrigatoriamente respeitadas as seguintes condições:
</p>

<ol type="a">
    <li><p align="justify">Alojamento das armaduras e suas interferências com as armaduras de outros elementos estruturais, respeitando os espaçamentos e cobrimentos estabelecidos nesta Norma;</p></li>
    <li><p align="justify">Lançamento e vibração do concreto de acordo com a NBR 14931” Execução de estruturas de concreto – procedimento” [17];</p></li>
</ol>


<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[l_{\text{ef}} = l_0 + a_1 + a_2\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(1)</p></td>
    </tr>
</table>
<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ D(t_i) = 1 - \frac{0.2}{t_i} \cdot 0.01 \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(1)</p></td>
    </tr>
</table>
<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[a_1, a_2 \leq \begin{cases}
\frac{t_1}{2}, & \frac{t_2}{2} \\
0, & 30.h\]
\end{cases}</td>

    </tr>
</table>



<h2>Lajes</h2>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=𝑑+𝑐𝑜𝑏+∅_𝑒+∅_𝑙/2\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(3)</p></td>
    </tr>
</table>

<ol type="a">
    <li><p align="justify">7 cm para cobertura não em balanço;</p></li>
    <li><p align="justify">8 cm para lajes de piso não em balanço;</p></li>
    <li><p align="justify">10 cm para lajes em balanço;</p></li>
    <li><p align="justify">10 cm para lajes que suportem veículos de peso total menor ou igual a 30 kN;</p></li>
    <li><p align="justify">12 cm para lajes que suportem veículos de peso total maior que 30 kN;</p></li>
    <li><p align="justify">15 cm para lajes com protensão apoiadas em vigas, com o mínimo de L/42 para lajes de piso biapoiadas e L/50 para lajes de piso contínuas;</p></li>
    <li><p align="justify">16 cm para lajes lisas e 14 cm para lajes-cogumelo, fora do capitel.</p></li>
    <li><p align="justify">A espessura da mesa, quando não existirem tubulações horizontais embutidas, deve ser maior ou igual a 1/15 da distância entre as faces das nervuras (𝑙_0) e não menor que 4 cm; </p></li>
    <li><p align="justify">O valor mínimo absoluto da espessura da mesa deve ser 5 cm, quando existirem tubulações embutidas de diâmetro menor ou igual a 10 mm. Para tubulações com diâmetro 𝛷 maior que 10 mm, a mesa deve ter a espessura mínima de 4 cm + 𝛷 (Diâmetro nominal da tubulação), ou 4 cm + 2.𝛷 no caso de haver cruzamento destas tubulações;</p></li>
    <li><p align="justify">A espessura das nervuras não pode ser inferior a 5 cm; </p></li>
    <li><p align="justify">Nervuras com espessura menores que 8 cm não podem conter armadura de compressão.</p></li>
</ol>


<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=𝑙_𝑒𝑓/12\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(4)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=𝑙_𝑒𝑓/10\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(5)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=𝑙_𝑒𝑓/5\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(6)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=𝑑+𝑐𝑜𝑏+∅_𝑙/2\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(7)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ 𝜆=𝑙_𝑦∕𝑙_𝑥\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(7)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=2%.(𝑙_𝑦+𝑙_𝑥)/2\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(8)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=2%.𝑙_𝑥\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(9)</p></td>
    </tr>
</table>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ ℎ=4%.𝑙_𝑥\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(10)</p></td>
    </tr>
</table>

<h2>Pilares</h2>

<table style = "width:100%">
    <tr>
       
        <td style="width: 90%;">𝑙_𝑒≤{█(&𝑙_0+ℎ@&𝑙)┤</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(11)</p></td>
    </tr>
</table>

<ol type="a">
    <li><p align="justify">0,45.l: Pilar de extremidade ou pilar de canto na direção da menor dimensão do pilar (b);</p></li>
    <li><p align="justify">0,50.l: Pilar de extremidade ou pilar de canto na direção da maior dimensão do pilar (h);</p></li>
    <li><p align="justify">0,50.l: 0,55.l: Complemento dos casos anteriores.</p></li>
</ol>

<div class = "right">
<p align="left">Piso: \[𝑄_𝑡𝑜𝑡 = 10 kN/m² a 12 kN/m²\]</p>
<p align="left">Cobertura: \[𝑄_𝑡𝑜𝑡 = 6 kN/m² a 8 kN/m²\]</p>
</div>


<table style = "width:100%">
    <tr>
        <td style="width: 90%;" align = "right">\[ 𝑁_𝑘^∗=𝑄_𝑡𝑜𝑡.𝐴_𝑖\]</td>
    </tr>
    <tr>
       <td style="width: 90%;" align = "right">\[ 𝑁_𝑘^∗=𝑛_𝑡𝑖𝑝𝑜^ .𝑁_𝑘^𝑡𝑖𝑝𝑜+𝑛_𝑐𝑜𝑏^ .𝑁_𝑘^𝑐𝑜𝑏\]</td> 
    </tr>
     <tr>
       <td style="width: 90%;"  align = "right">\[ 𝑁_𝑑^∗=𝛼.𝑁_𝑘^∗\]</td> 
    </tr>
</table>

<h1>Pré-dimensionamneto de elementos - Exemplos</h1>

<h2>Exemplo 01:</h2>
<p>Considerando a planta de forma apresentada na Figura a seguir determinar as seções transversais de todos os elementos considerando os critérios apresentados no livro de ECA I. Considerar para a esse exemplo que o concreto para a estrutural possui fck de 30 MPa e corresponde ao piso do 2º pavimento de um edifício modelo com um total de 4 pavimentos (Térreo, 1º piso, 2º piso e cobertura). Considere que todos os pavimentos tipo estão carregados com uma carga total de 25 kN/m² (Valor hipotético para esse exercício) e que o pavimento cobertura possui uma carga total de 15 kN/m².
</p>
<br>
<br>
<p>
    Estabelecer a altura das lajes: livro Prof Rebello
    <br>
    Exemplo 1: Solução Lajes maciças!
    <br>
    <br>
    λ -> Vamos utilizar disâncias médias
    <br>
    \[ b_x = b_y = 586 + 7 + 7 = 600m\]
    <br>
    O que resulta em:
    <br>
    \[ λ = 600 / 600 = 1\]
    LA 20
    <br>
    \[ h = 2% . (b_y +b_x)/2 = 2% . (600 + 600)/2 = 2% . 600 \]
    h = 12 cm -> Como á laje maciça b_w = 100cm 
</p>
<p>
    Para a viga VS1 -> Solução viga cont.<br>
    lef de cada vão h = lef / 12 
</p>
<p>
    Tramo 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tramo 2<br>
    h = 600 / 12 = 50 cm &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; h = 500 / 12 ≅ 42 cm 
    <br>
    <br>
    Compatibilizando hviga = 50 cm 
</p>
<br>
<p>
    Divisão por faixa de "responsabilidade" de cada pilar<br>
    Área sombreada 8,29m²
</p>
<br>
<br>
<p>
    \[𝐴_(𝑐,𝑃1)=1347,14/(0,85. 3/1,4+2/100.42)=506,17 〖𝑐𝑚〗^2 > 360 cm^2\]
    <br>
    \[ b_viga = 14 cm\]
    Logo:
    \[ h = 506,17/14 ≅ 36,15 cm\] 
    P1 -> 14 / 40 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; h ≅ 40

</p>

<h1> Materiais para o concreto armado (02)</h1>
<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th>Tipo do agregado</th>
      <th>Faixa de dimensões (mm)</th>
      <th>DMC em mm</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>Brita 0</td>
      <td>4,80 – 9,50</td>
      <td>9,50</td>
    </tr>
    <tr>
      <td>Brita 1</td>
      <td>9,50 – 19,00</td>
      <td>19,00</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Brita 2</td>
      <td>19,00 – 25,00</td>
      <td>25,00</td>
    </tr>
    <tr>
      <td>Brita 3</td>
      <td>25,00 – 50,00</td>
      <td>50,00</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Brita 4</td>
      <td>50,00 – 76,00</td>
      <td>76,00</td>
    </tr>
    <tr>
      <td>Brita 5</td>
      <td>76,00 – 100,00</td>
      <td>100,00</td>
    </tr>
  </tbody>
</table>

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th>Componente químico</th>
      <th>Teores médios (%)</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>CaO</td>
      <td>58 - 67</td>
    </tr>
    <tr>
      <td>SiO<sub>2</sub></td>
      <td>16 - 26</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Al<sub>2</sub>O<sub>3</sub></td>
      <td>4 - 8</td>
    </tr>
    <tr>
      <td>Fe<sub>2</sub>O<sub>3</sub></td>
      <td>1 - 5</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Outros</td>
      <td>0 - 5</td>
    </tr>
  </tbody>
</table>

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th>Componente químico</th>
      <th>Teores médios (%)</th>
      <th>"Responsabilidade"</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>Silicato tricálcico (CaO)<sub>3</sub>SiO<sub>2</sub> = C<sub>3</sub>S</td>
      <td>45 - 75</td>
      <td>É o maior responsável pela resistência em todas as idades, especialmente até o fim do primeiro mês de cura. Também seria o segundo em ordem de importância para o fator tempo de pega.</td>
    </tr>
    <tr>
      <td>Silicato dicálcico (CaO)<sub>2</sub>SiO<sub>2</sub> = C<sub>2</sub>S</td>
      <td>7 - 35</td>
      <td>Adquire maior importância no processo de endurecimento em idades mais avançadas, sendo largamente responsável pelo ganho de resistência a um ano ou mais.</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Aluminato tricálcico (CaO)<sub>3</sub>Al<sub>2</sub>O<sub>3</sub> = C<sub>3</sub>A</td>
      <td>0 - 13</td>
      <td>Contribui na resistência, especialmente no primeiro dia. Esse é o componente mineralógico mais reativo do clínquer ao lado do Silicato tricálcico.</td>
    </tr>
    <tr>
      <td>Ferraluminato tetracálcico (CaO)<sub>4</sub>Al<sub>2</sub>O<sub>3</sub>Fe<sub>2</sub>O<sub>3</sub> = C<sub>4</sub>AF</td>
      <td>0 - 18</td>
      <td>Em nada contribui com a resistência. Tem grandes vazios estruturais e é responsável pela reatividade elevada do composto. Portanto, é bastante responsável pela resistência à corrosão química do concreto. Além disso, é o responsável pela coloração acinzentada do concreto.</td>
    </tr>
  </tbody>
</table>


<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th>Tipo</th>
      <th>Cimento</th>
      <th>Resistência (MPa)</th>
      <th>Sufixo</th>
      <th>Clínquer + Gesso</th>
      <th>Escória siderúrgica</th>
      <th>Material pozolânico</th>
      <th>Material carbonático</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>Comum</td>
      <td>CP I</td>
      <td></td>
      <td></td>
      <td>95 - 100</td>
      <td>0</td>
      <td>0</td>
      <td>0 - 5</td>
    </tr>
    <tr>
      <td>Comum com adição</td>
      <td>CP I - S</td>
      <td></td>
      <td></td>
      <td>90 - 94</td>
      <td>0</td>
      <td>0</td>
      <td>6 - 10</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Composto</td>
      <td>CP II - E</td>
      <td>25, 32 ou 40</td>
      <td>RS<sup>1</sup> ou BC<sup>2</sup></td>
      <td>51 - 94</td>
      <td>6 - 34</td>
      <td>0</td>
      <td>0 - 15</td>
    </tr>
    <tr>
      <td>Composto</td>
      <td>CP II - Z</td>
      <td>25, 32 ou 40</td>
      <td>RS<sup>1</sup> ou BC<sup>2</sup></td>
      <td>71 - 94</td>
      <td>0</td>
      <td>6 - 14</td>
      <td>0</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Composto</td>
      <td>CP II - F</td>
      <td>25, 32 ou 40</td>
      <td>RS<sup>1</sup> ou BC<sup>2</sup></td>
      <td>75 - 89</td>
      <td>0</td>
      <td>0</td>
      <td>11 - 25</td>
    </tr>
    <tr>
      <td>Alto-forno</td>
      <td>CP III</td>
      <td>25, 32 ou 40</td>
      <td></td>
      <td>25 - 65</td>
      <td>35 - 75</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>Pozolânico</td>
      <td>CP IV</td>
      <td>25, 32 ou 40</td>
      <td></td>
      <td>45 - 85</td>
      <td>0</td>
      <td>15 - 50</td>
      <td>0 - 10</td>
    </tr>
  </tbody>
</table>


<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th rowspan="2">Tipo</th>
      <th colspan="4">Ensaios de tração (valores mínimos)</th>
      <th colspan="2">Ensaio de dobramento a 180º</th>
      <th rowspan="2">Aderência</th>
    </tr>
    <tr style="background-color: #333; color: white;">
      <th>(f<sub>yk</sub>) - MPa</th>
      <th>(f<sub>st</sub>) - MPa</th>
      <th>Alongamento após ruptura em 10.φ – A %</th>
      <th>Alongamento total na força máxima – A<sub>gt</sub> %</th>
      <th>Diâmetro do pino (mm)</th>
      <th>Valores mínimos de η para</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>CA-25</td>
      <td>250</td>
      <td>1,20.f<sub>yk</sub></td>
      <td>18</td>
      <td>--</td>
      <td>φ ≥ 20</td>
      <td>φ &lt; 10mm</td>
      <td>1,0</td>
      <td>1,0</td>
    </tr>
    <tr>
      <td>CA-50</td>
      <td>500</td>
      <td>1,08.f<sub>yk</sub></td>
      <td>8</td>
      <td>5</td>
      <td>4.φ</td>
      <td>6.φ</td>
      <td>1,0</td>
      <td>1,5</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>CA-60</td>
      <td>600</td>
      <td>1,05.f<sub>yk</sub></td>
      <td>5</td>
      <td>--</td>
      <td>--</td>
      <td>5.φ</td>
      <td>1,0</td>
      <td>1,5</td>
    </tr>
  </tbody>
</table>

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #333; color: white;">
      <th rowspan="1">Diâmetro Nominal (mm)</th>
      <th colspan="2">Massa e tolerância por unidade de comprimento</th>
      <th colspan="2">Valores Nominais</th>
    </tr>
    <tr style="background-color: #333; color: white;">
        <th>Barras</th>
      <th>Massa Nominal<sup>2</sup> (kg/m)</th>
      <th>Máxima variação permitida para massa nominal</th>
      <th>Área da Seção (mm<sup>2</sup>)</th>
      <th>Perímetro (m)</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #ccc;">
      <td>6,30</td>
      <td>0,245</td>
      <td>± 7%</td>
      <td>31,20</td>
      <td>19,80</td>
    </tr>
    <tr>
      <td>8,00</td>
      <td>0,395</td>
      <td>± 7%</td>
      <td>50,30</td>
      <td>25,10</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>10,00</td>
      <td>0,617</td>
      <td>± 6%</td>
      <td>78,50</td>
      <td>31,40</td>
    </tr>
    <tr>
      <td>12,50</td>
      <td>0,963</td>
      <td>± 6%</td>
      <td>122,70</td>
      <td>39,30</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>16,00</td>
      <td>1,578</td>
      <td>± 5%</td>
      <td>201,10</td>
      <td>50,30</td>
    </tr>
    <tr>
      <td>20,00</td>
      <td>2,466</td>
      <td>± 5%</td>
      <td>314,20</td>
      <td>62,80</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>22,00</td>
      <td>2,984</td>
      <td>± 4%</td>
      <td>380,10</td>
      <td>69,10</td>
    </tr>
    <tr>
      <td>25,00</td>
      <td>3,853</td>
      <td>± 4%</td>
      <td>490,90</td>
      <td>78,50</td>
    </tr>
    <tr style="background-color: #ccc;">
      <td>32,00</td>
      <td>6,313</td>
      <td>± 4%</td>
      <td>804,20</td>
      <td>100,50</td>
    </tr>
    <tr>
      <td>40,00</td>
      <td>9,865</td>
      <td>± 4%</td>
      <td>1256,60</td>
      <td>125,70</td>
    </tr>
  </tbody>
</table>

<h1>Propriedades do concreto estrutural</h1>



<h1>Introdução à segurança estrututural</h1>












