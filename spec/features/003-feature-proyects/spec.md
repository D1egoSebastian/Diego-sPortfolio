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

## Proyecto 2: ControlDeFinanzasIA

- **URL:** https://github.com/D1egoSebastian/ControlFinanzas
- **Nombre:** ControlDeFinanzasIA — Control de Finanzas Personales con IA
- **Descripción:** Aplicación de escritorio multiplataforma (Windows, macOS, Linux) para el control de finanzas personales asistido por IA. Los datos viven en un único archivo SQLite local, sin telemetría; las funciones de IA son opcionales y el usuario aporta su propia API key (BYO). Cubre gastos e ingresos, categorías, presupuestos, metas de ahorro, deudas con cuotas, recurrentes, calendario, dashboard, notificaciones, exportación a PDF/Excel, backup/restore e importación CSV/Excel. Interfaz en español (es-DO) e inglés.
- **Estado (honesto):** Windows es la única plataforma ejecutada y probada; los builds de macOS y Linux están generados pero sin probar en hardware real. Todavía no hay release publicado ni binarios firmados. No presentar el proyecto como "publicado" ni "multiplataforma probado".
- **Imagen:** no hay capturas de pantalla disponibles; la tarjeta usa el modo compacto (icono + tags). Agregar capturas cuando existan.
- **En el CV impreso:** `resume: true`.

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
- [ ] El proyecto ControlDeFinanzasIA se muestra en la sección Projects (modo compacto, sin imagen) y en el CV impreso
- [ ] El slider del Hero no muestra proyectos (o se oculta si está vacío)
- [ ] La sección Portfolio no se muestra o aparece vacía sin romper el layout
- [ ] Las certificaciones aparecen en su sección correspondiente

## Casos Borde

- Con solo 1 proyecto, el layout showcase debe verse completo sin espacios vacíos
- Si no hay imágenes de slider, la card debe mostrarse sin imagen de fondo
- Portfolio vacío no debe causar errores de renderizado
