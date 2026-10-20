# CHANGELOG: EducAI & HyperFrames Video Render Suite

Todas las habilidades, descubrimientos técnicos y plantillas de este proyecto se registran de forma continua en este historial.

---

## [v1.1.0] - 2026-10-19: Consolidación Inicial EdTech & Moodle LMS
### 🧠 Nuevas Habilidades y Aprendizajes Adquiridos
- **Resolución de Bloqueos de Layout en Chrome Headless:**
  - Descubrimiento e implementación de directivas `data-layout-allow-occlusion="true"` y `data-layout-allow-overlap="true"` para elementos flotantes (sellos de impacto, cajas de drag & drop, tarjetas de superposición).
- **Control de Tiempo y Prohibición de CSS Transitions:**
  - Sustitución de `transition: ...` por timelines pausadas en GSAP conectadas a `window.__timelines["main"]` para evitar desincronizaciones en el renderizado cuadro a cuadro.
- **Ingeniería y Mezcla de Sonido (BGM & SFX):**
  - Calibración de música de fondo al 15% (`data-volume="0.15"`) para no competir con locuciones y preservación de niveles estándar de emisión a -1 dBTP.
  - Sincronización milimétrica de 10 efectos sonoros diegéticos (clicks, pops, swooshes, chimes, notificaciones y bass impact).
- **Nuevo Arquetipo Pedagógico Moodle LMS:**
  - Estructuración de video en 3 dimensiones: Estructura Tripartita (*Clase ➔ Lectura ➔ Práctica*), navegación con Step Progress Bar interactiva y cursor virtual animado con pulso de clic.

### 📦 Componentes y Sub-agentes Creados
- **Sub-Agente:** `agents/edtech-video-director.md`
- **Skill Antigravity:** `skills/edtech-moodle-video/SKILL.md`
- **Plantillas HTML Verificadas:**
  - `templates/moodle-showcase-60s.html`: Video promocional (1080p, 60s).
  - `templates/moodle-vertical-9-16.html`: Video adaptado para Reels/TikTok (9:16, 60s).
  - `templates/moodle-makeover-90s.html`: Presentación del Kit Renovación de Aula en 8 escenas (1080p, 90s).
  - `templates/moodle-tutorial-120s.html`: Tutorial de integración técnica con cursor reactivo y barra de pasos (1080p, 120s).
- **Banco de Audio Portable:** Colección completa de efectos SFX y música de fondo en `assets/audio/`.
