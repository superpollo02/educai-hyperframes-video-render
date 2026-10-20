# CHANGELOG: EducAI & HyperFrames Video Render Suite

Todas las habilidades, descubrimientos técnicos y plantillas de este proyecto se registran de forma continua en este historial.

---

## [v1.8.0] - 2026-10-19: Integración de Locución Neuronal Rioplatense (Voz Elena) en Toda la Suite
### 🧠 Nuevas Habilidades y Arquetipos
- **Motor TTS Neuronal en Español Rioplatense (`edge-tts` con `es-AR-ElenaNeural`):**
  - Incorporación de pistas de voz en off habladas reales (10 audios `.mp3` sintetizados a 44.1 kHz).
  - Tono andragógico, profesional, cercano y claro, respetando la cadencia y fonética del español rioplatense (Mendoza / Argentina).
- **Mezcla Sonora y Ducking Automático de BGM:**
  - Atenuación de las bandas sonoras de fondo (`data-volume="0.12"`) y balance de la pista vocal a volumen pleno (`data-volume="1.0"`) para garantizar inteligibilidad absoluta.
- **Re-renderizado Completo de la Suite:**
  - Las 7 unidades temáticas (U2 a U8), la Presentación del Programa Académico (60s) y la Inducción Rápida Oficial (210s) cuentan ahora con locución de narrador en off completa.
- **Nuevos Assets de Audio Registrados:**
  - `assets/audio/vo-*.mp3` (10 archivos de voz neuronal rioplatense de alta fidelidad).

## [v1.7.0] - 2026-10-19: Video de Inducción Rápida y Alocución Completa (3:30 min / 210s)
### 🧠 Nuevas Habilidades y Arquetipos
- **Arquetipo de Inducción Rápida Institucional (210s - 3m30s):**
  - Composición de media duración (6.300 fotogramas a 30 FPS) estructurada en 4 bloques temporales exactos:
    - *Bloque 1 (00:00 - 00:45):* Bienvenida, mito de la gratuidad y costo de oportunidad bioético.
    - *Bloque 2 (00:45 - 01:30):* Ficha operativa (8 semanas, 60 hs reloj, 100% virtual asincrónica) y regla tripartita de la Circular N° 5 (*Clase ➔ Lectura ➔ Práctica*).
    - *Bloque 3 (01:30 - 02:45):* Recorrido secuencial por las 8 unidades del programa académico del Lic. Gustavo Muñoz Gatón.
    - *Bloque 4 (02:45 - 03:30):* Sistema de *Doble Candado Automatizado* (Examen Final Integrador ≥ 70% + Encuesta de Calidad) y cierre institucional.
  - Carril de subtítulos sincronizado en 8 segmentos continuos.
- **Banda Sonora Extendida de 210s:**
  - `bgm-induccion-esalud-210s.wav`: Progresión armónica (*Dmaj7 -> F#m7 -> Gmaj7 -> A6*) con pulsos rítmicos de marimba, masterizada y calibrada a 210 segundos exactos a volumen 18%.
- **Nueva Plantilla Registrada:**
  - `templates/induccion-rapida-economia-salud-210s.html`

## [v1.6.0] - 2026-10-19: Integración NotebookLM & Video Oficial de Programa Académico
### 🧠 Nuevas Habilidades y Arquetipos
- **Integración con NotebookLM vía CLI (`nlm`):**
  - Conexión dinámica al cuaderno *curso2. residentes.Econ.salud* (`71ff8d57-211a-407e-8fc2-728114e4a70c`).
  - Extracción en tiempo real de la fuente oficial *01_PROGRAMA_ACADEMICO_ECONOMIA_DE_LA_SALUD_2026.md* (`0bd50821-1ba0-4603-8574-76939e34642c`, 26.022 caracteres).
- **Arquetipo de Presentación de Programa Académico Oficial (60s):**
  - Ficha institucional con 4 métricas clave: 8 semanas, 60 horas reloj acreditadas, 100% virtual asincrónica, Leyes Provinciales 7857/9526.
  - Síntesis de competencias andragógicas: Costo de oportunidad bioético, fallas de Arrow (1963) y evaluación económica (QALYs/AVAC).
  - Recorrido completo por las 8 Unidades del curso del Lic. Gustavo Muñoz Gatón.
  - Diagrama de flujo del *Sistema de Doble Candado Automatizado* (Examen Final Integrador ≥ 70% + Encuesta de Calidad obligatoria).
  - Línea de tiempo Gantt de cursado semana a semana.
- **Nueva Banda Sonora:**
  - `bgm-institucional-esalud-60s.wav`: Progresión armónica serena e inspiradora (*Cmaj9 -> Em7 -> Fmaj9 -> G6*) con pulsos de marimba y calibrada a 60.0 segundos a volumen 18%.
- **Nueva Plantilla Registrada:**
  - `templates/programa-academico-economia-salud-60s.html`

## [v1.5.0] - 2026-10-19: Serie Completa de Microlearning en Gestión de Salud (Unidades 2 a 8)
### 🧠 Nuevas Habilidades, Diseños Temáticos y Audio Suite
- **Consolidación de la Serie Formativa Completa (Unidades 2 a 8):**
  - **Unidad 4 (Ambulatoria):** Solución al fenómeno *No-Show* (35% ausentismo), categorización de agendas y citación escalonada.
  - **Unidad 5 (Epidemiológica):** Aplicación práctica del *ASIS Mendoza* para toma de decisiones y asignación de recursos.
  - **Unidad 6 (Legal & Seguridad):** La historia clínica como documento legal y modelo *Reason* de causas raíz en el error médico.
  - **Unidad 7 (Planificación):** Articulación de los 3 niveles directivos (*Estratégico, Táctico y Operacional*).
  - **Unidad 8 (Bioética & Costos):** Principio de *Costo de Oportunidad* y justicia distributiva en el hospital público.
- **Suite de Audio Dedicada (5 Nuevas Pistas Sonoras Originales):**
  - `bgm-u4-schedule-45s.wav`: Ritmo de agenda y pulsos cronométricos.
  - `bgm-u5-data-45s.wav`: Ondas analíticas y pulsos de datos demográficos.
  - `bgm-u6-legal-45s.wav`: Atmósfera solemne y armónicos de seguridad jurídica.
  - `bgm-u7-strategic-45s.wav`: Progresión armónica de visión de futuro y metas.
  - `bgm-u8-economics-45s.wav`: Cadencia bioética y balance distributivo.
- **Calibración de Contraste Accesible WCAG AA:**
  - Optimización cromática en degradados institucionales y botones CTA para superar el ratio de contraste 3:1 exigido por el motor headless.
- **Nuevas Plantillas Registradas:**
  - `templates/unidad4-consultorios-externos-45s.html`
  - `templates/unidad5-epidemiologia-asis-45s.html`
  - `templates/unidad6-marco-legal-error-medico-45s.html`
  - `templates/unidad7-planificacion-en-salud-45s.html`
  - `templates/unidad8-economia-salud-costos-45s.html`

## [v1.4.0] - 2026-10-19: Arquetipo de Red Sistémica RISS & Network Synapse BGM
### 🧠 Nuevas Habilidades y Arquetipos
- **Arquetipo de Red Sistémica de Salud (RISS):**
  - Representación visual de nodos asistenciales interconectados: nodo Centro de Salud (CAPS) de primer nivel, nodo Hospital Complejo de tercer nivel y puente interactivo central con derivación y contrarreferencia activa.
  - Gauge radial de impacto asistencial (medidor de código verde al 70%) para ilustrar la sobrecarga de guardia evitable.
- **Nueva Pista Sonora Network Synapse Synth:**
  - Banda sonora original de pulsos sinápticos y sintetizador armónico (`bgm-network-synapse-45s.wav`) en progresión *C#m -> Aadd9 -> E -> B* a 45.0s y volumen 18%.
- **Nueva Plantilla Registrada:**
  - `templates/unidad3-hospital-caps-redes-45s.html`: Video formativo panorámico (16:9, 45s, 1080p) con carril de subtítulos sincronizado palabra a palabra.

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
