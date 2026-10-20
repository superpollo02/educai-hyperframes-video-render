# CHANGELOG: EducAI & HyperFrames Video Render Suite

Todas las habilidades, descubrimientos técnicos y plantillas de este proyecto se registran de forma continua en este historial.

---

## [v1.3.0] - 2026-10-19: Arquetipo Formativo Médico Dual Arena & Warm Focus BGM
### 🧠 Nuevas Habilidades y Arquetipos
- **Arquetipo Comparativo "Dual Arena" (Administración vs. Gestión):**
  - Estructuración pedagógica andragógica en dos columnas dinámicas de contraste (*Hacer las cosas bien* vs. *Hacer las cosas correctas*), tarjetas de fricción operativa en residencias y sello institucional de docentes de referencia (*Dra. Susana Salomón & Dra. Laura Piovano*).
- **Nueva Pista Sonora Warm Focus Synthesizer:**
  - Banda sonora original armónica (`bgm-warm-focus-45s.wav`) basada en progresiones de acordes de piano eléctrico y sintetizador (*Dmaj9 -> Gmaj7 -> Bm7 -> Asus4*), con pulsos de marimba y calibrada a 45.0s y volumen 18%.
- **Nueva Plantilla Registrada:**
  - `templates/unidad2-gestion-vs-administracion-45s.html`: Video formativo panorámico (16:9, 45s, 1080p) con carril de subtítulos sincronizado palabra a palabra.

## [v1.2.0] - 2026-10-19: Estilo Clinical Healthcare & Nueva Pista Sonora
### 🧠 Nuevas Habilidades y Arquetipos
- **Nuevo Estilo Estético "Clinical Teal & Obsidian":**
  - Paleta cromática médica (#06151f base, acentos #38bdf8 cyan y #2dd4bf teal) con tarjetas translúcidas de cristal esmerilado (`backdrop-filter: blur(16px)`).
- **Nuevo Paisaje Sonoro:**
  - Banda sonora ambiental melódica tecnológica (`bgm-ambient-40s.wav`) en loop determinista a 40 segundos.
  - Efectos de sonido clínicos: chime de entrada, pop suave en transiciones y campana de certificación.
- **Nueva Plantilla:**
  - `templates/gestion-salud-40s.html`: Video instructivo de 40 segundos para diplomados y cursos de posgrado en salud.

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
