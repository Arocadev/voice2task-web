<div align="center">

# Voice2Task — Web

**Landing page de Voice2Task**  
*Voice2Task landing page*

[![Astro](https://img.shields.io/badge/Astro-5.0-orange?logo=astro)](https://astro.build)
[![Vercel](https://img.shields.io/badge/Vercel-deployed-black?logo=vercel)](https://vercel.com)

</div>

---

## ¿Qué es esto?

Landing page pública de **Voice2Task**, la app Android que convierte notas de voz en tareas estructuradas con IA. Incluye selector de idioma ES/EN, descripción de funcionalidades, flujo de uso, preguntas frecuentes, integraciones disponibles y enlace de descarga del APK.

---

## ✨ Funcionalidades

### 🌍 Bilingüe
Selector ES/EN con cambio dinámico sin recarga de página. Todo el contenido traducido al completo.

### 🎙️ Hero animado
Icono con ondas concéntricas pulsantes y barras de frecuencia tipo ecualizador que representan la captura de voz.

### 🧩 Características
Tarjetas con los puntos fuertes de la app: rápido, inteligente, privado y organizado.

### ⚙️ Cómo funciona
Flujo visual de 4 pasos: habla → se entiende → se organiza → lo tienes listo.

### 🔌 Integraciones
Vista de las herramientas con las que conecta Voice2Task: Trello, Notion y Google Calendar (próximamente).

### ❓ Preguntas frecuentes
Acordeón con las dudas más comunes sobre la app y las integraciones.

### 📱 Descarga directa
Enlace al APK de la app Android en GitHub Releases.

### 📜 Páginas legales
Política de privacidad y términos de uso, cada una con su propio selector de idioma.

### ⚡ Estática
Sin backend, despliegue instantáneo en cualquier CDN.

---

## 🛠️ Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Framework | Astro |
| Estilos | CSS puro (variables + custom properties) |
| Tipografía | Space Grotesk (títulos) + Inter (texto) — Google Fonts |
| Despliegue | Vercel |

---

## 🎨 Identidad visual

| Token | Valor |
|---|---|
| Fondo | `#0B1111` |
| Fondo secundario | `#101919` |
| Color primario | `#14B8A6` |
| Color primario claro | `#2DD4BF` |
| Texto | `#F8FAFC` |
| Texto secundario | `#94A3B8` |

---

## 📁 Estructura del proyecto

```
voice2task-web/
├── public/
│   ├── favicon.ico
│   ├── logo.png
│   └── logo-mark.png
├── src/
│   ├── styles/
│   │   └── global.css          # Estilos globales (tokens, layout, componentes)
│   └── pages/
│       ├── index.astro         # Página principal
│       ├── privacidad.astro    # Política de privacidad (ES/EN)
│       └── terminos.astro      # Términos de uso (ES/EN)
├── astro.config.mjs
└── package.json
```

---

## 🚀 Instalación

```bash
git clone https://github.com/ArocaDev/voice2task-web.git
cd voice2task-web
npm install
npm run dev
```

Disponible en `http://localhost:4321`

---

## 🌐 Despliegue

La landing está desplegada en Vercel con despliegue automático en cada push a `main`.

---

## 🗺️ Roadmap

- [ ] Capturas de pantalla de la app en la landing
- [ ] Vídeo demo embebido
- [ ] Dominio propio en aroca.dev

---

## 🔗 Repositorios del proyecto

| Componente | Repositorio |
|---|---|
| Landing web (este repo) | [voice2task-web](https://github.com/ArocaDev/voice2task-web) |
| Backend API REST | [voice2task](https://github.com/ArocaDev/voice2task) |
| App Android | [voice2task-android](https://github.com/ArocaDev/voice2task-android) |

---

## 👤 Autor

**Alejandro Rodríguez Calabuig**  
[github.com/ArocaDev](https://github.com/ArocaDev) · [LinkedIn](https://linkedin.com/in/alejandro-rodriguez-calabuig-a871a1230)

---

## 📄 Licencia

Proyecto personal en desarrollo. No licenciado para uso comercial.  
*Personal project under development. Not licensed for commercial use.*
