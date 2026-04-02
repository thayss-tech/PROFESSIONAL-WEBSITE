<div align="center">
  <h1 align="center">🌐 Thayss Tech Hub | Frontend Architecture</h1>
  <p align="center">
    <strong>Arquitectura estática, diseño de interfaz y hub central de mi ecosistema profesional en Data Science.</strong>
  </p>

  <p align="center">
    <a href="https://thayss-tech.github.io/WEB/"><img src="https://img.shields.io/badge/Status-Producción-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Status"></a>
    <img src="https://img.shields.io/badge/HTML5-Semantic_Web-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-Responsive-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <a href="AQUI_TU_LINKEDIN"><img src="https://img.shields.io/badge/Red-LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  </p>
</div>

<br>

## 📑 Tabla de Contenidos
1. [Visión General de la Arquitectura](#-visión-general-de-la-arquitectura)
2. [Características Técnicas y UX](#-características-técnicas-y-ux)
3. [Topología del Repositorio](#-topología-del-repositorio)
4. [Infraestructura y Despliegue](#-infraestructura-y-despliegue)
5. [Integración con Modelos de Machine Learning](#-integración-con-modelos-de-machine-learning)

---

## 📌 Visión General de la Arquitectura

Este repositorio contiene el código fuente **frontend** de mi plataforma profesional. Actúa como el punto de entrada centralizado (Hub) para reclutadores técnicos, consolidando mis credenciales y dirigiendo el tráfico de manera estructurada hacia mis pipelines de datos y modelos predictivos (Riesgo, Fraude, etc.).

Se priorizó un enfoque de **Vanilla Web Development** (código puro sin frameworks pesados) para garantizar tiempos de carga mínimos, máxima personalización y control total sobre el DOM.

## ⚙️ Características Técnicas y UX

* **Desarrollo Semántico:** Uso riguroso de etiquetas HTML5 para garantizar accesibilidad (a11y) y una correcta indexación.
* **Diseño Adaptativo (Mobile-First):** Implementación de *Media Queries* en CSS3 que aseguran una renderización perfecta en cualquier resolución (smartphones, tablets, monitores).
* **Rendimiento Optimizado:** * Carga asíncrona de recursos.
  * Archivos estáticos e imágenes minimizadas.
  * Cero dependencias de librerías externas que bloqueen el renderizado principal.

## 📂 Topología del Repositorio

La base del código sigue un estándar limpio de separación de responsabilidades (estructura, diseño y contenido):

```text
📦 thayss-tech.github.io/WEB
 ┣ 📜 index.html           # Estructura semántica principal (DOM)
 ┣ 📂 assets/              # Reglas de cascada, variables CSS y scripts de interactividad
 │  ┣ 📂 css/              # Hojas de estilo modularizadas
 │  ┣ 📂 js/               # Lógica de frontend e interacciones
 │  ┗ 📂 fonts/            # Tipografías web-safe optimizadas
 ┣ 📂 images/              # Recursos gráficos comprimidos para bajo consumo de banda
 ┣ 📂 certificates/        # Respaldos en PDF de certificaciones técnicas
 ┗ 📜 README.md            # Documentación técnica actual
