<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sala de Estar Moderna de Casa na Praia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .living-room {
            width: 19m;
            height: 19m;
            display: grid;
            grid-template-areas:
                "sofa sofa poltrona poltrona"
                "mesa-centro mesa-centro mesa-centro mesa-centro"
                "tapete tapete tapete tapete"
                "estante estante estante tv"
                "mesa-lateral mesa-lateral mesa-lateral mesa-lateral";
            gap: 10px;
            background-color: #ffffff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .sofa {
            grid-area: sofa;
            background-color: #fafafa;
            padding: 10px;
        }
        .poltrona {
            grid-area: poltrona;
            background-color: #e0ffff;
            padding: 10px;
        }
        .mesa-centro {
            grid-area: mesa-centro;
            background-color: #f5f5dc;
            padding: 10px;
        }
        .tapete {
            grid-area: tapete;
            background-color: #deb887;
            padding: 10px;
        }
        .estante {
            grid-area: estante;
            background-color: #d3d3d3;
            padding: 10px;
        }
        .tv {
            grid-area: tv;
            background-color: #000;
            padding: 10px;
            color: #fff;
            text-align: center;
        }
        .mesa-lateral {
            grid-area: mesa-lateral;
            background-color: #fafad2;
            padding: 10px;
        }
        .luminaria-chao {
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            background-color: #fffacd;
            padding: 10px;
        }
        .prateleiras {
            position: absolute;
            left: 20px;
            top: 10px;
            background-color: #add8e6;
            padding: 10px;
        }
        .plantas {
            position: absolute;
            left: 20px;
            bottom: 20px;
            background-color: #98fb98;
            padding: 10px;
        }
        .cortinas {
            position: absolute;
            right: 20px;
            bottom: 20px;
            background-color: #fff;
            padding: 10px;
        }
        .almofadas {
            position: absolute;
            right: 20px;
            bottom: 10px;
            background-color: #f5fffa;
            padding: 10px;
        }
        .pufes {
            position: absolute;
            left: 20px;
            top: 40px;
            background-color: #ffdead;
            padding: 10px;
        }
        .espelho {
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #eee;
            padding: 10px;
        }
        .cesto {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #d2b48c;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="living-room">
        <div class="sofa">Sofá Seccional</div>
        <div class="poltrona">Poltronas</div>
        <div class="mesa-centro">Mesa de Centro</div>
        <div class="tapete">Tapete</div>
        <div class="estante">Estante/Buffet</div>
        <div class="tv">TV</div>
        <div class="mesa-lateral">Mesa Lateral</div>
        <div class="luminaria-chao">Luminária de Chão</div>
        <div class="prateleiras">Prateleiras Flutuantes</div>
        <div class="plantas">Plantas</div>
        <div class="cortinas">Cortinas</div>
        <div class="almofadas">Almofadas Decorativas</div>
        <div class="pufes">Pufes/Ottomans</div>
        <div class="espelho">Espelho</div>
        <div class="cesto">Cesto de Vime</div>
    </div>
</body>
</html> 