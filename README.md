<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Buggati</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #301414;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #000000;
            color: #c29fa1;
            padding: 15px;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .card {
            background-color: white;
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        img {
            width: 750px;
            border-radius: 8px;
        }

        a {
            color: #301414;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: red;
        }

        button {
            background-color: #301414;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #c29fa1;
        }

        footer {
            background-color: #000000;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>

</head>
<body>

<header>
    <h1>Variações da Buggati</h1>
    <p>Carro de luxo - Chiron & Veron</p>
</header>

<main>

    <div class="card">
        <h2>Sobre o aluno</h2>
        <p>Nome:Miguel, Luiz, Josué e Ana Luiza</p>
        <p>Turma:301</p>
        <p>Data: 25 / 02 / 2026</p>
    </div>

    <div class="card">
        <h2>Quais são as variaçoes?</h2>
        <ul>
            <li>Potência e desempenho do motor</li>
            <li>Velocidade máxima e aceleração</li>
            <li>Tecnologia e inovação mecânica</li>
            <li>Design e acabamento interno</li>
        </ul>
    </div>

    <div class="card">
<center>
        <h2>Buggati Chiron</h2>
        <img src="https://bugatti.imgix.net/677aa8b9531541bbada7c4e0/chiron-sport-og.jpg">
</center>
    </div>

<div class="card">
<center>
        <h2>Buggati Veron</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJyAPXqPqu5VBGzsVZPykRPWTQRw2agTEC6g&s">
</center>
    </div>

    <div class="card">
        <h2>Link de exemplo</h2>
        <p>
            <a href="https://www.youtube.com/watch?v=EIgoI5fiZHY">
                Abrir a comparação
            </a>
        </p>
    </div>

    <div class="card">
        <h2>Interação</h2>
        <button onclick="mostrarMensagem()">Clique aqui</button>
        <p id="mensagem"></p>
    </div>

</main>

<footer>
    Página criada no Laboratório Web
</footer>

<script>
    function mostrarMensagem() {
        document.getElementById("mensagem").innerHTML =
        "Obrigado por chegar até aqui. :D";
    }
</script>

</body>
</html>
