<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Presentación Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        .main {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
        }
        .main h1 {
            color: #333;
        }
        .main p {
            font-size: 18px;
            color: #666;
        }
        .footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Bienvenido a Mi Página de Presentación</h1>
            <nav>
                <ul>
                    <li><a href="#about">Sobre Mí</a></li>
                    <li><a href="#projects">Proyectos</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="main container">
        <h1 id="about">Sobre Mí</h1>
        <p>Hola, mi nombre es [Tu Nombre] y soy [Tu Profesión o Área de Estudio]. Tengo una pasión por [Tu Pasión o Interés].</p>
        
        <h1 id="projects">Proyectos</h1>
        <p>Aquí puedes ver algunos de los proyectos en los que he trabajado:</p>
        <ul>
            <li>Proyecto 1: Descripción breve del proyecto.</li>
            <li>Proyecto 2: Descripción breve del proyecto.</li>
            <li>Proyecto 3: Descripción breve del proyecto.</li>
        </ul>
        
        <h1 id="contact">Contacto</h1>
        <p>Si deseas ponerte en contacto conmigo, puedes enviarme un correo a: <a href="mailto:tuemail@ejemplo.com">tuemail@ejemplo.com</a></p>
    </section>
    <footer class="footer">
        <p>&copy; 2025 [Tu Nombre]. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
