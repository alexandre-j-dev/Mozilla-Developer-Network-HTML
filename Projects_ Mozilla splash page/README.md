<span><i>English ver.</i> <a href="https://github.com/alexandre-j-dev/MDN-Mozilla-Developer-Network-HTML/blob/HTML/Projects_%20Mozilla%20splash%20page/README.en.md"> README</a></span>

<h1> Resumo do projeto </h1>

<p>Neste projeto, temos uma página inicial do Mozilla quase finalizada, que visa dizer algo legal e interessante sobre o que o Mozilla representa e fornecer alguns links para outros recursos. Infelizmente, nenhuma imagem ou vídeo foi adicionado ainda - este é o seu trabalho! Você precisa adicionar algumas mídias para tornar a página bonita e fazer mais sentido. As seguintes subseções detalham o que precisa ser feito:</p>

<strong>Habilidades aprendidas (utilizadas):</strong>
<ul>
<li>Imagens responsivas nas páginas</li>
<li>Problemas de mudança de resolução e direção de arte</li>
<li>Imagens raster e vetoriais (svg)</li>
<li>Atributos scrset e size</li>
<li>Elemento &lt;picture&gt;</li>
<li>Minimizando consumo de largura de banda em imagens</li>
</ul>

<h2> Ponto de partida: </h2>

<p>Para iniciar este projeto, você precisa do HTML e das imagens disponíveis no diretório do github <a href="https://github.com/mdn/learning-area/tree/main/html/multimedia-and-embedding/mdn-splash-page-start"> mdn-splash-start-page.</a> Salve o conteúdo de <a href="https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/mdn-splash-page-start/index.html"> index.html </a> em um novo arquivo chamado index.html em sua máquina local. Em seguida, salve <a href="https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/mdn-splash-page-start/pattern.png"> pattern.png </a> no mesmo diretório. </p>


<h2> Requisitos: </h2>

<h3> Preparando imagens </h3>

<p>Usando seu editor de imagens favorito, crie versões de 400px e 120px de largura de:</p>

<ul>
<li>firefox_logo-only_RGB.png</li>
<li>firefox-addons.jpg</li>
<li>mozilla-dinosaur-head.png</li>
</ul>

<p>Chame-os de algo sensato, por exemplo. firefoxlogo400.png e firefoxlogo120.png</p>
<p>Junto com mdn.svg, essas imagens serão seus ícones para vincular a outros recursos, dentro da área de informações adicionais. Você também criará um link para o logotipo do Firefox no cabeçalho do site. Salve cópias de tudo isso dentro do mesmo diretório que index.html.</p>
<p>Em seguida, crie uma versão de paisagem de 1200px de red-panda.jpg e uma versão de retrato de 600px de largura que mostre o panda em mais de um close-up. Novamente, chame-os de algo sensato para que você possa identificá-los facilmente. Salve uma cópia de ambos dentro do mesmo diretório que index.html.</p>
<p>Você deve otimizar suas imagens JPG e PNG para torná-las tão pequenas quanto possível, enquanto ainda parecem boas. O tinypng.com é um ótimo serviço para fazer isso facilmente.</p>

<h3>Adicionando um logotipo ao cabeçalho</h3>

<p>Dentro do elemento &lt;header&gt;, adicione um elemento &lt;img&gt; que incorporará a versão pequena do logotipo do Firefox no cabeçalho.</p>

<h3>Adicionando um vídeo ao conteúdo do artigo principal</h3>

<p>Logo dentro do elemento &lt;article&gt; (logo abaixo da tag de abertura), incorpore o vídeo do YouTube encontrado em <a href="https://www.youtube.com/watch?v=ojcNcvb1olg"> https://www.youtube.com/watch?v=ojcNcvb1olg </a>, usando as ferramentas apropriadas do YouTube para gerar o código. O vídeo deve ter 400px de largura.</p>

<h3>Adicionando imagens responsivas aos links de informações adicionais</h3>

<p>Dentro do &lt;div&gt; com a classe de informações adicionais, você encontrará quatro elementos &lt;a&gt; — cada um com um link para uma página interessante relacionada ao Mozilla. Para completar esta seção, você precisará inserir um &lt;img&gt; elemento dentro de cada um contendo os atributos src, alt, srcset e tamanhos apropriados. Em cada caso (exceto um - qual é inerentemente responsivo?) queremos que o navegador veicule a versão de 120px de largura quando a largura da janela de visualização for de 500px de largura ou menos, ou a versão de 400px de largura caso contrário. Certifique-se de combinar as imagens corretas com os links corretos!

<h3>Art direction do panda vermelho </h3>

<p>Dentro do &lt;div&gt; com a classe red-panda, queremos inserir um elemento <picture> que serve a pequena imagem de panda de retrato se a janela de visualização tiver 600px de largura ou menos, e a imagem de paisagem grande caso contrário.
</p>


<h2>Dicas e sugestões</h2>

<ul>
<li>Utilize o W3C HTML Checker para validar seu HTML e detectar erros que possam ter passados despercebidos.</li>
<li>Você não precisa conhecer nenhum CSS para fazer esse projeto; você só precisa linkar o CSS fornecido ao documento HTML.</li>
</ul>

Examplo:
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page/wide-shot.png"> Mozilla splash page (done) </a></li> 
<li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page/narrow-shot.png"> Narrow ver. </a></li>
</ul>

Validador:
<a href="https://validator.w3.org">W3C HTML Checker</a>  <br><hr>
  
<strong>Veja abaixo</strong><br>
<a href="https://htmlpreview.github.io/?https://github.com/alexandre-j-dev/MDN-Mozilla-Developer-Network-HTML/blob/HTML/Projects_%20Mozilla%20splash%20page/index.html"> Renderizar </a><br>

<strong>Projetos de conclusão MDN</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Mozilla_splash_page"> Mozilla splash page </a>

<strong>Avaliação no Mozilla Discourse</strong><br>
<a href=" ">Ir para avaliação </a>
