# Fitness-<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Portal Profesional | Publicidad y Contenido</title>
    <style>
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: var(--light); color: var(--dark); }
        header { background: var(--primary); color: white; padding: 1rem; text-align: center; }
        nav { display: flex; justify-content: center; gap: 20px; background: white; padding: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .container { max-width: 1000px; margin: 20px auto; padding: 0 20px; }
        
        /* Sección de Venta de Publicidad */
        .ad-sales { background: white; padding: 30px; border-radius: 10px; border: 2px solid var(--primary); margin-bottom: 40px; }
        .pricing-table { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px; }
        .price-card { border: 1px solid #ddd; padding: 20px; text-align: center; border-radius: 8px; transition: 0.3s; }
        .price-card:hover { transform: translateY(-5px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .btn-buy { background: var(--primary); color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 10px; }
        
        /* Estructura del Blog */
        .articles { display: grid; grid-template-columns: 2fr 1fr; gap: 20px; }
        article { background: white; padding: 20px; border-radius: 8px; margin-bottom: 20px; }
        .sidebar { background: #e2e8f0; padding: 20px; border-radius: 8px; height: fit-content; }
    </style>
</head>
<body>

<header>
    <h1>Portal de Innovación y Deporte</h1>
    <p>Impulsando el futuro del rendimiento y la gestión</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#articulos">Artículos</a>
    <a href="#anunciate">Anúnciate aquí</a>
</nav>

<div class="container">
    <section id="anunciate" class="ad-sales">
        <h2>Impulsa tu Marca con Nosotros</h2>
        <p>Llega a una audiencia segmentada interesada en tecnología, deporte y gestión profesional.</p>
        
        <div class="pricing-table">
            <div class="price-card">
                <h3>Banner Lateral</h3>
                <p>Visibilidad mensual en todos los artículos.</p>
                <div style="font-size: 24px; font-weight: bold; margin: 10px 0;">$XX.00</div>
                <a href="https://wa.me/tu-numero" class="btn-buy">Contactar Ventas</a>
            </div>
            <div class="price-card">
                <h3>Artículo Patrocinado</h3>
                <p>Reseña completa de tu producto o servicio.</p>
                <div style="font-size: 24px; font-weight: bold; margin: 10px 0;">$XX.00</div>
                <a href="#" class="btn-buy">Ver Requisitos</a>
            </div>
        </div>
    </section>

    <div class="articles">
        <main id="articulos">
            <article>
                <h2>Optimización Tecnológica en el Deporte</h2>
                <p>Explora cómo la inteligencia artificial está cambiando las reglas del juego en la administración de clubes...</p>
                <small>Publicado hace 2 días</small>
            </article>
            <article>
                <h2>Tendencias en Gestión de Centros Deportivos</h2>
                <p>Las claves para una administración eficiente y digitalizada en 2026.</p>
                <small>Publicado hace 5 días</small>
            </article>
        </main>

        <aside class="sidebar">
            <h3>Espacio Publicitario</h3>
            <div style="width:100%; height:250px; background:#ccc; display:flex; align-items:center; justify-content:center;">
                300 x 250 (Tu anuncio aquí)
            </div>
        </aside>
    </div>
</div>

</body>
</html>
