# 🚀 Proyectos de Hackathons

Este directorio contiene los proyectos participantes de cada hackathon.

## ¿Cómo agregar tu proyecto?

1. **Fork** este repositorio
2. **Editá** el archivo JSON de la hackathon correspondiente (ej: `foundations.json`)
3. **Agregá** tu proyecto al array `projects`
4. **Hacé un PR** con tu proyecto

## Estructura de un proyecto

```json
{
  "id": "mi-proyecto",
  "name": "Nombre del Proyecto",
  "description": "Descripción corta de qué hace tu proyecto.",
  "team": [
    {
      "name": "Tu Nombre",
      "github": "tu-github-username",
      "role": "Lead Dev"
    }
  ],
  "repo": "https://github.com/tu-usuario/tu-repo",
  "demo": "https://tu-demo.vercel.app",
  "tech": ["TypeScript", "React", "Lightning"],
  "status": "building",
  "submittedAt": "2026-03-03"
}
```

## Campos

| Campo | Requerido | Descripción |
|-------|-----------|-------------|
| `id` | ✅ | ID único (lowercase, guiones) |
| `name` | ✅ | Nombre del proyecto |
| `description` | ✅ | Descripción corta (max 200 chars) |
| `team` | ✅ | Array de miembros del equipo |
| `status` | ✅ | Estado actual del proyecto |
| `repo` | ❌ | Link al repositorio |
| `demo` | ❌ | Link a demo/preview |
| `tech` | ❌ | Tecnologías usadas |
| `submittedAt` | ❌ | Fecha de inscripción (YYYY-MM-DD) |

## Estados posibles

- `idea` - Solo una idea, sin código
- `building` - En desarrollo
- `submitted` - Entregado para evaluación
- `finalist` - Seleccionado como finalista
- `winner` - Ganador 🏆

## Archivos por hackathon

- `foundations.json` - Marzo 2026 (⚡ ACTIVA)
- `identity.json` - Abril 2026
- `zaps.json` - Mayo 2026
- `commerce.json` - Junio 2026
- `media.json` - Julio 2026
- `ai-agents.json` - Agosto 2026
- `infrastructure.json` - Septiembre 2026
- `integration.json` - Octubre 2026

---

¿Dudas? Preguntá en el [Discord de La Crypta](https://discord.com/invite/SN8JNhMgvY) ⚡
