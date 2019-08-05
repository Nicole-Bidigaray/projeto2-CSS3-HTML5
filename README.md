# projeto2-CSS3-HTML5
Projeto site TecBlog
<!DOCTYPE html>
<html lang="en">

<head>
    <title>TecBlog - O seu Blog de tecnologia</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="css/estilo.css" rel="stylesheet" type="text/css">
</head>

<body>

    <div id="area-cabecalho">

        <div id="area-logo">

            <h1>Tec<span class="branco">Blog</span></h1>

        </div>

        <div id="area-menu">
            <a href="index.html">Home</a>
            <a href="jogos.html">Jogos</a>
            <a href="celulares.html">Celulares</a>
            <a href="informatica.html">Informática</a>
            <a href="eletronicos.html">Eletrônicos</a>
        </div>

    </div>

    <div id="area-principal">

        <div id="area-postagens">

            <!-- abertura postagem -->
            <div class="postagem">

                <h2>Titulo da postagem 1</h2>
                <span class="data-postagem">postado 20 de março 2022</span>
                <img width="620px" src="imagens/imagem1.jpg">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sed augue nec nibh rutrum hendrerit. In elit lacus, ultrices id ultricies vel, elementum ut ante. Praesent sollicitudin arcu pharetra justo condimentum mattis sed ac quam. Maecenas placerat
                    mauris in sapien mattis, id tincidunt felis congue. Proin at fringilla ligula. Maecenas ultrices commodo elementum.
                </p>
                <a href="">Leia Mais</a>
            </div>
            <!--// fechamento postagem -->

            <!-- abertura postagem -->
            <div class="postagem">

                <h2>Titulo da postagem 2</h2>
                <span class="data-postagem">postado 10 de março 2022</span>
                <img width="620px" src="imagens/imagem2.jpg">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sed augue nec nibh rutrum hendrerit. In elit lacus, ultrices id ultricies vel, elementum ut ante. Praesent sollicitudin arcu pharetra justo condimentum mattis sed ac quam. Maecenas placerat
                    mauris in sapien mattis, id tincidunt felis congue. Proin at fringilla ligula. Maecenas ultrices commodo elementum.
                </p>
                <a href="">Leia Mais</a>
            </div>
            <!--// fechamento postagem -->
        </div>

        <div id="area-lateral">

            <div class="conteudo-lateral">
                <h3>Postagens recentes</h3>
                <div class="postagem-lateral">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <a href="">Leia mais</a>
                </div>

                <div class="postagem-lateral" style="border-bottom:none;">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <a href="">Leia mais</a>
                </div>
            </div>

            <div class="conteudo-lateral">
                <h3>Categorias</h3>

                <a href="">Jogos</a><br>
                <a href="">Celulares</a><br>
                <a href="">Informática</a><br>
                <a href="">Eletrônicos</a><br>
                <a href="">Jogos</a><br>

            </div>

        </div>

        <div id="rodape">Todos os direitos reservados</div>


</body>

</html>

/*Limpar formatações padrão*/

* {
    margin: 0;
    padding: 0;
}

body {
    font-size: 1em;
    font-family: "Trebuchet MS", Helvetica, sans-serif;
    background: #e6e6e6;
}


/*
**** Layout ****
*/

#area-cabecalho {
    background-color: #f7b600;
    padding: 15px;
    text-align: center;
}

#area-logo,
#area-menu {
    padding: 10px;
}

#area-principal {
    width: 920px;
    margin: 0 auto;
    padding: 15px;
}

#area-postagens {
    width: 660px;
    float: left;
}

#area-lateral {
    width: 240px;
    float: right;
}

.postagem {
    padding: 20px;
    margin-bottom: 20px;
    background: white;
}

.conteudo-lateral {
    background: white;
    padding: 10px;
    margin-bottom: 20px;
}

.postagem-lateral {
    font-size: 0.8em;
    padding: 5px;
    border-bottom: 1px dotted #CCC;
}

#rodape {
    clear: both;
    text-align: center;
    padding: 15px;
    background: #CCC;
}


/*
**** Formatação do menu ****
*/

a {
    text-decoration: none;
}

a:link,
a:visited {
    color: #f7b600;
}

a:hover {
    text-decoration: underline;
}

#area-cabecalho a:link,
#area-cabecalho a:visited {
    color: #FFF;
    padding: 8px 12px;
}

#area-cabecalho a:hover {
    color: #f7b600;
    background: #FFF;
    text-decoration: none;
}


/*
**** Formatações em geral ****
*/

h1 {
    color: #4e4e4e;
    font-size: 2.5em;
}

h2 {
    color: #f7b600;
}

h3 {
    color: #565656;
    background: #CCC;
    padding: 5px;
}

.branco {
    color: white;
}

.data-postagem {
    font-size: 0.8em;
    border-bottom: 1px solid #f4f4f4;
    padding-bottom: 10px;
    margin-bottom: 10px;
    display: block;
}
