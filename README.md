<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TECNOMODO | Equipos Biomédicos</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primario: #0077cc;
      --secundario: #00c896;
      --acento: #f04e30;
      --fondo: #f8f9fb;
      --oscuro: #1a1a1a;
      --claro: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      background: var(--fondo);
      color: var(--oscuro);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, var(--primario), var(--secundario));
      color: #fff;
      text-align: center;
      padding: 3rem 1rem;
      animation: fadeInDown 1.2s ease-out;
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .logo {
      width: 100px;
      margin-bottom: 1rem;
    }

    nav {
      background: #fff;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
      animation: fadeIn 1.5s ease-out;
    }

    nav a {
      text-decoration: none;
      color: var(--primario);
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--acento);
    }

    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: 2rem auto;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      opacity: 0;
      transform: translateY(30px);
      animation: sectionFade 0.8s ease-out forwards;
    }

    section:hover {
      transform: scale(1.01);
      transition: transform 0.3s ease-in-out;
    }

    @keyframes sectionFade {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      border-left: 5px solid var(--primario);
      padding-left: 0.5rem;
      margin-bottom: 1rem;
      color: var(--primario);
    }

    ul, ol {
      padding-left: 1.5rem;
    }

    ul li, ol li {
      margin-bottom: 0.5rem;
    }

    footer {
      background: var(--oscuro);
      color: #ccc;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
      animation: fadeInUp 1.5s ease-out;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .tagline {
      font-style: italic;
      color: #e0f7fa;
    }

    @media (max-width: 768px) {
      nav {
        flex-wrap: wrap;
      }

      section {
        padding: 2rem 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="img/logo.png" alt="Logo TECNOMODO" class="logo" />
    <h1>TECNOMODO</h1>
    <p class="tagline">Tecnología • Muestras • Organismos • Doping</p>
  </header>

  <nav>
    <a href="#equipo">Equipo</a>
    <a href="#mision">Misión</a>
    <a href="#vision">Visión</a>
    <a href="#objetivos">Objetivos</a>
    <a href="#inventario">Inventario</a>
    <a href="#cronograma">Cronograma</a>
  </nav>

  <section id="equipo">
    <h2>Grupo Corporativo</h2>
    <p>Somos un equipo multidisciplinario comprometido con la innovación en tecnología biomédica:</p>
    <ul>
      <li>Edna Gabriela Albarracín</li>
      <li>Deisy Lorena Díaz</li>
      <li>Johan Ricardo Novoa</li>
      <li>Mariana Valentina Muñoz</li>
      <li>Angely Dayanna Camargo</li>
      <li>Ernesto Alejandro Soto</li>
      <li>Miguel Ángel Cierra</li>
      <li>Allison Gabriela Ramírez</li>
    </ul>
  </section>

  <section id="mision">
    <h2>Misión</h2>
    <p>Innovar con la implementación de tecnologías biomédicas que mejoren el diagnóstico y tratamiento de los pacientes, asegurando prácticas seguras, eficientes y normativamente responsables.</p>
  </section>

  <section id="vision">
    <h2>Visión</h2>
    <p>Ser líderes en el mercado colombiano y latinoamericano en soluciones biomédicas, reconocidos por la excelencia, calidad tecnológica, ética profesional y la satisfacción de nuestros clientes.</p>
  </section>

  <section id="objetivos">
    <h2>Objetivos Corporativos</h2>
    <ul>
      <li>Expandir nuestra presencia nacional en tres años.</li>
      <li>Adoptar e implementar innovaciones tecnológicas biomédicas.</li>
      <li>Lograr un crecimiento económico sostenible y ético.</li>
      <li>Capacitar continuamente a nuestro equipo humano.</li>
      <li>Incrementar la satisfacción del cliente en un 10% anual.</li>
    </ul>
  </section>

  <section id="inventario">
    <h2>Inventario de Marcas</h2>
    <p>Trabajamos con marcas líderes en el sector. Algunos de nuestros equipos destacados incluyen:</p>
    <ul>
      <li>Incubadoras con control ambiental inteligente</li>
      <li>Baños térmicos de alta precisión</li>
      <li>Estereomicroscopios con cámara digital</li>
      <li>Autoclaves automáticas con sensores integrados</li>
    </ul>
  </section>

  <section id="cronograma">
    <h2>Cronograma de Actividades</h2>
    <ol>
      <li>Semana 1-2: Instalación de incubadoras y calibración inicial</li>
      <li>Semana 3: Instalación de baño termostático</li>
      <li>Semana 4: Introducción de estereomicroscopios y capacitación</li>
      <li>Semana 5: Autoclaves y pruebas de esterilización</li>
      <li>Semana 6: Revisión y rendición de cuentas</li>
      <li>Semana 7: Retroalimentación y planificación de renovación</li>
    </ol>
  </section>

  <footer>
    <p>© 2025 TECNOMODO — Todos los derechos reservados.</p>
    <p>Contacto: <a href="mailto:contacto@tecnomodo.co" style="color: #00c896;">contacto@tecnomodo.co</a></p>
  </footer>

</body>
</html>
