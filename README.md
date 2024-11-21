
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú de Navegación</title>
    <style>
        .menu {
            background-color: #66CCFF;
            overflow: hidden;
        }

        .menu ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .menu li {
            float: left;
        }

        .menu li a {
            display: block;
            color: black;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        .menu li a:hover {
            background-color: #59CCDD;  
        }

        .menu li ul {
            display: none;
        }

        .menu li:hover ul {
            display: block;
        }
    </style>
</head>
<body>
    <nav class="menu">
        <ul>
            <li><a href="https://www.google.com.mx/?hl=es-419">Inicio</a></li>
            <li>
                <a href="#">Servicios</a>
                <ul>
                    <a href="https://www.facebook.com/">Redes sociale</a>
                    <a href="https://www.instagram.com/">Marketing</a>
                    <a href="https://www.youtube.com/">Medios Visuales</a>
                </ul>
            </li>
            <li><a href="https://www.google.com.mx/maps/preview">Ubicación</a></li>
            <li><a href="https://outlook.office.com/mail/">Contacto</a></li>
        </ul>
    </nav>
</body>
</html>
