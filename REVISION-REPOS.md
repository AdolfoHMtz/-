# Revisión de repositorios — AdolfoHMtz

Revisión de los 27 repositorios de la cuenta (octubre 2026): lo que contiene cada uno y qué conviene hacer con él.

## ⭐ Conservar y destacar (fijar en el perfil)

Elige 6 para fijar (GitHub → *Customize your pins*):

| Repo | Por qué | Mejora sugerida |
|---|---|---|
| `ProjectSO2-simulators` | El mejor README, demo en vivo y TypeScript | Ninguna, es el modelo a seguir |
| `PeliculasAPP` | Angular + Ionic, consume una API y tiene demo | Agregar capturas al README |
| `Proyecto-Desarrollo-de-Aplicaciones-Moviles` | Proyecto full-stack (Angular + Django) | Descripción en inglés o español sin errores ("Poryecto") |
| `TareAPP` | Ionic, tiene demo | Agregar capturas |
| `Matematicas-Discretas` | React, tiene demo | Agregar descripción al repo |
| `Memory-Management-Pagination` | Simulador visual | **Le falta README**: agrega descripción y demo |

## 🔒 Privados (no se ven en el perfil)

- `SImuladorExam-v1`: tu proyecto activo. Cuando sea presentable, hazlo público y corrige el nombre (`SimuladorExam`).
- `app_movil_escolar_api`: está duplicado dentro de `Proyecto-Desarrollo-de-Aplicaciones-Moviles`, así que puede quedarse privado o archivarse.

## 📦 Conservar, pero archivar (*Settings → Archive*)

Son tareas escolares con valor histórico. Archivar las marca como "solo lectura" sin borrarlas.

- `Programacion1`: ejercicios en C++
- `Mat.Discretas`: prácticas de HTML
- `Memorama`, `Tic-Tac_Toe`, `SumasyRestas`, `Ordinario`: primeros proyectos web de 2022. Les falta README; si los conservas, agrégales una línea de descripción.
- `CalidaddeSoftware`: un solo archivo `.cpp`
- `Memory-Management`: versión anterior de `Memory-Management-Pagination` (mismo proyecto). Archívalo o bórralo.
- `app-movil-escolar-webapp`: versión casi idéntica de `Proyecto-Desarrollo-de-Aplicaciones-Moviles` (solo agrega `netlify.toml`). Quédate con uno.

## 🗑️ Candidatos a eliminar

| Repo | Motivo |
|---|---|
| `-` | Sin nombre real y sin contenido. Ahora tiene este README de perfil: muévelo a `AdolfoHMtz/AdolfoHMtz` y borra este repo. |
| `prueb` | Plantilla vacía de React + Vite ("prueba") |
| `ProyectoIngSoftware` | Plantilla de Vite con el README por defecto; duplicado |
| `IngSoftwareProject` | Igual que el anterior; tres repos para el mismo proyecto |
| `Ing.Software` | Solo contiene `server.js` y **934 archivos de `node_modules`** subidos por error; `frontend` es un submódulo roto |
| `Proyecto-Discretas` | Solo tiene el README, está vacío |
| `App-Web-Barberia-US` | Solo tiene el README, está vacío (o súbele el código si existe) |
| `AprendizajeGit` (fork) | Fork de práctica sin cambios propios |
| `OmiPortal` (fork) | Fork de 2022 sin cambios propios |

> 💡 Si `Ing.Software` es el proyecto final real, en lugar de borrarlo mejor límpialo: agrega un `.gitignore` con `node_modules/`, ejecuta `git rm -r --cached backend/node_modules`, sube el código del frontend y escribe un README.

## ✅ Hábitos para que el perfil se vea profesional

1. **Todo repo público lleva README**: qué es, capturas, cómo ejecutarlo y el link a la demo.
2. **Descripción y *topics*** en cada repo (el engrane ⚙️ junto a "About").
3. **`.gitignore` siempre**: nunca subas `node_modules/`, `.env` ni contraseñas.
4. **Un proyecto = un repo.** Evita `prueb`, `-` y los duplicados.
5. **Nombres claros** en kebab-case: `simulador-examen`, `gestion-academica`.
6. Pon el link de la demo en el campo *Website* del repo.
