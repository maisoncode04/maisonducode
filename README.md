<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maison du Code - Aprende a programar</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: #0a0a0a;
      color: #f1c40f;
    }

    header {
      text-align: center;
      padding: 2rem;
      background: #000000;
      background-image: url('https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      color: white;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      text-shadow: 2px 2px 5px #000;
    }

    .subtitulo {
      font-size: 1.3rem;
      margin-top: 0.5rem;
      text-shadow: 1px 1px 4px #000;
    }

    .contenido {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .seccion {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: space-between;
      margin-top: 2rem;
    }

    .tarjeta {
      flex: 1 1 45%;
      background: #111;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 0 10px #f1c40f33;
      color: white;
    }

    .tarjeta img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 1rem;
    }

    .tarjeta h2 {
      font-size: 1.6rem;
      margin-bottom: 0.8rem;
    }

    .tarjeta p {
      line-height: 1.6;
      font-size: 1rem;
    }

    .boton {
      display: inline-block;
      background: #f1c40f;
      color: #000;
      padding: 0.8rem 1.5rem;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      margin-top: 1rem;
      transition: 0.3s ease;
    }

    .boton:hover {
      background: #d4ac0d;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #ccc;
      font-size: 0.95rem;
    }

    .contacto {
      margin-top: 2rem;
      text-align: center;
      font-size: 1rem;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      box-shadow: 0 0 10px #00000080;
      text-decoration: none;
      font-size: 24px;
      z-index: 999;
    }

    .whatsapp:hover {
      background: #20b858;
    }
  </style>
</head>
<body>
  <header>
    <h1>MAISON DU CODE</h1>
    <div class="subtitulo">Aprende a programar como un experto, desde hoy.</div>
  </header>

  <div class="contenido">
    <p>Curso 100% online, en vivo y práctico. Desde nivel principiante hasta experto. Aprendé con apoyo personalizado y obtené experiencia real.</p>

    <div class="seccion">
      <div class="tarjeta">
        <img src="https://images.unsplash.com/photo-1581092919534-520aed937b7b?auto=format&fit=crop&w=800&q=80" alt="Curso Avanzado">
        <h2>Curso Avanzado</h2>
        <p>
          Enfocado en fundamentos sólidos y proyectos reales.<br>
          Cursos de 3 a 6 meses.<br>
          Certificado y acceso a oportunidades laborales.
        </p>
        <a class="boton" href="https://www.paypal.com/webapps/billing/plans/subscribe?plan_id=P-27Y27559LY955542HNAOBRGI" target="_blank">Inscribirme - $500</a>
      </div>

      <div class="tarjeta">
        <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=800&q=80" alt="Curso Experto">
        <h2>Curso Experto</h2>
        <p>
          Desarrollo profesional: backend, APIs, y proyectos avanzados.<br>
          Postulaciones a empresas y asesoría en propuestas laborales.<br>
          Acceso exclusivo a herramientas y red profesional.
        </p>
        <a class="boton" href="https://www.paypal.com/webapps/billing/plans/subscribe?plan_id=P-42W834552H3420805NAOBT2I" target="_blank">Inscribirme - $1000</a>
      </div>
    </div>

    <div class="contacto">
      ¿Problemas con el pago? Contáctanos al <a href="https://wa.me/50670386023" target="_blank">+506 7038 6023</a>
    </div>
  </div>

  <footer>
    Si te unes a los programas, te incluimos entre los que se actualizan constantemente.
  </footer>

  <a class="whatsapp" href="https://wa.me/50670386023" target="_blank" title="Contáctanos por WhatsApp">&#x1F4AC;</a>
</body>
</html>
