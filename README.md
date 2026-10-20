# EducAI & HyperFrames Video Render Suite 🎓🎬

Paquete integral, agente especializado y banco de plantillas para **Antigravity** que permite diseñar, animar y renderizar videos programáticos profesionales para **Entornos Virtuales de Aprendizaje (LMS / Moodle)**, plataformas EdTech y capacitaciones corporativas utilizando el motor de renderizado de video web **HyperFrames**.

Desarrollado a partir de lecciones aprendidas en producción real, resolución de conflictos de determinismo GSAP, diseño de audio multinivel y validaciones automáticas WCAG AA en Chrome Headless.

---

## 🌟 Características Principales

1. **Agente Especializado:**
   * [`agents/edtech-video-director.md`](agents/edtech-video-director.md): Director de video educativo y diseñador instruccional con reglas de determinismo, navegación paso a paso y arquitectura tripartita.
2. **Skill Antigravity:**
   * [`skills/edtech-moodle-video/SKILL.md`](skills/edtech-moodle-video/SKILL.md): Metodología para crear recorridos interactivos de Moodle, demostraciones de paquetes SCORM 1.2 y sincronización de notas en tiempo real.
3. **Plantillas Maestras Renderizadas y Verificadas:**
   * `templates/moodle-showcase-60s.html`: Video promocional de alto impacto (1080p, 60 segundos) comparando aula tradicional vs. Aula Piloto Tripartita.
   * `templates/moodle-vertical-9-16.html`: Adaptación para dispositivos móviles (1080×1920) para Instagram Reels, TikTok y YouTube Shorts.
   * `templates/moodle-makeover-90s.html`: Presentación del Kit Makeover / Renovación de Aula en 8 escenas.
   * `templates/moodle-tutorial-120s.html`: Tutorial técnico de 120 segundos con cursor reactivo animado, Step Progress Bar y llamada de advertencia en opciones críticas de Moodle.
4. **Diseño Sonoro Multicapa Portable:**
   * Música de fondo calibrada al 15% - 30% (`data-volume="0.15"`).
   * 10 efectos sonoros diegéticos sincronizados incluidos en `assets/audio/` (Clicks, Swooshes, Pops, Chimes, Notificaciones y Bass Impact).

---

## 💻 Cómo Replicar e Instalar en Otra Computadora con Antigravity

Si estás configurando este entorno de trabajo en otra computadora con tu usuario de Antigravity / Gemini:

### Paso 1: Clonar el Repositorio
```bash
git clone https://github.com/superpollo02/educai-hyperframes-video-render.git
cd educai-hyperframes-video-render
```

### Paso 2: Instalar el Plugin en Antigravity Global
Copia el directorio o enlázalo a la carpeta global de plugins de Antigravity:

* **En Windows (PowerShell):**
  ```powershell
  $dest = "$HOME\.gemini\config\plugins\educai-hyperframes"
  New-Item -ItemType Directory -Path $dest -Force
  Copy-Item -Path ".\*" -Destination $dest -Recurse -Force
  ```
* **En macOS / Linux:**
  ```bash
  mkdir -p ~/.gemini/config/plugins/educai-hyperframes
  cp -r ./* ~/.gemini/config/plugins/educai-hyperframes/
  ```

### Paso 3: Reiniciar la Sesión de Antigravity
Al reiniciar el editor o abrir una nueva conversación, Antigravity detectará automáticamente:
* El agente **EdTech Video Director** (`agents/edtech-video-director.md`).
* La habilidad **edtech-moodle-video** (`skills/edtech-moodle-video/SKILL.md`).
* Las directivas de renderizado y el ciclo de aprendizaje continuo (`AGENTS.md`).

---

## 🚀 Comandos del Flujo de Trabajo (HyperFrames CLI)

Para trabajar sobre cualquiera de las plantillas o iniciar un nuevo video:

```bash
# 1. Previsualizar en vivo en el navegador (hot reload)
npx hyperframes preview

# 2. Validar tiempos, layout, oclusiones y contraste WCAG AA
npx hyperframes check

# 3. Renderizar a video final MP4 (1080p determinista)
npx hyperframes render
```

---

## 🔄 El Ciclo de Aprendizaje Continuo (Session Distillation Protocol)

Este repositorio opera bajo una directiva permanente de auto-mejora:
1. **Detección**: En cada sesión de trabajo, el asistente de IA identifica activamente nuevos patrones, trucos de animación, soluciones a bugs de layout o requerimientos didácticos no documentados previamente.
2. **Cristalización**: Los aprendizajes se empaquetan en un sub-agente, una nueva habilidad ejecutable (`SKILL.md`) o una nueva plantilla HTML verificada.
3. **Respaldo Automático**: Al concluir la sesión, el asistente actualiza el `CHANGELOG.md`, el `README.md` y realiza un `git push` a este repositorio para asegurar la persistencia en la nube.

---

## 🛡️ Lecciones de Ingeniería Aprendidas
- **Resolución de Oclusión y Overlap:** Integración de directivas `data-layout-allow-overlap="true"` y `data-layout-allow-occlusion="true"` para elementos flotantes (sellos, tarjetas y cursores).
- **Prohibición de CSS Transitions:** Toda animación de cambio de estado se controla exclusivamente a través de la timeline pausada de GSAP (`window.__timelines["main"]`).
- **Normalización de Audio:** Balance estéreo y recorte dinámico conforme a la duración física del archivo (`-1 dBTP`).

---

Licencia: MIT · Creado con Antigravity & HyperFrames por superpollo02.
