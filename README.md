# David Naranjo López — Página de presentación personal

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

## Publicar en GitHub Pages

1. Crear un repositorio llamado `naranjodavid04.github.io`.
2. Subir estos archivos (index.html en la raíz).
3. La página quedará en https://naranjodavid04.github.io

## Secciones editables

- **Certificados en curso** (`index.html`, sección `#certificados`): duplicar el bloque
  `<div class="cert cert--pending">` por cada certificación y reemplazar el texto.
- **Proyectos**: cada proyecto es un `<article class="project">`; los destacados llevan
  además la clase `project--featured`.
