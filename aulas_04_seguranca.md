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
<br>

<p align="justify">Conceitualmente, segurança estrutural pode ser dada como a distância entre uma situação de ruína e uma situação de uso, sendo que ao longo da vida útil dessa estrutura a segurança permitirá a ela suportar as ações mais desfavoráveis que podem vir a ocorrer.</p>

<center><img src="assets\images\aula_04\fig_1.png" width="100%"></center>
<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>

<br>

<ul>
    <li>Incerteza intrínseca (Natural)</li>
    <li>Incerteza epistêmica</li>
</ul>

<br>

<table border="1" cellpadding="5" cellspacing="0" align="center">
  <tbody>
    <tr>
      <td>Métodos Clássicos ou Método das Tensões Admissíveis:</td>
      <td>\(\sigma_r = \sigma_{lim} / \gamma \) para \(\gamma \ge 1 \)</td>
    </tr>
    <tr>
      <td>Método dos Estados Limites</td>
      <td>Método atual empregado nas normativas nacionais e internacionais.</td>
    </tr>
  </tbody>
</table>

<p align = "justify">Basicamente o modelo semi-probablísticosimplementou a filosofia das combinações e dos coeficientes parciais de segurança.</p>

\[
𝑔_𝑅 (𝑓_𝑘/\gamma_𝑚 ) \ge 𝑔_𝑆 (\gamma_𝑓 \cdot 𝑄_𝑘 )
\]

<center><img src="assets\images\aula_04\fig_2.png" width="100%"></center>
<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>

<br>

<p align = "justify">No caso das normativas brasileiras existem dois tipos de abordagem para consideração dos Estados Limites. A ABNT NBR 8681 “Ações e segurança nas estruturas – Procedimento” [13] define esses dois conceitos, são eles:</p>
<ul>
    <li>Estado Limite Último (ELU)</li>
    <li>Estado Limite de Serviço (ELS)</li>
</ul>


<h2>11.1 Aspectos sobre a resistência</h2>

<table border="1" cellpadding="5" cellspacing="0" align="center">
  <tbody>
    <tr>
      <td>\(f_d = f_k / \gamma_m \)</td>
      <td>\(\gamma_m = \gamma_{m1} \cdot \gamma_{m2} \cdot \gamma_{m3} \)</td>
    </tr>
  </tbody>
</table>

<p align="justify">Onde:</p>
<ul>
    <li>\(\gamma_{m1}\) leva em conta a variabilidade da resistência efetiva, transformando a resistência característica em um valor extremo de menor probabilidade de ocorrência;</li>
    <li>\(\gamma_{m2}\) considera as diferenças entre a resistência efetiva do material da estrutura e a resistência medida convencionalmente em corpos-de-prova padronizados;</li>
    <li>\(\gamma_{m3}\) considera as incertezas existentes na determinação das solicitações.</li>
</ul>


<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
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
    <tr>
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

<p align="justify">A mesma norma afirma que para avaliações em Estado Limite de Serviço não necessitam de minoração, portanto, \(\gamma_m = 1,0\).</p>

<h2>11.2 Ações e combinações</h2>

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th rowspan ="2">Classe de carregamento</th>
      <th colspan="2">Ação variável principal da combinação</th>
    </tr>
    <tr>
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
    <tr>
      <td>Longa duração</td>
      <td>Longa duração</td>
      <td>Mais de 6 meses</td>
    </tr>
    <tr>
      <td>Média duração</td>
      <td>Média duração</td>
      <td>1 semana a 6 meses</td>
    </tr>
    <tr>
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

<table border="1" cellpadding="5" cellspacing="0" align="center">
  <tbody>
    <tr>
      <td>\(
        p_{\text{max}} = \max\left\{
        \begin{aligned}
            &\gamma_g \cdot g_k + \gamma_{q_1} \cdot q_{1,k} + \psi_{q_2} \cdot \gamma_{q_2} \cdot q_{2,k}, \\
            &\gamma_g \cdot g_k + \gamma_{q_2} \cdot q_{2,k} + \psi_{q_1} \cdot \gamma_{q_1} \cdot q_{1,k}
        \end{aligned}
        \right\}
        \)</td>
      <td>Regra de Turkstra</td>
    </tr>
  </tbody>
</table>

<center><img src="assets\images\aula_04\fig_3.png" width="100%"></center>
<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>

<table style="text-align: center; border: 1px solid; border-collapse: collapse; width: 100%;" align="center">
  <thead>
    <tr>
      <th rowspan="3" style="border: 1px solid; padding: 5px;">Combinações de ações</th>
      <th colspan="8" style="border: 1px solid; padding: 5px;">Ações</th>
    </tr>
    <tr>
      <th colspan="2" style="border: 1px solid; padding: 5px;">Permanentes (g)</th>
      <th colspan="2" style="border: 1px solid; padding: 5px;">Variáveis (q)</th>
      <th colspan="2" style="border: 1px solid; padding: 5px;">Protensão (p)</th>
      <th colspan="2" style="border: 1px solid; padding: 5px;">Recalques de apoio e retração</th>
    </tr>
    <tr>
      <th style="border: 1px solid; padding: 5px;">D<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">F<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">G<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">T<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">D<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">F<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">D<sup>1</sup></th>
      <th style="border: 1px solid; padding: 5px;">F<sup>1</sup></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid; padding: 5px;">Normais</td>
      <td style="border: 1px solid; padding: 5px;">1,4<sup>2</sup></td>
      <td style="border: 1px solid; padding: 5px;">1,0</td>
      <td style="border: 1px solid; padding: 5px;">1,4</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0,9</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0</td>
    </tr>
    <tr>
      <td style="border: 1px solid; padding: 5px;">Especiais ou de construção</td>
      <td style="border: 1px solid; padding: 5px;">1,3</td>
      <td style="border: 1px solid; padding: 5px;">1,0</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">1,0</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0,9</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0</td>
    </tr>
    <tr>
      <td style="border: 1px solid; padding: 5px;">Excepcionais</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">1,0</td>
      <td style="border: 1px solid; padding: 5px;">1,0</td>
      <td style="border: 1px solid; padding: 5px;">0</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0,9</td>
      <td style="border: 1px solid; padding: 5px;">1,2</td>
      <td style="border: 1px solid; padding: 5px;">0</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="9" style="text-align: left; padding: 10px; border: 1px solid;">
        <p align="justify">¹ D é desfavorável, F é favorável, G representa as cargas variáveis em geral e T a temperatura.</p>
        <p align="justify">² Para as cargas permanentes de pequenas variabilidades, como o peso próprio das estruturas, especialmente as pré-moldadas, esse coeficiente pode ser reduzido para 1,3.</p>
      </td>
    </tr>
  </tfoot>
</table>


<br><br>

<table style = "text-align:center" border="1" cellpadding="5" cellspacing="0" align ="center">
  <thead>
    <tr>
      <th colspan = "2" rowspan ="2">Ações</th>
      <th colspan="3">γ<sub>f2</sub></th>
    </tr>
    <tr>
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
    <tr>
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
    <tr>
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
  <tfoot>
    <tr>
      <td colspan="5" style="text-align: left; padding: 10px;">
        <p align="justify">1 Para valores de ψ<sub>1</sub> relativos às pontes e principalmente aos problemas de fadiga, ver seção 23 (NBR6118).</p>
        <p align="justify">2 Edifícios residenciais.</p>
        <p align="justify">3 Edifícios comerciais, de escritotio, estações e edifícios públicos</p>
      </td>
    </tr>
</table>

<br><br>

<p align="justify">Onde:</p>
<ul>
    <li>\(\gamma_{f2} = 1,00\) (combinações raras)</li>
    <li>\(\gamma_{f2} = \psi_{1}\) (Combinações frequentes);</li>
    <li>\(\gamma_{f2} = \psi_{2}\) (Combinações quase permanentes)</li>
</ul>

<h2>11.3 Coeficientes adicionais</h2>

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
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