# Navaja Barbería — Sistema de reservas (demo)

Sitio de una sola página con un sistema de reservas online funcional para "Navaja", barbería ficticia (Formosa, Argentina). Pieza de demo/portfolio de [CEDETEC Digital](https://cedetec-digital.netlify.app/), pensada para prospección en el rubro de barberías y peluquerías.

No representa un negocio real: nombre, dirección, teléfono y contenido son de ejemplo. No tiene ningún vínculo con otros proyectos de demo del portfolio (por ejemplo, el restaurante Ámbar): es un repo y un sitio completamente independientes.

## Contenido

Sitio estático de un solo archivo (`index.html`, sin dependencias de build ni backend):

- Landing con servicios, equipo y ubicación.
- Sistema de reservas de 5 pasos (servicio → barbero → día y horario → datos del cliente → confirmación), con disponibilidad de horarios simulada de forma determinística.
- Al confirmar: genera un mensaje de WhatsApp pre-cargado, permite descargar un `.ics` para el calendario, y guarda el turno en `localStorage` del navegador para mostrarlo en "Mis próximos turnos".

## Deploy

Al ser HTML estático, se puede publicar directo en GitHub Pages, Netlify o Vercel apuntando a la raíz del repo.
