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

<center><img src="assets\images\aula_08\fig_1.png" width="80%"></center>
<p align = "center"><b>Figura 1.</b> Bla bla bla.</p>

<center><img src="assets\images\aula_08\fig_2.png" width="80%"></center>
<p align = "center"><b>Figura 2.</b> Bla bla bla.</p>

<center><img src="assets\images\aula_08\fig_3.png" width="80%"></center>
<p align = "center"><b>Figura 3.</b> Bla bla bla.</p>

<p align="justify">Estádios:</p>
<ol type = "a">
  <li><strong>Estádio I:</strong> Esse estágio inicial de linearidade na respsota experiemntal;</li>
  <li><strong>Estádio II:</strong> Uma certa redução da inclinação da curva marcando o início do trecho de não linearidade;</li>
  <li><strong>Estádio III:</strong> Plastificação da armadura e/ou plastificação do concreto.</li>
</ol>

<center><img src="assets\images\aula_08\fig_4.png" width="100%"></center>
<p align = "center"><b>Figura 4.</b> Bla bla bla.</p>

<p align="justify">Para o <strong>Estádio I</strong> são válidas algumas hipóteses, são elas:</p>
<ul>
    <li><strong>A região de concreto tracionado, abaixo da linha neutra</strong> (\(h – x\)), <strong>está íntegra</strong> (não há fissuras) devido à pequena intensidade das <strong>tensões normais de tração</strong>, as quais <strong>são menores que a tensão resistente do concreto</strong> (fct);</li>
    <li>As <strong>tensões na região comprimida são proporcionais às deformações</strong>, correspondendo ao trecho linear elástico do diagrama tensão-deformação do concreto;</li>
    <li>O diagrama de <strong>tensão normal ao longo da seção é linear</strong> (Ia) – exceto quando o <strong>concreto está na iminência da ruptura devido à tração</strong> (Ib), em que se tem um diagrama plastificado na região de tração do concreto (Ver Figura 1.8).</li>
</ul>

<center><img src="assets\images\aula_08\fig_5.png" width="100%"></center>
<p align = "center"><b>Figura 5.</b> Bla bla bla.</p>

<br>

$$
\begin{align*}
  &A_h = b_f \cdot h_f + b_w \cdot h + A_s \cdot (\alpha - 1)\\
  &y_h = \frac{b_f \cdot \left(\frac{h_f²}{2}\right) + b_w \cdot \frac{h²}{2} + A_s \cdot (\alpha - 1) \cdot d}{A_h}\\
  &I_h = \frac{b_f \cdot h_f³}{12} + \frac{b_w \cdot h³}{12} + b_f \cdot h_f \cdot \left(y{cg} - \frac{h_f}{2}\right)² + b_w \cdot h \cdot \left(y{cg} - \frac{h}{2}\right)² + A_s \cdot (\alpha - 1) \cdot d \cdot (y_h - d)²
\end{align*}
$$

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

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td colspan="2">
                \(x_{II} = \frac{-a_2 \pm \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1}\)
            </td>
            <td>
                \(\begin{align*}
                    &a_1 = \frac{b_w}{12} \\
                    &a_2 = h_f \cdot (b_f - b_w) + (\alpha_e - 1) \cdot A'_s + \alpha_e \cdot A_s \\
                    &a_3 = -d' \cdot (\alpha_e - 1) \cdot A'_s - d \cdot \alpha_e \cdot A_s - \frac{h_f^2}{2} \cdot (b_f - b_w)
                \end{align*}\)
            </td>
        </tr>
        <tr>
            <td colspan="2">Para \(x_{II} \leq h_f\):</td>
            <td>
                \(I_{II} = \frac{b_f \cdot x_{II}^3}{3} + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2\)
            </td>
        </tr>
        <tr>
            <td colspan="2">Para \(x_{II} > h_f\):</td>
            <td>
                \(I_{II} = \frac{(b_f - b_w) \cdot h_f^3}{12} + \frac{b_w \cdot x_{II}^3}{3} + (b_f - b_w) \cdot \left(x_{II} - \frac{h_f}{2}\right)^2 + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2\)
            </td>
        </tr>
    </tbody>
</table>

<br>

$$
l_m = \left(\frac{M_r}{M_a} \right)^{n} \cdot I_c + \left[1 - \left(\frac{M_r}{M_a} \right)^{n}\right] \cdot I_{II}
$$

<br>

<p align="justify">Nas avaliações de flecha e fissuração por exemplo é necessária a consideração do efeito da fissuração sobre as propriedades geométricas da peça visto que na peça existem trechos fissurados e outros não fissurados. Para isso avaliamos a inércia média da peça proposto por Branson e descrito em Carvalho e Figueiredo Filho.</p>

<br>

<h1>Estádio III e domínios da deformação</h1>

<ol type = "a">
  <li>Devido ao aumento do momento fletor, a <strong>fissuração da peça na região tracionada</strong>, abaixo da linha neutra (\(ℎ – 𝑥\)), <strong>aumenta consideravelmente</strong>. Portanto, assim como no Estádio II – em que ocorrem as primeiras fissuras no concreto tracionado, a <strong>resistência a tração do concreto é desprezada</strong>, considerando-se que apenas o <strong>aço resiste aos esforços de tração</strong>;</li>
  <li>A fibra mais comprimida do concreto <strong>começa a plastificar a partir da deformação específica de \(\epsilon{c2} = 0,20% \)</strong> (grupo II equação 1.15 volume I), <strong>chegando a atingir</strong>, sem aumento de tensão, <strong>a deformação específica de \(\epsilon{cu} = 0,35%\)</strong> para concretos do grupo I e para concretos do grupo II essa deformação é calculada conforme equação 1.16 volume I;
  </li>
  <li>O <strong>diagrama de tensões tende a ficar vertical</strong> (uniforme), <strong>com quase todas as fibras trabalhando com sua tensão máxima de compressão</strong>, ou seja, praticamente todas as fibras atingiram deformações superiores a \(\epsilon_{c2} = 0,20%\) e chegando até \(\epsilon{cu} = 0,35%\) (ver valores para grupo II do concreto cap. 1 Volume I);</li>
  <li><strong>A peça está bastante fissurada</strong>, com as <strong>fissuras se aproximando da linha neutra, fazendo com que sua profundida diminua</strong> e, consequentemente, a <strong>região comprimida de concreto também</strong>.</li>
</ol>

<br>

<p align="justify">Diferentemente dos Estádios I e II – em que são verificados os ELS, no Estádio III tem-se o dimensionamento da peça de concreto armado no Estado Limite Último (ELU), ou seja, na iminência da ruptura.
<br><br>
<strong>Diante disso, tem-se que no Estádio III existem ao todo cinco incógnitas (\(𝐴_𝑠, 𝐴_𝑠^′, 𝜎_𝑠, 𝜎_𝑠^′ e 𝑥_𝐼𝐼𝐼\))</strong>. 
<br><br>
<strong>Estática tem-se apenas duas equações</strong>: somatório das forças é igual a zero e somatório dos momentos internos é igual ao momento solicitante externo. 
<br><br>
É necessário <strong>recorrer às relações entre as deformações</strong> da seção transversal para se conseguir mais três novas equações. Essa etapa será chamada de determinação dos <strong>domínios de deformação</strong>. </p>

<h2>Hipóteses Básicas para Cálculo</h2>	

<p align="justify">As <strong>seções transversais se mantêm planas</strong> após a deformação; </p>

$$
\frac{x}{d} = \frac{\epsilon_{c}}{\epsilon_{c} + \epsilon_{s}}
$$

<p align="justify">A <strong>deformação das barras passivas</strong> aderentes ou o acréscimo de deformação das barras ativas aderentes em tração ou compressão <strong>deve ser a(o) mesma(o) do concreto em seu entorno</strong>;
<br><br>
As <strong>tensões de tração no concreto</strong>, normais à seção transversal, <strong>devem ser desprezadas no ELU</strong>;
<br><br>
A <strong>distribuição de tensões no concreto é feita de acordo com o diagrama parábola-retângulo</strong>, definido em 8.2.10.1, com tensão de pico igual a \(0,85 \cdot f_{cd}), com \(f_{cd}\) definido em 12.3.3. <strong>Esse diagrama pode ser substituído pelo retângulo de profundidade \(y = \lambda \cdot x \)</strong>, onde o valor do parâmetro \(\lambda\) pode ser tomado igual as equações abaixo:</p>

<br>

$$
\begin{align*}
  &\lambda = 0,80 \quad \text{para} \quad f_{ck} \leq 50 MPa \\
  &\lambda = 0,80 - \left(\frac{f_{ck} - 50}{400}\right) \quad \text{para} \quad f_{ck} > MPa
\end{align*}
$$

<br>

<center><img src="assets\images\aula_08\fig_8.png" width="100%"></center>
<p align = "center"><b>Figura 8.</b> Bla bla bla.</p>

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
    </tr>
</table>

<br>

<table class="math-table" cellpadding="5" cellspacing="0">
    <tbody>
        <tr>
            <td colspan="2">
                \(a_c = 0,85\)
            </td>
            <td>
                \(f_{ck} \le 50 MPa\)
            </td>
        </tr>
        <tr>
            <td colspan="2">\(a_c = 0,85 \cdot \left(1 - \left(\frac{f_{ck} - 50}{200}\right)\right)\)</td>
            <td>
                \(50 MPa < f_{ck} \le 90 MPa\)
            </td>
        </tr>
    </tbody>
</table>

<br>

<p align="justify">No caso da seção transversal da viga/lajes for de apoio ou de ligação com outros elementos estruturais, há ainda outras considerações a serem feitas sobre a capacidade de rotação desses elementos.</p>

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
            <td colspan="2">\(\beta_x \frac{x}{d} /le 0,35\)</td>
            <td>
                \(50 MPa < f_{ck} \le 90 MPa\)
            </td>
        </tr>
        <tr>
            <td colspan="2">
                \(\frac{x}{d} \le \left(\frac{\delta - 0,45}{1,25} \right) \)
            </td>
            <td>
                \(f_{ck} \le 50 MPa\)
            </td>
        </tr>
        <tr>
            <td colspan="2">\(\frac{x}{d} \le \left(\frac{\delta - 0,56}{1,25} \right) \)</td>
            <td>
                \(50 MPa < f_{ck} \le 90 MPa\)
            </td>
        </tr>
    </tbody>
</table>

<br>

<p align="justify">Considereando a redistribuição dos esforços:</p>
<ul>
    <li>\(\delta \ge 0,90\) para estruturas de nós móveis.</li>
    <li>\(\delta \ge 0,75\) para qualquer outro caso.</li>
</ul>

<h2>Domínios de Deformação</h2>