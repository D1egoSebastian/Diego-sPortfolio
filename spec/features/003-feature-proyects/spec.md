# Fase 3: Proyectos

- **Descripción:** Proporcionar al agente la información de proyectos para el portafolio.

## Proyecto 1: Diego's Mind

- **URL:** https://github.com/D1egoSebastian/DiegosMind
- **Nombre:** Diego's Mind — Blog Personal Full-Stack
- **Descripción:** Aplicación web personal de blog/diario donde publico posts sobre videojuegos, películas, libros, filosofía y pensamientos. Incluye un panel de administración con autenticación para gestionar el contenido (CRUD de posts, categorías y tags) y una vista pública para los lectores con filtros por categoría, calificaciones y animaciones.
- **Layout recomendado:** `showcase` (1 a 3 proyectos; cada proyecto ocupa una tarjeta de ancho completo)

### Tecnologías
| Capa | Tecnologías |
|---|---|
| Frontend | Next.js 16, React 19, TypeScript, Tailwind CSS v4, Framer Motion |
| Backend | ASP.NET Core 10 Web API (C#), Entity Framework Core 10, JWT Bearer Auth |
| Base de Datos | PostgreSQL |
| Infraestructura | Docker, Cloudinary, Vercel |
| Herramientas | BCrypt, Scalar, OpenAPI/Swagger |

## Proyecto 2: Control De Finanzas IA

- **URL:** https://github.com/D1egoSebastian/ControlFinanzas
- **Nombre (en el portfolio):** Control De Finanzas IA (el repositorio y el producto se llaman `ControlDeFinanzasIA`)
- **Descripción (corta y directa):** Aplicación de escritorio para llevar el control de las finanzas personales (gastos, ingresos, presupuestos, metas de ahorro y deudas) con un asistente de IA opcional. Desarrollada con Spec-Driven Development (SDD): cada funcionalidad se define en una especificación antes de implementarse. No detallar el entorno técnico en la descripción; eso va en los tags.
- **Estado (honesto):** Windows es la única plataforma ejecutada y probada; los builds de macOS y Linux están generados pero sin probar en hardware real. Todavía no hay release publicado ni binarios firmados. No presentar el proyecto como "publicado" ni "multiplataforma probado".
- **Imagen / portada:** captura del dashboard en `/images/projects/controlfinanzasia.png`. Se usa como portada en la sección Projects, en el slider "Featured Projects" del Hero (`sliderImage`, `sliderOrder: 2`) y no requiere imagen adicional.
- **En el CV impreso:** `resume: true`.
- **En "Projects & Ventures":** segunda tarjeta en `serviceSites` de `src/data/site.json`, con el mismo nombre "Control De Finanzas IA".

### Tecnologías
| Capa | Tecnologías |
|---|---|
| UI | Avalonia UI (MVVM), C# |
| Plataforma | .NET 8 (LTS), desarrollo cross-platform |
| Datos | SQLite, Entity Framework Core (Code First) |
| IA | Integración BYO con APIs compatibles con OpenAI / Anthropic / OpenRouter |
| Calidad | xUnit, NetArchTest |

## Portfolio (Client Work)
- Actualmente no hay trabajo freelance para mostrar. La sección debe quedar oculta o con array vacío.

## Certificaciones
(Incluidas en spec de Fase 1)

## Criterios de Aceptación

- [ ] El proyecto Diego's Mind se muestra en la sección Projects con layout showcase
- [ ] El proyecto "Control De Finanzas IA" se muestra en Projects (con portada), en el slider "Featured Projects", en la tarjeta de "Projects & Ventures" y en el CV impreso
- [ ] El slider del Hero no muestra proyectos (o se oculta si está vacío)
- [ ] La sección Portfolio no se muestra o aparece vacía sin romper el layout
- [ ] Las certificaciones aparecen en su sección correspondiente

## Casos Borde

- Con solo 1 proyecto, el layout showcase debe verse completo sin espacios vacíos
- Si no hay imágenes de slider, la card debe mostrarse sin imagen de fondo
- Portfolio vacío no debe causar errores de renderizado
