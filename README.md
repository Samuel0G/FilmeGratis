<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sites Filmes Gratis</title>
    <link rel="stylesheet" href="estilosFilmes.css">
</head>
<body>
    <header>
        <h1>Filmes Gratis Online</h1>
    </header>
    <header>
        <nav>
            <ul>
                <li class="menu-item"><a href="#home">Home</a></li>
                <li class="menu-item"><a href="#cadastro">Cadastro</a></li>
                <li class="menu-item"><a href="#relatorios">Relatórios</a></li>
                <li class="menu-item"><a href="#grid">Grid</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="filme">
            <img src="imagem_filme1.jpg" alt="Filme 1">
            <h2>Filme 1</h2>
            <p>Descrição do Filme 1.</p>
            <a href="link_para_o_filme1.mp4" target="_blank">Assistir</a>
        </section>
        <section class="filme">
            <img src="imagem_filme2.jpg" alt="Filme 2">
            <h2>Filme 2</h2>
            <p>Descrição do Filme 2.</p>
            <a href="link_para_o_filme2.mp4" target="_blank">Assistir</a>
        </section>
        
    </main>
    <footer>
        <p>&copy; 2023 Meu Site de Filmes</p>
    </footer>
</body>
</html>


</css>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

h1 {
    margin: 0;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.filme {
    margin-bottom: 20px;
}

.filme img {
    max-width: 100%;
    height: auto;
}

.filme h2 {
    margin: 10px 0;
}

.filme p {
    margin: 0;
}

.filme a {
    display: block;
    text-align: center;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    padding: 10px 0;
    border-radius: 5px;
}

.filme a:hover {
    background-color: #555;
}
/* Estilize o menu para exibir os itens lado a lado */
.menu-item {
    display: inline-block;
    margin-right: 10px;  
}


.menu-item a {
    text-decoration: none;
    background-color: #333;
    color: #fff;
    padding: 5px 10px;
    border-radius: 5px;
}

.menu-item a:hover {
    background-color: #555;
}
</css>
