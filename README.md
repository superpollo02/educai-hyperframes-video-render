# EducAI & HyperFrames Video Render Suite 🎓🎬

Paquete integral y agente especializado para **Antigravity** que permite diseñar, animar y renderizar videos programáticos profesionales para **Entornos Virtuales de Aprendizaje (LMS / Moodle)**, plataformas EdTech y capacitaciones corporativas utilizando el motor **HyperFrames**.

Desarrollado a partir de lecciones aprendidas en producción real, resolución de conflictos de determinismo GSAP, diseño de audio multinivel y validaciones automáticas WCAG AA en Chrome Headless.

---

## 🌟 Características Principales

1. **Agente Especializado:**
   * [`agents/edtech-video-director.md`](agents/edtech-video-director.md): Director de video educativo y diseñador instruccional con reglas estrictas de determinismo, navegación paso a paso y arquitectura tripartita.
2. **Skill Antigravity:**
   * [`skills/edtech-moodle-video/SKILL.md`](skills/edtech-moodle-video/SKILL.md): Metodología para crear recorridos interactivos de Moodle, demostraciones de paquetes SCORM 1.2 y sincronización de notas en tiempo real.
3. **Plantillas Maestras Renderizadas y Verificadas:**
   * `templates/moodle-showcase-60s.html`: Video promocional de alto impacto (1080p, 60 segundos) comparando aula tradicional vs. Aula Piloto Tripartita.
   * `templates/moodle-vertical-9-16.html`: Adaptación para dispositivos móviles (1080×1920) para Instagram Reels, TikTok y YouTube Shorts.
   * `templates/moodle-makeover-90s.html`: Presentación completa del Kit Makeover / Renovación de Aula en 8 escenas.
   * `templates/moodle-tutorial-120s.html`: Tutorial técnico de 120 segundos con cursor reactivo animado, Step Progress Bar y llamada de advertencia en opciones críticas de Moodle.
4. **Diseño Sonoro Multicapa:**
   * Música de fondo calibrada al 15% - 30% (`data-volume="0.15"`).
   * 10 efectos sonoros diegéticos sincronizados (Clicks, Swooshes, Pops, Chimes, Notificaciones y Bass Impact).

---

## 🚀 Uso Rápido con HyperFrames CLI

```bash
# Previsualizar en vivo en el navegador
npx hyperframes preview

# Validar tiempos, layout, oclusiones y contraste WCAG AA
npx hyperframes check

# Renderizar a video final MP4
npx hyperframes render
```

---

## 🛡️ Lecciones de Ingeniería Aprendidas
- **Resolución de Oclusión y Overlap:** Integración de directivas `data-layout-allow-overlap="true"` y `data-layout-allow-occlusion="true"` para elementos flotantes (sellos, tarjetas y cursores).
- **Prohibición de CSS Transitions:** Toda animación de cambio de estado se controla exclusivamente a través de la timeline pausada de GSAP.
- **Normalización de Audio:** Balance estéreo y recorte dinámico conforme a la duración física del archivo (`-1 dBTP`).

---

Licencia: MIT · Creado con Antigravity & HyperFrames por superpollo02.
