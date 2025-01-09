---
title: Modelo estrutural e esforços
layout: default
parent: Aulas
nav_order: 6
---

<h2>Introdução a análise estrutural</h2>

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

{: .important-title }
> O que é modelo estrutural?
>
> Trata-se de um protótipo que procura simular um edifício real no computador [1]. A Figura 1 apresenta a prototipagem computacional de um edifício de múltiplos pavimentos.

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig1.png" width = "7100%"></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig1"><b>Figura 1.</b> Edifício real <i>versus</i> edifício simulado.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Alguns exemplos de modelos podem ser estabelecidos, vejamos a <a href="#fig2">Figura 2</a>:
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig2aa.png" width = "75%"></center></td>
    <td><center><img src = "assets/images/aula_06/fig2bb.png" width = "90%"></center></td>
  </tr>
  <tr>
    <td><center><p align = "center">(a) Modelo de viga contínua + lajes por métodos aproximados.</p></center></td>
    <td><center><p align = "center">(b) Pórtico H + Pilares.</p></center></td>
  </tr>
  <tr>
    <td><center><img src = "assets/images/aula_06/fig2cc.png" width = "80%"></center></td>
    <td><center><img src = "assets/images/aula_06/fig2dd.png" width = "90%"></center></td>
  </tr>
  <tr>
    <td><center><p align = "center">(c) Grelha somente de vigas.</p></center></td>
    <td><center><p align = "center">(d) Pórtico espacial ou tridimensional.</p></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig2"><b>Figura 2.</b> Exemplo de modelos estruturais <a href="#ref1">[1]</a>.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Sobre a ótica do tipo de análise estrutural, são duas as perspectivas possíveis para avaliação dos esforços em uma estrutura, são elas: (a) a análise linear; ou (b) a análise não linear. A análise não linear normalmente é dividida em três sub grupos, que incluem no problema complexidades que aproximam o modelo do fenômeno natural que deseja representar. O três sub grupos são divididos:
</p>

<ul>
    <li>Análise não linear com fonte geométrica;</li>
    <li>Análise não linear com fonte de contato;</li>
    <li>Análise não linear com fonte física.</li>
</ul>

<p align = "justify">
  Vejamos o exemplo da análise não linear geométrica na <a href="#fig3">Figura 3</a>:
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig3aa.png" width = "60%"></center></td>
    <td><center><img src = "assets/images/aula_06/fig3bb.png" width = "60%"></center></td>
  </tr>
  <tr>
    <td><center><p align = "center">(a) Estrutura indeformada sobre ação da carga F.</p></center></td>
    <td><center><p align = "center">(b) Estrutura deformada sobre ação da carga F.</p></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig3"><b>Figura 3.</b> Comportamento de uma barra de 1 grau de liberdade (<i>gdl</i>) submetida a uma carga de compressão F.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Agora um exemplo da análise não linear de contato na <a href="#fig4">Figura 4</a>:
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig4aa.png" width = "80%"></center></td>
    <td><center><img src = "assets/images/aula_06/fig4bb.png" width = "75%"></center></td>
  </tr>
  <tr>
    <td><center><p align = "center">(a) Placa rígida aplicada sobre um cilindro de borracha.</p></center></td>
    <td><center><p align = "center">(b) Relação carga versus deslocamento para o problema.</p></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig4"><b>Figura 4.</b> Comportamento não linear das condições de contorno.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Vejamos também um exemplo de análise não linear física na <a href="#fig5">Figura 5</a>:
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig5.png" width = "75%"></center></td>
  </tr>
  <tr>
    <td><center><p align = "justify" id = "fig5"><b>Figura 5.</b> Comportamento não linear físico do concreto devido aop processo de fissuração.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Do ponto de vista do projeto estrutural de edificações usuais de concreto armado temos dois tipos usuais de aplicações: (a) a não linearidade física; e (b) a não linearidade geométrica. Porém aplicaremos essas condições em casos específicos que serão listados aqui. Para isso utilizaremos informações do item <b>14.5.2</b> da <a href="#ref2">ABNT NBR 6118 [2]</a>. Admitiremos em nossas análises o aspecto do cálculo de esforços lineares com as seguintes ponderações:
</p>

<ol>
    <li><p align = "justify">Na análise global, as características geométricas podem ser determinadas pela seção bruta de concreto dos elementos estruturais. Em análises locais para cálculo dos deslocamentos, na eventualidade da fissuração, esta deve ser considerada.</p></li>
    <li><p align = "justify">Os valores para o módulo de elasticidade e o coeficiente de Poisson devem ser adotados de acordo com o apresentado em 8.2.8 e 8.2.9, devendo, em princípio, ser considerado o módulo de elasticidade secante E<sub>cs</sub>.</p></li>
    <li><p align = "justify">Os resultados de uma análise linear são usualmente empregados para a verificação de estados- limites de serviço.</p></li>
    <li><p align = "justify">Os esforços solicitantes decorrentes de uma análise linear podem servir de base para o dimensiona- mento dos elementos estruturais no estado-limite último, mesmo que esse dimensionamento admita a plastificação dos materiais, desde que se garanta uma dutilidade mínima às peças.</p></li>
</ol>

<p align = "justify">
  De forma a considerar a análise não linear física no processo de cálculo vamos empregar os critérios do <i>software</i> TQS conforme descrito na <a href="#fig6">Figura 6</a>.
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig6.png" width = "100%"></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig6"><b>Figura 6.</b> Considerações de não linearidade física na avaliação dos esforços <a href="#fig6">[3]</a>.</p></center></td>
  </tr>
</table>

<p align = "justify">
  A não linearidade geométrica normalmente é aplicada quando desejamos avaliar elementos que tem sua geometria altera significativamente pelos esforços, no nosso caso os pilares. Para isso classificaremos as estruturas em: (a) nós móveis e (b) nós fixos. 
  <br><br>
  Uma estrutura será considerada, de nós fixos, quando os deslocamentos horizontais dos nós são pequenos e, por decorrência, os efeitos gerados são desprezíveis (inferiores a 10 % dos respectivos esforços da análise com geometria fixa) <a href="#ref2">[2]</a>.
  <br><br>
  Já as estruturas de nós móveis são aquelas onde os deslocamentos horizontais não são pequenos e, em decorrência, os efeitos gerados são importantes (superiores a 10 % dos respectivos esforços iniciais). 
</p>

{: .important}
> Os esforços gerados por uma análise linear considerando a geometria fixa é denominado como esforço de 1º ordem. Já a situação onde os deslocamentos horizontais são importantes e geram mudanças significativas nos esforços é denominada como esforço de 2º ordem. Normalmente esforços de 2º ordem estão associados a ações que geram o tombamento da estrutura como por exemplo o vento o desaprumo.

<p align = "justify">
  A consideração dos efeitos ditos de 2º ordem será realizada por meios de procedimentos numéricos e com o cálculo da variável \(\gamma _z\). Tal variável avalia a importância desses efeitos de segunda ordem e então caso eles sejam significativos os esforços da estrutura devem ser majorados pelo valor de \(0,95 \cdot \gamma _z\).
</p>

<h2>Pórtico e o subsistema horizontal de lajes</h2>

<p align = "justify">
  Os <i>softwares</i> mais modernos empregados na atualidade permitem a modelagem tridimensional de uma estrutural. Logo dentro de uma perspectiva de aplicação o modelo hoje dito como ideal é o modelo tridimensional com representação da laje como elemento de grelha. A <a href="#fig7">Figura 7</a> apresenta esse modelo que é utilizado pelo <i>software</i> TQS.
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td><center><img src = "assets/images/aula_06/fig7.png" width = "80%"></center></td>
  </tr>
  <tr>
    <td colspan="2"><center><p align = "justify" id = "fig7"><b>Figura 7.</b> Considerações de não linearidade física na avaliação dos esforços <a href="#fig6">[3]</a>.</p></center></td>
  </tr>
</table>

<p align = "justify">
  Neste conteúdo vamos empregar o modelo de pórtico para avaliação dos esforços em pilares e vigas e o modelo tabular para esforços em lajes que é um modelo amplamente aceito para aplicação em estruturas usuais de geometria regular.
  <br><br>
  Iniciando pelo sub-sistema de lajes obteremos os esforços de flexão via teoria da elasticidade linear e os esforços de cisalhamento via teoria de ruptura, gentilmente conhecido como método do "telhado".
  <br><br>
  O método de tabelas consiste em considerar a laje como um elemento de placa esbelto (ver <a href="#fig8">Figura 8</a>) e resolver numericamente a equação de equilíbrio de placas fletidas dado conforme <a href="#eq1">equação 1</a>.
</p>

<table border = "0" style = "width:100%">
  <tr>
    <td>\[
\frac{\partial^4 w}{\partial x^4} + 2 \frac{\partial^4 w}{\partial x^2 \partial y^2} + \frac{\partial^4 w}{\partial y^4} = \frac{p(x, y)}{D}
\]</td>
    <td><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<p align = "justify">
A <a href="#eq1">equação 1</a> só tem solução analítica para alguns casos particulares como por exemplo em placas circulares. Devido a essa dificuldade de solução formas alternativas foram encontradas para determinar os esforços e deslocamentos em placas com geometrias retangulares com diversas condições de contorno.
</p>

<h4>Considerações sobre os apoios</h4>

<h2>Referências</h2>
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1]</p></td>
            <td><p align = "left">Kimura A. Informática Aplicada a Estruturas de Concreto Armado. Editora Oficina de Textos; 2ed. 2018.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">Associação Brasileira de Normas Técnicas. ABNT NBR 6118: Projeto de estruturas de concreto – procedimento. Rio de Janeiro (RJ): ABNT; 2023.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">TQS informática. Manual sistemas computacionais engenharia estrutural. 20--.</p></td>
        </tr>
    </tbody>
</table>