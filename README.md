<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фракталы</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 20px;
        }
        .fractal {
            text-align: center;
            width: 300px;
        }
        .fractal img {
            max-width: 100%;
            height: auto;
        }
        .description {
            font-size: 16px;
            color: #555;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <h1>Фракталы: Математические Искусства</h1>
    <p style="text-align:center; font-size: 18px;">Фракталы — это геометрические структуры, которые повторяются на разных масштабах и имеют самоподобие. Давайте посмотрим на несколько примеров фракталов!</p>
    
    <div class="container">
        <!-- Множество Мандельброта -->
        <div class="fractal">
            <h2>Множество Мандельброта</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Mandelbrot_set_%28simple%29.png" alt="Множество Мандельброта">
            <p class="description">Множество Мандельброта является одним из самых известных фракталов, с его самоподобной структурой на разных уровнях масштабирования.</p>
        </div>

        <!-- Фрактал Жюлиа -->
        <div class="fractal">
            <h2>Фрактал Жюлиа</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Julia_set_%28black_and_white%29.png" alt="Фрактал Жюлиа">
            <p class="description">Фрактал Жюлиа состоит из множества точек на комплексной плоскости, которые создают удивительные и бесконечно повторяющиеся узоры.</p>
        </div>

        <!-- Снежинка Коха -->
        <div class="fractal">
            <h2>Снежинка Коха</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/Koch_curve_iter_4.svg" alt="Снежинка Коха">
            <p class="description">Снежинка Коха — это фрактал, который создается путем повторяющегося добавления треугольников к каждой стороне исходного равностороннего треугольника.</p>
        </div>

        <!-- Треугольник Серпинского -->
        <div class="fractal">
            <h2>Треугольник Серпинского</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Sierpinski_triangle.svg" alt="Треугольник Серпинского">
            <p class="description">Треугольник Серпинского — это фрактал, образующийся путем удаления центральных треугольников из более крупных, повторяя процесс на каждом уровне.</p>
        </div>
    </div>

</body>
</html>
