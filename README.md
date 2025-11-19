# AISLANDOFUTRO-
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Aislando Futuro - Lana de Oveja Sustentable y Capacitación</title>
<style>
  /* Reset base */
  body {
    margin: 0;
    padding: 0;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    background-color: #f9faf7;
    color: #2a3a10;
    line-height: 1.7;
    font-size: 1.1em;
  }
  a {
    color: #4a7531;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  header {
    background: linear-gradient(90deg, #538832 0%, #2f4f17 100%);
    color: #fafef8;
    text-align: center;
    padding: 80px 20px 60px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.3);
  }
  header h1 {
    font-size: 3.6rem;
    margin: 0.2rem 0;
    font-weight: 900;
    letter-spacing: 1.2rem;
  }
  header p {
    margin: 0;
    font-style: italic;
    font-weight: 600;
    font-size: 1.4rem;
    letter-spacing: 0.12rem;
  }
  nav {
    background-color: #3d5c18;
    padding: 18px;
    display: flex;
    justify-content: center;
    gap: 30px;
    font-weight: 700;
    font-size: 1.1rem;
    flex-wrap: wrap;
    box-shadow: inset 0 -3px 3px rgba(0,0,0,0.25);
  }
  nav a {
    padding: 10px 18px;
    border-radius: 8px;
    color: #d7e3bf;
    transition: background-color 0.3s ease;
  }
  nav a.active, nav a:hover {
    background-color: #538832;
    color: #fff;
  }
  main {
    width: 90%;
    max-width: 1300px;
    margin: 50px auto 70px;
    background: #fffefa;
    padding: 55px 70px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(47, 90, 12, 0.25);
  }
  h2 {
    font-size: 2.8rem;
    font-weight: 900;
    margin-bottom: 35px;
    color: #467426;
    border-bottom: 6px solid #6ea02e;
    padding-bottom: 12px;
  }
  h3 {
    font-size: 1.8rem;
    font-weight: 700;
    margin-bottom: 18px;
    color: #3e6d16;
  }
  p.lead {
    font-size: 1.35rem;
    font-weight: 600;
    margin-bottom: 20px;
    color: #50782e;
  }
  section {
    margin-bottom: 85px;
  }
  .clearfix::after {
    content: "";
    display: table;
    clear: both;
  }
  img.content-img {
    max-width: 100%;
    height: auto;
    border-radius: 20px;
    box-shadow: 3px 3px 12px rgba(0,0,0,0.18);
    object-fit: cover;
  }
  .img-left {
    float: left;
    width: 40%;
    margin-right: 40px;
    margin-bottom: 25px;
  }
  .img-right {
    float: right;
    width: 40%;
    margin-left: 40px;
    margin-bottom: 25px;
  }
  ul {
    font-weight: 600;
    list-style-position: inside;
    max-width: 900px;
    color: #3f6611;
  }
  ul li {
    margin-bottom: 13px;
    font-size: 1.1rem;
  }
  .product-info {
    background-color: #e8f1d9;
    border-left: 8px solid #69982d;
    padding: 22px 30px;
    margin-bottom: 30px;
    border-radius: 15px;
    box-shadow: 0 3px 12px rgba(105, 152, 45, 0.3);
  }
  .product-info strong {
    color: #557d1f;
  }
  .benefits-list {
    column-count: 1;
    max-width: 850px;
    padding-left: 0;
    margin-bottom: 45px;
  }
  .benefits-list li {
    list-style: none;
    position: relative;
    padding-left: 30px;
    margin-bottom: 18px;
  }
  .benefits-list li::before {
    content: '✔';
    position: absolute;
    left: 0;
    color: #4caf50;
    font-weight: 700;
  }
  .course-list li {
    border-radius: 15px;
    background-color: #daf2a6;
    padding: 22px 30px;
    margin-bottom: 20px;
    box-shadow: 0 4px 15px rgba(110, 160, 46, 0.3);
    font-weight: 700;
    font-size: 1.1rem;
  }
  .testimonial-list li {
    background: #dbeeaa;
    padding: 25px;
    border-radius: 20px;
    margin-bottom: 25px;
    font-weight: 700;
    box-shadow: 0 3px 18px rgba(97, 133, 53, 0.32);
  }
  blockquote {
    margin-left: 0;
    font-style: italic;
    color: #4a7028;
    border-left: 6px solid #6eaa32;
    padding-left: 20px;
  }
  form {
    max-width: 600px;
    margin: 0 auto;
    background: #dbf2a8;
    padding: 30px 35px;
    border-radius: 20px;
    box-shadow: 0 6px 22px rgba(98, 136, 49, 0.4);
  }
  form label {
    display: block;
    font-weight: 800;
    margin: 20px 0 7px 0;
    color: #466817;
    font-size: 1.1rem;
  }
  form input, form textarea, form select {
    width: 100%;
    padding: 13px 18px;
    font-size: 1.1rem;
    border: 2.5px solid #69982d;
    border-radius: 12px;
    resize: vertical;
    box-sizing: border-box;
  }
  form textarea { height: 110px; }
  form button {
    margin-top: 25px;
    background-color: #53882d;
    color: white;
    font-weight: 900;
    font-size: 1.3rem;
    padding: 14px 38px;
    border: none;
    border-radius: 15px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  form button:hover {
    background-color: #7d9f39;
  }
  footer {
    background-color: #3a5c17;
    color: #e7f0c9;
    text-align: center;
    padding: 30px 10px;
    font-size: 1rem;
    letter-spacing: 0.1rem;
    font-weight: 600;
    border-top: 5px solid #599a2f;
    box-shadow: 0 -8px 22px rgba(86, 128, 29, 0.72);
  }
  footer p {
    margin: 8px 0;
  }
  @media (max-width: 1080px) {
    header h1 {
      font-size: 2.8rem;
      letter-spacing: 1rem;
    }
    nav {
      gap: 15px;
      font-size: 1rem;
      padding: 14px;
    }
    .img-left, .img-right {
      float: none !important;
      margin: 0 auto 30px;
      width: 85% !important;
      display: block;
    }
    main {
      padding: 40px 30px;
    }
    .benefits-list {
      column-count: 1;
    }
  }
  @media (max-width: 480px) {
    header h1 {
      font-size: 2.2rem;
      letter-spacing: 0.9rem;
    }
    nav {
      font-size: 0.9rem;
    }
    main {
      padding: 30px 20px;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Aislando Futuro</h1>
  <p>Soluciones sustentables con lana de oveja y capacitación técnica especializada</p>
</header>

<nav>
  <a href="#sobre-nosotros" class="active">Sobre Nosotros</a>
  <a href="#productos">Productos</a>
  <a href="#capacitaciones">Capacitaciones</a>
  <a href="#beneficios">Beneficios</a>
  <a href="#equipo">Equipo</a>
  <a href="#proyectos">Proyectos</a>
  <a href="#testimonios">Testimonios</a>
  <a href="#blog">Blog</a>
  <a href="#preguntas">Preguntas Frecuentes</a>
  <a href="#reseñas">Reseñas</a>
  <a href="#contacto">Contacto</a>
</nav>

<main>

<section id="sobre-nosotros" class="clearfix">
  <h2>Sobre Nosotros</h2>
  <img src="https://images.unsplash.com/photo-1516912482297-5c21ab2e3b03?auto=format&fit=crop&w=600&q=80" alt="Lana de oveja natural" class="img-right content-img" />
  <p class="lead">
    En <strong>Aislando Futuro</strong>, somos pioneros en la comercialización y asesoría de lana de oveja 100% natural, sustentable y certificada por Laboratorio IDIEM. Nuestro compromiso es promover prácticas constructivas que reduzcan la huella ambiental y optimicen el confort térmico de las viviendas y edificios.
  </p>
  <p>
    Nuestra lana de oveja destaca por la alta conductividad térmica (0,046 W/mK°), resistencia al fuego, capacidad termorreguladora y un proceso productivo con mínima emisión de CO2, lo que la convierte en una alternativa superior frente a aislantes sintéticos tradicionales.
  </p>
  <p>
    No solo entregamos un producto con certificaciones de calidad, sino que también ofrecemos capacitaciones especializadas y acompañamiento continuo para que nuestros clientes maximicen los beneficios y la eficiencia energética en sus proyectos.
  </p>
</section>

<section id="productos" class="clearfix">
  <h2>Productos</h2>
  
  <article class="product-info clearfix">
    <h3>Rollo aislante térmico sustentable</h3>
    <img src="https://images.unsplash.com/photo-1486308510493-cb558a7fb7f0?auto=format&fit=crop&w=600&q=80" alt="Rollo de lana de oveja aislante" class="img-left content-img" />
    <p>
      <strong>Precio:</strong> $10.000 + IVA por metro cuadrado<br>
      <strong>Dimensiones:</strong> 2,40 x 0,60 metros<br>
      <strong>Conductividad térmica:</strong> 0,046 W/mK°<br>
      <strong>Certificación:</strong> Producto certificado por Laboratorio IDIEM<br>
      <strong>Composición:</strong> 100% lana de oveja natural de alta pureza.<br>
      <strong>Instalación:</strong> Fácil y rápida para techos y muros, compatible con sistemas constructivos modernos.<br>
    </p>
    <h4>Características técnicas y beneficios:</h4>
    <ul class="benefits-list">
      <li>Reducción del consumo energético entre 50% a 65% al aislar térmicamente </li>
      <li>Producto ignífugo; no inflamable, previniendo intoxicación por humo tóxico</li>
      <li>Bajo gasto energético y baja emisión de CO2 durante su producción</li>
      <li>Espesor estándar de 50 mm, conforme a normativas ambientales vigentes</li>
      <li>Aislamiento termorregulado que controla la humedad y mantiene ambientes saludables</li>
      <li>Duración ilimitada, garantizando vida útil prolongada a la edificación</li>
    </ul>
  </article>
  
  <article class="product-info clearfix">
    <h3>Lana de oveja a granel</h3>
    <img src="https://images.unsplash.com/photo-1514432324607-a09d9fca96de?auto=format&fit=crop&w=600&q=80" alt="Lana de oveja a granel" class="img-right content-img" />
    <p>
      <strong>Precio:</strong> $9.000 + IVA por kilo.<br>
      Ideal para proyectos especiales y grandes superficies que requieren aislamiento térmico ecológico a medida.<br>
      Producto natural, certificado, ignífugo y con excelente capacidad de aislamiento acústico y térmico.
    </p>
    <p>Compatible con sistemas de relleno sostenible y nuevas tecnologías constructivas para edificaciones verdes.</p>
  </article>
  
  <article>
    <h3>Accesorios para instalación</h3>
    <p>
      Disponemos de complementos exclusivos: cintas adhesivas biodegradables, fijadores naturales y sellantes ecológicos diseñados para optimizar la hermeticidad y durabilidad del aislamiento con lana de oveja.
    </p>
  </article>
</section>

<section id="capacitaciones">
  <h2>Capacitaciones</h2>
  <p class="lead">
    Nuestra oferta formativa está orientada a entregar conocimientos técnicos y prácticos para aprovechar al máximo las propiedades de la lana de oveja, garantizando instalaciones de alta calidad y eficientes.
  </p>
  <ul class="course-list">
    <li><strong>Curso Introducción a la lana de oveja:</strong> Propiedades físicas, térmicas y beneficios ambientales del material. Duración: 5 horas (modalidad online y presencial).</li>
    <li><strong>Curso Técnicas de instalación básica:</strong> Preparación, herramientas y procedimientos estándar para aislamiento térmico eficiente. Duración: 7 horas presenciales.</li>
    <li><strong>Curso Avanzado de instalación profesional:</strong> Control de calidad, soluciones para ambientes complejos, normativas y protocolos de seguridad. 12 horas, incluye práctica certificada.</li>
    <li><strong>Seminario de innovación en aislantes ecológicos:</strong> Últimas tendencias en materiales sustentables y cómo integrarlos efectivamente con la lana de oveja. Modalidad webinar, 3 horas.</li>
    <li><strong>Curso para instructores certificados:</strong> Formación para impartir capacitaciones, evaluación y certificación oficial exclusiva para profesionales.</li>
    <li><strong>Taller completo Construcción sostenible:</strong> Caso práctico, diseño y ejecución con lana de oveja para proyectos que buscan certificaciones verdes tipo LEED y otras. 2 días intensivos.</li>
  </ul>
  <h3>Beneficios de participar en nuestras capacitaciones</h3>
  <ul class="benefits-list">
    <li>Material didáctico de última generación y acceso digital permanente</li>
    <li>Certificación oficial reconocida nacionalmente</li>
    <li>Acceso a asesoría exclusiva post-curso para implementación de proyectos</li>
    <li>Descuentos en compra de productos para asistentes</li>
    <li>Networking con profesionales del sector de construcción sustentable</li>
  </ul>
</section>

<section id="beneficios">
  <h2>Beneficios al ser Cliente</h2>
  <p>
    Contar con Aislando Futuro como socio significa mucho más que comprar lana de oveja. Disfruta beneficios exclusivos que optimizan tu inversión, mejoran tu experiencia y aseguran calidad permanente.
  </p>
  <ul class="benefits-list">
    <li><strong>15% descuento</strong> en Sodimac en productos relacionados con aislamiento y construcción.</li>
    <li>Acceso gratuito a todas nuestras capacitaciones y talleres técnicos.</li>
    <li>Asesoría técnica y comercial personalizada en todo momento.</li>
    <li>Acceso privilegiado a lanzamientos y novedades del sector sustentable.</li>
    <li>Garantía extendida hasta 10 años en todos los productos adquiridos.</li>
    <li>Material educativo continuo para profesionales y técnicos.</li>
    <li>Bonos y promociones exclusivas en eventos y campañas especiales.</li>
    <li>Apoyo prioritario postventa para optimizar resultados.</li>
  </ul>
</section>

<section id="equipo" class="clearfix">
  <h2>Nuestro Equipo</h2>
  <p>
    Un conjunto de expertos multidisciplinarios dedicados a construir futuro sustentable a través de innovación, conocimiento y compromiso.
  </p>
  <div style="display:flex; flex-wrap: wrap; gap:50px; justify-content: center; margin-top: 30px;">
    <div style="flex: 1 1 280px; text-align: center;">
      <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=300&q=80" alt="Paz Osorio, Ingeniera Civil" style="border-radius: 15px; width: 100%; box-shadow: 0 6px 20px rgba(55, 87, 22, 0.3);" />
      <h3>Juan Pérez</h3>
      <p>Ingeniero Civil – Director Técnico</p>
    </div>
    <div style="flex: 1 1 280px; text-align: center;">
      <img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91?auto=format&fit=crop&w=300&q=80" alt="Amara Canteros, Coordinadora" style="border-radius: 15px; width: 100%; box-shadow: 0 6px 20px rgba(55, 87, 22, 0.3);" />
      <h3>María López</h3>
      <p>Coordinadora de Capacitaciones</p>
    </div>
    <div style="flex: 1 1 280px; text-align: center;">
      <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=300&q=80" alt="Alejandro Cáceres, Asesor Comercial" style="border-radius: 15px; width: 100%; box-shadow: 0 6px 20px rgba(55, 87, 22, 0.3);" />
      <h3>Pedro Álvarez</h3>
      <p>Asesor Comercial y Postventa</p>
    </div>
  </div>
</section>

<section id="proyectos">
  <h2>Proyectos Destacados</h2>
  <div style="margin-top: 25px;">
    <h3>Condominio Ecológico "Verde Vivo" - Temuco</h3>
    <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="Condominio Verde Vivo" class="content-img" />
    <p>
      Instalación completa de rollos de lana de oveja en 45 viviendas logrando reducción del consumo energético superior al 60%, ambientes más confortables y reducción en uso de sistemas de calefacción.
    </p>
  </div>
  <div style="margin-top: 40px;">
    <h3>Escuela Sostenible "Alma Verde" - Valdivia</h3>
    <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=600&q=80" alt="Escuela Alma Verde" class="content-img" />
    <p>
      Proyecto conjunto con municipalidad para aislar aulas con lana de oveja, mejorando confort térmico y acústico para más de 600 estudiantes, además capacitación del personal con nuestros cursos especializados.
    </p>
  </div>
</section>

<section id="testimonios">
  <h2>Testimonios</h2>
  <ul class="testimonial-list">
    <li>
      "La calidad y asesoría de Aislando Futuro superaron nuestras expectativas. Altamente recomendado." – <strong>Bastián López.</strong>
    </li>
    <li>
      "Gracias a sus capacitaciones logré instalar el aislante correctamente y reducir costos energéticos notoriamente." – <strong>Aylin Pincheira.</strong>
    </li>
    <li>
      "Un producto con durabilidad y eficacia comprobada que junto a su asesoría, hace la diferencia." – <strong>Corporación Edificios Verdes</strong>
    </li>
  </ul>
</section>

<section id="blog">
  <h2>Blog y Noticias</h2>
  <article>
    <h3>¿Por qué elegir materiales naturales en construcción?</h3>
    <p>Los materiales naturales como la lana de oveja ofrecen beneficios ambientales y de salud que los sintéticos no alcanzan.</p>
    <a href="#" class="btn-primary" aria-label="Leer más sobre materiales naturales">Leer Más</a>
  </article>
  <article>
    <h3>Nuevas normativas ambientales y su impacto en aislantes</h3>
    <p>Conoce las normativas actuales y cómo nuestra lana de oveja cumple para contribuir a construcciones verdes.</p>
    <a href="#" class="btn-primary" aria-label="Leer más sobre normativas ambientales">Leer Más</a>
  </article>
  <article>
    <h3>Capacitación: clave para proyectos sustentables exitosos</h3>
    <p>La formación es esencial para garantizar la eficiencia y durabilidad de los aislantes naturales.</p>
    <a href="#" class="btn-primary" aria-label="Leer más sobre capacitación para proyectos">Leer Más</a>
  </article>
</section>

<section id="preguntas">
  <h2>Preguntas Frecuentes</h2>
  <ul class="course-list">
    <li><strong>¿La lana de oveja resiste humedad?</strong><br> No es impermeable pero regula eficazmente la humedad manteniendo el aislamiento y previniendo daños.</li>
    <li><strong>¿En qué se diferencia la lana de oveja de otros aislantes?</strong><br> Es un material renovable, ignífugo, termorregulador y con un proceso de producción de baja huella ambiental.</li>
    <li><strong>¿Puedo usarla para renovar viviendas existentes?</strong><br> Sí, ofrecemos soluciones técnicas para aislamiento retroactivo y eficiente.</li>
    <li><strong>¿Los cursos son online o presenciales?</strong><br> Brindamos ambas modalidades para adaptarnos a necesidades.</li>
    <li><strong>¿Son necesarias herramientas especiales para instalarla?</strong><br> No, la instalación es sencilla y la capacitación explica todas las técnicas y herramientas.</li>
  </ul>
</section>

<section id="reseñas">
  <h2>Reseñas de Clientes</h2>
  <p>Valoramos tu experiencia. Cuéntanos cómo Aislando Futuro ha impactado tus proyectos y expectativas.</p>
  <div class="reseñas-container">
    <ul id="lista-reseñas" class="reseñas-lista" aria-live="polite" aria-relevant="additions">
      <!-- Reseñas se agregan aquí -->
    </ul>
    <form id="form-reseñas" onsubmit="return agregarReseña(event)" aria-label="Formulario para dejar reseña">
      <label for="autor">Nombre</label>
      <input aria-required="true" type="text" id="autor" name="autor" placeholder="Tu nombre" required minlength="3" />
      <label for="emailR">Correo electrónico (no será publicado)</label>
      <input aria-required="true" type="email" id="emailR" name="emailR" placeholder="ejemplo@correo.com" required />
      <label for="rating">Calificación</label>
      <select aria-required="true" id="rating" name="rating" required>
        <option value="" disabled selected>Selecciona</option>
        <option value="5">★★★★★ Excelente</option>
        <option value="4">★★★★ Muy bueno</option>
        <option value="3">★★★ Bueno</option>
        <option value="2">★★ Regular</option>
        <option value="1">★ Malo</option>
      </select>
      <label for="comentario">Comentario</label>
      <textarea aria-required="true" id="comentario" name="comentario" placeholder="Escribe tu reseña aquí" required minlength="15" rows="5"></textarea>
      <button type="submit">Enviar Reseña</button>
    </form>
  </div>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>Estamos aquí para ayudarte y asesorarte en cada paso. Contáctanos para cotizaciones, preguntas o agendar capacitaciones técnicas.</p>
  <p style="font-weight: 900; font-size: 1.4rem; margin: 20px 0;">📞 Teléfono / WhatsApp:
  <a href="tel:+56928963880" style="color:#3e6e11;">+56 9 2896 3880</a></p>
  <p style="font-weight: 900; font-size: 1.3rem; margin: 20px 0;">✉️ Email: <a href="mailto:contacto@aislandofuturo.com" style="color:#3e6e11;">contacto@aislandofuturo.com</a></p>

  <form id="contactForm" onsubmit="return validarFormulario()" style="max-width:700px; margin: 40px auto;">
    <label for="nombreC">Nombre completo</label>
    <input type="text" id="nombreC" name="nombreC" placeholder="Tu nombre completo" required minlength="3" />
    <label for="emailC" style="margin-top:20px;">Correo electrónico</label>
    <input type="email" id="emailC" name="emailC" placeholder="ejemplo@correo.com" required />
    <label for="telefonoC" style="margin-top:20px;">Teléfono (opcional)</label>
    <input type="tel" id="telefonoC" name="telefonoC" placeholder="+56 9 1234 5678" />
    <label for="mensajeC" style="margin-top:20px;">Mensaje</label>
    <textarea id="mensajeC" name="mensajeC" rows="6" placeholder="Escribe tu consulta aquí" required minlength="15"></textarea>
    <button type="submit">Enviar Mensaje</button>
  </form>
</section>

</main>

<footer>
  <p>© 2025 Aislando Futuro - Todos los derechos reservados</p>
  <p>Contacto: <a href="mailto:contacto@aislandofuturo.com" style="color:#bdd79c;">contacto@aislandofuturo.com</a> | <a href="tel:+56928963880" style="color:#bdd79c;">+56 9 2896 3880</a></p>
  <p>Desarrollado con compromiso ambiental y profesionalismo</p>
</footer>

<script>
  // Validaciones formulario contacto
  function validarFormulario() {
    const nombre = document.getElementById('nombreC').value.trim();
    const email = document.getElementById('emailC').value.trim();
    const mensaje = document.getElementById('mensajeC').value.trim();
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

    if (nombre.length < 3) {
      alert('Ingresa un nombre válido (mínimo 3 caracteres).');
      document.getElementById('nombreC').focus();
      return false;
    }
    if (!emailRegex.test(email)) {
      alert('Ingresa un correo electrónico válido.');
      document.getElementById('emailC').focus();
      return false;
    }
    if (mensaje.length < 15) {
      alert('El mensaje debe tener al menos 15 caracteres.');
      document.getElementById('mensajeC').focus();
      return false;
    }
    alert('Mensaje enviado correctamente, nos pondremos en contacto pronto.');
    return true;
  }

  // Función para agregar reseña a la lista (simulación solo en el navegador)
  const listaResenas = document.getElementById('lista-reseñas');
  const formResenas = document.getElementById('form-reseñas');

  function agregarReseña(event) {
    event.preventDefault();
    const autor = document.getElementById('autor').value.trim();
    const emailR = document.getElementById('emailR').value.trim();
    const rating = document.getElementById('rating').value;
    const comentario = document.getElementById('comentario').value.trim();

    if (autor.length < 3 || !emailR || !rating || comentario.length < 15) {
      alert('Por favor, completa todos los campos correctamente (comentario min 15 caracteres).');
      return false;
    }

    const estrellas = '★'.repeat(rating) + '☆'.repeat(5 - rating);

    const nuevoComentario = document.createElement('li');
    nuevoComentario.innerHTML = `<div aria-label="Calificación de ${rating} estrellas" style="color: #c9b233; font-size: 1.3em;">${estrellas}</div>
                                <div class="reseña-autor" style="font-weight:bold; color: #3e6e11;">${autor}</div>
                                <p style="margin-top: 5px;">${comentario}</p>`;

    listaResenas.insertBefore(nuevoComentario, listaResenas.firstChild);
    formResenas.reset();
    alert('Gracias por tu reseña, ha sido agregada con éxito.');
    return true;
  }
</script>

</body>
</html>
