<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Significado de la Obra</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self'">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #121212;
            color: #ffffff;
            padding: 50px;
            user-select: none;
        }
        .container {
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.2);
            max-width: 800px;
            margin: auto;
        }
        h1 {
            color: #00ffcc;
            font-size: 2em;
        }
        p {
            color: #cccccc;
            line-height: 1.8;
        }
    </style>
</head>
<body>
    <script>
        // Deshabilitar clic derecho
        document.addEventListener("contextmenu", event => event.preventDefault());
        
        // Prevenir atajos de teclado peligrosos
        document.addEventListener("keydown", function (event) {
            if (event.ctrlKey && (event.key === "u" || event.key === "s" || event.key === "i")) {
                event.preventDefault();
            }
        });
    </script>
    
    <div class="container">
        <h1>"Dificultad y Simplicidad"</h1>
        <p>Esta obra representa la comunicación humana en su forma más pura. Las técnicas espontáneas simbolizan la evolución del lenguaje, mientras que los símbolos ocultos reflejan la diversidad lingüística.</p>
        <p>Cada trazo es irrepetible, como las palabras que forman nuestra historia. Los materiales inusuales evocan la transformación del lenguaje a lo largo del tiempo.</p>
        <p>La obra invita a la reflexión sobre la conexión entre culturas y la belleza de la expresión humana.</p>
    </div>
</body>
</html>


