# Temas Beamer para la Universidad Nacional de Colombia y la Universidad Distrital

Este repositorio contiene el desarrollo de temas y plantillas para presentaciones en LaTeX Beamer, adaptados a la identidad visual de la **Universidad Nacional de Colombia** y la **Universidad Distrital Francisco José de Caldas**. El objetivo es facilitar la creación de diapositivas profesionales y coherentes con la imagen institucional de ambas universidades.

## Contenido

### Temas

El repositorio incluye los siguientes temas coordinados para cada universidad:

#### Universidad Nacional de Colombia

- `beamercolorthemeunal.sty` (tema de colores)
- `beamerfontthemeunal.sty` (tema de fuentes)
- `beamerinnerthemeunal.sty` (tema interno)
- `beamerouterthemeunal.sty` (tema externo)
- `beamerthemeunal.sty` (tema principal que integra los anteriores)

#### Universidad Distrital Francisco José de Caldas

- `beamercolorthemeud.sty` (tema de colores)
- `beamerfontthemeud.sty` (tema de fuentes)
- `beamerinnerthemeud.sty` (tema interno)
- `beamerouterthemeud.sty` (tema externo)
- `beamerthemeud.sty` (tema principal que integra los anteriores)

### Plantillas

Se incluyen ejemplos de uso para cada tema:

- `unal-theme-example.tex` (ejemplo para la Universidad Nacional)
- `ud-theme-example.tex` (ejemplo para la Universidad Distrital)

Además, se recomienda incluir los logos oficiales en la carpeta `images/` para cada universidad.

## Uso

Para utilizar estos temas en tus presentaciones Beamer:

1. Descarga o clona este repositorio.
2. Coloca los archivos `.sty` y la carpeta `images` en el mismo directorio que tu archivo `.tex`.
3. En el preámbulo de tu documento, selecciona el tema deseado, por ejemplo:

   ```latex
   \usetheme{unal}
   % o
   \usetheme{ud}
   ```

4. Compila tu presentación como de costumbre.

Puedes personalizar los colores, fuentes o logos editando directamente los archivos `.sty` correspondientes.

## Desarrollo

Estos temas están en desarrollo activo. Si tienes sugerencias, mejoras o encuentras errores, por favor abre un issue o envía un pull request.

## Créditos y agradecimientos

Este trabajo es un fork del excelente [beamertheme-uconn](https://github.com/ctsit/beamertheme-uconn) desarrollado por [ctsit](https://github.com/ctsit). Agradecemos al autor original por su aporte a la comunidad y por permitir la adaptación de su trabajo a otras instituciones.

---
