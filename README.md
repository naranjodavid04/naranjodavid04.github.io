# David Naranjo López — Página de presentación personal

**En línea:** https://naranjodavid04.github.io

Sitio estático (HTML + CSS + JS puro, sin dependencias) con estética editorial matemática.

## Estructura

```
index.html          Página principal (todas las secciones)
css/styles.css      Estilos
js/main.js          Animaciones de scroll y menú móvil
assets/
  retrato.jpeg      Foto de retrato (hero)
  cuerpo-completo.jpeg  Foto de cuerpo completo (intereses)
  docs/
    CV_David_Naranjo.pdf
    Certificado_Aptis_C1_David_Naranjo.pdf
```

## Ver en local

```
python -m http.server 8000
```

y abrir http://localhost:8000

## Actualizar la página publicada

Tras editar cualquier archivo:

```
git add -A
git commit -m "Descripción del cambio"
git push
```

GitHub Pages reconstruye el sitio automáticamente en 1–2 minutos.

## Secciones editables

- **Certificados en curso** (`index.html`, sección `#certificados`): duplicar el bloque
  `<div class="cert cert--pending">` por cada certificación y reemplazar el texto.
- **Proyectos**: cada proyecto es un `<article class="project">`; los destacados llevan
  además la clase `project--featured`.
