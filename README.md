<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Amplificador de Guitarra</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Amplificador de Guitarra Simulado</h1>

        <button id="start-btn">Iniciar Microfone</button>

        <div class="controls">
            <label for="gain">Ganho: </label>
            <input type="range" id="gain" min="0" max="2" value="1" step="0.01">
            
            <label for="distortion">Distorção: </label>
            <input type="range" id="distortion" min="0" max="1000" value="0">
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
# digital-amp
um site que usa o microfone, tanto do proprio dispositivo, de um propiro microfone com fio ou sem fio ligado ao dispositivo móvel.
