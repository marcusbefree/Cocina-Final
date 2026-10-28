# Cocina Valle Real · Horario

Horario semanal de la cocina (de jueves a miércoles). Es una sola página (`index.html`) publicada con GitHub Pages. El horario vive en `horario.json`.

## Para el equipo

- Abre la página, toca tu nombre y el teléfono lo recuerda.
- **📅 Agregar a mi calendario** te suscribe a `calendario/<tu-id>.ics`. En iPhone se abre Calendario y en Google Calendar se agrega desde el navegador. Cada vez que se publica, tu calendario se actualiza solo.
- **💬 Avisar al encargado** manda por WhatsApp qué limpiezas terminaste.

## Para el encargado

1. Toca 🔒 y escribe el PIN.
2. Edita las celdas o usa los pinceles de abajo.
3. La primera vez, entra a **⋯ → Conexión para publicar** y pega un *fine-grained token* de GitHub con acceso solo a este repositorio y permiso **Contents: Read and write**. El token se guarda únicamente en ese navegador.
4. Toca **☁️ Publicar**. Se hace un solo commit con `horario.json` y los calendarios de cada persona. El equipo ve los cambios en 1 o 2 minutos.

Si alguien más publicó mientras editabas, la página no sobrescribe sus cambios. Te avisa y te deja elegir qué versión conservar.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La app completa |
| `horario.json` | Datos publicados: equipo, turnos y semanas |
| `calendario/*.ics` | Calendarios de suscripción, generados al publicar |
| `manifest.webmanifest`, `icon.svg` | Para instalarla en la pantalla de inicio |

El PIN solo evita ediciones accidentales. Lo que realmente protege el horario es el token de GitHub.
