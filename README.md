# Bom-dia-pra-mais-mais-<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bom dia gatinha 😏</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }

        .page {
            display: none;
            width: 100vw;
            height: 100vh;
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 20px;
            animation: fadeIn 0.5s ease-in;
        }

        .page.active {
            display: flex;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .content {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            max-width: 600px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .content h1 {
            font-size: 24px;
            color: #d946ef;
            margin-bottom: 30px;
            line-height: 1.6;
        }

        .btn {
            padding: 15px 30px;
            font-size: 16px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            background: linear-gradient(135deg, #d946ef, #ec4899);
            color: white;
            font-weight: bold;
            box-shadow: 0 4px 15px rgba(217, 70, 239, 0.4);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(217, 70, 239, 0.6);
        }
    </style>
</head>
<body>
    <!-- PÁGINA 1 -->
    <div class="page active">
        <div class="content">
            <h1>Bom dia gatinha 😏</h1>
            <div class="buttons-container">
                <button class="btn" onclick="nextPage()">Bom dia</button>
                <button class="btn" onclick="nextPage()">Nada ver</button>
            </div>
        </div>
    </div>

    <!-- PÁGINA 2, 3, 4, 5... -->
    <!-- (Código similar para as outras páginas) -->

    <script>
        let currentPage = 1;
        const totalPages = 5;

        function nextPage() {
            // Lógica para mudar de página
        }
    </script>
</body>
</html>