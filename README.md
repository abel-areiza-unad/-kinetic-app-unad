# KINETIC — FIT COACH AI

**Prototipo funcional TRL5** · Proyecto de Grado · Ingeniería de Sistemas · UNAD 2026

> Aplicación móvil de entrenamiento físico adaptativo con agente virtual de inteligencia artificial y sistema de gamificación, orientada a mejorar la adherencia y motivación hacia la actividad física en usuarios del Área Metropolitana de Medellín.

---

## Descripción del proyecto

KINETIC es una solución de software móvil que integra tres componentes principales:

- **Sistema de recomendación adaptativo** — ajusta dinámicamente los planes de entrenamiento según el historial de rendimiento, nivel de fatiga y objetivos del usuario.
- **Agente virtual con IA (Nova AI)** — actúa como coach personalizado con interacción por chat en tiempo real, analizando el estado del usuario para adaptar la sesión del día.
- **Gamificación** — sistema de niveles, puntos de experiencia (XP), retos semanales, logros desbloqueables y tabla de posiciones comunitaria para mantener la motivación a largo plazo.

Este repositorio contiene el **prototipo funcional de nivel TRL5** desarrollado como evidencia del componente práctico de la Fase 4 del Proyecto de Grado.

---

## Pantallas implementadas

| Pantalla | Descripción |
|---|---|
| Splash / Onboarding | Presentación del producto y estado del agente IA |
| Configuración de perfil | Formulario de datos personales, objetivo fitness y nivel de actividad |
| Primeros pasos (Nova AI) | Bienvenida personalizada con insight del coach virtual |
| Dashboard principal | Resumen de nivel, XP, racha activa y entrenamiento del día |
| Plan de entrenamiento | Selección de día, lista de ejercicios con intensidad y grupos musculares |
| Entrenamiento activo | Temporizador en tiempo real, contador de repeticiones y tips del coach |
| Coach Virtual AI | Chat interactivo con respuestas contextualizadas del agente Nova AI |
| Logros y Desafíos | XP, nivel actual, retos semanales, insignias y ranking comunitario |
| Estadísticas y Análisis | Métricas de rendimiento, gráfica de tendencia de peso e insights de IA |
| Ajustes y Perfil | Datos de usuario, dispositivos conectados, notificaciones y estado de rendimiento |

---

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de todas las pantallas |
| CSS3 | Diseño visual, animaciones, variables de color, layout responsivo |
| JavaScript (Vanilla) | Lógica de navegación, temporizador, chat mock, interactividad |

Sin dependencias externas. No requiere servidor, instalación ni compilación.

---

## Cómo ejecutar el prototipo

```bash
# Clonar el repositorio
git clone https://github.com/abel-areiza-unad/-kinetic-app-unad.git

# Abrir directamente en el navegador
# Navegar a la carpeta y abrir index.html con doble clic
# o desde la terminal:
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

No se requiere ningún paso adicional. El prototipo es completamente autocontenido en un único archivo `index.html`.

---

## Funcionalidades interactivas del prototipo

- **Flujo de onboarding completo** — navegación desde splash hasta dashboard con selección de objetivos y nivel de actividad
- **Temporizador de entrenamiento** — cuenta regresiva de 60 segundos con anillo SVG animado que cambia a rojo en los últimos 10 segundos
- **Control de series** — avance automático de series (1/4 → 2/4 → ... → completado)
- **Contador de repeticiones** — botones `−` y `+` funcionales
- **Chat con Nova AI** — envío de mensajes por texto o respuestas rápidas, con respuestas rotativas del agente
- **Tabs de progreso** — alternancia entre panel de Logros y panel de Estadísticas
- **Toggles de notificaciones** — interruptores funcionales en la pantalla de perfil
- **Navegación por tab bar** — barra de navegación inferior persistente con estado activo por pantalla

---

## Nivel de maduración tecnológica (TRL)

Este prototipo corresponde al nivel **TRL 5 — Tecnología validada en entorno relevante**:

- La solución replica fielmente los flujos de usuario definidos en el diseño oficial (Figma)
- Demuestra la viabilidad funcional de los tres módulos principales del sistema (recomendación adaptativa, agente virtual, gamificación)
- Puede ser operado y evaluado por usuarios finales sin asistencia técnica
- Sirve como base para el desarrollo de la versión productiva con backend real, IA integrada y base de datos

---

## Información académica

| Campo | Detalle |
|---|---|
| Curso | Proyecto de Grado — Código 202016907 |
| Programa | Ingeniería de Sistemas |
| Escuela | ECBTI — Universidad Nacional Abierta y a Distancia (UNAD) |
| Fase | Fase 4 — Desarrollo de la propuesta Ingenieril |
| Tutor | Rubén Darío Ordóñez |
| Autor | Abel Dario Areiza Zabala |
| Período | 2026-1 |

---

## Diseño de referencia

El prototipo fue desarrollado a partir del diseño de alta fidelidad disponible en Figma:
[KINETIC APP — Figma Design](https://www.figma.com/design/5xrFCddG9dkhVGMS8BPJ2D/KINETIC-APP-UNAD)
