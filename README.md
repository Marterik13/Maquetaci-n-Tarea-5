# Maquetacion-Tarea-5
Tarea 5 de Programación Web, Spa.
[index.html](https://github.com/user-attachments/files/23270836/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spa Salon - Promociones</title>
    <link rel="stylesheet" href="estilos.css">
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
</head>
<body>

    <div class="page-wrapper">
        
        <div class="top-pink-bar"></div>
        <div class="header-main">
            <div class="logo">
                <img src="imagenes/logocabecera.jpg" alt="Spa Salon Logo">
            </div>
            <div class="social-icons">
                <a href="#"><img src="imagenes/icono_facebook.jpg" alt="Facebook"></a>
                <a href="#"><img src="imagenes/icono_instagram.jpg" alt="Instagram"></a>
                <a href="#"><img src="imagenes/icono_twitter.jpg" alt="Twitter"></a>
            </div>
        </div>
        <div class="nav-container">
            <div class="nav-links">
                <a href="#">GALERÍA</a>
                <a href="#">PRECIOS</a>
                <a href="#">CONTÁCTANOS</a>
                <a href="#">EQUIPO</a>
            </div>
        </div>
        
        <div class="hero-section">
            <div class="hero-content">
                <h1>PROMOCIONES DE MARZO</h1>
                <p>Se acerca la época de playa y por eso preparamos estas dos promociones ideales para ti.</p>
                <div class="hero-buttons">
                    <a href="#form-section" id="btn-solicitar" class="btn btn-primary">Solicitar Promoción</a>
                    
                    <a href="#video-section" id="btn-ver-video" class="btn btn-secondary">Ver Video</a>
                </div>
            </div>
        </div>

        <div class="section science-section">
            <div class="container-content"> 
                <div class="two-column">
                    <div class="text-content">
                        <h2 class="section-subtitle">Los productos Science of Beauty</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vitae risus eget massa commodo finibus. Curabitur ut egestas sapien. Suspendisse potenti. Nullam sollicitudin, neque at facilisis ullamcorper, odio sem lacinia nibh, ac pulvinar nulla leo ut nisl. Fusce in imperdiet elit, sed egestas mi. Nulla facilisi. Aenean nec quam eget.</p>
                    </div>
                    <div class="image-content">
                        <img src="imagenes/fotovelas.jpg" alt="Productos de belleza">
                    </div>
                </div>
            </div>
        </div>
        
        <div class="section talent-section">
            <div class="container-content"> 
                
                <h2 class="section-title">Buscamos talento para integrarlos a nuestro equipo</h2>
                
                <div class="two-column">
                    <div class="image-content">
                        <img src="imagenes/fotoaromatizante.jpg" alt="Frascos de spa">
                    </div>
                    <div class="text-content jobs-list">
                        <h3>Puesto de trabajo para Recepcionista</h3>
                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
                        <h3>Puesto de trabajo para Masajista</h3>
                        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Aliquam erat volutpat.</p>
                        <h3>Puesto de trabajo para Nutriologo</h3>
                        <p>Nunc consequat interdum varius sit amet mattis. Risus commodo viverra maecenas accumsan lacus vel facilisis. Phasellus egestas tellus rutrum tellus pellentesque eu tincidunt. At erat pellentesque adipiscing commodo elit at imperdiet.</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="section footer-grid">
            <div class="container-content"> 
                <div class="two-column">
                    
                    <div class="form-content" id="form-section">
                        <h2 class="section-subtitle">Recibe noticias y promociones de SPA SALON</h2>
                        
                        <p class="subheading-form">Un lugar para consentirte de pies a cabeza<br>Servicio de salón estética y Spa personalizado</p>
                        
                        <p class="contact-info">
                            <span class="label-pink">TELEFONO:</span> 999 420 8871
                        </p>
                        <p class="contact-info">
                            <span class="label-pink">CORREO:</span> info@spasalon.com
                        </p>
                        
                        <form id="contact-form" novalidate>
                            <div class="form-group">
                                <label for="email-input">
                                    Tu dirección de correo electrónico
                                </label>
                                <input type="email" id="email-input" placeholder="* tunombre@example.com">
                                <span id="email-error" class="error-message"></span>
                            </div>
                            <button type="submit" class="btn btn-black btn-submit">Enviar</button>
                        </form>
                    </div>

                    <div class="video-content" id="video-section">
                        <h2 class="section-subtitle">Nuestras Instalaciones</h2>
                        
                        <div class="video-wrapper">
                            <iframe 
                                width="560" 
                                height="315" 
                                src="https://www.youtube.com/embed/w4qaODLR_Xg" 
                                title="YouTube video player" 
                                frameborder="0" 

                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="footer-bar">
            <div class="logo">
                <img src="imagenes/logo_spa.png" alt="Spa Salon Logo">
            </div>
            <div class="footer-credits">
                <p>Erik Gamaliel Poot Martín<br>Programación Web<br>7SA</p>
            </div>
        </div>

        <div class="top-pink-bar"></div>

    </div> <script src="script.js"></script>
</body>
</html>
