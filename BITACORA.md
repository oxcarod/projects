# Bitácora de Cambios — Centro de Mando

Registro de avances, decisiones y cambios realizados en el centro de mando.

---

## 2026-03-24 — Sesión inicial: Setup completo

### Lo que se hizo

- **Git configurado globalmente**
  - Usuario: `Stark`
  - Email: `oxcarod@hotmail.com`
  - Propósito: identidad en todos los commits

- **GitHub CLI instalado**
  - Herramienta `gh` instalada via winget
  - Cuenta `oxcarod` autenticada por navegador
  - Protocolo HTTPS para push/pull

- **Repos `projects/` creado**
  - Archivo: `CLAUDE.md` (centro de mando raíz)
  - Archivo: `USO.md` (guía de uso)
  - Carpeta: `_templates/proyecto-claude.md` (plantilla para proyectos)
  - Archivo: `.gitignore` (excluye subproyectos)
  - Repo: https://github.com/oxcarod/projects
  - Estado: 1 commit — Initial commit

- **Repos `asistente/` creado**
  - Archivo: `CLAUDE.md` (contexto del asistente)
  - Carpetas: `notas/`, `ideas/`, `pendientes/`, `datos/`
  - Repo: https://github.com/oxcarod/asistente
  - Estado: 1 commit — Initial commit

- **Decisiones tomadas**
  - Repos por proyecto (no un repo grande)
  - Todos los proyectos apuntan al mismo usuario GitHub: `oxcarod`
  - Cada proyecto nuevo recibe CLAUDE.md interno con plantilla
  - Centro de mando ignore los subproyectos para evitar duplicación

### Próximos pasos pendientes

- [ ] Agregar primer contenido al asistente (nota, idea o pendiente)
- [ ] Registrar proyecto existente en `Claude Projects/`
- [ ] Vincular `medSystem` al centro de mando
- [ ] Explorar la carpeta `Claude Projects/` y registrar lo que hay

---

*Última actualización: 2026-03-24*
