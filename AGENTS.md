# Directiva del Proyecto: Aprendizaje Continuo, Sub-Agentes y Respaldo en GitHub

Este documento rige el comportamiento de **Antigravity** en este repositorio y en cualquier estación de trabajo donde se clone.

---

## 🔄 El Ciclo de Aprendizaje Continuo (Session Distillation Protocol)

En cada sesión de trabajo sobre este proyecto de video renderizado con HyperFrames / EducAI:

### 1. Detección Proactiva de Aprendizajes y Patrones Nuevos
Al resolver cualquier desafío durante la sesión, el agente evaluará:
- **Soluciones a fallos técnicos y quirks de render:** Directivas no documentadas (ej. `data-layout-allow-occlusion`, `data-layout-allow-overlap`, evasión de advertencias de linter, límites de GPU headless).
- **Nuevos arquetipos de video:** Estructuras pedagógicas innovadoras, nuevos componentes de navegación (Step Progress Bar, timelines circulares, mapas interactivos) o simulaciones SCORM.
- **Calibración de sonido:** Frecuencias de corte, volúmenes de fondo (BGM ducking al 15%), sincronización de efectos diegéticos.

### 2. Auto-Empaquetado en Componentes de Antigravity
Todo aprendizaje consolidado debe plasmarse inmediatamente en la estructura estándar:
- **Sub-agente especializado:** En `agents/<nombre-agente>.md` con su rol, directivas y competencias clave.
- **Skill Antigravity:** En `skills/<nombre-skill>/SKILL.md` con su frontmatter YAML y metodología paso a paso.
- **Plantilla reproducible:** En `templates/<plantilla>.html`, verificada con `npx hyperframes check`.
- **Assets portables:** Cualquier audio (`.mp3`), fuente (`.woff2`) o gráfico se añade a `assets/`.

### 3. Registro y Respaldo Sincronizado en GitHub
Al terminar la tarea o antes del cierre de turno:
- Registrar los cambios en `CHANGELOG.md` siguiendo el versionado semántico.
- Actualizar el `README.md` con las nuevas capacidades y comandos de instalación.
- Ejecutar commit descriptivo y `git push` a:
  `https://github.com/superpollo02/educai-hyperframes-video-render`
