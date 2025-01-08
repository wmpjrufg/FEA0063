<!-- ![image](https://github.com/user-attachments/assets/505e1604-6de5-4285-a64f-2ec9312cba74)---
title: aula 001 - bla bla
parent: Aulas
layout: home
nav_order: 1
--- -->

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

<p>-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>

<h1> Materiais para o concreto armado (02)</h1>
<h2>Materias que compõem o concreto armado</h2>


<br><br><br><br>
<p>------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>
<h1>11 Introdução à segurança estrututural</h1>
<br><br>

<p>Conceitualmente, segurança estrutural pode ser dada como a distância entre uma situação de ruína e uma situação de uso, sendo que ao longo da vida útil dessa estrutura a segurança permitirá a ela suportar as ações mais desfavoráveis que podem vir a ocorrer.</p>
<br>
<table style = "width:100%" align = "center">
    <tr align = "left">
        <td style="width: 100%;">
		<ul>
			<li>Incerteza intrínseca (Natural)</li>
			<li>Incerteza epistêmica</li>
		</ul>
	</td>
    </tr>
</table>
<br><br>

<ol type="a">
	<li><p align="justify">Métodos Clássicos ou Método das Tensões Admissíveis; \[𝜎_𝑟=𝜎_𝑙𝑖𝑚/𝛾\] para 𝛾 ≥ 1 </p></li>
	<li><p align="justify">Método dos Estados Limites. <br><br><br><br>
            </p>
            <span style="position: absolute; left: 30%; top: 25%; transform: translate(-50%, -50%); font-size: 50px;">&#8600;</span>
            <p align ="center">
            Método atual empregado nas normativas nacionais e internacionais.
            </p></li>
</ol>
<br><br>
<p align = "right">Basicamente o modelo semi-probablísticos<br>
	implementou a filosofia das combinações<br>
	e dos coeficientes parciais de segurança.<br>
	<br>
	\[𝑔_𝑅 (𝑓_𝑘/𝛾_𝑚 )≥𝑔_𝑆 (𝛾_𝑓.𝑄_𝑘 )\]
</p>
<br>
<p>No caso das normativas brasileiras existem dois tipos de abordagem para consideração dos Estados Limites. A ABNT NBR 8681 “Ações e segurança nas estruturas – Procedimento” [13] define esses dois conceitos, são eles:</p><br>

<ol type="a">
    <li><p align="justify">Estado Limite Último (ELU)</p></li>
    <li><p align="justify">Estado Limite de Serviço (ELS)</p></li>
</ol>
<br><br>
<h2>11.1 Aspectos sobre a resistência</h2>
<br>

<table style = "width:100%" align = "center">
    <tr align = "center">
        <td style="width: 50%;">\[𝑓_𝑑=𝑓_𝑘/𝛾_𝑚\]</td>
	<td style="width: 50%;">\[𝛾_𝑚=𝛾_𝑚1.𝛾_𝑚2.𝛾_𝑚3\]</td>
    </tr>
</table>
<br>
<p>
	𝛾 <sub>𝑚1</sub> leva em conta a variabilidade da resistência efetiva, transformando a resistência característica em um valor extremo de menor probabilidade de ocorrência;<br>
 	𝛾 <sub>𝑚2</sub> considera as diferenças entre a resistência efetiva do material da estrutura e a resistência medida convencionalmente em corpos-de-prova padronizados;<br>
  	𝛾 <sub>𝑚3</sub> considera as incertezas existentes na determinação das solicitações.
</p>
<br>


<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #ddd;">
      <th>Combinações</th>
      <th>Concreto γ<sub>c</sub></th>
      <th>Aço γ<sub>s</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Normais</td>
      <td>1,40</td>
      <td>1,15</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Especiais ou de construção</td>
      <td>1,20</td>
      <td>1,15</td>
    </tr>
    <tr>
      <td>Excepcionais</td>
      <td>1,20</td>
      <td>1,00</td>
    </tr>
  </tbody>
</table>
<p>A mesma norma afirma que para avaliações em Estado Limite de Serviço não necessitam de minoração, portanto, 𝛾<sub>𝑚</sub> = 1,0.</p>
<br>
<h2>11.2 Ações e combinações</h2>
<br>
<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #ddd;">
      <th rowspan ="2">Classe de carregamento</th>
      <th colspan="2">Ação variável principal da combinação</th>
    </tr>
    <tr style="background-color: #ddd;">
      <th >Duração acumulada</th>
      <th>Ordem de grandeza da duração</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Permanente</td>
      <td>Permanente</td>
      <td>Vida útil da construção</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Longa duração</td>
      <td>Longa duração</td>
      <td>Mais de 6 meses</td>
    </tr>
    <tr>
      <td>Média duração</td>
      <td>Média duração</td>
      <td>1 semana a 6 meses</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Curta duração</td>
      <td>Curta duração</td>
      <td>Menos de 1 semana</td>
    </tr>
    <tr>
      <td>Duração instantânea</td>
      <td>Duração instantânea</td>
      <td>Muito curta</td>
    </tr>
  </tbody>
</table>
<br>

<table style = "width:100%" align = "center">
    <tr align = "center">
        <td style="width: 70%;">\[𝑝_𝑚𝑎𝑥=𝑚𝑎𝑥{█(&𝛾_𝑔.𝑔_𝑘+𝛾_𝑞1.𝑞_(1,𝑘)+〖𝜓_0𝑞2.𝛾_𝑞2.𝑞〗_(2,𝑘)@&𝛾_𝑔.𝑔_𝑘+𝛾_𝑞2.𝑞_(2,𝑘)+〖𝜓_0𝑞1.𝛾_𝑞1.𝑞〗_(1,𝑘) )┤\]</td>
	<td style="width: 30%;"><p>Regra de Turkstra</p></td>
    </tr>
</table>
<br>



<table style = "text-align:center;" border="1" cellpadding="5" cellspacing="0" align = "center">
  <thead>
    <tr style="background-color: #ddd;">
      <th rowspan="3">Combinações de ações</th>
      <th colspan = "8"> ações</th>
    </tr>
       <tr style="background-color: #ddd;">
      <th colspan="2">Permanentes (g)</th>
      <th colspan="2">Variáveis (q)</th>
      <th colspan="2">Protensão (p)</th>
      <th colspan="2">Recalques de apoio e retração</th>
    </tr>
    <tr style="background-color: #ddd;">
      <th>D<sup>1</sup></th>
      <th>F<sup>1</sup></th>
      <th>G<sup>1</sup></th>
      <th>T<sup>1</sup></th>
      <th>D<sup>1</sup></th>
      <th>F<sup>1</sup></th>
      <th>D<sup>1</sup></th>
      <th>F<sup>1</sup></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Normais</td>
      <td>1,4<sup>2</sup></td>
      <td>1,0</td>
      <td>1,4</td>
      <td>1,2</td>
      <td>1,2</td>
      <td>0,9</td>
      <td>1,2</td>
      <td>0</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Especiais ou de construção</td>
      <td>1,3</td>
      <td>1,0</td>
      <td>1,2</td>
      <td>1,0</td>
      <td>1,2</td>
      <td>0,9</td>
      <td>1,2</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Excepcionais</td>
      <td>1,2</td>
      <td>1,0</td>
      <td>1,0</td>
      <td>0</td>
      <td>1,2</td>
      <td>0,9</td>
      <td>1,2</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>
	D é desfavoravel, F é favoravel, G representa as cargas variáveis em geral e T a temperatura.<br>
 	Para as cargas permanentes de pequenas variabilidade, coo o peso próprio das estruturas, especialmente as pré-moldadas, esse coeficiente pode ser reduzido para 1,3.
</p>
<br>

<table style = "text-align:center" border="1" cellpadding="5" cellspacing="0" align ="center">
  <thead>
    <tr style="background-color: #ddd;">
      <th colspan = "2" rowspan ="2">Ações</th>
      <th colspan="3">γ<sub>f2</sub></th>
    </tr>
    <tr style="background-color: #ddd;">
      <th>ψ<sub>0</sub></th>
      <th>ψ<sub>1</sub></th>
      <th>ψ<sub>2</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">Cargas acidentais de edifícios</td>
      <td>Locais em que não há predominância de pesos de equipamentos que permanecem fixos por longos períodos de tempo, nem de elevadas concentrações de pessoas<sup>2</sup></td>
      <td>0,5</td>
      <td>0,4</td>
      <td>0,3</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Locais em que há predominância de pesos de equipamentos que permanecem fixos por longos períodos de tempo, ou de elevada concentração de pessoas<sup>3</sup></td>
      <td>0,7</td>
      <td>0,6</td>
      <td>0,4</td>
    </tr>
    <tr>
      <td>Biblioteca, arquivos, oficinas e garagens</td>
      <td>0,8</td>
      <td>0,7</td>
      <td>0,6</td>
    </tr>
    <tr style="background-color: #eee;">
      <td>Vento</td>
      <td>Pressão dinâmica do vento nas estruturas em geral</td>
      <td>0,6</td>
      <td>0,3</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Temperatura</td>
      <td>Variações uniformes de temperatura em relação à média anual local</td>
      <td>0,6</td>
      <td>0,5</td>
      <td>0,3</td>
    </tr>
  </tbody>
</table>
<p>
	<sup>1</sup>Para valores de ψ<sub>1</sub> relativos às pontes e principalmente aos problemas de fadiga, ver seção 23 (NBR6118).<br>
	<sup>2</sup>Edifícios residenciais.<br>
	<sup>3</sup>Edifícios comerciais, de escritotio, estações e edifícios públicos
</p>
<br>

<ol type="a">
	<li><p align="justify">γ<sub>f2</sub> = 1,00 (combinações raras) </p></li>
	<li><p align="justify">γ<sub>f2</sub> = ψ<sub>1</sub> (Combinações frequentes);</p></li>
	<li><p align="justify">γ<sub>f2</sub> = ψ<sub>2</sub> (Combinações quase permanentes)</p></li>
</ol>
<br>

<h2>11.3 Coeficientes adicionais</h2>
<br>
<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr style="background-color: #ddd;">
      <th>Dimensão<sup>1,3</sup></th>
      <th>19</th>
      <th>18</th>
      <th>17</th>
      <th>16</th>
      <th>15</th>
      <th>14</th>
      <th>13</th>
      <th>12</th>
      <th>11</th>
      <th>10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>γ<sub>n</sub><sup>2</sup></td>
      <td>1,00</td>
      <td>1,05</td>
      <td>1,10</td>
      <td>1,15</td>
      <td>1,20</td>
      <td>1,25</td>
      <td>1,30</td>
      <td>1,35</td>
      <td>1,40</td>
      <td>1,45</td>
    </tr>
  </tbody>
</table>
<br>

<table style = "width:100%" align = "center">
    <tr align = "center">
        <td style="width: 80%;"><p>𝛾<sub>𝑛</sub> = 1,95−0,05.𝑏</p></td>
	<td style="width: 20%;"><p>Pilar</p></td>
    </tr>
     <tr align = "center">
        <td style="width: 80%;"><p>𝛾<sub>𝑛</sub> = 1,95−0,05.h</p></td>
	<td style="width: 20%;"><p>Laje</p></td>
     </tr>
</table>
<br>

<table style = "width:100%" align = "center">
    <tr align = "center">
        <td style="width: 80%;"><p>\[├ 𝐹_𝑑=〖𝛾_𝑔.𝐹〗_(𝑔,𝑘)+〖𝛾_𝜀𝑔.𝐹〗_(𝜀𝑔,𝑘)+〖𝛾_𝑞.(𝐹┤〗_(1𝑞,𝑘)+∑1_(𝑗=2)^𝑛▒〖𝜓_(0,𝑗) 𝐹_(𝑞𝑗,𝑘) 〗)+〖𝛾_𝜀𝑔.𝜓_(0,𝑗).𝐹〗_(𝜀𝑞,𝑘)\]</p></td>
	<td style="width: 20%;"><p>Combinação Última Normal</p></td>
    </tr>
     <tr align = "center">
        <td style="width: 80%;"><p>\[ 𝐹_(𝑑,𝑠𝑒𝑟)=∑1_(𝑖=1)^𝑚▒〖𝐹_(𝑔𝑖,𝑘)+∑1_(𝑗=1)^𝑛▒〖𝜓_2𝑗.𝐹_(𝑞𝑗,𝑘) 〗〗\]</p></td>
	<td style="width: 20%;"><p>Combinação Quase Permanente</p></td>
     </tr>
</table>
<br>
<p>--------------------------------------------------------------------------------------------------------Estádios I E II---------------------------------------------------------------------------------------------------------------------------------------------------------</p>
<h1>Estádios I E II</h1>
<br><br>
<br><br>
<p>Elementos lineares de concreto armado, conforme a NBR 6118, são dimensionados considerando flexão normal simples, uma vez que o plano do momento fletor está em um dos eixos principais da seção transversal e acompanha as ações de força cortante. No entanto, esta mesma norma estabelece que o dimensionamento de peças submetidas a flexão normal simples deve ser feito de maneira separada (dimensionamento devido ao momento fletor e dimensionamento devido à força cortante).</p>
<br><br>
<h4 align = "center">Estádios</h4>
<br>
<table border="1" cellpadding="5" cellspacing="0" align = "center">
  <thead>
    <tr style="background-color: #ddd;">
      <th>
      	<ol type = "a" style = "text-align:left">
		<li>Estádio I: Esse estágio inicial de linearidade na resposta experimental</li>
		<li>Estádio II: Uma certa redução da inclinação da curva marcando o início do trecho de não linearidade</li>
		<li>Estádio III: Plastificação da armadura e/ou plastificação do concreto.</li>
	</ol>
      </th>
    </tr>
  </thead>
</table>
<br>
<p>
	Para o Estádio I são válidas algumas hipóteses, são elas: <br>
	A região de concreto tracionado, abaixo da linha neutra (h – x), está íntegra (não há fissuras) devido à pequena intensidade das tensões normais de tração, as quais são menores que a tensão resistente do concreto (fct); <br>
	As tensões na região comprimida são proporcionais às deformações, correspondendo ao trecho linear elástico do diagrama tensão-deformação do concreto; <br>
	O diagrama de tensão normal ao longo da seção é linear (Ia) – exceto quando o concreto está na iminência da ruptura devido à tração (Ib), em que se tem um diagrama plastificado na região de tração do concreto (Ver Figura 1.8). <br>

</p>
<br><br>
<p>
	No Estádio II ocorre um aumento da intensidade do momento fletor solicitante, o que produz uma tensão de tração na maioria dos pontos abaixo da Linha Neutra (L.N.) que supera a tensão resistente do concreto à tração, o que resulta nos seguintes comportamentos:<br>
	O momento fletor solicitante supera o momento de fissuração, o que provoca o aparecimento das fissuras na região de concreto tracionado, abaixo da linha neutra (h – x). Devido a esse fato, considera-se que apenas o aço resiste aos esforços de tração (despreza- 
        se o concreto tracionado); <br>
	<br>
	Admite-se que a tensão de compressão no concreto continue linear; <br>
	<br>
	As fissuras de tração na flexão do concreto são visíveis.

</p>
<br>
<table border="0" cellpadding="5" cellspacing="0" align = "center">
  <thead>
    <tr style="background-color: #ddd;">
      <th rowspan = "3">\[𝑥_𝐼𝐼=(𝑎_2±√(〖𝑎_2〗^2−4.𝑎_1.𝑎_3 ))/(2.𝑎_1 )\]</th>
      <th>𝑎<sub>1</sub> =𝑏<sub>𝑤</sub>/12</th>
    </tr>
    <tr style="background-color: #ddd;">
      
      <th>\[𝑎_2=ℎ_𝑓.(𝑏_𝑓  − 𝑏_𝑤 )+(𝛼_𝑒  − 1).𝐴_𝑠^′+𝛼_𝑒.𝐴_𝑠\]</th>
    </tr>
    <tr style="background-color: #ddd;">
    
      <th>\[𝑎_3=−𝑑^′.(𝛼_𝑒  − 1).𝐴_𝑠^′−𝑑.𝛼_𝑒.𝐴_𝑠−〖ℎ_𝑓〗^2/2.(𝑏_𝑓  − 𝑏_𝑤 )\]</th>
    </tr>
  </thead>
</table>
<br>
<p>
	Para X <sub>11</sub> ≤ h <sub>f</sub><br><br>
 	\[𝐼_𝐼𝐼=(𝑏_𝑓.〖𝑥_𝐼𝐼〗^3)/3+𝛼_𝑒.𝐴_𝑠.(𝑥_𝐼𝐼−𝑑)^2+(𝛼_𝑒−1).𝐴_𝑠^′.(𝑥_𝐼𝐼−𝑑^′ )^2\] <br><br><br>
  	Para X <sub>11</sub> > h <sub>f</sub><br><br>
 	\[𝐼_𝐼𝐼=((𝑏_𝑓−𝑏_𝑤 ).〖ℎ_𝑓〗^3)/12+(𝑏_𝑤.〖𝑥_𝐼𝐼〗^3)/3+(𝑏_𝑓−𝑏_𝑤 ).(𝑥_𝐼𝐼−ℎ_𝑓/2)^2+𝛼_𝑒.𝐴_𝑠.(𝑥_𝐼𝐼−𝑑)^2+(𝛼_𝑒−1).𝐴_𝑠^′.(𝑥_𝐼𝐼−𝑑^′ )^2\] <br>
</p>
<br><br>
<p>
	Nas avaliações de flecha e fissuração por exemplo é necessária a consideração do efeito da fissuração sobre as propriedades geométricas da peça visto que na peça existem trechos fissurados e outros não fissurados. Para isso avaliamos a inércia média da peça proposto por Branson e descrito em Carvalho e Figueiredo Filho.<br><br>
 	\[𝐼_𝑚=(𝑀_𝑟/𝑀_𝑎 )^𝑛.𝐼_𝑐+[1−(𝑀_𝑟/𝑀_𝑎 )^𝑛 ].𝐼_𝐼𝐼\]
	
</p>
<br><br>
<p>--------------------------------------------------------------------------------------------------------------Estádio III e domínios de deformação-----------------------------------------------------------------------------------------------------------------------------------------------------------</p>
<br>
<h1>28 Estádio III e domínios de deformação</h1>
<br><br>
<ol type = "a"> 
	<li>Devido ao aumento do momento fletor, a fissuração da peça na região tracionada, abaixo da linha neutra (ℎ – 𝑥), aumenta consideravelmente. Portanto, assim como no Estádio II – em que ocorrem as primeiras fissuras no concreto tracionado, a resistência a tração do concreto é desprezada, considerando-se que apenas o aço resiste aos esforços de tração;</li>
	<li>A fibra mais comprimida do concreto começa a plastificar a partir da deformação específica de 𝜀_𝑐2=0,20% (grupo II equação 1.15 volume I), chegando a atingir, sem aumento de tensão, a deformação específica de 𝜀_𝑐𝑢=0,35% para concretos do grupo I e para concretos do grupo II essa deformação é calculada conforme equação 1.16 volume I;</li>
	<li>O diagrama de tensões tende a ficar vertical (uniforme), com quase todas as fibras trabalhando com sua tensão máxima de compressão, ou seja, praticamente todas as fibras atingiram deformações superiores a 𝜀_𝑐2=0,20% e chegando até 𝜀_𝑐𝑢=0,35% (ver valores para grupo II do concreto cap. 1 Volume I);</li>
	<li>A peça está bastante fissurada, com as fissuras se aproximando da linha neutra, fazendo com que sua profundida diminua e, consequentemente, a região comprimida de concreto também.</li>
</ol>
<br>
<p>
	Diferentemente dos Estádios I e II – em que são verificados os ELS, no Estádio III tem-se o dimensionamento da peça de concreto armado no Estado Limite Último (ELU), ou seja, na iminência da ruptura.
	<br>
	Diante disso, tem-se que no Estádio III existem ao todo cinco incógnitas (𝐴_𝑠, 𝐴_𝑠^′, 𝜎_𝑠, 𝜎_𝑠^′ e 𝑥_𝐼𝐼𝐼) 
	<br>
	Estática tem-se apenas duas equações: somatório das forças é igual a zero e somatório dos momentos internos é igual ao momento solicitante externo. 
	<br>
	É necessário recorrer às relações entre as deformações da seção transversal para se conseguir mais três novas equações. Essa etapa será chamada de determinação dos domínios de deformação.
</p>
<br><br>
<h2 align = "center">28.1 HIPÓTESES BÁSICAS PARA CÁLCULO</h2>
<br><br>
<p>
	as seções transversais se mantêm planas após a deformação; \[𝑥/𝑑=𝜀_𝑐/(𝜀_𝑐+𝜀_𝑠 )\]
	<br>
	a deformação das barras passivas aderentes ou o acréscimo de deformação das barras ativas aderentes em tração ou compressão deve ser a(o) mesma(o) do concreto em seu entorno;
	<br>
	as tensões de tração no concreto, normais à seção transversal, devem ser desprezadas no ELU;
	<br>
	a distribuição de tensões no concreto é feita de acordo com o diagrama parábola-retângulo, definido em 8.2.10.1, com tensão de pico igual a 〖0,85.𝑓〗_𝑐𝑑, com 𝑓_𝑐𝑑 definido em 12.3.3. Esse diagrama pode ser substituído pelo retângulo de profundidade 𝑦=𝜆.𝑥, onde o valor do parâmetro 𝜆 pode ser tomado igual as equações abaixo:
	<br>
	𝜆 = 0,80 para 𝑓<sub>ck</sub> ≤ 50 MPa <br>
	𝜆 = 0,80 - ((𝑓<sub>ck</sub> - 50)/400), para 𝑓<sub>ck</sub> >50 MPa  ≤ 50 MPa
</p>
<br>
<p>A tensão deve ser alterada caso a seção tenha acréscimo ou não de área comprimida.</p><br>
<table style = "width:100%" align="center" border="1" cellpadding="8">
    <tr>
        <td style="width: 100%;">
            <img src="" alt="LISHA NEUTRA (28)" >
        </td>
    </tr>
</table>
<br>
<p>
	𝜎<sub>𝑐𝑑</sub> = 𝛼<sub>𝑐</sub>.𝑓<sub>𝑐𝑑</sub> <-------------------------------------->𝜎<sub>𝑐𝑑</sub> = 0,90.𝛼<sub>𝑐</sub>.𝑓<sub>𝑐𝑑</sub> <br> <br>
 	𝛼<sub>𝑐</sub> = 0,85 para 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br>
  	𝛼<sub>𝑐</sub> = 0,85 . (1 - (𝑓<sub>𝑐k</sub> - 50) / 200) para 50 MPa < 𝑓<sub>𝑐k</sub> ≤ 50 MPa
</p>
<br>
<p>
	No caso da seção transversal da viga/lajes for de apoio ou de ligação com outros elementos estruturais, há ainda outras considerações a serem feitas sobre a capacidade de rotação desses elementos.
</p>
<br>
<p align = "center">
	β<sub>x</sub> = x/d ≤ 0,45 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br>
 	β<sub>x</sub> = x/d ≤ 0,35 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; para 50 MPa < 𝑓<sub>𝑐k</sub> ≤ 50 MPa
</p>
<p>
	x/d ≤ (&#948; - 0,45) / 1,25 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br>
	x/d ≤ (&#948; - 0,56) / 1,25 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; para 50 MPa < 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br><br>
	&#948; ≥ 0,90 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Para estruturas de nós móveis <br>
	&#948; ≥ 0,75 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Para qualquer outro caso
		
</p>
<br><br>
<h2>28.2 SOMÍNIOS DE DOFORMAÇÃO</h2>
<br>
<p>Os conjuntos de deformações específicas do concreto e do aço ao longo de uma seção transversal retangular com armadura simples (só tracionada) submetida a ações normais definem cinco domínios de deformação. Os domínios representam as diversas possibilidades de ruína da seção; a cada par de deformações específicas de cálculo (εs) e (εc) correspondem um esforço normal, se houver, e um momento fletor atuantes na seção. Para verificar esses domínios é apresentada a Figura a seguir com todos os seis intervalos de deformações.
</p>
<br>
<table style = "width:100%" align="center" border="1" cellpadding="8">
    <tr align = "left">
        <td style="width: 50%;"><p>a) Para concretos de classes até C50:</p></td>
	<td style="width: 50%;"><p>b) Para concretos de classes C55 até C90:</p></td>
    </tr>
     <tr align = "left">
        <td style="width: 50%;"><p>εc2 = 2,0 %;</p></td>
	<td style="width: 50%;"><p>εc2 = 2,0 % + 0,085% . (f<sub>ck</sub> - 50)<sup>0,53</sup></p></td>
     </tr>
     <tr align = "left">
        <td style="width: 50%;"><p>εcu = 3,5 %;</p></td>
	<td style="width: 50%;"><p>εc2 = 2,0 % + 35% . [(90 - f<sub>ck</sub> - 50) / 100]<sup>4</sup></p></td>
     </tr>
</table>
<br>
<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>
<br>
<h1>Dimensionamento de seções retangulares - armadura simples</h1>
<br>
<p>Como visto no capítulo anterior o problema da flexão pura no Estádio III envolve uma série de variáveis como determinação das tensões nas armaduras, a própria armadura e a posição da linha neutra. Logo nesse capítulo teremos como objetivo principal a explicação dos artifícios necessários para obtenção da área de aço de uma peça de concreto armado, seja ela uma seção retangular ou seção Tê
</p>
<br>
<p>
	\[𝑏_𝑤.𝑑.𝜆.𝛽_𝑥.𝛼_𝑐.𝑓_𝑐𝑑+𝜎_𝑠𝑐.𝐴_𝑠𝑐=𝜎_𝑠𝑡.𝐴_𝑠𝑡 <br>\]<br><br>
	\[𝑀_𝑠𝑑=𝑏_𝑤.𝑑^2.𝜆.𝛽_𝑥.𝛼_𝑐.𝑓_𝑐𝑑.(1−0,50. 𝜆.𝛽_𝑥 )+ 𝜎_𝑠𝑐.𝐴_𝑠𝑐.(𝑑−𝑑^′ )\] <br><br>
	\[𝜀_𝑐𝑐/𝛽_𝑥 =𝜀_𝑠𝑐/(𝛽_𝑥−𝑑^′/𝑑)=𝜀_𝑠𝑡/(1−𝛽_𝑥 )\]<br><br>
 	β<sub>x</sub> = x/d ≤ 0,45 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br>
 	β<sub>x</sub> = x/d ≤ 0,35 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; para 50 MPa < 𝑓<sub>𝑐k</sub> ≤ 50 MPa

</p>
<br>
<p>Com essa quantidade de equações é possível montar um sistema com 4 equações e 5 incógnitas portanto o problema de flexão acaba sendo um sistema possível, porém indeterminado com infinitas soluções. Logo você como projetista deverá arbitrar uma condição para que seja possível determinar a solução para esse sistema.<br>
No primeiro caso (armadura dupla) estabeleceremos que não conhecemos as armaduras, mas conhecemos a relação 𝛽_𝑥 limitante. Logo se conhecemos 𝛽_𝑥 conhecemos a posição da linha neutra (𝑥_𝐼𝐼𝐼). Para o segundo caso, chamado aqui de armadura simples, não conhecemos a linha neutra e admitimos que a armadura de compressão (𝐴_𝑠𝑐) não se faz necessária. A grande questão é quando estabelecer uma situação ou outra?! <br><br>
Do ponto de vista de comportamento peças estruturais com armadura dupla são empregadas quando é necessária a redução da posição da linha neutra.<br><br>
M<sub>lim</sub> 0,45 . b<sub>w</sub> . 𝜆. d<sup>2</sup>. 𝛼<sub>c</sub>. 𝑓<sub>cd</sub>. (1-0,225. 𝜆) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑓<sub>𝑐k</sub> ≤ 50 MPa <br>
M<sub>lim</sub> 0,35 . b<sub>w</sub> . 𝜆. d<sup>2</sup>. 𝛼<sub>c</sub>. 𝑓<sub>cd</sub>. (1-0,175. 𝜆) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; para 50 MPa < 𝑓<sub>𝑐k</sub> ≤ 50 MPa
</p>
<br>
<p>

\[M_{sd} = b_w \cdot \alpha_c \cdot f_{cd} \cdot \lambda \cdot x \cdot \left( d - 0.50 \cdot \lambda \cdot x \right)\]
<br>
\[x_{III} = \frac{d + \sqrt{d^2 - 2 \cdot \left( \frac{M_{sd}}{b_w \cdot \alpha_c \cdot f_{cd}} \right)}}{\lambda}\]
<br>
\[A_{st} = \frac{M_{sd}}{f_{yd} \cdot \left( d - 0.50 \cdot \lambda \cdot x_{III} \right)}\]

</p>
<br>
<p>-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>

<br>
<h1>Dimensionamento de seções retangulares - armadura dupla</h1>
<br>

<p>
	Nessa análise o momento fletor total de cálculo (Msd) é composto em duas parcelas: O momento M1sd que é igual ao máximo momento absorvido por uma armadura simples (parcela M1d), ou seja, Mlim e a parcela M2sd que é a parcela referente parcela M<sub>2d</sub>.<br><br>
	
A<sub>st</sub> = A<sub>1st</sub> + A<sub>2st</sub> <br>
\[A_{\text{1st}} = \frac{M_{\text{1sd}}}{f_{yd} \cdot \left( d - 0.50 \cdot \lambda \cdot x_{\text{III}} \right)}\] <br><br>
\[A_{\text{2st}} = \frac{M_{\text{2sd}}}{f_{yd} \cdot \left( d - d' \right)}\]<br><br>
\[A_{\text{st}} = \frac{M_{\text{1sd}}}{f_{yd} \cdot \left( d - 0.50 \cdot \lambda \cdot x_{\text{III}} \right)} + \frac{M_{\text{2sd}}}{f_{yd} \cdot \left( d - d' \right)}\]<br><br>
</p>
<br><br>
<p>------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>
<br>
<h1>25 Aspectos sobre qualidade e durabilidade de estruturas de concreto</h1>
<br><br><br><br>

<table style = "text-align:center" border="1" align = "center">
    <tr>
        <th rowspan="2">Tipo de estrutura</th>
        <th colspan="5">Vida Útil de Projeto (VUP) mínima</th>
    </tr>
    <tr>
        <th>BS 7543 (1992)</th>
        <th>ISO 2394 (1998)</th>
        <th>FIB 84 (2006) e EM 206-1 (2007)</th>
        <th>NBR 15575 (2013)</th>
        <th>FIB 58 (2010)</th>
    </tr>
    <tr>
        <td>Temporárias</td>
        <td>&ge; 10 anos</td>
        <td>1 a 5 anos</td>
        <td>&ge; 10 anos</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Partes estruturais substituíveis (Ex.: apoios)</td>
        <td>&ge; 10 anos</td>
        <td>&ge; 25 anos</td>
        <td>10 a 25 anos</td>
        <td>23 a 20 anos</td>
        <td>25 a 30 anos</td>
    </tr>
    <tr>
        <td>Estruturas para agricultura e semelhantes</td>
        <td>-</td>
        <td>-</td>
        <td>15 a 30 anos</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Estruturas offshore</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>&ge; 35 anos</td>
    </tr>
    <tr>
        <td>Edifícios industriais e reformas</td>
        <td>&ge; 30 anos</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Edifícios e outras estruturas comuns</td>
        <td>&ge; 50 anos</td>
        <td>&ge; 50 anos</td>
        <td>&ge; 50 anos</td>
        <td>50 anos</td>
        <td>&ge; 50 anos</td>
    </tr>
    <tr>
        <td>Edifícios novos e reformas de edifícios públicos</td>
        <td>&ge; 60 anos</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Edifícios monumentais, pontes e outras estruturas de engenharia civil</td>
        <td>&ge; 120 anos</td>
        <td>-</td>
        <td>&ge; 100 anos</td>
        <td>-</td>
        <td>&ge; 100 anos</td>
    </tr>
    <tr>
        <td>Edifícios monumentais, pontes e outras estruturas de engenharia civil</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>&ge; 200 anos</td>
    </tr>
</table>
<br><br>
<p>Souza e Ripper [5] afirmam que a durabilidade é afetada por três grandes fatores: (a) Falhas relacionadas a etapas de projeto; (b) Falhas relacionadas a etapas de execução; e (c) Falhas relacionadas a etapa de utilização. Porém a nível de projeto, são eles: </p>
<br>
<ol type = "a">
	<li>Falta de compatibilização de projetos (arquitetônicos, estruturais, hidráulicos, elétricos etc.);</li>
	<li>Má especificação de materiais;</li>
	<li>Detalhamentos incorretos ou insuficientes;</li>
	<li>Erros de dimensionamento;</li>
	<li>Má definição de concepções estruturais, erro de dimensionamento de cargas atuantes etc.</li>
</ol>
<br>
<p>De acordo com a NBR 6118 [3] os mecanismos mais importantes para o envelhecimento de uma estrutura são dados a seguir:</p>
<br><br>
<ol type = "a">
	<li>Mecanismos preponderantes de deterioração relativos ao concreto: </li>
	<li>Mecanismos preponderantes de deterioração relativos à armadura:</li>
	<li>Ações mecânicas, movimentações de origem térmica, impactos, ações cíclicas etc.</li>
</ol>
<br><br> <br>
<table style = "text-align:center" border="1" align = "center">
    <tr>
        <th>Classe de agressividade ambiental</th>
        <th>Agressividade</th>
        <th>Classificação geral do tipo de ambiente para efeito de projeto</th>
        <th>Risco de deterioração da estrutura</th>
    </tr>
    <tr>
        <td>I</td>
        <td>Fraca</td>
        <td>
            Rural<br>
            Submersa
        </td>
        <td>Insignificante</td>
    </tr>
    <tr>
        <td>II</td>
        <td>Moderada</td>
        <td>Urbana<sup>1,2</sup></td>
        <td>Pequeno</td>
    </tr>
    <tr>
        <td>III</td>
        <td>Forte</td>
        <td>
            Marinha<sup>1</sup><br>
            Industrial<sup>1,2</sup>
        </td>
        <td>Grande</td>
    </tr>
    <tr>
        <td>IV</td>
        <td>Muito forte</td>
        <td>
            Industrial<sup>1,3</sup><br>
            Respingo de maré
        </td>
        <td>Elevado</td>
    </tr>
</table>
<br>
<br>
<br>
<p>
	Medeiros et al. [6] e Helene [9] afirmam que a durabilidade um sistema estrutural em concreto dependerá da regra dos 4C, conforme descrito a seguir:
</p>
<br><br>
<ol type = "a">
	<li>Composição ou traço;</li>
	<li>Compactação ou adensamento efetivo do concreto na estrutura;</li>
	<li>Cura efetiva do concreto na estrutura;</li>
	<li>Cobrimento das armaduras.</li>
</ol>
<br><br><br><br>
<table style = "text-align:center" border="1" align = "center">
    <tr>
        <th rowspan="2">Concreto<sup>1</sup></th>
        <th rowspan="2">Tipo<sup>2</sup></th>
        <th colspan="4">Classe de agressividade</th>
    </tr>
    <tr>
        <th>I</th>
        <th>II</th>
        <th>III</th>
        <th>IV</th>
    </tr>
    <tr>
        <td>Relação água/cimento em massa</td>
        <td>CA</td>
        <td>&le; 0,65</td>
        <td>&le; 0,60</td>
        <td>&le; 0,55</td>
        <td>&le; 0,45</td>
    </tr>
    <tr>
        <td>Classe de concreto (ABNT NBR 8953)</td>
        <td>CA</td>
        <td>&ge; C20</td>
        <td>&ge; C25</td>
        <td>&ge; C30</td>
        <td>&ge; C40</td>
    </tr>
    <tr>
        <td>Consumo de cimento Portland por metro cúbico de concreto (kg/m³)</td>
        <td>CA</td>
        <td>&ge; 260</td>
        <td>&ge; 280</td>
        <td>&ge; 320</td>
        <td>&ge; 360</td>
    </tr>
</table>
<br><br><br>

<table style = "text-align:center" aling = "center" border="0">
    <tr>
        <th>Classe</th>
        <th>Abatimento (mm)</th>
        <th>Aplicações típicas</th>
    </tr>
    <tr>
        <td>S10</td>
        <td>10 &le; A &lt; 50</td>
        <td>Concreto extrusado, vibroprensado ou centrifugado</td>
    </tr>
    <tr>
        <td>S50</td>
        <td>50 &le; A &lt; 100</td>
        <td>Alguns tipos de pavimentos e de elementos de fundação</td>
    </tr>
    <tr>
        <td>S100</td>
        <td>100 &le; A &lt; 160</td>
        <td>Elementos estruturais, com lançamento convencional do concreto</td>
    </tr>
    <tr>
        <td>S160</td>
        <td>160 &le; A &lt; 220</td>
        <td>Elementos estruturais com lançamento bombeado do concreto</td>
    </tr>
    <tr>
        <td>S220</td>
        <td>&ge; 220</td>
        <td>Elementos estruturais esbeltos ou com alta densidade de armaduras</td>
    </tr>
</table>
<br><br><br>

<table style = "text-align:center" align = "center" border="1">
  <tr>
    <th>
      c<sub>nom</sub> = c<sub>min</sub> + 𝛥<sub>c</sub>
    </th>
    <th>
      <table style = "text-align:center" align = "center" border="1">
          <tr>
              <th rowspan="2">Tipo de estrutura</th>
              <th rowspan="2">Componente ou elemento</th>
              <th colspan="4">Classe de agressividade ambiental (CAA)</th>
          </tr>
          <tr>
              <th>I</th>
              <th>II</th>
              <th>III</th>
              <th>IV<sup>2</sup></th>
          </tr>
          <tr>
              <td rowspan="3">Concreto armado</td>
              <td>Laje<sup>1</sup></td>
              <td>20</td>
              <td>25</td>
              <td>35</td>
              <td>45</td>
          </tr>
          <tr>
              <td>Viga/Pilar</td>
              <td>25</td>
              <td>30</td>
              <td>40</td>
              <td>50</td>
          </tr>
          <tr>
              <td>Elementos estruturais em contato com solo<sup>3</sup></td>
              <td>-</td>
              <td>30</td>
              <td>40</td>
              <td>50</td>
          </tr>
      </table>
     </th>
  </tr>
</table>
<br><br><br>

<table style = "text-align:center" align = "center" border="0">
	<tr>
    	<th><br>
        	\[𝑓_(𝑐𝑘,𝑒𝑠𝑡)=2.(𝑓_1+𝑓_2+…𝑓_(𝑚−1))/(𝑚−1)−𝑓_𝑚\]<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </th>
        <th rowspan = "3">
   	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </th>
        <th><br>
        	Para 𝑛 (número de amostras) 6 ≤ 𝑛 ≤ 20
        </th>
    </tr>
    <tr>
    	<th><br>
        	\[𝑓_(𝑐𝑘,𝑒𝑠𝑡)=𝑓_𝑐𝑚−1,65 . 𝑆𝑑\]<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </th>
        <th rowspan = "2">
        	Para n ≥ 20:
        </th>
    </tr>
    <tr>
    	<th><br>
        	\[𝑆𝑑= √(1/(𝑛−1) ∑1_(𝑖=1)^𝑛▒(𝑓_𝑖−𝑓_𝑐𝑚 )²)\]<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </th>
    </tr>
</table>
<br><br><br><br><br><br>
<p>---------------------------------------------------------------------------------------Dimensionamento de seções Tê------------------------------------------------------------------------------------------------------------------</p>
<br>
<h1>32 Dimensionamento de seções Tê</h1>
<br>
<body>
   <table style = "text-align:justify" align = "right" border="1" width="400">
    <tr>
        <th>A grande questão no cálculo da seção Tê é a definição desta largura de colaboração da mesa ou aba (𝑏<sub>𝑓</sub>).
        Essa definição de largura colaborante é complexa e depende de uma série de fatores como por exemplo, tipo de carregamento,
        tipo e afastamento entre apoios, rigidez da alma e da laje
</th>    
    </tr>
</table>
<br>
</table>
<br><br><br><br><br><br><br><br>
  <table style = "text-align:justify" align = "center" border="0" width="400">
    <tr>
        <th>NBR 6118 em seu item 14.6.2.2<br><br>
            \[𝑏_(1≤) {█(&0,1.𝑎@&0,5.𝑏_2 )┤\]<br><br>
            \[𝑏_(3≤) {█(&0,1.𝑎@&𝑏_4 )┤\]
</th>    
    </tr>
  </table>
	<table style = "text-align:left">
    <tr>
        <th>
            <ol type="a">
                <li>Viga simplesmente apoiada: 𝑎 = 1,00.𝑙;</li>
                <li>Tramo com momento em uma só extremidade: 𝑎 = 0,75.𝑙;</li>
                <li>Tramo com momentos nas duas extremidades: 𝑎 = 0,60.𝑙;</li>
                <li>Tramo em balanço: 𝑎 = 2,00.𝑙.</li>
            </ol>
        </th>    
    </tr>
</table>
<br><br><br><br>
<br><br><br><br>
<p>
	𝜆 . x ≤ h<sub>f</sub> <br><br>
	𝜆 . x > h<sub>f</sub><br><br><br>
 	M<sub>1sd</sub> = (b<sub>f</sub> - b<sub>w</sub>) . h<sub>f</sub> . 𝑎<sub>c</sub> . f<sub>cd</sub> . (d - 0,5 . h<sub>f</sub>)<br><br>
  	M<sub>2sd</sub> = M<sub>sd</sub> - M<sub>1sd</sub>
</p>
<br><br><br>
<p>
	\[A_{1st} = \frac{M_{1sd}}{f_{yd} \cdot \left( d - 0.5 \cdot h_f \right)}\]<br><br>
	A<sub>st</sub> = A<sub>1st</sub> + A<sub>2st</sub><br><br><br>
	Onde: <br><br>
	A<sub>1st</sub> - Parcela de aço que advém da contribuição da mesa;<br><br>
	A<sub>2st</sub> - Parcela de aço que advém da contribuição da nervura.
</p>




