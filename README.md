# TEST DE EXPLORACIÓN FÍSICA EN DOLOR 🩺

Aplicación web médica interactiva para el aprendizaje y consulta rápida de pruebas ortopédicas y maniobras de exploración física en dolor crónico y agudo.

Desarrollada con diseño *Medical Glassmorphism* optimizado para **iPhone (Safari PWA)** y **Mac / Desktop**, con vídeos didácticos integrados de **Physiotutors** y **Educom Continuing Education™**.

---

## 🚀 Características Principales

- 🦴 **8 Áreas Anatómicas Completas**: Hombro, Codo, Muñeca/Mano, Columna Cervical, Columna Lumbar/Torácica, Pelvis y Sacroilíaca, Cadera, Rodilla y Tobillo/Pie.
- 🎬 **Vídeos Didácticos HD Embebidos**: Demostraciones paso a paso de [Physiotutors](https://www.youtube.com/@Physiotutors) y [Educom Continuing Education™](https://www.youtube.com/@EducomContinuingEducation).
- 🧍 **Atlas Anatómico SVG Interactivo**: Puntos táctiles con pulso dinámico para filtrado por articulación en un solo toque.
- 📊 **Evidencia y Psicométrica**: Valores de Sensibilidad (SnNOut), Especificidad (SpPin), Likelihood Ratios (LR+, LR-) y Clústeres diagnósticos (Laslett, Wainner, LCA, etc.).
- 🧠 **Algoritmos Clínicos de Decisión**: Árboles de flujo diagnóstico para dolor anterior de hombro, ciatalgia vs sacroilíaco y rodilla traumática aguda.
- 📝 **Modo Estudio & Casos Clínicos**: Casos reales interactivos con retroalimentación diagnóstica inmediata y contador de aciertos.
- 📱 **100% PWA para iPhone**: Compatible con "Añadir a pantalla de inicio" en Safari iOS sin barras de navegación del navegador y con funcionamiento offline.
- 🌙 **Modo Oscuro / Claro**: Paleta de alto contraste médico con persistencia en `localStorage`.

---

## 📲 Cómo Instalar en tu iPhone (Página de Inicio en Safari)

1. Despliega la web en **Vercel** o abre la URL en **Safari** en tu iPhone.
2. Pulsa el botón **Compartir** de Safari (icono del cuadrado con flecha hacia arriba en la barra inferior).
3. Selecciona **"Añadir a pantalla de inicio"** (Add to Home Screen).
4. Asigna el nombre **"Exploración Dolor"** y pulsa **Añadir**.
5. ¡Listo! Se creará un icono de app nativa en tu iPhone a pantalla completa.

---

## 🌐 Cómo Desplegar en GitHub y Vercel

### Opción 1: Con GitHub y Vercel (Recomendado)
1. Crea un nuevo repositorio en GitHub: `test-exploracion-dolor`.
2. Sube los archivos de este directorio:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Test de Exploración Física en Dolor"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/test-exploracion-dolor.git
   git push -u origin main
   ```
3. Entra en [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub.
4. Haz clic en **"Add New..." → "Project"**.
5. Importa el repositorio `test-exploracion-dolor` y pulsa **"Deploy"**.
6. En pocos segundos tendrás tu URL pública (ejemplo: `https://test-exploracion-dolor.vercel.app`).

---

## 📂 Estructura del Proyecto

```
TEST DE EXPLORACION DOLOR/
├── index.html              # Estructura SPA y vistas interactivas
├── styles.css              # Sistema de diseño, glassmorphism y modo oscuro/claro
├── app.js                  # Lógica reactiva, reproductores y simulador
├── data/
│   └── tests_catalog.json  # Catálogo médico estructurado con +24 tests y vídeos
├── manifest.json           # Configuración PWA para instalación móvil
├── sw.js                   # Service Worker para caché sin conexión
├── vercel.json             # Configuración de despliegue en Vercel
└── README.md               # Documentación y guía de uso
```

---

*Desarrollado con dedicación para la formación y práctica clínica en Medicina del Dolor.*
