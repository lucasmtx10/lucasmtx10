### Boas vindas ao meu perfil 💙
index.html

     !DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Flashcard</title>
</head>
<body>
    <main>
        <section id="container">
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>Cirno</h3>
                    <div class="cartao__pergunta">
                        Qual é o poder/habilidade da Cirno?
                    </div>
                </div>
                <div class="cartao__resposta">
                    O poder da Cirno é criar gelo
                </div>
            </article>
            <article class="cartao">
                <div class="cartao__conteudo">
                    <h3>Sakuya</h3>
                    <div class="cartao__pergunta">
                        Qual é o poder/habilidade da Sakuya?
                    </div>
                </div>
                <div class="cartao__resposta">
                    O poder da Sakuya é atirar facas de gelo e parar o tempo
                </div>
            </article>
        </section>
    </main>
    <footer>
        <p>Touhou Saito, feito de fã pra fã, sem fins lucrativos</p>
    </footer>
</body>
</html>   




css.slyle

body {
    background-color: bisque;
    font-family: 'Bai Jamjuree', sans-serif;
    margin: 0;
    padding: 0;
}

footer {
    background-color: black;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
    text-align: center;
    padding: 10px 0;
    font-family: 'Bai Jamjuree', sans-serif;
}

footer p {
    margin: 0;
    font-size: 14px;
}
