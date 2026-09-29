# Componentes visuales del perfil

El perfil combina una cabecera con ondas, una línea de escritura animada e iconos de las tecnologías. Los componentes descargados se incluyen en `assets` para que puedas subirlos junto a los README.

| Componente | Proyecto original | Uso |
| --- | --- | --- |
| Iconos de tecnologías | [Skill Icons](https://github.com/tandpfun/skill-icons) | Java, MySQL para SQL, Git, HTML, CSS, JavaScript, PHP y Python. |
| Escritura animada | [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg) | Tres frases en cada idioma; versiones clara y oscura. |
| Cabecera con ondas | [Capsule Render](https://github.com/kyechan99/capsule-render) | Nombre breve, subtítulo y degradado personalizado. |

Los archivos de licencia de estos proyectos están incluidos en `assets`. El pie de página es un SVG propio que retoma los colores de la cabecera.

## Color y movimiento

Se usa una armonía de lavanda, azul y turquesa, con un pequeño acento melocotón. El objetivo es combinar interés visual con continuidad entre las secciones. Es una decisión de diseño; las asociaciones emocionales de los colores no son universales.

La cabecera anima las ondas en ciclos largos y el texto aparece suavemente. La línea de escritura incluye pausas. La cabecera y la escritura tienen versiones para fondos claros y oscuros. Las imágenes tienen texto alternativo; las tecnologías y los intereses también aparecen como texto en el README.

## Subida

Sube `README.md`, `README.en.md`, `VISUALS.md`, `ASSET_SOURCES.json` y **toda la carpeta `assets`** al repositorio público `cgonmat0908b`. No necesitas instalar extensiones ni configurar GitHub Actions.

Los SVG de la cabecera tienen una forma inicial estática de respaldo para los lectores que no reproduzcan la animación. Los SVG animados conservan su movimiento al descargarlos del generador; al alojarlos en tu propio repositorio no requieren consultar las API de generación. En la versión clara se ajustó el color del texto para mejorar el contraste sobre las ondas translúcidas.

Como referencia para la legibilidad se ha utilizado el [criterio de contraste del W3C](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html). Esto orienta los ajustes de color; no constituye una auditoría completa de accesibilidad del perfil en GitHub.

## Cambiar las frases o los iconos

Para regenerar las imágenes, consulta [ASSET_SOURCES.json](ASSET_SOURCES.json), que conserva las direcciones públicas utilizadas y los parámetros de personalización. Las API pueden cambiar con el tiempo.

Referencias consultadas el 30 de septiembre de 2026, hora de España.
