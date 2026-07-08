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
      <a href="#capabilities">Capacidades</a>
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
        <a href="#capabilities">Capacidades</a>
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
Convirtiendo datos en información útil.
</h3>

<p class="hero-introduction">
Analista de Datos Junior con experiencia práctica en  
<strong>SQL</strong>, 
<strong>PostgreSQL</strong>,
<strong>Python</strong>, 
<strong>Power BI</strong> 
y <strong>Excel</strong>. 
</p>
<p> Desarrollo proyectos completos de análisis de datos, desde la preparación y exploración de los datos hasta la creación de dashboards interactivos. </p>

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



<section id="about" class="section section-muted about-section">

<div class="portfolio-container">

  <div class="about-grid">

  <div class="about-photo">

   <img
          src="{{ '/assets/images/foto_cv.png' | relative_url }}"
          alt="Alejandro Morillas">

</div>

<div class="about-copy">

<p class="eyebrow">SOBRE MÍ</p>

  <p class="about-text">
    Soy <strong>Alejandro Morillas</strong>, Analista de Datos Junior con formación en
          SQL, PostgreSQL, Python, Power BI y Excel.
  </p>

  <p class="about-text">
  Después de más de dos décadas de experiencia profesional, 
  decidí orientar mi carrera hacia el análisis de datos con un objetivo claro: 
  ayudar a las empresas a tomar mejores decisiones basadas en la información.
  </p>

  <p class="about-text">
  Actualmente continúo ampliando mis conocimientos mediante proyectos prácticos 
  que me permiten desarrollar una metodología de trabajo basada en el análisis, 
  la resolución de problemas y la mejora continua.
  </p>

<p class="about-text">
  Me motiva especialmente comprender cómo funcionan los procesos de negocio, 
  detectar oportunidades de mejora y encontrar soluciones que aporten valor 
  a través de los datos.
  </p>

  </div>

  </div>

<blockquote class="about-quote">

"Estoy convencido de que los datos tienen valor cuando ayudan a resolver problemas reales y facilitan mejores decisiones. Por eso disfruto analizando procesos, detectando oportunidades de mejora y desarrollando soluciones que aporten valor al negocio."

</blockquote>

<div class="about-actions">

<a class="button button-primary"
    href="https://www.linkedin.com/in/alejandro-morillas-data/"
    target="_blank"
    rel="noopener noreferrer">
    LinkedIn
</a>

<a
class="button button-primary"
href="https://github.com/alejandromtdata"
target="_blank"
rel="noopener noreferrer">
GitHub
</a>

<a
class="button button-primary"
href="{{ '/assets/documents/Alejandro_Morillas_CV_data_analyst.pdf' | relative_url }}"
download>
Descargar CV
</a>  





  </div>

  </div>

</section>

<section id="capabilities" class="section" aria-labelledby="capabilities-title">

  <div class="portfolio-container">

  <div class="section-heading">
      <p class="eyebrow">CAPACIDADES</p>

  <h2 id="capabilities-title">
        ¿Qué puedo aportar?
      </h2>

  <p> Tecnologías y conocimientos que utilizo para desarrollar proyectos de análisis de datos de principio a fin. </p>
    </div>

  <div class="skills-grid">

  <div class="skill-card">
        <h3>Limpieza de datos</h3>

  <ul>
          <li>– Tratamiento de datos inconsistentes</li>
          <li>– Gestión de valores nulos</li>
          <li>– Transformación de datasets</li>
        </ul>
      </div>

  <div class="skill-card">
        <h3>Análisis</h3>

  <ul>
          <li>– SQL y PostgreSQL</li>
          <li>– Python (Pandas)</li>
          <li>– Estadística descriptiva</li>
        </ul>
      </div>

  <div class="skill-card">
        <h3>Visualización</h3>

  <ul>
          <li>– Dashboards en Power BI</li>
          <li>– Diseño de KPIs</li>
          <li>– Storytelling con datos</li>
        </ul>
      </div>

  <div class="skill-card">
        <h3>Entorno de trabajo</h3>

  <ul>
          <li>– Git y GitHub</li>
          <li>– VS Code </li>
          <li>– Metodología de proyectos</li>
        </ul>
      </div>

  </div>

  </div>

</section>

<section id="contact" class="section contact-section" aria-labelledby="contact-title">
    <div class="portfolio-container">
      <div class="contact-panel">
        <p class="eyebrow">Contacto</p>
        <h2 id="contact-title">¿Hablamos de datos?</h2>
        <p>Si compartes esta forma de entender el análisis de datos 
        y crees que puedo aportar valor a tu equipo, 
        estaré encantado de conversar contigo..</p>

      
<div class="contact-actions">

<a class="button button-primary"
   href="mailto:alejandromtdata@outlook.es">
   Enviar correo
</a>

<a class="button button-primary"
   href="tel:+34699217069">
   Llamar
</a>
    </div>
      </div>
</div>

</section>


<footer class="portfolio-footer">
  <div class="portfolio-container footer-inner">
    <p>© {{ site.time | date: '%Y' }} Alejandro Morillas</p>
    <a href="#main-content">Volver arriba</a>
  </div>
</footer>
