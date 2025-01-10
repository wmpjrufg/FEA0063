---
title: Carregamentos
layout: default
parent: Aulas
nav_order: 5
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->


<h1>Determinação de Ações na Estrutura</h1>
<br>

<p align = "justify">
  A determinação das ações atuantes para o cálculo de uma estrutura é feita conforma a <b>ABNT NBR 6120</b> atualizada no ano de 2019 que após quase quatro decadas de estagnaação veio trazendo atualizações e algumas modificações.
</p>
<p ali = "justify">
  A seguir elencamos os itens da nbr 6120 que apresentam carregamentos importantes e normalmente empregadosa em projetos de concreto são eles:

  <ol>
    <li><b>Tabela 3 cargas distribuídas alvenaria conforme a NBR 6120:2019</li>
    <li><b>Tabela 4 cargas distribuídas de telhado conforme a NBR 6120:2019</li>
    <li><b>Tabela 5 cargas distribuídas de pisos conforme a NBR 6120:2019</li>
  </ol>
</p>
<br>

<p id="tab1"></p>
<table border="1" >
    <thead>
        <tr>
            <th colspan = "2">Materiais</th>
            <th>γ<sub>ap</sub> (kN/m³)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan ="5">1 Rochas</td>
            <td>Arenito</td>
            <td>21 a 27 (24)</td>
        </tr>
        <tr>
            <td>Basalto, diorito, gabro</td>
            <td>28</td>
        </tr>
        <tr>
            <td>Gnaisse</td>
            <td>30</td>
        </tr>
        <tr>
            <td>Granito, sienito, pórfiro</td>
            <td>27 a 30 (28,5)</td>
        </tr>
        <tr>
            <td>Mármore e Calcário</td>
            <td>28</td>
        </tr>
        <tr>
            <td rowspan ="6">2 Blocos artificiais e pisos</td>
            <td>Blocos de concreto vazados (função estrutural, classes A e B, ABNT NBR 6136)</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos vazados com paredes vazadas (função estrutural, ABNT NBR 15270-1)</td>
            <td>12</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos vazados com paredes maciças (função estrutural, ABNT NBR 15270-1)</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos maciços</td>
            <td>18</td>
        </tr>
        <tr>
            <td>Lajotas cerâmicas</td>
            <td>18</td>
        </tr>
        <tr>
            <td>Porcelanato</td>
            <td>23</td>
        </tr>
        <tr>
            <td rowspan="6">3 Revestimentos e concretos</td>
            <td>Argamassa de cal, cimento e areia</td>
            <td>19</td>
        </tr>
        <tr>
            <td>Argamassa de cal</td>
            <td>12 a 18 (15)</td>
        </tr>
        <tr>
            <td>Argamassa de cimento e areia</td>
            <td>19 a 23 (21)</td>
        </tr>
        <tr>
            <td>Argamassa de gesso</td>
            <td>12 a 18 (15)</td>
        </tr>
        <tr>
            <td>Concreto simples</td>
            <td>24</td>
        </tr>
        <tr>
            <td>Concreto armado</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 1.</b> Tabela para o peso específico dos materiais <a href="#ref2">[2]</a>.</p>
<br>
<br>

<p id="tab2"></p>
<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th colspan = "2">Local</th>
      <th >Carga uniformemente distribuída (kN/m²)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">Áreas Técnicas</td>
      <td>Barrilete</td>
      <td>1,50<sup>1</sup></td>
    </tr>
    <tr>
      <td>Áreas Técnicas em Geral</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Casa de máquinas de elevador de passageiros (vel ≤ 1,00 m/s)</td>
      <td>30,00<sup>2, 3, 4</sup></td>
    </tr>
    <tr>
      <td>Sala de gerador e transformador (sem leiaute)</td>
      <td>10,00</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="7">Edifícios residenciais</td>
      <td>Dormitório</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td>Sala, Copa e Cozinha</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td>Despensa, área de serviço e lavanderia</td>
      <td>2,00</td>
    </tr>
    <tr>
      <td>Academia</td>
      <td>3,00<sup>5</sup></td>
    </tr>
    <tr>
      <td>Salão de festas, salão de jogos</td>
      <td>3,00<sup>5</sup></td>
    </tr>
    <tr>
      <td>Corredores de uso comum</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores dentro de unidades autônomas</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td rowspan="5">Edifícios comerciais</td>
      <td>Salas de uso geral e sanitários</td>
      <td>2,50</td>
    </tr>
    <tr>
      <td>Regiões de arquivos deslizantes</td>
      <td>5,00</td>
    </tr>
    <tr>
      <td><i>Call center</i></td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores de uso comum</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores dentro de unidades autônomas</td>
      <td>2,50</td>
    </tr>
  </tbody>
</table>
<p align = "justify"><b>Tabela 2.</b> Tabela para a carga uniformente distribuída para edterminados locais <a href="#ref2">[2]</a>.</p>
<br>

<h3>Carga para telhado</h3>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[q = 0,50 \cdot \alpha
\\
\alpha = \begin{pmatrix} 
1,00 & \\
2,00 & - 0,50i\\ 
0,50 & 
\end{pmatrix}
para
\begin{pmatrix}
1\% < i \leq 2\% \\
2\% < i < 3\% \\
i \geq 3\%
\end{pmatrix}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq1">(1)</p></td>
  </tr>
</table>
<br>
<br>
<br>

<h3>Tipos de carregamentos</h3>
<p align = "justy">
  As formas que os carregamentos são dispersos em cada elemento estrutural (pilar, viga, laje)varião com o elemento que a carga está atuando.<br>
  <ul>
    <li><b>LAJES</b>:<br>
    Em lajes as cargas normalmente se apresentão de forma distribuída, no caso distribuído em área, sendo a força sobre área, com a unidade (kN/m<sup>2</sup>).</li><br>
    <li><b>VIGAS:<b><br>
    Em vigas a carga se apresenta de forma distribuída semelhante a lajes, porém com uma diferênça, em vigas a carga é lineramente distribuída, sendo a força peso sobre o comprimento da viga com a unidade (kN/m).</li><br>
    <li><b>PILARES:<b><br>
    Já em pilares a carga é considerada de forma pontual atuante no centro do elemento, com a unidade (kN).</li>
  </ul>
</p>
<br>
<br>
<h2>Laje Maciça</h2>

<p  align = "justy">
  Para lajes maciças a carga atuante nas mesmas pode ser cálcula por meio da Equação <a href="#Eq2">2</a> abaixo.
</p>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[G_{pp}^{laje} = h_{laje} \cdot \gamma_c\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq1">(2)</p></td>
  </tr>
</table>
<br>
<h2>Laje Nervurada</h2>

<p align = "justy">
  Para lajes Nervuradas, a carga distribuída em área é obtida via catálogo, normalmente fornecido pelo fabricante das formas utilizadas para a confecção da laje. Como o catálogo fornecido pela empresa <b>atex</b> pelo <a href="https://atex.com.br/pt/wp-content/uploads/2020/10/Formas-Atex-Bidirecionais.pdf" style="color: blue;">LINK</a>
</p>
<br>

<h2>Carga de alvenaria em lajes</h2>

<p align = "justy">
  Para determinatar a carga que a alvenaria exerce sobre uma laje deve ser lavado em conta se a laje é armada em uma ou duas direções, que pode ser facimente descobreto por meio da Equação <a href="#Eq3">3</a>.
</p>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[\lambda = \frac{l_y}{l_x}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq3">(3)</p></td>
  </tr>
</table>
<p align = "justy">
  onde l<sub>x</sub> é a menor dimensão de área da laje;<br>
  l<sub>y</sub> é a maior dimensão de área da laje <br>
  e λ é o fator que dita de a laje é armada em uma ou duas direções
</p>
<br>
<h4>Para λ ≤ 2</h4>

<p align = "justy">
  Para um valor de λ ≤ 2 a carga é dada pela Equação <a href="#Eq4">4</a>.
</p>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[G_{EC}^{alv} = \frac{(a + b) \cdot H_{alv} \cdot e_{alv} \cdot \gamma_{alv}}{l_x \cdot l_y}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq4">(4)</p></td>
  </tr>
</table>
<p align = "justy">
  onde 𝐻<sub>𝑎𝑙𝑣</sub> é a altura da alvenaria;<br>
  𝑒<sub>𝑎𝑙𝑣</sub> é a expessura da alvenaria:<br>
  𝛾<sub>𝑎𝑙𝑣</sub> é O peso específico da alvenaria;<br>
  𝐺<sub>𝐸𝐶</sub><sup>𝑎𝑙𝑣</sup> é a carga
</p>
<br>
<h4>Para λ > 2</h4>

<p align = "justy">
  Para um valor de λ > 2 a carga é dada pelas Equações <a href="#Eq5">5</a> e <a href="#Eq6">6</a>.
</p>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[G_{EC}^{alv} = \frac{(H_{alv} \cdot e_{alv} \cdot l_{alv}) \cdot \gamma_{alv}}{l_x \cdot l_{inf}}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq5">(5)</p></td>
  </tr>
</table>
<p align = "justy">
  onde 𝑙<sub>𝑖𝑛𝑓</sub> é a altura da laje somada com a expessura da alvenaria<br>
</p>
<center><img src="assets\images\aula_05\fig_1.png" width="100%"></center>
<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>
<br><br>
<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[G_{EC}^{alv} = H_{alv} \cdot e_{alv} \cdot \gamma_{alv}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq6">(6)</p></td>
  </tr>
</table>
<center><img src="assets\images\aula_05\fig_2.png" width="100%"></center>
<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>
<br><br><br>

<h2>Carga de Alvenaria em Vigas</h2>

<p align = "justy">
  Para alvenaria sobre uma viga a carga é dada pela Equação <a href="#Eq7">7</a>
</p>

<table border = "0" style = "width: 100%;">
  <tr>
    <td align = "left" style = "width: 90%;">\[G_{EC}^{alv} = (H_{alv} \cdot e_{alv}) \cdot \gamma_{alv}\]</td>
    <td align = "right" style = "width: 10%;"><p id = "eq7">(7)</p></td>
  </tr>
</table>
<br><br><br>
<center><img src="assets\images\aula_05\fig_3.png" width="100%"></center>
<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>