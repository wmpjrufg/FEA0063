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
<img src="" width="600" height="600">
<br>
<br>
<p>
    Estabelecer a altura das lajes: livro Prof Rebello
    <br>
    Exemplo 1: Solução Lajes maciças!
</p>





