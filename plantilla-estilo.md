AÑADIR ESTE ENCABEZADO PARA NO GUARDAR CACHÉ

<meta charset="utf-8">
    <!-- Forzar al navegador a no guardar en caché la página HTML -->
    <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

    <title>La Visión del Cordero ante el Trono</title>

ESTILO COLORES PASTELES

<!-- Reveal.js CSS CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.5.0/reveal.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.5.0/theme/serif.min.css" id="theme">

    <!-- Fonts Google -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Marcellus&family=Plus+Jakarta+Sans:ital,wght@0,300;0,400;0,600;1,400&display=swap" rel="stylesheet">

    <style>
        :root {
            --bg-color: #FDFBF7;
            --text-color: #2D3748;
            --accent-sage: #8A9A86;
            --accent-terracotta: #D98A6C;
            --accent-sand: #E2D4C9;
            --card-bg: rgba(255, 255, 255, 0.75);
            --card-border: #E0D7CD;
        }

        body {
            background-color: var(--bg-color);
        }

        .reveal {
            font-family: 'Plus Jakarta Sans', sans-serif;
            color: var(--text-color);
        }

        .reveal h1, .reveal h2, .reveal h3, .reveal h4 {
            font-family: 'Marcellus', serif;
            color: #1A202C;
            text-transform: none;
            letter-spacing: 0.02em;
        }

        .reveal h1 { font-size: 2.2em; color: var(--accent-terracotta); }
        .reveal h2 { font-size: 1.6em; color: var(--accent-sage); border-bottom: 2px solid var(--accent-sand); padding-bottom: 10px; }

        /* Tarjetas con Paleta Pastel */
        .card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 16px;
            padding: 25px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.03);
            backdrop-filter: blur(5px);
            margin-top: 15px;
        }

        .quote-box {
            background-color: #F4EFEA;
            border-left: 5px solid var(--accent-terracotta);
            padding: 20px;
            border-radius: 8px;
            font-style: italic;
            text-align: left;
            margin: 15px 0;
            font-size: 0.9em;
            line-height: 1.5;
        }

        .hebrew-text {
            font-family: 'Marcellus', serif;
            color: var(--accent-terracotta);
            font-weight: bold;
            font-size: 1.1em;
        }

        /* Gradación Visual */
        .progression-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin-top: 30px;
        }

        .progression-step {
            background: #EBF1EA;
            border: 1px solid #C8D6C5;
            border-radius: 12px;
            padding: 15px 20px;
            width: 20%;
            text-align: center;
            font-weight: 600;
        }

        .arrow {
            font-size: 1.5em;
            color: var(--accent-terracotta);
        }

        /* Responsive Columns */
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            text-align: left;
        }

        .grid-3col {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 15px;
            text-align: left;
            font-size: 0.85em;
        }

        ul {
            line-height: 1.6;
        }

        li {
            margin-bottom: 10px;
        }

        .highlight {
            color: var(--accent-terracotta);
            font-weight: 600;
        }

        /* Footer / Subtítulo */
        .subtitle {
            font-size: 0.6em;
            opacity: 0.7;
            margin-top: 10px;
        }
    </style>

ESTILO OSCURO CON DORADO

<style>
        /* Paleta de Colores y Estilo Oscuro Coherente */
        :root {
            --bg-dark: #121212;
            --text-light: #e0e0e0;
            --gold: #d4af37;
            --gold-light: #f3e5ab;
            --card-bg: rgba(255, 255, 255, 0.05);
            --card-border: rgba(212, 175, 55, 0.3);
        }

        body {
            background-color: var(--bg-dark);
            font-family: 'Inter', sans-serif;
            color: var(--text-light);
        }

        /* Fondo general oscuro con gradiente sutil para la presentación */
        .reveal-viewport {
            background: radial-gradient(circle at center, #1e1e1e 0%, #121212 100%) !important;
        }

        .reveal .controls {
            color: var(--gold);
        }

        .reveal h1, .reveal h2, .reveal h3, .reveal h4 {
            font-family: 'Cinzel', serif !important;
            color: var(--gold) !important;
            text-transform: uppercase !important;
            letter-spacing: 1px;
        }

        .reveal h1 { font-size: 2.8em; text-shadow: 0 0 10px rgba(212,175,55,0.3); }
        .reveal h2 {
            font-size: 2.3em;
            border-bottom: 1px solid var(--card-border);
            padding-bottom: 8px;
            margin-bottom: 18px;
        }

        /* Tarjetas de Contenido */
        .content-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 4px 25px rgba(0,0,0,0.6);
            text-align: left;
            margin: 0 auto;
            max-width: 900px;
        }

        /* Tamaño de fuente reducido idéntico al estilo oscuro (0.8em / 0.85em) */
        .reveal p, .reveal li {
            font-size: 1.4em;
            line-height: 1.5;
            color: var(--text-light);
        }

        .reveal ul {
            list-style: none;
            padding-left: 0;
            margin: 0;
        }

        .reveal ul li {
            position: relative;
            padding-left: 25px;
            margin-bottom: 12px;
        }

        .reveal ul li::before {
            content: "—";
            color: var(--gold);
            font-weight: bold;
            position: absolute;
            left: 0;
            top: 0px;
        }

        /* Versículos y Destacados */
        .bible-verse {
            background: rgba(212, 175, 55, 0.08);
            border-left: 4px solid var(--gold);
            padding: 15px 18px;
            border-radius: 0 8px 8px 0;
            font-style: italic;
            color: var(--gold-light);
            margin-bottom: 18px;
            font-size: 1.0em;
        }

        .scripture-ref {
            font-size: 1.0em;
            font-weight: 600;
            color: var(--gold);
            text-transform: uppercase;
            letter-spacing: 1px;
            display: block;
            margin-bottom: 6px;
        }

        /* Grid layout para diapositivas comparativas */
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .grid-card {
            background: var(--card-bg);
            border-radius: 8px;
            padding: 18px;
            border: 1px solid var(--card-border);
        }

        /* Pregunta Reflexiva */
        .reflection-box {
            background: rgba(212, 175, 55, 0.08);
            border: 1px dashed var(--gold);
            border-radius: 8px;
            padding: 18px;
            text-align: center;
            margin-top: 18px;
        }

        /* Logo Fijo en la marca de agua (Footer) */
        #persistent-logo {
            position: fixed;
            bottom: 24px;
            right: 32px;
            width: 45px;
            height: 45px;
            z-index: 99;
            opacity: 0.55;
            transition: opacity 0.3s ease;
            pointer-events: none;
            filter: drop-shadow(0 0 5px rgba(212,175,55,0.3));
        }

        #persistent-logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
    </style>

AÑADIR ESTO PARA CAMBIAR EL COLOR DE LAS FLECHAS DE NAVEGACION

  .reveal .controls {
            color: var(--gold);
        }