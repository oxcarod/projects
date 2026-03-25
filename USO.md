# Guía de Uso — Centro de Mando de Proyectos

## Estructura

```
Documents/projects/
├── CLAUDE.md           ← Centro de mando (este archivo)
├── USO.md              ← Esta guía
├── _templates/         ← Plantillas
│   └── proyecto-claude.md
└── [proyecto-1]/       ← Tus proyectos
    ├── .git/
    └── CLAUDE.md
```

## Flujos de trabajo

### 1. Crear un proyecto nuevo
Desde `projects/` (o cualquier subcarpeta), dime:
> "Crea el proyecto X con descripción Y"

Yo me encargo de:
- Crear la carpeta
- Inicializar el repo Git
- Crear el CLAUDE.md interno con la plantilla
- Registrarlo en el centro de mando

### 2. Trabajar en un proyecto específico
Abre Claude Code apuntando a la subcarpeta del proyecto:
```
cd Documents/projects/mi-proyecto
claude
```
Así tendrás el contexto de ese proyecto específico.

### 3. Sincronizar con GitHub
Cuando quieras subir un proyecto:
1. Crea el repo en github.com (púgilco o privado)
2. Dime "sube el proyecto X a GitHub" y me pasas la URL del repo
3. Yo lo vinculo y hago el primer push

### 4. Ver todos los proyectos
Desde `projects/`, dime:
> "Dame un resumen de todos mis proyectos"
> "¿Qué cambios pendientes tengo?"

Yo leo el CLAUDE.md raíz y los repos Git y te doy el panorama completo.

### 5. Registrar un proyecto existente
Si ya tienes una carpeta con código en `projects/`:
> "Registra el proyecto X que ya existe"

Yo le agrego Git y el CLAUDE.md interno.

## Configuración Git

- Usuario GitHub: **oxcarod**
- Email commits: **oxcarod@hotmail.com**
- Nombre en commits: **Stark**
