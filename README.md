<!DOCTYPE html>
<html lang="br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O tutorial HTML</title>
</head>
<body>
    <h1>HTML Descomplicado: Entendendo as Tags</h1>
    
    <p>Olá, meus queridos "vovôs" e "vovós" tecnológicos! Tudo bem com vocês? Hoje, vou explicar pra vocês, de um jeito simples e descontraído, o que são as famosas tags do HTML. Pensa nelas como as pecinhas de um quebra-cabeça que ajudam a construir a internet do jeito que a gente vê. Preparados? Bora lá! 🚀</p>
    <p>Você já se perguntou como as páginas da web são construídas? Ou como o conteúdo que você vê quando acessa um site é mostrado da maneira que é? A resposta para essas perguntas passa por uma linguagem fundamental chamada HTML (HyperText Markup Language). O HTML é a espinha dorsal de qualquer página web, e é através dele que organizamos o conteúdo e damos sentido à informação que aparece na tela.</p>
    
       
    <h2>&lt;HTML&gt;</h2>
    <p>A tag &lt;html&gt; é o ponto de partida de qualquer página HTML. Ela envolve todo o conteúdo da página, e é como se fosse uma caixa gigante que vai manter todos os outros elementos dentro dela. Então, sempre que você começa a escrever um arquivo HTML, a primeira coisa que você faz é abrir a tag &lt;html&gt;.</p>
        <pre>
            &lt;html&gt;
            &lt;!-- O conteúdo da página vai aqui --&gt;
            &lt;/html&gt;
        </pre>
    <h3>&lt;HEAD&gt;</h3>
    <p>O &lt;head&gt; é onde você coloca informações que não aparecem diretamente na página, mas que são essenciais para o funcionamento e organização do site. Dentro dessa tag, você pode colocar o título da página, links para folhas de estilo (CSS), fontes externas, e até meta-informações sobre a página, como palavras-chave para mecanismos de busca.</p>
        <pre>
            &lt;head&gt;
                &lt;title&gt;Minha Primeira Página&lt;/title&gt;
                &lt;link rel="stylesheet" href="styles.css"&gt;
            &lt;/head&gt;
        </pre>
    <h3>&lt;BODY&gt;</h3>
    <p>Agora, o &lt;body&gt; é a tag onde a mágica acontece! Todo o conteúdo visível da página fica dentro dessa tag: textos, imagens, vídeos, links, botões, etc. Você coloca o que o usuário vai ver e interagir dentro dela.</p>
        <pre>
            &lt;body&gt;
                &lt;!-- O conteúdo VISÍVEL da página vai aqui --&gt;
            &lt;/body&gt;
        </pre>

    <h4>Títulos e subtítulos:&lt;h1&gt;&lt;h2&gt;&lt;h3&gt;...&lt;h6&gt;</h4>
    <p>Imagine que você está escrevendo um livro com capítulos e subtítulos. O HTML tem tags específicas para criar esses títulos, que vão do maior pro menor. </p>
    <pre>        
        &lt;h1&gt;É o título principal&lt;/h1&gt;
        &lt;h2&gt;Subtítulo importante.&lt;/h2&gt;
        &lt;h3&gt;Subtítulos menores&lt;/h3&gt;        
    </pre>
    


<h4>&lt;p&gt; Parágrafos</h4>
    <p>A tag &lt;p&gt; é usada para parágrafos de texto. Se você tem uma ideia que quer explicar em um bloco de texto, você vai usar essa tag para separá-la do restante do conteúdo.</p>       
    <pre>
        &lt;p&gt;Esse é um parágrafo de exemplo. Aqui podemos colocar informações sobre o assunto que estamos tratando.&lt;/p&gt;

    </pre>

<h4>&lt;ul&gt;&lt;ol&gt;&lt;li&gt; Listas</h4>
    <p> O &lt;ul&gt; é para listas não ordenadas (com marcadores), enquanto o &lt;ol&gt; é para listas ordenadas (com números). Dentro de ambas, usamos a tag &lt;li&gt; para definir cada item da lista.
    
    <pre>      
        <h5>Lista não ordenada</h5>
        &lt;ul&gt;
            &lt;li&gt;Item 1&lt;/li&gt;
            &lt;li&gt;Item 2&lt;/li&gt;
            &lt;li&gt;Item 3&lt;/li&gt;
        &lt;ul&gt;   
            <h5>Lista  ordenada</h5>
        &lt;ol&gt;
            &lt;li&gt;Item 1&lt;/li&gt;
            &lt;li&gt;Item 2&lt;/li&gt;
            &lt;li&gt;Item 3&lt;/li&gt;
        &lt;ol&gt;
    </pre>

<h4>&lt;a&gt; Links</h4>
    <p>A tag &lt;a&gt; é uma das mais poderosas em HTML, porque é ela que cria links para outras páginas ou para seções dentro da mesma página. O atributo href define para onde o link vai direcionar.</p>
    <pre>
        &lt;a href="https://google.com"&gt;Clique aqui pra visitar o Google!&lt;/a&gt;
    </pre>

<h4>&lt;img&gt; Imagens</h4>
    <p>Se você quiser adicionar imagens à sua página, a tag &lt;img&gt; é a que você vai usar. Ela precisa do atributo src para indicar o caminho da imagem, e também pode ter o atributo alt para descrever a imagem caso ela não carregue ou para tornar a página mais acessível.</p>
    <p>Repare que essa tag não possui fechamento.
    <pre>
        &lt;img src="imagem.jpg" alt="Descrição da imagem"&gt;
        <img >
    </pre>

    <h5>&lt;blockquote&gt; Citações</h5>
    <pre>
        &lt;blockquote&gt;
        “Seja a mudança que você quer ver no mundo.” - Gandhi
        &lt;/blockquote&gt;
    </pre>

<h5>&lt;abbr&gt; Mostra a explicação de siglas.</h5>
    <pre>
        &lt;abbr title="HyperText Markup Language"&gt;HTML&lt;/abbr"&gt;
        <img >
    </pre>
    
<h5>Formatos Diversos</h5>
<ul>
    <li>&lt;mark&gt; Destaca algo, como se fosse aquele marca-texto amarelo.</li>
        <pre>
            &lt;mark&gt;<mark>Essa palavra aqui é importante!</mark>&lt;/mark&gt;
        </pre>
    
    <li> &lt;small&gt; Quer escrever um textinho pequeno? Use essa tag!</li>
        <pre>
            &lt;small&gt;<small>(Essa informação é bem pequenininha)</small>&lt;/small&gt;
        </pre>
    <li>&lt;strong&gt; Dá aquele destaque especial. </li>
        <pre>
            &lt;strong&gt;<strong>(IMPORTANTE)</strong>&lt;/strong&gt;
        </pre>
    <li>&lt;i&gt; Texto em itálico</li>
        <pre>
            &lt;i&gt;<i>Trecho em itálico</i>&lt;/i&gt;
        </pre>
    <li>&lt;u&gt; Texto sublinhado</li>
        <pre>
            &lt;u&gt;<u>Trecho sublinhado</u>&lt;/u&gt;
        </pre>
    <li>&lt;sup&gt; Texto sobrescrito.</li>
        <pre>
            &lt;sup&gt;<sup>Usado em expoentes</sup>&lt;/sup&gt;
        </pre>
    <li>&lt;sub&gt; Texto subescrito.</li>
        <pre>
            &lt;sub&gt;<sub>Usado em rodapés</sub>&lt;/sub&gt;
        </pre>
    <li>&lt;del&gt; Texto riscado, como se tivesse sido deletado.</li>
        <pre>
            &lt;del&gt;<del>Essa informação foi removida</del>&lt;/del&gt;
        </pre> 
    <li>&lt;font&gt; Muda o estilo do texto, como cor e tamanho.</li>
        <pre>
            <font color="red">&lt;font color = "red"> Esse trecho é vermelho</sub>&lt;/font&gt;</font>
        </pre>
    <li>&lt;hr&gt; Desenha uma linha pra separar as coisas. Tipo um divisor de capítulos. Essa tag não tem fechamento.</li>
        <pre>
            &lt;hr&gt;
        </pre>      
</ul>



<h2>Conclusão</h2>
<p>Essas são algumas das tags mais importantes que formam a base do HTML. Elas ajudam a estruturar o conteúdo de uma página e garantir que ela seja bem organizada e acessível. Claro, há muitas outras tags e atributos que você pode explorar, mas começar com essas é o primeiro passo para criar sites simples e funcionais.</p>
</body>
</html>
