# voice2task-web
> Landing page de Voice2Task | Voice2Task landing page

---

## Español

Landing page pública de **Voice2Task**, la app Android que convierte notas de voz en tareas estructuradas con IA. Incluye selector de idioma ES/EN, sección de características, flujo de funcionamiento, preguntas frecuentes, páginas legales y enlace de descarga del APK.

---

### ✨ Funcionalidades

- 🌍 **Bilingüe** — selector ES/EN con cambio dinámico sin recarga de página
- 📱 **Descarga directa** — enlace al APK de la app Android
- 🎙️ **Hero animado** — icono con ondas concéntricas y barras de frecuencia tipo ecualizador
- 🧩 **Características** — tarjetas con los puntos fuertes de la app (rápido, inteligente, privado, organizado)
- ⚙️ **Cómo funciona** — flujo visual de 4 pasos: habla → se entiende → se organiza → lo tienes listo
- ❓ **Preguntas frecuentes** — acordeón con dudas comunes sobre la app
- 🔌 **Integraciones** — vista de las herramientas con las que conecta (Telegram, Trello, Google Calendar, Notion)
- 📜 **Páginas legales** — Privacidad y Términos de uso, con selector de idioma propio
- ⚡ **Estática** — sin backend, despliegue instantáneo en cualquier CDN

---

### 🛠️ Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Framework | Astro |
| Estilos | CSS puro (variables + custom properties) |
| Tipografía | Space Grotesk (títulos) + Inter (texto) — Google Fonts |
| Despliegue | Vercel |

---

### 🎨 Identidad visual

| Token | Valor |
|---|---|
| Fondo | `#0B1111` |
| Fondo secundario | `#101919` |
| Color primario | `#14B8A6` |
| Color primario claro | `#2DD4BF` |
| Texto | `#F8FAFC` |
| Texto secundario | `#94A3B8` |

---

### 📁 Estructura del proyecto

```
voice2task-web/
├── public/
│   ├── favicon.ico            # Icono de pestaña / navbar
│   ├── logo.png                # Logo completo (mic + texto)
│   └── logo-mark.png           # Icono del logo, centrado, para el hero
├── src/
│   ├── styles/
│   │   └── global.css          # Estilos globales (tokens, layout, componentes)
│   └── pages/
│       ├── index.astro         # Página principal (hero, características, cómo funciona, FAQ, descarga)
│       ├── privacidad.astro    # Política de privacidad (ES/EN)
│       └── terminos.astro      # Términos de uso (ES/EN)
├── astro.config.mjs
└── package.json
```

---

### 🚀 Instalación

```bash
git clone https://github.com/ArocaDev/voice2task-web.git
cd voice2task-web
npm install
npm run dev
```

Web disponible en `http://localhost:4321`

---

### 🔗 Repositorios del proyecto

| Componente | Repositorio |
|---|---|
| Backend API REST | [voice2task](https://github.com/ArocaDev/voice2task) |
| Landing web (este repo) | [voice2task-web](https://github.com/ArocaDev/voice2task-web) |
| App Android | [voice2task-android](https://github.com/ArocaDev/voice2task-android) |

---

## 🌐 English

Public landing page for **Voice2Task**, the Android app that converts voice notes into structured tasks using AI. Includes an ES/EN language selector, a features section, how-it-works flow, FAQ, legal pages and an APK download link.

---

### ✨ Features

- 🌍 **Bilingual** — ES/EN selector with dynamic switching without page reload
- 📱 **Direct download** — link to the Android APK
- 🎙️ **Animated hero** — icon with concentric pulse rings and equalizer-style frequency bars
- 🧩 **Features** — cards highlighting the app's strengths (fast, smart, private, organised)
- ⚙️ **How it works** — 4-step visual flow: speak → understood → organised → ready
- ❓ **FAQ** — accordion with common questions about the app
- 🔌 **Integrations** — showcase of the tools it connects with (Telegram, Trello, Google Calendar, Notion)
- 📜 **Legal pages** — Privacy Policy and Terms of Use, each with its own language selector
- ⚡ **Static** — no backend, instant deployment on any CDN

---

### 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Astro |
| Styles | Pure CSS (variables + custom properties) |
| Typography | Space Grotesk (headings) + Inter (body) — Google Fonts |
| Deployment | Vercel |

---

### 🎨 Visual identity

| Token | Value |
|---|---|
| Background | `#0B1111` |
| Secondary background | `#101919` |
| Primary color | `#14B8A6` |
| Primary light | `#2DD4BF` |
| Text | `#F8FAFC` |
| Muted text | `#94A3B8` |

---

### 📁 Project structure

```
voice2task-web/
├── public/
│   ├── favicon.ico            # Tab / navbar icon
│   ├── logo.png                # Full logo (mic + wordmark)
│   └── logo-mark.png           # Centered icon mark, used in the hero
├── src/
│   ├── styles/
│   │   └── global.css          # Global styles (tokens, layout, components)
│   └── pages/
│       ├── index.astro         # Main page (hero, features, how it works, FAQ, download)
│       ├── privacidad.astro    # Privacy Policy (ES/EN)
│       └── terminos.astro      # Terms of Use (ES/EN)
├── astro.config.mjs
└── package.json
```

---

### 🚀 Installation

```bash
git clone https://github.com/ArocaDev/voice2task-web.git
cd voice2task-web
npm install
npm run dev
```

Available at `http://localhost:4321`

---

## 👤 Autor / Author

**Alejandro Rodríguez Calabuig** — [github.com/ArocaDev](https://github.com/ArocaDev) · [LinkedIn](https://linkedin.com/in/alejandro-rodriguez-calabuig-a871a1230)

---

## 📄 Licencia / License

Proyecto personal en desarrollo.
Personal project under development.
