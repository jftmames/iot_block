# 📘 Blockchain & IoT – Curso Universitario (SPA estática)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Este repositorio contiene la **web de la asignatura Blockchain e IoT**, optativa de 4º curso en el **Grado en Ingeniería Informática**.  
Está construida como una **Single Page Application (SPA) 100% estática**, sin servidor, lista para desplegar en **Vercel**.

---

## 🚀 Contenido

La web incluye:

- **Módulo 1 – Ecosistema IoT (Sesiones 1–6)**
  - Introducción al IoT
  - Capas de un sistema IoT
  - Sensores
  - Protocolos de comunicación
  - Plataformas de mercado
  - Industria 4.0 y mantenimiento predictivo
- **Caso Harvard: InduWare**
  - Dilema estratégico: reforzar IoT tradicional vs. integrar Blockchain
  - Exhibits con incidentes de ciberseguridad y comparativa de costes
- **Entregas en Blackboard**
  - Entrega 1: Seguridad IoT + Blockchain
  - Entrega 2: Elección de plataforma IoT
  - Entrega 3: Propuesta grupal preliminar
- **Exhibits interactivos**
  - Gráfico de incidentes de ciberseguridad (2023–2024)
  - Costes estimados de cada alternativa

---

## 🛠️ Tecnologías utilizadas

- **HTML5 + CSS3 + JavaScript** (SPA sin servidor)
- **[PicoCSS](https://picocss.com/)** para estilo minimalista
- **Chart.js** para gráficos interactivos
- **LocalStorage** para recordar el tema claro/oscuro
- **100% estática** → no requiere Node.js, backend ni bases de datos

---

## 📦 Estructura del repositorio

```bash
/
├── index.html      # SPA con todo el contenido dinámico
├── vercel.json     # Configuración para Vercel (rutas limpias, cache)
└── README.md       # Este documento
