<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aragón App - Descubre lo Mejor de Aragón</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Aragón App</h1>
        <p>Descubre los mejores lugares de Aragón</p>
        <button onclick="window.location.href='#contacto'">Contáctanos</button>
    </header>

    <section id="destacados">
        <h2>Lugares Destacados</h2>
        <div class="galeria">
            <div class="lugar">
                <img src="img/zaragoza.jpg" alt="Zaragoza">
                <h3>Zaragoza</h3>
                <p>Conoce la impresionante Basílica del Pilar y mucho más en la capital aragonesa.</p>
            </div>
            <div class="lugar">
                <img src="img/monasterio-piedra.jpg" alt="Monasterio de Piedra">
                <h3>Monasterio de Piedra</h3>
                <p>Un lugar mágico con cascadas y paisajes impresionantes.</p>
            </div>
            <div class="lugar">
                <img src="img/albarracin.jpg" alt="Albarracín">
                <h3>Albarracín</h3>
                <p>Un encantador pueblo medieval entre montañas.</p>
            </div>
        </div>
    </section>

    <section id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Aragón App es tu guía digital para descubrir los mejores destinos turísticos, gastronomía y actividades en Aragón. Disfruta de una experiencia personalizada y accede a recomendaciones locales en cualquier momento.</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Aragón App. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
