!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>En Busca del Hongo Olvidado</title>
    <style>
        /* Estilos CSS */
        body {
            background-color: #F5F0E9; /* Fondo beige desgastado */
            font-family: 'Arial', sans-serif; /* Fuente legible */
            color: #4A4A4A; /* Gris oscuro para texto */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2E4A2B; /* Verde oscuro para el encabezado */
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1 {
            font-family: 'Courier New', monospace; /* Fuente tipo máquina de escribir */
            margin: 0;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: #8B5A2B; /* Marrón terroso */
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline; /* Subrayado al pasar el ratón */
        }
        .banner {
            background-image: url('https://via.placeholder.com/800x200/4A4A4A/FFFFFF?text=San+Tadeo+lluvioso'); /* Imagen ficticia */
            background-size: cover;
            padding: 50px;
            text-align: center;
            color: white;
            font-size: 24px;
            text-shadow: 2px 2px 4px #000;
        }
        .section {
            margin: 20px;
            padding: 15px;
            background-color: white;
            border: 1px solid #8B5A2B; /* Borde marrón */
        }
        h2 {
            color: #2E4A2B; /* Verde oscuro para títulos */
        }
        .testimonio {
            background-color: #E8ECEF; /* Gris claro */
            padding: 10px;
            margin: 10px 0;
            border-left: 4px solid #2E4A2B;
        }
        .teoria {
            background-color: #2E4A2B;
            color: white;
            padding: 10px;
            margin: 5px 0;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        input, textarea, button {
            padding: 8px;
            font-size: 16px;
        }
        button {
            background-color: #8B5A2B;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #6B3E1F;
        }
        footer {
            background-color: #4A4A4A;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <h1>En Busca del Hongo Olvidado</h1>
        <p>Un blog del Dr. Javier Morales - Investigando lo que San Tadeo no puede recordar</p>
        <nav>
            <a href="#inicio">Inicio</a> | 
            <a href="#entradas">Entradas</a> | 
            <a href="#testimonios">Testimonios</a> | 
            <a href="#teorias">Teorías</a> | 
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <!-- Banner -->
    <div class="banner" id="inicio">
        ¿Qué olvidaste hoy?
    </div>

    <!-- Entradas -->
    <div class="section" id="entradas">
        <h2>Entradas del Blog</h2>
        <div class="post">
            <h3>El Comienzo de una Obsesión</h3>
            <p>Mi nombre es Javier Morales, médico en San Tadeo. Hace unas semanas, un hombre ingresó al hospital tras un incidente menor...</p>
            <a href="#">Leer más</a>
        </div>
        <div class="post">
            <h3>El Hongo que Borra Recuerdos</h3>
            <p>He bautizado a este hongo como Cladosporium memorium. Parece liberar una sustancia que interfiere con la memoria...</p>
            <a href="#">Leer más</a>
        </div>
        <!-- Añade más entradas aquí copiando este formato -->
    </div>

    <!-- Testimonios -->
    <div class="section" id="testimonios">
        <h2>Voces de San Tadeo</h2>
        <div class="testimonio">
            <p><strong>José Ramírez:</strong> "Cuando era niño, mis amigos tocaron a un chico raro en la escuela. Uno quedó en trance, el otro no recordaba nada."</p>
        </div>
        <div class="testimonio">
            <p><strong>Giuliana:</strong> "La maestra Marina trajo a un niño nuevo en una tormenta. Le pregunté su nombre, pero ella no respondió."</p>
        </div>
    </div>

    <!-- Teorías -->
    <div class="section" id="teorias">
        <h2>Hipótesis en Progreso</h2>
        <div class="teoria">El hongo podría activarse con humedad (tormentas).</div>
        <div class="teoria">San Tadeo es un foco: ¿clima, suelo, o algo más?</div>
        <div class="teoria">Portadores inmunes podrían ser parte de una línea generacional.</div>
    </div>

    <!-- Contacto -->
    <div class="section" id="contacto">
        <h2>Únete a la Búsqueda</h2>
        <p>Si has visto algo extraño en San Tadeo, compártelo aquí:</p>
        <form>
            <input type="text" placeholder="Nombre (opcional)">
            <input type="email" placeholder="Correo (opcional)">
            <textarea placeholder="Tu historia" rows="5"></textarea>
            <button type="submit">Enviar pista</button>
        </form>
    </div>

    <!-- Pie de página -->
    <footer>
        <p>© Dr. Javier Morales - San Tadeo. La verdad está en lo que olvidamos.</p>
    </footer>
</body>
</html>
