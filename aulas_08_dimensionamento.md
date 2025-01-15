---
title: Hipóteses básicas e dimensionamento
layout: default
parent: Aulas
nav_order: 7
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Estádio I e Estádio II</h1>

<p align="justify">Elementos lineares de concreto armado, conforme a NBR 6118, <strong>são dimensionados considerando flexão normal simples</strong>, uma vez que o plano do momento fletor está em um dos eixos principais da seção transversal e acompanha as ações de força cortante. No entanto, esta mesma norma estabelece que o <strong>dimensionamento de peças submetidas a flexão normal simples deve ser feito de maneira separada</strong> (dimensionamento devido ao momento fletor e dimensionamento devido à força cortante).

<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_1.png" width="80%"></center>
<br>
<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_2.png" width="80%"></center>
<br>
<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_3.png" width="80%"></center>

<p align="justify">Estádios:</p>
<ol type = "a">
  <li><strong>Estádio I:</strong> Esse estágio inicial de linearidade na respsota experiemntal;</li>
  <li><strong>Estádio II:</strong> Uma certa redução da inclinação da curva marcando o início do trecho de não linearidade;</li>
  <li><strong>Estádio III:</strong> Plastificação da armadura e/ou plastificação do concreto.</li>
</ol>

<p align = "center"><b>Figura 4.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_4.png" width="100%"></center>

<p align="justify">Para o <strong>Estádio I</strong> são válidas algumas hipóteses, são elas:</p>
<ul>
    <li><strong>A região de concreto tracionado, abaixo da linha neutra</strong> (\(h – x\)), <strong>está íntegra</strong> (não há fissuras) devido à pequena intensidade das <strong>tensões normais de tração</strong>, as quais <strong>são menores que a tensão resistente do concreto</strong> (fct);</li>
    <li>As <strong>tensões na região comprimida são proporcionais às deformações</strong>, correspondendo ao trecho linear elástico do diagrama tensão-deformação do concreto;</li>
    <li>O diagrama de <strong>tensão normal ao longo da seção é linear</strong> (Ia) – exceto quando o <strong>concreto está na iminência da ruptura devido à tração</strong> (Ib), em que se tem um diagrama plastificado na região de tração do concreto (Ver Figura 1.8).</li>
</ul>

<p align = "center"><b>Figura 5.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_5.png" width="100%"></center>

<br>

<table border = "0" style = "width:100%">
  <tr>
    <td style="width:90%">\[ A_h = b_f \cdot h_f + b_w \cdot h + A_s \cdot (\alpha - 1) \]</td>
    <td style="width:10%"><p align = "right" id = "eq1">(1)</p></td>
  </tr>
    <tr>
        <td style="width:90%">\[ y_{cg} = \frac{b_f \cdot \frac{h_f}{2} + b_w \cdot \frac{h}{2} + A_s \cdot (\alpha - 1) \cdot d}{A_h} \]</td>
        <td style="width:10%"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width:90%">\[ I_h = \frac{b_f \cdot h_f^3}{12} + \frac{b_w \cdot h^3}{12} + b_f \cdot h_f \cdot \left(y_{cg} - \frac{h_f}{2}\right)^2 + b_w \cdot h \cdot \left(y_{cg} - \frac{h}{2}\right)^2 + A_s \cdot (\alpha - 1) \cdot d \cdot (y_h - d)^2 \]</td>
        <td style="width:10%"><p align = "right" id = "eq3">(3)</p></td>
    </tr>
</table>

<br>

<p align="justify">No <strong>Estádio II</strong> ocorre um <strong>aumento da intensidade do momento fletor solicitante</strong>, o que <strong>produz uma tensão de tração</strong> na maioria dos pontos abaixo da Linha Neutra (L.N.) que <strong>supera a tensão resistente do concreto à tração</strong>, o que resulta nos seguintes comportamentos:</p>
<ul>
    <li>O <strong>momento fletor solicitante supera o momento de fissuração</strong>, o que provoca o aparecimento das fissuras na região de concreto tracionado, abaixo da linha neutra (\(h – x\)). Devido a esse fato, considera-se que apenas o aço resiste aos esforços de tração (despreza-se o concreto tracionado);</li>
    <li>Admite-se que a <strong>tensão de compressão no concreto continue linear</strong>;</li>
    <li>As <strong>fissuras de tração</strong> na flexão do concreto <strong>são visíveis</strong>.
<ul>

<br>

<table border="0" style="width:100%">
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_08/fig_6.png" alt="Figura 6" width = "60%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig1">Seção sem armadura</p>
            </center>
        </td>
    </tr>
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_08/fig_7.png" alt="Figura 7" width = "60%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig1">Seção com armadura</p>
            </center>
        </td>
    </tr>
</table>

  <br>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ x_{II} = \frac{-a_2 \pm \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} \]</td>
        <td style="width:10%"><p align = "right" id = "eq4">(4)</p></td>
    </tr>
</table>

<p align="justify">Onde:</p>

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td>\(a_1 = \frac{b_w}{12}\)</td>
        </tr>
        <tr>
            <td>\(a_2 = h_f \cdot (b_f - b_w) + (\alpha_e - 1) \cdot A'_s + \alpha_e \cdot A_s\)</td>
        </tr>
        <tr>
            <td>\(a_3 = -d' \cdot (\alpha_e - 1) \cdot A'_s - d \cdot \alpha_e \cdot A_s - \frac{h_f^2}{2} \cdot (b_f - b_w)\)</td>
        </tr>
    </tbody>
</table>

<br>

<p align="justify">Para \(x_{II} \leq h_f\):</p>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ I_{II} = \frac{b_f \cdot x_{II}^3}{3} + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2 \]</td>
        <td style="width:10%"><p align = "right" id = "eq5">(5)</p></td>
    </tr>
</table>

<p align="justify">Para \(x_{II} > h_f\):</p>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ I_{II} = \frac{(b_f - b_w) \cdot h_f^3}{12} + \frac{b_w \cdot x_{II}^3}{3} + (b_f - b_w) \cdot \left(x_{II} - \frac{h_f}{2}\right)^2 + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2 \]</td>
        <td style="width:10%"><p align = "right" id = "eq6">(6)</p></td>
    </tr>
</table>

<br>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ l_m = \left(\frac{M_r}{M_a} \right)^{n} \cdot I_c + \left[1 - \left(\frac{M_r}{M_a} \right)^{n}\right] \cdot I_{II} \]</td>
        <td style="width:10%"><p align = "right" id = "eq7">(7)</p></td>
    </tr>
</table>

<br>

<p align="justify">Nas avaliações de flecha e fissuração por exemplo é necessária a consideração do efeito da fissuração sobre as propriedades geométricas da peça visto que na peça existem trechos fissurados e outros não fissurados. Para isso avaliamos a inércia média da peça proposto por Branson e descrito em Carvalho e Figueiredo Filho.</p>

<br>

<h1>Estádio III e domínios da deformação</h1>

<br>

<ol type = "a">
  <li>Devido ao aumento do momento fletor, a <strong>fissuração da peça na região tracionada</strong>, abaixo da linha neutra (\(h – x\)), <strong>aumenta consideravelmente</strong>. Portanto, assim como no Estádio II – em que ocorrem as primeiras fissuras no concreto tracionado, a <strong>resistência a tração do concreto é desprezada</strong>, considerando-se que apenas o <strong>aço resiste aos esforços de tração</strong>;</li>
  <li>A fibra mais comprimida do concreto <strong>começa a plastificar a partir da deformação específica de \(\epsilon_{c2} = 0,20% \)</strong> (grupo II equação 1.15 volume I), <strong>chegando a atingir</strong>, sem aumento de tensão, <strong>a deformação específica de \(\epsilon_{cu} = 0,35%\)</strong> para concretos do grupo I e para concretos do grupo II essa deformação é calculada conforme equação 1.16 volume I;
  </li>
  <li>O <strong>diagrama de tensões tende a ficar vertical</strong> (uniforme), <strong>com quase todas as fibras trabalhando com sua tensão máxima de compressão</strong>, ou seja, praticamente todas as fibras atingiram deformações superiores a \(\epsilon_{c2} = 0,20%\) e chegando até \(\epsilon_{cu} = 0,35%\) (ver valores para grupo II do concreto cap. 1 Volume I);</li>
  <li><strong>A peça está bastante fissurada</strong>, com as <strong>fissuras se aproximando da linha neutra, fazendo com que sua profundida diminua</strong> e, consequentemente, a <strong>região comprimida de concreto também</strong>.</li>
</ol>

<p align="justify">Diferentemente dos Estádios I e II – em que são verificados os ELS, no Estádio III tem-se o dimensionamento da peça de concreto armado no Estado Limite Último (ELU), ou seja, na iminência da ruptura.
<br><br>
<strong>Diante disso, tem-se que no Estádio III existem ao todo cinco incógnitas \(\left(𝐴_𝑠, 𝐴_𝑠^′, \sigma_𝑠, 𝜎_𝑠^′\right)\) e \(\left(𝑥_{𝐼𝐼𝐼} \right)\)</strong>. 
<br><br>
<strong>Estática tem-se apenas duas equações</strong>: somatório das forças é igual a zero e somatório dos momentos internos é igual ao momento solicitante externo. 
<br><br>
É necessário <strong>recorrer às relações entre as deformações</strong> da seção transversal para se conseguir mais três novas equações. Essa etapa será chamada de determinação dos <strong>domínios de deformação</strong>. </p>

<h2>Hipóteses Básicas para Cálculo</h2>	

<br>

<p align="justify">As <strong>seções transversais se mantêm planas</strong> após a deformação; </p>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[\frac{x}{d} = \frac{\epsilon_{c}}{\epsilon_{c} + \epsilon_{s}} \]</td>
        <td style="width:10%"><p align = "right" id = "eq8">(8)</p></td>
    </tr>
</table>

<p align="justify">A <strong>deformação das barras passivas</strong> aderentes ou o acréscimo de deformação das barras ativas aderentes em tração ou compressão <strong>deve ser a(o) mesma(o) do concreto em seu entorno</strong>;
<br><br>
As <strong>tensões de tração no concreto</strong>, normais à seção transversal, <strong>devem ser desprezadas no ELU</strong>;
<br><br>
A <strong>distribuição de tensões no concreto é feita de acordo com o diagrama parábola-retângulo</strong>, definido em 8.2.10.1, com tensão de pico igual a \(0,85 \cdot f_{cd}\), com \(f_{cd}\) definido em 12.3.3. <strong>Esse diagrama pode ser substituído pelo retângulo de profundidade \(y = \lambda \cdot x \)</strong>, onde o valor do parâmetro \(\lambda\) pode ser tomado igual as equações abaixo:</p>

<br>

<p align="justify">Para \(\quad \text{para} \quad f_{ck} \leq 50 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \lambda = 0,80 \]</td>
        <td style="width:10%"><p align = "right" id = "eq9">(9)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(\quad \text{para} \quad f_{ck} > 50 MPa\):</p>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \lambda = 0,80 - \left(\frac{f_{ck} - 50}{400}\right) \]</td>
        <td style="width:10%"><p align = "right" id = "eq10">(10)</p></td>
    </tr>
</table>

<br>

<p align = "center"><b>Figura 8.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_8.png" width="100%"></center>

<br>

<p align="justify">A tensão deve ser alterada caso a seção tenha acréscimo ou não de área comprimida.</p>

<br>

<table border="0" style="width:100%">
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_08/fig_9.png" alt="Figura 9" width = "80%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig9">\(\sigma_{cd} = a_c \cdot f_{cd}\)</p>
            </center>
        </td>
        <td style="width:10%"><p align = "right" id = "eq11">(11)</p></td>
    </tr>
    <tr>
        <td>
            <center>
                <img src="assets/images/aula_08/fig_10.png" alt="Figura 10" width = "80%">
            </center>
        </td>
        <td>
            <center>
                <p align="justify" id="fig10">\(\sigma_{cd} = 0,90  a_c \cdot f_{cd}\)</p>
            </center>
        </td>
        <td style="width:10%"><p align = "right" id = "eq12">(12)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(f_{ck} \leq 50 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ a_c = 0,85 \]</td>
        <td style="width:10%"><p align = "right" id = "eq13">(13)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(50 MPa < f_{ck} \leq 90 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ a_c = 0,85 \cdot \left(1 - \left(\frac{f_{ck} - 50}{200}\right)\right) \]</td>
        <td style="width:10%"><p align = "right" id = "eq14">(14)</p></td>
    </tr>
</table>

<br>

<p align="justify">No caso da seção transversal da viga/lajes for de apoio ou de ligação com outros elementos estruturais, há ainda outras considerações a serem feitas sobre a capacidade de rotação desses elementos.</p>

<br>

<p align="justify">Para \(f_{ck} \leq 50 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \beta_x = \frac{x}{d} \leq 0,45 \]</td>
        <td style="width:10%"><p align = "right" id = "eq15">(15)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(50 MPa < f_{ck} \leq 90 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \beta_x \frac{x}{d} \le 0,35 \]</td>
        <td style="width:10%"><p align = "right" id = "eq16">(16)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(\frac{x}{d} \leq \left(\frac{\delta - 0,45}{1,25} \right)\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \frac{x}{d} \leq \left(\frac{\delta - 0,45}{1,25} \right) \]</td>
        <td style="width:10%"><p align = "right" id = "eq17">(17)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(\frac{x}{d} \leq \left(\frac{\delta - 0,56}{1,25} \right)\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ \frac{x}{d} \leq \left(\frac{\delta - 0,56}{1,25} \right) \]</td>
        <td style="width:10%"><p align = "right" id = "eq18">(18)</p></td>
    </tr>
</table>

<br>

<p align="justify">Considereando a redistribuição dos esforços:</p>
<ul>
    <li>\(\delta \ge 0,90\) para estruturas de nós móveis.</li>
    <li>\(\delta \ge 0,75\) para qualquer outro caso.</li>
</ul>

<h2>Domínios de Deformação</h2>

<br>

<p align="justify">Os conjuntos de deformações específicas do concreto e do aço ao longo de uma seção transversal retangular com armadura simples (só tracionada) submetida a ações normais <strong>definem cinco domínios de deformação</strong>. Os <strong>domínios representam</strong> as diversas <strong>possibilidades de ruína da seção; a cada par de deformações específicas de cálculo (\(\epsilon_s\)) e (\(\epsilon_c\))</strong> correspondem um esforço normal, se houver, e um momento fletor atuantes na seção. Para verificar esses domínios é apresentada a Figura a seguir com todos os seis intervalos de deformações.</p>

<br>

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td colspan="2">Para concretos de classes até C50:</td>
            <td>Para concretos de classes C55 até C90:</td>
        </tr>
        <tr>
            <td colspan="2">\(\epsilon_{c2} = 2,0 ‰\)</td>
            <td>\(\epsilon_{c2} = 2,0 ‰ + 0,085 ‰ \cdot (f_{ck} - 50)^{0,53}\)</td>
        </tr>
        <tr>
            <td colspan="2">\(\epsilon_{c2} = 2,0 ‰\)</td>
            <td>\(\epsilon_{cu} = 2,6 ‰ + 35 ‰ \cdot \left[\frac{90 - f_{ck}}{100}^4 \right]\)</td>
        </tr>
    </tbody>
</table>

<br>

<p align = "center"><b>Figura 11.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_11.png" width="80%"></center>

<br>

<p align = "center"><b>Figura 12.</b> Reta <strong>a</strong>.</p>
<center><img src="assets\images\aula_08\fig_12.png" width="60%"></center>

<br>

<p align="justify">A reta a corresponde situação de tração uniforme, caso em que toda a seção é tracionada de modo uniforme. A posição da linha encontra-se no infinito negativo (\(x = - \infty \)). O Estado Limite Último é atingido por deformação plástica excessiva da armadura passiva sendo caracterizado por um alongamento de 10‰ na mesma. A seção resistente é constituída somente pelas armaduras visto que em situações de tração no ELU o concreto não contribui com a resistência do conjunto [3,5,7–9].</p>

<br>

<p align = "center"><b>Figura 12.</b> Domínio 1.</p>
<center><img src="assets\images\aula_08\fig_13.png" width="60%"></center>

<br>

<p align="justify">O domínio 1 corresponde ao caso de tração não uniforme na seção transversal. A linha neutra ainda é externa a seção e as deformações na parte superior da peça variam entre 10‰ e 0. Logo a linha neutra poderá variar desde \( x > - \infty\) até \(x \ge 0\). O Estado Limite Último e caracterizado por deformação plástica excessiva da armadura passiva. A seção resistente é composta apenas pelas armaduras [3,5,7–9].</p>

<br>

<p align = "center"><b>Figura 14.</b> Domínio 2.</p>
<center><img src="assets\images\aula_08\fig_14.png" width="60%"></center>

<br>

<p align="justify">No domínio 2 a linha neutra adentra a seção de concreto (𝑥 > 0 até 𝑥 ≤ \(0,259 \cdot d\) grupo I). Essa situação abrange os casos de flexão simples e flexão composta com grande excentricidade. Este domínio corresponde às situações em que o Estado Limite Último é atingido pelo alongamento da armadura em 10‰ e o encurtamento da fibra mais comprimida de concreto é inferior a \(\epsilon_{cu}\) [3,5,7–9].
<br><br>
Nesse domínio 2 podemos perceber que o concreto não está no máximo possível da sua compressão (\(0 \ge \epsilon_c \ge \epsilon_{cu}\)) portanto é comum encontrar na literatura que nessas ocasiões o concreto está “mal aproveitado”. Portanto o domínio 2 é o último caso de ruína por deformação plástica da armadura [3,5,7–9].</p>

<br>

<p align = "center"><b>Figura 15.</b> Domínio 3.</p>
<center><img src="assets\images\aula_08\fig_15.png" width="60%"></center>

<br>

<p align="justify">O domínio 3 corresponde à flexão simples e flexão composta com grande excentricidade. Esse estado abrange os casos em que o Estado Limite Último é alcançado na borda comprimida da seção com o encurtamento de \(\epsilon_{cu}\) e o alongamento na armadura está compreendido entre 10‰ e \(\epsilon_{yd}\). Esta é a situação desejável para o projeto estrutural em concreto armado, pois os materiais são aproveitados de forma econômica (aço em tensão de escoamento e concreto no máximo de sua compressão) e a ruína poderá ser avisada pelo aparecimento de muitas fissuras motivadas pelo escoamento da armadura. As peças de concreto armado nestas condições são denominadas por muitos autores como “peças sub-armadas” [3,5,7–9]. </p>

<br>

<p align = "center"><b>Figura 16.</b> Domínio 4.</p>
<center><img src="assets\images\aula_08\fig_16.png" width="60%"></center>

<br>

<p align="justify"> O domínio 4 abrange os casos de flexão simples e flexão composta com grande excentricidade. Refere-se aos casos em que no estado limite último o encurtamento de \(\epsilon_{cu}\) é alcançado na borda comprimida da seção e já na armadura as deformações transitam entre \(\epsilon_{yd}\) (tracionado) e um valor de deformação de compressão menor que \(\epsilon_{cu}\). O estado limite último é caracterizado pela ruptura do concreto comprimido sem que haja escoamento da armadura. Cobre o campo de profundidade da linha neutra desde \(x > x_{34}\) até \(x = h\). As peças de concreto armado nestas condições são denominadas peças “super-armadas” e devem ser evitadas tanto quanto possíveis [3,5,7–9]. No caso de pilares é inevitável esse tipo de domínio sendo este aceito para peças dessa natureza.
<br><br>
O domínio 4 tem um caso particular denominado de 4a que é uma situação onde as armaduras inferiores apresentam deformações de compressão conforme pode ser visto na Figura 1.20.
</p>

<br>

<p align = "center"><b>Figura 17.</b> Domínio 5.</p>
<center><img src="assets\images\aula_08\fig_17.png" width="60%"></center>

<br>

<p align="justify">O domínio 5 refere-se à compressão não uniforme (sem tração), com toda a seção de concreto comprimida. A linha neutra é externa à seção e cobre o campo de profundidade da linha neutra desde \(x > h\) até \(x ≤ +∞\). O Estado Limite Último e atingido pela ruptura do concreto comprimido com encurtamento na borda mais comprimida situado entre \(\epsilon_{cu}\) e \(\epsilon_{c2}\) [3,5,7–9].</p>

<br>

<p align = "center"><b>Figura 18.</b> Reta <strong>b</strong>.</p>
<center><img src="assets\images\aula_08\fig_18.png" width="60%"></center>

<br>

<p align="justify">A reta b refere-se à situação oposta à reta a, ou seja, a situação de compressão uniforme. O encurtamento das fibras possui valor de \(\epsilon_{c2}\) [3,5,7–9]. Nesse caso a linha neutra \(x = + \infty \).</p>

<br>

<h2>Dimensionamento de seções retangulares</h2>

<br>

<p align="justify">Como visto no capítulo anterior o problema da flexão pura no Estádio III envolve uma série de variáveis como determinação das tensões nas armaduras, a própria armadura e a posição da linha neutra. Logo nesse capítulo teremos como <strong>objetivo principal a explicação dos artifícios necessários para obtenção da área de aço de uma peça de concreto armado</strong>, seja ela uma seção retangular ou seção Tê.</p>

<br>

<p align = "center"><b>Figura 19.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_19.png" width="80%"></center>

<br>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[b_w \cdot d \cdot \lambda \cdot \beta_x \cdot \alpha_c \cdot f_{cd} + \sigma_{sc} \cdot A_{sc} = \sigma_{st} \cdot A_{st} \]</td>
        <td style="width:10%"><p align = "right" id = "eq19">(19)</p></td>
    </tr>
    <tr>
        <td style="width:90%">\[M_{sd} = b_w \cdot d^2 \cdot \lambda \cdot \beta_x \cdot \alpha_c \cdot f_{cd} \cdot (1 - 0,50 \cdot \lambda \cdot \beta_x) + \sigma_{sc} \cdot A_{sc} \cdot (d - d') \]</td>
        <td style="width:10%"><p align = "right" id = "eq20">(20)</p></td>
    </tr>
    <tr>
        <td style="width:90%">\[\frac{\varepsilon_{cc}}{\beta_x} = \frac{\varepsilon_{sc}}{\beta_x} - \frac{d'}{d} = \frac{\varepsilon_{st}}{1 - \beta_x}\]</td>
        <td style="width:10%"><p align = "right" id = "eq21">(21)</p></td>
    </tr>
</table>

<br>

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td colspan="2">
                \(\beta_x = \frac{x}{d} \le 0,45\)
            </td>
            <td>
                \(f_{ck} \le 50 MPa\)
            </td>
        </tr>
        <tr>
            <td colspan="2">\(\beta_x \frac{x}{d} \le 0,35\)</td>
            <td>
                \(50 MPa < f_{ck} \le 90 MPa\)
            </td>
        </tr>
    </tbody>
</table>

<br>

<p align="justify">Com essa quantidade de equações é possível montar um sistema com <strong>4 equações e 5 incógnitas</strong> portanto o problema de flexão acaba sendo um sistema possível, porém indeterminado com infinitas soluções. Logo você como <strong>projetista deverá arbitrar</strong> uma condição para que seja possível <strong>determinar a solução para esse sistema</strong>.
<br><br>
<strong>No primeiro caso (armadura dupla) estabeleceremos que não conhecemos as armaduras, mas conhecemos a relação \(\beta_𝑥\)</strong> limitante. Logo se conhecemos \(\beta_𝑥\) conhecemos a posição da linha neutra (\(x_{III}\)). Para o segundo caso, chamado aqui de <strong>armadura simples, não conhecemos a linha neutra e admitimos que a armadura de compressão (\(𝐴_{𝑠𝑐}\)) não se faz necessária</strong>. A grande questão é quando estabelecer uma situação ou outra?!
<br><br>
Do ponto de vista de comportamento peças estruturais com <strong>armadura dupla</strong> são <strong>empregadas</strong> quando é necessária a <strong>redução da posição da linha neutra</strong>.
</p>

<br>

<p align="justify">Para \(f_{ck} \leq 50 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ M_{lim} = 0,45 \cdot b_w \cdot \lambda \cdot d² \cdot \alpha_c \cdot f_{cd} \cdot (1 - 0,225 \cdot \lambda) \]</td>
        <td style="width:10%"><p align = "right" id = "eq22">(22)</p></td>
    </tr>
</table>

<br>

<p align="justify">Para \(50 MPa < f_{ck} \leq 90 MPa\):</p>
<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ M_{lim} = 0,35 \cdot b_w \cdot \lambda \cdot d² \cdot \alpha_c \cdot f_{cd} \cdot (1 - 0,172 \cdot \lambda) \]</td>
        <td style="width:10%"><p align = "right" id = "eq23">(23)</p></td>
    </tr>
</table>

<br>

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td colspan="2">
                \(M_{lim} = 0,45 \cdot b_w \cdot \lambda \cdot d² \cdot \alpha_c \cdot f_{cd} \cdot (1 - 0,225 \cdot \lambda)\)
            </td>
            <td>
                \(f_{ck} \le 50 MPa\)
            </td>
        </tr>
        <tr>
            <td colspan="2">\(M_{lim} = 0,35 \cdot b_w \cdot \lambda \cdot d² \cdot \alpha_c \cdot f_{cd} \cdot (1 - 0,172 \cdot \lambda)\)</td>
            <td>
                \(50 MPa < f_{ck} \le 90 MPa\)
            </td>
        </tr>
    </tbody>
</table>

<br>

<p align = "center"><b>Figura 20.</b> Bla bla bla.</p>
<center><img src="assets\images\aula_08\fig_20.png" width="80%"></center>

<br>

<table border = "0" style = "width:100%">
    <tr>
        <td style="width:90%">\[ M_{sd} = b_w \cdot \alpha_c \cdot f_{cd} \cdot \lambda \cdot x \cdot (d - 0,50 \cdot \lambda \cdot x) \]</td>
        <td style="width:10%"><p align = "right" id = "eq24">(24)</p></td>
    </tr>
    <tr>
        <td style="width:90%">\[ x_{III} = \frac{d + \sqrt{d^2 - 2 \cdot \left(\frac{M_{sd}}{b_w \cdot \alpha_c \cdot f_{cd}}\right)}}{\lambda} \]</td>
        <td style="width:10%"><p align = "right" id = "eq25">(25)</p></td>
    </tr>
    <tr>
        <td style="width:90%">\[ A_{st} = \frac{M_{sd}}{f_{yd} \cdot \left(d - 0,50 \cdot \lambda \cdot x_{III}\right)} \]</td>
        <td style="width:10%"><p align = "right" id = "eq26">(26)</p></td>
    </tr>
</table>







<h2>Exercício 1 - Propriedades geomértricas no Estádio I e II</h2>

<p align = "justify">
    Verificar as propriedades da seção transversal de uma laje pré-fabricada com altura de 16 cm (d = 13,9 cm). Considere que esta laje é construída com o fck = 20 MPa e que a área de aço das sapatas pré-fabricadas é de 3,615 cm². Essa laje é disposta em um vão de 5 m, tem distância intereixos de 50 cm e uma capa de 4 cm. <br>
    <br>
    Considere para o módulo de elasticidade do aço igual a 200 GPa e para o concreto empregue a Tabela 8.1 da NBR 6118.
</p>

<center><img src="assets\images\aula_08\fig_21.jpg" width="100%"></center>
<p align = "center"><b>Figura 21.</b> bla bla.</p>

<p align = "justify">
    Inicialmente é necessario determinar o módulo de elasticidade do concreto em função da sua ressitência caracterísstica à compressão através da Tabela 8.1 da NBR 6118 <a href="#ref1">[1]</a>
</p>

<table>
    <tr>
        <td>
            <center><img src="assets\images\aula_08\fig_22.png" width="100%"></center>
        </td>
    </tr>
</table>
<p align = "justify">
    Com a determinação do módulo de elasticidade do concreto definido, deve-se calcular o módulo de deformação secante (αe) pela Equação***.
</p>

<p id="Eq2"></p>
<table border = "0" style = "width:100%">
    <tr>
        <td>\[E_{s}= \alpha_e * E_{cs}\]</td>
        <td>***</td>
    </tr>
</table>
<p align = "justify">
    onde E<sub>s</sub> é o módulo de elasticidade do aço;<br>
    E<sub>cs</sub> é o módulo de elasticidade do concreto.<br>
</p>
<p align = "justify">
    Através da Equação <a href="#Eq10">***</a> obtém-se o seguinte valor para o códulo de deformação secant:
</p>
<table border = "0" style = "width:100%">
    <tr>
        <td>\[\dfrac{E_s}{E_{cs}}=\dfrac{200}{21}=9,526=\alpha_e\]</td>
    </tr>
</table>
<br>

<br>
<p align ="justify">
    O proximo passo que deve ser realizado é o cálculo da área da peça pré-fabricada (A<sub>h</sub>), da altura da peça pré-fabricada (y<sub>h</sub>) e da inercia da da peça pré-fabricada (I<sub>h</sub>), dadas pelas Equações <a href="#Eq10">*</a>, <a href="#Eq10">**</a>, <a href="#Eq10">***</a>.
</p>
<br>
<table>
    <tr>
        <td>\[A_h = (b_f - b_w) \cdot h_f + b_w \cdot h + A_s \cdot (\alpha_e - 1)\]</td>
        <td>*</td>
    </tr>
    <tr>
        <td>\[y_h = \frac{(b_f - b_w) \cdot \frac{h_f^2}{2} + b_w \cdot \frac{h^2}{2} + A_s \cdot (\alpha_e - 1) \cdot d}{A_h}\]</td>
        <td>**</td>
    </tr>
        <tr>
        <td>\[I_h = \frac{(b_f - b_w) \cdot h_f^3}{12} + \frac{b_w \cdot h^3}{12} + (b_f - b_w) \cdot h_f \cdot \left( y_{cg} - \frac{h_f}{2} \right)^2 + b_w \cdot h \cdot \left( y_{cg} - \frac{h}{2} \right)^2 + A_s \cdot (\alpha_e - 1) \cdot d \cdot \left( y_h - d \right)^2\]</td>
        <td>***</td>
    </tr>
</table>


<center><img src="assets\images\aula_08\fig_23.jpg" width="100%"></center>
<p align = "center"><b>Figura 21.</b> bla bla.</p>


<p align = "justify">
    Tratando-se da geometria a peça como seção Tê conforme a Figura <a href="#fig23">23</a> pois h<sub>f</sub> ≠ 0 e b<sub>w</sub> ≠ b<sub>f</sub>
</p>
<p id="fig23"></p>
<center><img src="assets\images\aula_08\fig_23.jpg" width="100%"></center>
<p align = "center"><b>Figura 23.</b> Seção Tê.</p>
<p align = "justify">
    Tomando a seção da peça como seção Tê obtém-se os seguintes valores para a área, alrura e inercia da peça:
</p>
<table>
    <tr>
        <td>\[A_h = 350 cm^2\]</td>
    </tr>
    <tr>
        <td>\[y_h = 5,782 cm\]</td>
    </tr>
        <tr>
        <td>\[I_h = 8733,03 cm^4\]</td>
    </tr>
</table>
<br>
<h3>Estádio II</h3>
<p align = "justify">
    Para o estádio II na primeira etapa que dever ser realizada vamos estimar b<sub>w</sub> = b<sub>f</sub>, para utilizar nas Equações <a href="#Eq23">@</a>, <a href="#Eq23">@@</a>, <a href="#Eq23">@@@</a>. 
</p>
<table border = "0" style = "width:100%">
    <tr>
        <td>\[x_{II} = \frac{a_2 \pm \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1}\]</td>
        <td><p id="Eq23">(@#)</p></td>
    </tr>
    <tr>
        <td>\[a_1 = \frac{b_w}{12}\]</td>
        <td><p id="Eq23">(@)</p></td>
    </tr>
    <tr>
        <td>\[a_2 = h_f \cdot (b_f - b_w) + (\alpha_e - 1) \cdot A_s' + \alpha_e \cdot A_s\]</td>
        <td><p id="Eq23">(@@)</p></td>
    </tr>
    <tr>
        <td>\[a_3 = -d' \cdot (\alpha_e - 1) \cdot A_s' - d \cdot \alpha_e \cdot A_s - \frac{h_f^2}{2} \cdot (b_f - b_w)\]</td>
        <td><p id="Eq23">(@@@)</p></td>
    </tr>
</table>
<p align = "justify">
    Realizando os cálculos das Equações <a href="#Eq23">@</a>, <a href="#Eq23">@@</a>, <a href="#Eq23">@@@</a> obtém-se os seguintes valores: 
</p>
<table border = "0" style = "width:100%">
    <tr>
        <td>\[a_1=25cm\]</td>
    </tr>
    <tr>
        <td>\[a_2=34,4286cm^2\]</td>
    </tr>
    <tr>
        <td>\[a_3=-478,5571cm^3\]</td>
    </tr>
</table>
<p align = "justify">
    Subistituindo os valores obtidos para a<sub>2</sub>, a<sub>2</sub>, a<sub>3</sub> na Equação <a href="#Eq23">@#</a> obtém-se o seguinte valor para X<sub>II</sub>:
</p>
<table border = "0" style = "width:100%">
    <tr>
        <td>\[X_{II}=3,74 cm\]</td>
    </tr>
</table>
<p align = "justify">
    Como X<sub>II</sub> é menor que h<sub>f</sub> que possúi um valor de 4cm a linha neutra se encontra na mesa!<br>
    Com isso podemos cácular a inécia (33wdqdhjd) utilizando a Equação <a href="#Eq23">%</a>.
</p> 
<table border = "0" style = "width:100%">
    <tr>
        <td>\[I_{II} = \frac{b_f \cdot x_{II}^3}{3} + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A_s' \cdot (x_{II} - d')^2\]</td>
        <td><p id="Eq23">(@@)</p></td>
    </tr>
</table>
<p align = "justify">
    Através da Equação <a href="#Eq23">%</a> chega-se ao seguinte valor para a inercia (3dadfdf):
</p>
<table border = "0" style = "width:100%" align = "center">
    <tr>
        <td>\[I_{II} = 4425,8036 cm^4\]</td>
    </tr>
</table>