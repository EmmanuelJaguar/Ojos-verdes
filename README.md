# Ojos-verdes-
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ojos Verdes</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #6a82fb, #fc5c7d);
            font-family: 'Dancing Script', cursive;
            color: #333;
        }

        .book {
            position: relative;
            width: 350px;
            height: 500px;
            overflow: hidden;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .page {
            width: 100%;
            height: 100%;
            padding: 20px;
            box-sizing: border-box;
            position: absolute;
            top: 0;
            left: 0;
            display: none;
            text-align: center;
        }

        .page.active {
            display: block;
        }

        .arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            font-size: 30px;
            cursor: pointer;
            color: white;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 50%;
            user-select: none;
            transition: background 0.3s;
        }

        .arrow:hover {
            background: rgba(0, 0, 0, 0.8);
        }

        .arrow.left {
            left: 10px;
        }

        .arrow.right {
            right: 10px;
        }

        h1 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #444;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
            color: #555;
        }

        .poem {
            margin-top: 20px;
            font-size: 16px;
            line-height: 1.8;
            color: #666;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
</head>
<body>

    <div class="book">
        <!-- Página 1 (Manteniendo el poema original) -->
        <div class="page active">
            <h1>Ojos Verdes</h1>
            <p>Había una vez una chica con ojos verdes como esmeraldas...</p>
            <div class="poem">
                Verdes como el musgo en la piedra antigua,<br>
                tus ojos guardan historias que el tiempo enlía.<br>
                En su profundidad, el mundo se cobija,<br>
                y en su brillo, la vida se ilumina.<br>
                Son dos luceros que alumbran mi sendero,<br>
                con su fulgor, el camino es ligero.<br>
                En ellos habita un fuego que no cesa,<br>
                y en su mirada, el alma se confiesa.
            </div>
        </div>
        <!-- Página 2 -->
        <div class="page">
            <div class="poem">
                En sus pupilas, la aurora se esconde,<br>
                ríos de esmeralda cruzan su mirada.<br>
                Luz infinita, de magia bordada,<br>
                verde misterio que el alba responde.<br>
                Brilla en sus ojos un eco profundo,<br>
                como dos faros de inmenso reflejo.<br>
                Verde horizonte que al cielo dejó,<br>
                sueño que incendia y envuelve mi mundo.
            </div>
        </div>
        <!-- Página 3 -->
        <div class="page">
            <div class="poem">
                Ojos que guardan la calma del río,<br>
                verdes abismos de luz sin medida.<br>
                Llamas danzantes de un alma encendida,<br>
                brisa que aviva su dulce rocío.<br>
                Pétalos puros de fresca esperanza,<br>
                brillan en sombras, su manto es eterno.<br>
                Verde infinito, de hechizo sempiterno,<br>
                como la tierra que el viento abalanza.
            </div>
        </div>
        <!-- Página 4 -->
        <div class="page">
            <div class="poem">
                Brotan en ellos mil bosques dormidos,<br>
                brisas secretas de un alba divina.<br>
                Surco estrellado de luz cristalina,<br>
                verdes paisajes en cielos perdidos.<br>
                Danza en su iris la noche y el día,<br>
                ríos dorados que arrastran ensueños.<br>
                Verde susurro de mágicos sueños,<br>
                brilla en su fuego la eterna armonía.
            </div>
        </div>
        <!-- Página 5 -->
        <div class="page">
            <div class="poem">
                En su mirada la luna se enreda,<br>
                verde lucero que besa la brisa.<br>
                Brilla un encanto que nunca agoniza,<br>
                rayo de vida que el tiempo no queda.<br>
                Cantan sus ojos leyendas de oro,<br>
                claros espejos del alma profunda.<br>
                Verde misterio que el aire circunda,<br>
                fuego que arde sin miedo al azoro.
            </div>
        </div>
        <!-- Página 6 -->
        <div class="page">
            <div class="poem">
                Ojos que hechizan la noche callada,<br>
                verde fulgor que ilumina los mares.<br>
                Brisa que baila en eternos cantares,<br>
                luz que en la sombra jamás se apaga.<br>
                Dulce reflejo de estrellas dormidas,<br>
                guarda secretos de un cielo lejano.<br>
                Verde tormenta de un sueño temprano,<br>
                nacen en ellos las almas perdidas.
            </div>
        </div>
        <!-- Página 7 -->
        <div class="page">
            <div class="poem">
                Como dos perlas de un mar escondido,<br>
                brillan sus ojos en dulce armonía.<br>
                Luz que despierta con fresca alegría,<br>
                verdes paisajes que el viento ha encendido.<br>
                Cantan sus ojos historias de fuego,<br>
                faro infinito que guía senderos.<br>
                Verde relámpago, eterno viajero,<br>
                brilla en su danza sutil sin sosiego.
            </div>
        </div>
        <!-- Página 8 -->
        <div class="page">
            <div class="poem">
                En su mirada se enciende la aurora,<br>
                verde reflejo de campos dorados.<br>
                Rayos ocultos en cielos callados,<br>
                llama que arde, que nunca se ahoga.<br>
                Brillan sus ojos en dulce tormenta,<br>
                luz que hipnotiza con frágil destreza.<br>
                Verde misterio de oculta belleza,<br>
                rayo que al alba su magia sustenta.
            </div>
        </div>
        <!-- Página 9 -->
        <div class="page">
            <div class="poem">
                Ojos que gritan secretos del viento,<br>
                verde murmullo de un bosque encantado.<br>
                Brillo que danza en el agua reflejado,<br>
                dulce misterio de un cielo sediento.<br>
                Cantan estrellas en su fulgor puro,<br>
                verde infinito que nunca perece.<br>
                Sueño que arde, que nunca se ofrece,<br>
                rayo que besa con fuego seguro.
            </div>
        </div>
        <!-- Página 10 -->
        <div class="page">
            <div class="poem">
                Como un espejo de un valle dormido,<br>
                verde reflejo de historias perdidas.<br>
                Brisa de estrellas en sombras tejidas,<br>
                ríos secretos de un alba encendido.<br>
                Cantan sus ojos la luna escondida,<br>
                brisa que quiebra la voz de la tierra.<br>
                Verde susurro que el alma destierra,<br>
                danza de fuego, pasión encendida.
            </div>
        </div>
        <!-- Página 11 -->
        <div class="page">
            <div class="poem">
                Ojos que encienden la llama del cielo,<br>
                verde infinito de un mar escondido.<br>
                Fuego que danza con brillo encendido,<br>
                brisa que rompe la sombra en su vuelo.<br>
                Cantan sus ojos leyendas doradas,<br>
                luces que besan la piel de la aurora.<br>
                Verde destello que todo enamora,<br>
                brilla su encanto en noches calladas.
            </div>
        </div>
        <!-- Página 12 -->
        <div class="page">
            <div class="poem">
                Ojos de fuego, de un verde sublime,<br>
                brillan al alba como un astro eterno.<br>
                Sombra que danza con eco moderno,<br>
                luz que en mi mente su magia imprime.<br>
                Dulce reflejo de un cielo encantado,<br>
                cantan estrellas su luz infinita.<br>
                Verde murmullo que nunca marchita,<br>
                rayo que en sombras fulgor ha dejado.
            </div>
        </div>
        <!-- Página 13 -->
        <div class="page">
            <div class="poem">
                Verde misterio que al mundo hipnotiza,<br>
                ojos que encienden la brisa del día.<br>
                Ríos dorados que fluyen con vida,<br>
                luz que en la noche su esencia eterniza.<br>
                Brillan en ellos mil versos callados,<br>
                cantan los astros su eco divino.<br>
                Verde horizonte de un sueño genuino,<br>
                brilla en su danza un fuego sagrado.
            </div>
        </div>
        <!-- Página 14 -->
        <div class="page">
            <div class="poem">
                Como esmeraldas que el viento resguarda,<br>
                ojos que tiemblan en dulce reflejo.<br>
                Brillo que rompe la sombra y el viejo<br>
                tiempo en su danza la magia resguarda.<br>
                Dulce fulgor de un latido en la brisa,<br>
                verde profundo que al alma enamora.<br>
                Luz que al ocaso su encanto decora,<br>
                canta la aurora con eco de risa.
            </div>
        </div>
        <!-- Página 15 -->
        <div class="page">
            <div class="poem">
                Dos universos de luz infinita,<br>
                verde tesoro de un cielo callado.<br>
                Brillo que danza con fuego dorado,<br>
                luz que en mi alma su eco palpita.<br>
                Ríos de vida que surcan la nada,<br>
                ojos de un alba que nunca termina.<br>
                Verde reflejo de un sol que ilumina,<br>
                magia que en sombras la luna derrama.
            </div>
        </div>
        <!-- Página 16 -->
        <div class="page">
            <div class="poem">
                Ojos que guardan la paz de la aurora,<br>
                verde reflejo de un valle escondido.<br>
                Brillo que enciende la flor del olvido,<br>
                luz que en el aire su magia atesora.<br>
                Cantan sus iris con fuego sagrado,<br>
                ríos eternos de un sol infinito.<br>
                Verde latido que todo es bendito,<br>
                brilla su encanto en mi pecho sellado.
            </div>
        </div>
        <!-- Página 17 -->
        <div class="page">
            <div class="poem">
                Como relámpagos surgen sus ojos,<br>
                verdes abismos de un cielo estrellado.<br>
                Brillo que danza con eco dorado,<br>
                luz que al destino destierra cerrojos.<br>
                Dulce reflejo de un mar sin orillas,<br>
                ondas que al viento su fuego le entregan.<br>
                Verde latido que nunca doblegan,<br>
                sueño que en sombras la vida titila.
            </div>
        </div>
        <!-- Página 18 -->
        <div class="page">
            <div class="poem">
                Verde reflejo de un bosque en la luna,<br>
                ojos que atrapan la brisa callada.<br>
                Brillo que en sombras la vida desata,<br>
                luz que en el aire su esencia se acuna.<br>
                Cantan estrellas con dulce armonía,<br>
                ríos de fuego que nunca se apagan.<br>
                Verde infinito que todo embriaga,<br>
                sueño que en sombras la noche tejía.
            </div>
        </div>
        <!-- Página 19 -->
        <div class="page">
            <div class="poem">
                Dos esmeraldas de un alba dorada,<br>
                ojos que guardan la luz del invierno.<br>
                Brillo que danza con ritmo eterno,<br>
                fuego que el viento jamás apaga.<br>
                Dulce susurro que el tiempo detiene,<br>
                verde reflejo que todo cautiva.<br>
                Luz que en la sombra su encanto cultiva,<br>
                rayo que en mi alma su magia contiene.
            </div>
        </div>
        <!-- Página 20 -->
        <div class="page">
            <div class="poem">
                Ojos que encienden el sol al ocaso,<br>
                verdes abismos de un mundo lejano.<br>
                Brillo que en sombras se vuelve soberano,<br>
                luz que en mi pecho desata su lazo.<br>
                Cantan estrellas con brillo callado,<br>
                ríos que encienden la brisa del cielo.<br>
                Verde horizonte de un dulce anhelo,<br>
                sueño que en sombras su magia ha dejado.
            </div>
        </div>
        <!-- Página 21 -->
        <div class="page">
            <div class="poem">
                Esos ojos que endulzan con solo mirarlos,<br>
                destellos de vida, secretos callados.<br>
                Son ríos profundos, de verdes bordados,<br>
                que atrapan mi mundo sin yo desearlo.<br>
                Hipnotizan, hechizan, desatan la calma,<br>
                dos faros que queman con fuego sereno.<br>
                Los miro, y el tiempo se vuelve terreno,<br>
                su luz me desarma, me atrapa, me embalsama.
            </div>
        </div>
    </div>

    <div class="arrow left" onclick="changePage(-1)">&#10094;</div>
    <div class="arrow right" onclick="changePage(1)">&#10095;</div>

    <script>
        let currentPageIndex = 0;
        const pages = document.querySelectorAll('.page');
        const totalPages = pages.length;

        function changePage(direction) {
            // Ocultar la página actual
            pages[currentPageIndex].classList.remove('active');

            // Calcular la nueva página
            currentPageIndex += direction;

            // Asegurarse de que no se salga de los límites
            if (currentPageIndex < 0) {
                currentPageIndex = totalPages - 1;
            } else if (currentPageIndex >= totalPages) {
                currentPageIndex = 0;
            }

            // Mostrar la nueva página
            pages[currentPageIndex].classList.add('active');
        }
    </script>

</body>
</html>
