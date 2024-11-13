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

body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: white;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    padding: 20px;
    text-align: center;
}

h1 {
    margin: 0;
}

#conteudo {
    padding: 20px;
}

#descricao {
    font-size: 1.2em;
    margin-bottom: 20px;
}

#imagem-filme {
    text-align: center;
}

#imagem-filme img {
    width: 100%;
    max-width: 500px;
}

button {
    background-color: #0066cc;
    color: white;
    font-size: 1.1em;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    margin: 10px 0;
}

button:hover {
    background-color: #004d99;
}

footer {
    background-color: #333;
    padding: 10px;
    text-align: center;
    color: #ccc;
}


// Função que exibe uma mensagem sobre viagens interdimensionais
document.getElementById('mostrar-mensagem').addEventListener('click', function() {
    const mensagemDiv = document.getElementById('mensagem');
    if (mensagemDiv.style.display === 'none') {
        mensagemDiv.style.display = 'block';
    } else {
        mensagemDiv.style.display = 'none';
    }
});

// Função que exibe o trailer do filme
function mostrarTrailer() {
    const videoDiv = document.getElementById('video-trailer');
    if (videoDiv.style.display === 'none') {
        videoDiv.style.display = 'block';
    } else {
        videoDiv.style.display = 'none';
    }
}


