
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GREEN SYNC - Mi Tienda</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@40400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', Arial, sans-serif; /* Changed font to Poppins */
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #8edc86; /* Slightly darker green for header */
            padding: 20px;
            text-align: center;
            color: #fff; /* White text for contrast */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }

        header h1 {
            color: #fff; /* Ensure h1 text is white */
            margin: 0; /* Remove default margin for h1 */
        }

        img {
            width: 200px;
            border-radius: 50%;
            aspect-ratio: 1;
            object-fit: cover;
        }

        .logo {
            width: 60px; /* Slightly larger logo */
            height: auto;
            margin-left: 15px;
            vertical-align: middle;

        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #b3ecc0; /* A bit lighter green for nav */
            padding: 10px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08); /* Subtle shadow */
        }

        nav a {
            margin: 0 20px; /* Increased spacing */
            text-decoration: none;
            color: #333;
            font-weight: 600; /* Bolder font weight */
            transition: color 0.3s ease; /* Smooth transition for hover */
        }

        nav a:hover {
            color: #5cb85c; /* Green on hover */
        }

        section {
            padding: 40px 20px; /* More vertical padding */
            max-width: 960px; /* Max width for content sections */
            margin: 0 auto; /* Center sections */
            background-color: #ffffff; /* White background for sections */
            margin-bottom: 20px; /* Space between sections */
            border-radius: 8px; /* Rounded corners for sections */
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05); /* Soft shadow for sections */
        }

        h2,
        h3 {
            color: #4CAF50; /* A nice green for headings */
            text-align: center; /* Center section titles */
            margin-bottom: 25px; /* Space below headings */
        }

        .product {
            border: 1px solid #e0e0e0; /* Lighter border */
            padding: 20px; /* More padding */
            margin: 15px; /* More margin */
            border-radius: 12px; /* More rounded corners */
            text-align: center;
            background-color: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08); /* Stronger shadow for products */
            transition: transform 0.3s ease; /* Hover effect */
            display: inline-block; /* For potential multiple products in a row */
            width: calc(50% - 30px); /* Adjust width for two products per row */
            vertical-align: top;
            box-sizing: border-box; /* Include padding and border in the element's total width and height */
        }

        .product:hover {
            transform: translateY(-5px); /* Lift effect on hover */
        }

        .product img {
            max-width: 80%; /* Ensure product images fit */
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .product button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 12px 25px;
            cursor: pointer;
            border-radius: 25px;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }

        .product button:hover {
            background-color: #45a049;
        }

        footer {
            background-color: #b3ecc0;
            text-align: center;
            padding: 20px;

            position: relative;
            width: 100%;
        }

        #carrito {
            background-color: #e8f5e9;
            padding: 25px;
            border: 1px solid #c8e6c9;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
        }

        #lista-carrito li {
            padding: 8px 0;
            border-bottom: 1px dashed #ddd;
            list-style-type: none;
        }

        #lista-carrito li:last-child {
            border-bottom: none;
        }

        @media (max-width: 768px) {
            .product {
                width: calc(100% - 30px);
            }
        }
    </style>
</head>

<body>
    <header>
        <div style="display: flex; align-items: center; justify-content: center;">
            <h1>GREEN SYNC</h1>
            <img src="nose.jpg" class="logo" alt="Green Sync Logo">
        </div>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#productos">Productos</a>
        <a href="#contacto">Contacto</a>
        <a href="#carrito">Carrito</a>
    </nav>

    <section id="inicio">
        <h2>Bienvenido a nuestra tienda</h2>
        <p>Hemos desarrollado una maceta inteligente capaz de regar automáticamente tus plantas, llevar un control de la
            temperatura en la que se encuentra y poseer luces UV, todo lo esencial para el cuidado de tus plantas.</p>
        <p>Nuestra maceta inteligente está equipada con sensores de humedad tanto en el suelo como en el ambiente, una
            bomba de agua para el riego de tus plantas, y luces UV, tecnología que ayuda a crecer tus plantas. Todo
            esto es controlado por Arduino Uno, programado para ayudarte con el cuidado de tus plantas e incluso
            cultivos.</p>
        <p>Adicionalmente, creamos una aplicación móvil para que puedas ver el monitoreo de tus plantas, para así
            conectarte con lo que más amas.</p>
        <p>Todo esto lo hemos desarrollado con un solo fin: ayudarte y cuidar lo que más amas.</p>
    </section>

    <section id="nosotros">
        <h2>Nosotros</h2>
        <h3>Visión</h3>
        <p>Ser un referente en la innovación de sistemas inteligentes de cuidado de plantas, utilizando tecnología
            avanzada para crear entornos óptimos y automatizados que mejoren la eficiencia en el cultivo y la
            jardinería, contribuyendo al crecimiento saludable y sostenible de las plantas.</p>
        <h3>Misión</h3>
        <p>Automatizar el cuidado de las plantas mediante el uso de sensores y actuadores, proporcionando un entorno
            controlado que garantice el monitoreo de la humedad, temperatura, riego y luz adecuada para optimizar el
            crecimiento y bienestar de las plantas.</p>
    </section>

    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="product">
            <h3>Maceta Inteligente</h3>
            <img src="002.jpg" alt="Maceta Inteligente Green Sync">
            <p>Q.350.00</p>
            <button onclick="agregarAlCarrito('Maceta Inteligente', 350)">Agregar al carrito</button>
        </div>

        <div class="product">
            <h3>Macetas</h3>
            <img src="003.jpg" alt="Macetas Tradicionales">
            <p>Q.65.00</p>
            <button onclick="agregarAlCarrito('Macetas Tradicionales', 75)">Agregar al carrito</button>
        </div>
    </section>

    <section id="carrito">
        <h2>Carrito de Compras</h2>
        <ul id="lista-carrito"></ul>
        <p><strong>Total:</strong> Q<span id="total">0</span></p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Escríbenos a: <a href="mailto:GreenSync@gmail.com"
                style="color: #4CAF50; text-decoration: none;">GreenSync@gmail.com</a></p>
        <p>Síguenos en redes sociales:</p>
        <p>
            <a href="https://www.facebook.com/share/19BwK5Vm8S/?mibextid=wwXIfr" target="_blank"
                style="color: #3b5998; text-decoration: none; margin-right: 15px;">Facebook</a>
            <a href="https://www.instagram.com/greensync_/profilecard/?igsh=MTYxcnR6ZXNpNDZrZw==" target="_blank"
                style="color: #e4405f; text-decoration: none;">Instagram</a>
        </p>
    </section>

    <footer>
        <p>&copy; 2025 GREEN SYNC - Mi Tienda Verde. Todos los derechos reservados.</p>
    </footer>

    <script>
        let total = 0;

        function agregarAlCarrito(producto, precio) {
            const lista = document.getElementById('lista-carrito');
            const item = document.createElement('li');
            item.textContent = `${producto} - Q${precio}`;
            lista.appendChild(item);
            total += precio;
            document.getElementById('total').textContent = total;
        }
    </script>
</body>

</html>
