# partefinal

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interestelar - Filme</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Interestelar - O Filme</h1>
    </header>
 
    <section id="conteudo">
        <div id="descricao">
            <p><strong>Interestelar</strong> é um épico de ficção científica dirigido por Christopher Nolan, lançado em 2014. O filme aborda temas como buracos de minhoca, viagens interdimensionais, e a sobrevivência da humanidade.</p>
            <p>Uma equipe de astronautas viaja através de um buraco de minhoca perto de Saturno em busca de um novo lar para a humanidade, que está à beira da extinção.</p>
        </div>
        
        <div id="imagem-filme">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Interstellar_2014_film_poster.jpg" alt="Pôster do filme Interestelar">
        </div>

        <button id="mostrar-mensagem">O que é uma viagem interdimensional?</button>
        <div id="mensagem" style="display:none;">
            <p>Uma viagem interdimensional refere-se à possibilidade de viajar para outra dimensão, que pode ser paralela ou diferente da nossa realidade. No filme, o conceito de buracos de minhoca é explorado como uma forma de realizar tais viagens.</p>
        </div>

        <div id="trailer">
            <button onclick="mostrarTrailer()">Assistir ao Trailer</button>
            <div id="video-trailer" style="display:none;">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/zSWdZVtXT7E" title="Trailer do filme Interestelar" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 - Todos os direitos reservados a <strong>Interestelar</strong> e Warner Bros.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html> 



