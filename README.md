# 💻 Mi Portafolio Web - Marcos Movilla

<!-- Tarjeta animada de bienvenida -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FFFFFF&background=FF000000&width=435&lines=Hello+%F0%9F%91%8B%2C+I%60m+Marcos+Movilla" alt="Typing SVG">
</a>

Estudiante en desarrollo de aplicaciones web, actualmente aprendiendo y explorando el mundo del código. Comencé mi camino en el desarrollo web en 2022, y desde entonces no he parado de aprender nuevas tecnologías y trabajar en proyectos que me desafían a mejorar.

---

## 🙋‍♂️ Sobre mí
Tengo 19 años y actualmente estoy cursando el ciclo formativo de **Desarrollo de Aplicaciones Web (DAW)**. Me gusta explorar nuevas tecnologías, resolver problemas y crear proyectos que me ayuden a mejorar como desarrollador.

### 🎯 Áreas de interés
*   **Desarrollo Frontend:** HTML, CSS, JavaScript, React
*   **Desarrollo Backend:** Node.js, PHP, MySQL

---

## 🛠️ Código del Proyecto (index.html)

A continuación se encuentra el código fuente completo y mejorado del portafolio, estructurado con HTML semántico, diseño responsivo (CSS Grid) y variables nativas para la gestión de estilos:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marcos Movilla | Desarrollador Web</title>
  <style>
    :root {
      --primary-color: #2563eb;
      --primary-gradient: linear-gradient(135deg, #2563eb, #1d4ed8);
      --bg-color: #f8fafc;
      --card-bg: #ffffff;
      --text-color: #334155;
      --text-light: #64748b;
    }

    body {
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      background: var(--primary-gradient);
      color: white;
      padding: 60px 20px;
      text-align: center;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    }

    header p {
      max-width: 600px;
      margin: 15px auto 0 auto;
      font-size: 1.1em;
      opacity: 0.9;
    }

    main {
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      background: var(--card-bg);
      margin-bottom: 30px;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    }

    h2 {
      color: var(--primary-color);
      margin-top: 0;
      border-bottom: 2px solid #e2e8f0;
      padding-bottom: 8px;
    }

    ul {
      list-style-type: none;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 12px;
    }

    ul li {
      background: #f1f5f9;
      padding: 10px 15px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      font-weight: 500;
    }

    ul li::before {
      content: "✓";
      margin-right: 10px;
      color: var(--primary-color);
      font-weight: bold;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 15px;
    }

    .project-card {
      border: 1px solid #e2e8f0;
      padding: 20px;
      border-radius: 8px;
      background: #fafafa;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .project-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
    }

    .project-card h3 {
      margin-top: 0;
      color: #1e293b;
    }

    .btn-contact {
      display: inline-block;
      background: var(--primary-gradient);
      color: white;
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 500;
      margin-top: 10px;
      transition: opacity 0.2s;
    }

    .btn-contact:hover {
      opacity: 0.9;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      font-size: 0.9em;
      color: var(--text-light);
    }
  </style>
</head>
<body>

  <header>
    <a href="[https://git.io/typing-svg](https://git.io/typing-svg)">
      <img src="[https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FFFFFF&background=FF000000&width=435&lines=Hello+%F0%9F%91%8B%2C+I%60m+Marcos+Movilla](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FFFFFF&background=FF000000&width=435&lines=Hello+%F0%9F%91%8B%2C+I%60m+Marcos+Movilla)" alt="Typing SVG">
    </a>
    <p>Estudiante de Desarrollo de Aplicaciones Web (DAW). Apasionado por crear soluciones a través del código desde 2022.</p>
  </header>

  <main>
    <section>
      <h2>Sobre mí</h2>
      <p>Tengo 19 años y actualmente estoy cursando el ciclo formativo de <strong>Desarrollo de Aplicaciones Web (DAW)</strong>. Me motiva explorar nuevas tecnologías, resolver problemas complejos y construir proyectos reales que me impulsen a crecer como desarrollador profesional.</p>
    </section>

    <section>
      <h2>Áreas de interés</h2>
      <ul>
        <li>Frontend (React, JS, CSS)</li>
        <li>Backend (Node.js, PHP)</li>
        <li>Bases de Datos (MySQL)</li>
        <li>Arquitectura Web</li>
      </ul>
    </section>

    <section>
      <h2>Proyectos destacados</h2>
      <div class="projects-grid">
        <div class="project-card">
          <h3>Proyecto 1</h3>
          <p style="color: var(--text-light); font-size: 0.9em;">Descripción breve del proyecto que hiciste. Tecnologías usadas: HTML, CSS, JS.</p>
        </div>
        <div class="project-card">
          <h3>Proyecto 2</h3>
          <p style="color: var(--text-light); font-size: 0.9em;">Próximamente. Proyecto enfocado en backend con PHP y MySQL. 👷</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Contacto</h2>
      <p>¿Tienes alguna idea en mente o te gustaría que colaboremos? ¡Estoy abierto a nuevas oportunidades y proyectos desafiantes! ✉️</p>
      <a href="mailto:marcosmovalver@gmail.com" class="btn-contact">Escríbeme por correo</a>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 - Diseñado con ❤️ por Marcos Movilla</p>
  </footer>

</body>
</html>
