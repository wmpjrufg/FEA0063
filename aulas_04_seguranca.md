---
title: Segurança estrutural
layout: default
parent: Aulas
nav_order: 4
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

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