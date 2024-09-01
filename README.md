<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site do Jurado de Batalha de Rima</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .header img {
            max-width: 150px;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .section {
            padding: 20px;
            background-color: #fff;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #222;
        }
        .points-table {
            width: 100%;
            border-collapse: collapse;
        }
        .points-table th, .points-table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }
        .points-table th {
            background-color: #f4f4f4;
        }
        .pros-list {
            list-style-type: none;
            padding: 0;
        }
        .pros-list li {
            padding: 5px 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="logo-familia-de-rua.png" alt="Logo Família de Rua">
        <h1>Juramento de Batalha de Rima</h1>
    </div>
    <div class="container">
        <div class="section" id="pontuacao">
            <h2>Pontuação</h2>
            <table class="points-table">
                <thead>
                    <tr>
                        <th>Bloco</th>
                        <th>Descrição</th>
                        <th>Nota Máxima</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Bloco 1</td>
                        <td>Performance</td>
                        <td>10</td>
                    </tr>
                    <tr>
                        <td>Bloco 2</td>
                        <td>Creatividade</td>
                        <td>10</td>
                    </tr>
                    <tr>
                        <td>Bloco 3</td>
                        <td>Originalidade</td>
                        <td>10</td>
                    </tr>
                    <tr>
                        <td>Bloco 4</td>
                        <td>Técnica</td>
                        <td>10</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="section" id="pros">
            <h2>Prós</h2>
            <ul class="pros-list">
                <li>Experiência em diversas batalhas de rima.</li>
                <li>Conhecimento profundo das técnicas de freestyle.</li>
                <li>Imparcialidade e justiça na avaliação.</li>
                <li>Capacidade de fornecer feedback construtivo.</li>
            </ul>
        </div>
    </div>
</body>
</html>
