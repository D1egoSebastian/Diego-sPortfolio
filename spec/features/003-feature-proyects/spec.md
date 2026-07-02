# Fase 3: Proyectos

- **Descripción:** Proporcionar al agente la información de proyectos para el portafolio.

## Proyecto 1: Diego's Mind

- **URL:** https://github.com/D1egoSebastian/DiegosMind
- **Nombre:** Diego's Mind — Blog Personal Full-Stack
- **Descripción:** Aplicación web personal de blog/diario donde publico posts sobre videojuegos, películas, libros, filosofía y pensamientos. Incluye un panel de administración con autenticación para gestionar el contenido (CRUD de posts, categorías y tags) y una vista pública para los lectores con filtros por categoría, calificaciones y animaciones.
- **Layout recomendado:** `showcase` (solo 1 proyecto)

### Tecnologías
| Capa | Tecnologías |
|---|---|
| Frontend | Next.js 16, React 19, TypeScript, Tailwind CSS v4, Framer Motion |
| Backend | ASP.NET Core 10 Web API (C#), Entity Framework Core 10, JWT Bearer Auth |
| Base de Datos | PostgreSQL |
| Infraestructura | Docker, Cloudinary, Vercel |
| Herramientas | BCrypt, Scalar, OpenAPI/Swagger |

## Portfolio (Client Work)
- Actualmente no hay trabajo freelance para mostrar. La sección debe quedar oculta o con array vacío.

## Certificaciones
(Incluidas en spec de Fase 1)

## Criterios de Aceptación

- [ ] El proyecto Diego's Mind se muestra en la sección Projects con layout showcase
- [ ] El slider del Hero no muestra proyectos (o se oculta si está vacío)
- [ ] La sección Portfolio no se muestra o aparece vacía sin romper el layout
- [ ] Las certificaciones aparecen en su sección correspondiente

## Casos Borde

- Con solo 1 proyecto, el layout showcase debe verse completo sin espacios vacíos
- Si no hay imágenes de slider, la card debe mostrarse sin imagen de fondo
- Portfolio vacío no debe causar errores de renderizado
