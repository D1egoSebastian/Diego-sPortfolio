# Fase 1: Información Personal

- **Descripción:** Proporcionar al agente toda la información personal para configurar el portafolio.

## Datos Personales

- **Nombre:** Diego Rodríguez
- **Título:** Ingeniero de Software
- **Enfoque:** Desarrollo Back-End, APIs con C# y ASP.NET Core, bases de datos relacionales y NoSQL, servicios RESTful, IA generativa y agentes inteligentes.
- **Foto:** `photo/pfp cv.jpg` (la Foto ponla mas estetica, un poco mas pequeña y en un marco redondeado)

## Certificaciones

- Scrum Foundation Professional — Certiprof 2025
- ASP.NET Core Backend C# — Udemy 2025
- API RESTful con Node.js / Express — Udemy 2026
- MySQL — Udemy 2025
- C# — Udemy 2024
- Fundamentos Desarrollo con IA — BigSchool 2026

## Contacto

- Teléfono: (849) 278-8810
- Email: sebastiandiegorr@gmail.com
- GitHub: github.com/D1egoSebastian
- LinkedIn: linkedin.com/in/diego-rodriguez-84a894322

## Idiomas

- Español: Nativo
- Inglés: B2 — Lectura técnica fluida

## Criterios de Aceptación

- [ ] El nombre y título aparecen correctamente en el Hero
- [ ] La foto de perfil se muestra en el Hero (desde `public/images/personal/portrait.png`)
- [ ] La bio extendida aparece en la sección About
- [ ] Los enlaces de contacto (email, teléfono, GitHub, LinkedIn) funcionan y están visibles
- [ ] Las certificaciones se muestran en la sección Certifications con nombre, emisor y fecha
- [ ] Los idiomas se muestran correctamente

## Casos Borde

- Si la foto no existe en la ruta esperada, el portafolio no debe mostrar imagen rota (ocultar el elemento)
- Si un campo de red social está vacío, no debe renderizar el enlace
- El teléfono debe tener formato para enlace `tel:` válido
