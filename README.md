# Nissan Versa - Carrera 80's

Juego de carreras arcade estilo años 80 (Nissan de los Altos, promoción de Julio).
El jugador maneja un **Nissan Versa** contra otro modelo Nissan (Sentra, Kicks o March,
elegido al azar en cada partida). Al terminar la carrera se muestran las
características del auto ganador junto con una promoción del Versa.

## Cómo jugarlo

Es un solo archivo HTML sin dependencias externas ni build step: `index.html`.

- **Local:** abre `index.html` directamente en el navegador, o sirve la carpeta
  con cualquier servidor estático, por ejemplo:
  ```
  python3 -m http.server 8080
  ```
  y entra a `http://localhost:8080/`.
- **Publicarlo:** al ser un sitio 100% estático, se puede subir a GitHub Pages,
  Netlify, Vercel o cualquier hosting estático simplemente copiando `index.html`.

## Controles

- **Escritorio:** flechas ← → (o A/D) para esquivar, `Espacio` para usar el boost NOS.
- **Móvil:** botones táctiles en pantalla o deslizar el dedo hacia la izquierda/derecha.

## Contenido

Las características de los autos (Versa, Sentra, Kicks, March) están en el objeto
`CARS` dentro de `index.html`; son de referencia con fines promocionales.
