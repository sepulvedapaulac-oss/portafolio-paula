# Portafolio · Paula Sepúlveda Caniuqueo

Sitio estático (sin servidor ni base de datos) con los proyectos y una muestra interactiva de cada curso.

## Contenido
- `index.html`: el portafolio. Los cursos nuevos están al inicio de «Proyectos» y hay filtros por área.
- `muestras/`: una lección y una actividad o laboratorio de cada curso, tal como salen del compilador (sin `imsmanifest.xml`):
  Ley Karin · Legislación Laboral · Diversidad e Inclusión · PEMP · Administración de Bodega · IA en Remuneraciones · Herramientas Digitales PYMES · Evaluación Diagnóstica de Excel · Comunicación Efectiva · Liderazgo Gentil · Servicio al Cliente (laboratorio 3C).
- La evaluación de Excel está en modo demostración: los resultados de quien la pruebe quedan solo en su navegador y no llegan a la planilla real.

## Muestras que faltan
Los proyectos que ya estaban en el portafolio apuntan a carpetas que no están en ningún repositorio. Si las tienes, cópialas así y aparecerán solas:

```
scorm/apilador-electrico/index.html
scorm/legislacion-sanitaria/index.html
scorm/informes-tecnicos/index.html
scorm/liderazgo-efectivo/index.html
scorm/ley-manejo-datos/index.html
scorm/supermercado/index.html
scorm/servicio-cliente/index.html
scorm/alfabetizacion-digital/index.html
videos/autoliderazgo.mp4
videos/grua-horquilla.mp4
```
Mientras falten, el botón muestra «Esta muestra se comparte a pedido» en vez de un error.

## Publicación
El sitio se publica con GitHub Pages desde la rama `main` de este repositorio:
https://sepulvedapaulac-oss.github.io/portafolio-paula/
Cada cambio que se sube a `main` se publica solo en uno o dos minutos.

## Revisar en tu computador
`python3 -m http.server` dentro de la carpeta y abre http://localhost:8000. Abrir `index.html` con doble clic también funciona, aunque algunos navegadores bloquean las muestras dentro de marcos al abrir archivos locales.
