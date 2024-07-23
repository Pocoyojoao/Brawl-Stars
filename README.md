<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogo de Adivinhar o Número</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        input[type="number"] {
            padding: 10px;
            font-size: 16px;
            margin-top: 10px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin-top: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .message {
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Adivinhe o Número</h1>
        <p>Estou pensando em um número entre 1 e 100. Tente adivinhar!</p>
        <input type="number" id="guess" min="1" max="100">
        <button onclick="checkGuess()">Adivinhar</button>
        <div class="message" id="message"></div>
    </div>

    <script>
        // Gerar um número aleatório entre 1 e 100
        const randomNumber = Math.floor(Math.random() * 100) + 1;

        function checkGuess() {
            const userGuess = Number(document.getElementById('guess').value);
            const messageElement = document.getElementById('message');
            
            if (userGuess < 1 || userGuess > 100) {
                messageElement.textContent = 'Por favor, insira um número entre 1 e 100.';
            } else if (userGuess === randomNumber) {
                messageElement.textContent = 'Parabéns! Você acertou!';
            } else if (userGuess < randomNumber) {
                messageElement.textContent = 'O número é maior. Tente novamente!';
            } else {
                messageElement.textContent = 'O número é menor. Tente novamente!';
            }
        }
    </script>
</body>
</html># Brawl-Stars