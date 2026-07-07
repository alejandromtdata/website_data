---
layout: portfolio
title: "Analista de Datos Junior"
description: "Alejandro Morillas Analista de Datos Junior."
---

<header class="portfolio-header">
  <div class="portfolio-container header-inner">
    <a class="brand" href="{{ '/' | relative_url }}">
    <span class="brand-name">Alejandro Morillas</span>
    <span class="brand-role">Data Analyst Junior</span>
    </a>

   <nav class="desktop-navigation" aria-label="Navegación principal">
      <a href="#projects">Proyectos</a>
      <a href="#about">Sobre mí</a>
      <a href="#skills">Tecnologias</a>
      <a href="#contact">Contacto</a>
      {% if site.cv_url %}
        <a class="button button-small button-primary" href="{{ site.cv_url | relative_url }}" download>Descargar CV</a>
      {% endif %}
    </nav>

  <details class="mobile-navigation">
      <summary>Menú</summary>
      <div class="mobile-navigation-panel">
        <a href="#projects">Proyectos</a>
        <a href="#about">Sobre mí</a>
        <a href="#skills">Stack tecnológico</a>
        <a href="#contact">Contacto</a>
        {% if site.cv_url %}
          <a href="{{ site.cv_url | relative_url }}" download>Descargar CV</a>
        {% endif %}
      </div>
    </details>
  </div>
</header>

<main id="main-content">
  <section class="hero section" aria-labelledby="hero-title">
    <div class="portfolio-container hero-grid{% unless page.dashboard_image %} hero-grid-single{% endunless %}">
      <div class="hero-content">
        <p class="eyebrow">ANALISTA DE DATOS JUNIOR</p>

<h1 id="hero-title">
Alejandro Morillas Torres
</h1>

<h3 class="hero-subtitle">
Construyendo mi carrera como Analista de Datos.
</h3>

<p class="hero-introduction">
Actualmente desarrollo proyectos de análisis de datos utilizando 
<strong>SQL</strong>, 
<strong>PostgreSQL</strong>,
<strong>Python</strong>, 
<strong>Power BI</strong> 
y <strong>Excel</strong>
</p>
<p> Mi objetivo es transformar datos en información clara que ayude a comprender mejor el negocio y facilite la toma de decisiones. </p>

<div class="hero-tech-stack">
  <div class="tech-pill">
      <img src="{{ '/assets/images/python.svg' | relative_url }}" alt="Python">
      <span>Python</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/postgresql.svg' | relative_url }}" alt="PostgreSQL">
      <span>PostgreSQL</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/power_bi.svg' | relative_url }}" alt="Power BI">
      <span>Power BI</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/excel.svg' | relative_url }}" alt="Excel">
      <span>Excel</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/pandas.svg' | relative_url }}" alt="Pandas">
      <span>Pandas</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/matplotlib.svg' | relative_url }}" alt="Matplotlib">
      <span>Matplotlib</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/seaborn.svg' | relative_url }}" alt="seaborn">
      <span>Seaborn</span>
  </div>
  <div class="tech-pill">
      <img src="{{ '/assets/images/vs_code.svg' | relative_url }}" alt="Vs Code">
      <span>VS Code</span>
  </div>
</div>

<!-- === PROYECTOS ==== -->

<section id="projects" class="section section-bordered" aria-labelledby="projects-title">

  <div class="portfolio-container">

  <div class="section-heading">

  <p class="eyebrow"> PROYECTOS </p>

  <h2 id="projects-title"> E-commerce Analytics </h2>

  <p>
  Proyecto completo de análisis de datos orientado al comercio electrónico.
  Incluye limpieza de datos, consultas SQL, análisis exploratorio y un dashboard
  interactivo desarrollado en Power BI.
  </p>

  </div>

  <figure class="project-dashboard">

  <img src="{{ '/assets/images/dashboard_screenshot.png' | relative_url }}" alt="Dashboard Power BI del proyecto E-commerce Analytics">

  </figure>

<div class="project-technologies">

  <p class="project-tech-title">
        Tecnologías utilizadas
  </p>

  <div class="project-tech-list">

  <span>
    <img src="{{ '/assets/images/python.svg' | relative_url }}" alt="">
    Python
  </span>

  <span>
    <img src="{{ '/assets/images/postgresql.svg' | relative_url }}" alt="">
    PostgreSQL
  </span>

  <span>
    <img src="{{ '/assets/images/power_bi.svg' | relative_url }}" alt="">
    Power BI
  </span>

  <span>
    <img src="{{ '/assets/images/excel.svg' | relative_url }}" alt="">
    Excel
  </span>

  </div>

</div>

  <div class="project-actions">

  <a class="button button-primary"
   href="https://github.com/alejandromtdata/proyecto_ecommerce_analytics"
   target="_blank"
   rel="noopener noreferrer">
    Ver proyecto
  </a>

{% if page.project_repository %}
  <a class="button button-secondary" href="{{ page.project_repository }}"> GitHub </a> {% endif %}

  </div>

</div>

</section>






  <section class="section" aria-labelledby="process-title">
    <div class="portfolio-container">
      <div class="section-heading section-heading-compact">
        <p class="eyebrow">Proceso analítico</p>
        <h2 id="process-title">Un proceso estructurado desde la pregunta hasta la conclusión.</h2>
      </div>

      <ol class="process-grid">
        <li>
          <span class="process-number">01</span>
          <h3>Comprender</h3>
          <p>Definir la pregunta y la decisión que debe respaldar el análisis.</p>
        </li>
        <li>
          <span class="process-number">02</span>
          <h3>Preparar</h3>
          <p>Limpiar y estructurar los datos para partir de una base fiable.</p>
        </li>
        <li>
          <span class="process-number">03</span>
          <h3>Analizar</h3>
          <p>Explorar los datos e identificar patrones relevantes para la pregunta inicial.</p>
        </li>
        <li>
          <span class="process-number">04</span>
          <h3>Comunicar</h3>
          <p>Presentar las conclusiones con claridad para facilitar los siguientes pasos.</p>
        </li>
      </ol>
    </div>
  </section>

  <section id="skills" class="section section-muted" aria-labelledby="skills-title">
    <div class="portfolio-container">
      <div class="section-heading">
        <p class="eyebrow">Stack tecnológico</p>
        <h2 id="skills-title">Herramientas organizadas según su propósito.</h2>
        <p>Un conjunto de herramientas para preparar, analizar y comunicar datos.</p>
      </div>

      <div class="skills-grid">
        <article class="skill-card">
          <p class="skill-number">01</p>
          <h3>Preparación de datos</h3>
          <ul>
            <li><span class="tech-icon" aria-hidden="true">SQL</span>SQL</li>
            <li><span class="tech-icon" aria-hidden="true">PG</span>PostgreSQL</li>
            <li><span class="tech-icon" aria-hidden="true">XL</span>Excel</li>
          </ul>
        </article>
        <article class="skill-card">
          <p class="skill-number">02</p>
          <h3>Análisis de datos</h3>
          <ul>
            <li><span class="tech-icon" aria-hidden="true">PY</span>Python</li>
            <li><span class="tech-icon" aria-hidden="true">PD</span>Pandas</li>
            <li><span class="tech-icon" aria-hidden="true">NP</span>NumPy</li>
          </ul>
        </article>
        <article class="skill-card">
          <p class="skill-number">03</p>
          <h3>Visualización</h3>
          <ul>
            <li><span class="tech-icon" aria-hidden="true">BI</span>Power BI</li>
          </ul>
        </article>
        <article class="skill-card">
          <p class="skill-number">04</p>
          <h3>Entorno de trabajo</h3>
          <ul>
            <li><span class="tech-icon" aria-hidden="true">GT</span>Git</li>
            <li><span class="tech-icon" aria-hidden="true">GH</span>GitHub</li>
            <li><span class="tech-icon" aria-hidden="true">VS</span>VS Code</li>
            <li><span class="tech-icon tech-icon-terminal" aria-hidden="true">&gt;_</span>Terminal</li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <section id="about" class="section" aria-labelledby="about-title">
    <div class="portfolio-container about-grid">
      <div class="about-intro">
        <p class="eyebrow">Sobre mí</p>
        <h2 id="about-title">Desarrollo experiencia práctica mediante análisis reales.</h2>
        {% if page.portrait_image %}
          <figure class="about-portrait">
            <img
              src="{{ page.portrait_image | relative_url }}"
              alt="{{ page.portrait_alt | default: 'Retrato profesional de Alejandro Morillas' }}"
              width="{{ page.portrait_width }}"
              height="{{ page.portrait_height }}"
              loading="lazy">
          </figure>
        {% endif %}
      </div>
      <div class="about-copy">
        <p>
          Soy Alejandro, Analista de Datos Junior, y desarrollo experiencia práctica a través de proyectos de análisis de datos.
        </p>
        <p>
          Trabajo con SQL, Python, Excel y Power BI, con especial atención al análisis estructurado y a la comunicación clara de las conclusiones.
        </p>
        <p>
          Mi objetivo es incorporarme a un equipo en el que pueda seguir aprendiendo y aportar un trabajo analítico riguroso y útil.
        </p>
      </div>
    </div>
  </section>

  <section id="contact" class="section contact-section" aria-labelledby="contact-title">
    <div class="portfolio-container">
      <div class="contact-panel">
        <p class="eyebrow">Contacto</p>
        <h2 id="contact-title">Hablemos de datos y oportunidades.</h2>
        <p>Estoy disponible para oportunidades como Analista de Datos Junior.</p>

        <div class="contact-actions">
          <a class="button button-primary" href="mailto:{{ site.email }}">Escríbeme</a>
          {% if site.linkedin_url %}
            <a class="button button-secondary" href="{{ site.linkedin_url }}">LinkedIn</a>
          {% endif %}
          <a class="button button-secondary" href="https://github.com/{{ site.github_username }}">GitHub</a>
          {% if site.cv_url %}
            <a class="button button-secondary" href="{{ site.cv_url | relative_url }}" download>Descargar CV</a>
          {% endif %}
        </div>
      </div>
    </div>
  </section>
</main>

<footer class="portfolio-footer">
  <div class="portfolio-container footer-inner">
    <p>© {{ site.time | date: '%Y' }} Alejandro Morillas</p>
    <a href="#main-content">Volver arriba</a>
  </div>
</footer>
