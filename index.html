<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cápsula Digital: El Guardián del Tesoro</title>
    <style>
        /* Estilos Globales - Estilo Hacker */
        body {
            margin: 0;
            padding: 0;
            background-color: #050505;
            background-image: radial-gradient(circle, #111 1px, transparent 1px);
            background-size: 30px 30px; /* Fondo de rejilla sutil */
            color: #00f3ff; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            height: 100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* El Guardián (Seguimiento suave) */
        #guardian {
            position: fixed;
            width: 100px;
            pointer-events: none; /* No bloquea los clics */
            z-index: 100;
            filter: drop-shadow(0 0 15px #00f3ff);
            will-change: transform;
        }

        /* Contenedor del Cofre */
        #escenario {
            text-align: center;
            z-index: 10;
        }

        #cofre {
            width: 180px;
            cursor: pointer;
            transition: all 0.3s ease;
            filter: drop-shadow(0 0 5px #ff00ff);
        }

        #cofre:hover {
            transform: scale(1.1) rotate(5deg);
            filter: drop-shadow(0 0 25px #ff00ff);
        }

        h2 {
            text-transform: uppercase;
            letter-spacing: 5px;
            text-shadow: 0 0 10px #00f3ff;
            margin-top: 20px;
            font-size: 1.2rem;
        }

        /* Ventana Emergente (Modal) */
        #modal-tesoro {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.95);
            z-index: 1000;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(10px);
        }

        .contenido-modal {
            background: #000;
            padding: 30px;
            border: 2px solid #00f3ff;
            box-shadow: 0 0 40px #00f3ff;
            border-radius: 20px;
            text-align: center;
            max-width: 400px;
        }

        .contenido-modal h1 {
            color: #fff;
            text-shadow: 0 0 10px #00f3ff;
            margin-bottom: 5px;
        }

        .contenido-modal p {
            color: #00f3ff;
            font-weight: bold;
            margin-bottom: 20px;
        }

        #tesoro-gif {
            width: 100%;
            border-radius: 10px;
            border: 1px solid #ff00ff;
        }

        .btn-cerrar {
            margin-top: 20px;
            padding: 10px 25px;
            background: transparent;
            color: #ff00ff;
            border: 1px solid #ff00ff;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-cerrar:hover {
            background: #ff00ff;
            color: white;
            box-shadow: 0 0 20px #ff00ff;
        }
    </style>
</head>
<body>

    <img src="guardian.png" id="guardian" alt="Guardián">

    <div id="escenario">
        <img src="cofre.png" id="cofre" alt="Cofre Mágico" onclick="mostrarSecreto()">
        <h2>Sistema Protegido</h2>
    </div>

    <div id="modal-tesoro">
        <div class="contenido-modal">
            <h1>¡ACCESO CONCEDIDO!</h1>
            <p>Bienvenido, Max</p>
            <img src="tesoro.gif" id="tesoro-gif" alt="Tesoro Encontrado">
            <br>
            <button class="btn-cerrar" onclick="cerrarModal()">BLOQUEAR DE NUEVO</button>
        </div>
    </div>

    <script>
        const guardian = document.getElementById('guardian');
        const modal = document.getElementById('modal-tesoro');
        
        // Variables para el movimiento fluido (Lerp)
        let mouseX = 0;
        let mouseY = 0;
        let currentX = 0;
        let currentY = 0;

        // Actualizar coordenadas del mouse
        document.addEventListener('mousemove', (e) => {
            mouseX = e.clientX;
            mouseY = e.clientY;
        });

        // Función de animación para el guardián
        function animarGuardian() {
            // El guardián se acerca al mouse un 10% de la distancia restante cada frame
            currentX += (mouseX - currentX) * 0.1;
            currentY += (mouseY - currentY) * 0.1;

            // Ajustamos para que el centro del guardián esté en el cursor
            guardian.style.transform = `translate(${currentX - 50}px, ${currentY - 50}px)`;
            
            requestAnimationFrame(animarGuardian);
        }

        // Iniciar animación
        animarGuardian();

        // Funciones de interacción
        function mostrarSecreto() {
            modal.style.display = 'flex';
        }

        function cerrarModal() {
            modal.style.display = 'none';
        }
    </script>
</body>
</html>
