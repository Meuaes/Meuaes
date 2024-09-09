<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundación Benéfico-Docente</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Fundación Benéfico-Docente</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#mision">Misión y Visión</a></li>
                <li><a href="#programas">Programas</a></li>
                <li><a href="#ayudar">Cómo Ayudar</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>Bienvenidos a nuestra Fundación</h2>
        <p>Trabajamos para mejorar la educación y apoyar a los más necesitados a través de programas de formación.</p>
    </section>

    <section id="mision">
        <h2>Misión y Visión</h2>
        <p>Nuestra misión es fomentar el acceso a la educación de calidad. La visión es un mundo donde todos tengan las mismas oportunidades de aprender y crecer.</p>
    </section>

    <section id="programas">
        <h2>Nuestros Programas</h2>
        <ul>
            <li><strong>Programa 1:</strong> Alfabetización para adultos.</li>
            <li><strong>Programa 2:</strong> Capacitación para docentes.</li>
            <li><strong>Programa 3:</strong> Becas para estudiantes.</li>
        </ul>
    </section>

    <section id="ayudar">
        <h2>Cómo Ayudar</h2>
        <p>Puedes ayudar a nuestra causa con donaciones o siendo voluntario en nuestros programas.</p>
        <form action="https://www.paypal.com/donate" method="post" target="_blank">
            <label for="cantidad">Monto de Donación:</label>
            <input type="number" id="cantidad" name="cantidad" min="1" placeholder="Ingrese el monto">
            <button type="submit">Donar</button>
        </form>
        <button>Voluntariado</button>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Correo: info@fundacion.org</p>
        <p>Teléfono: +123 456 789</p>
        <h3>Redes Sociales</h3>
        <ul class="social">
            <li><a href="https://facebook.com" target="_blank">Facebook</a></li>
            <li><a href="https://twitter.com" target="_blank">Twitter</a></li>
            <li><a href="https://instagram.com" target="_blank">Instagram</a></li>
        </ul>
    </section>

    <footer>
        <p>© 2024 Fundación Benéfico-Docente</p>
    </footer>
</body>
</html>
