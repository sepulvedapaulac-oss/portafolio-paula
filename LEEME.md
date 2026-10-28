# Portafolio · Paula Sepúlveda Caniuqueo

Sitio estático (sin servidor ni base de datos) con los proyectos y una muestra interactiva de cada curso.

## Contenido
- `index.html`: el portafolio. Los cursos nuevos están al inicio de «Proyectos» y hay filtros por área.
- `muestras/`: una lección y una actividad o laboratorio de cada curso, tal como salen del compilador (sin `imsmanifest.xml`):
  Ley Karin · Legislación Laboral · Diversidad e Inclusión · PEMP · Administración de Bodega · IA en Remuneraciones · Herramientas Digitales PYMES · Comunicación Efectiva (lección 1 en Mindsmith) · Apilador Eléctrico (lección 1 en Mindsmith y actividad práctica) · Operación Segura en Supermercados (lección de carnicería y fiambrería en Mindsmith y actividad práctica) · Grúa Horquilla (lección 5 en Mindsmith y desafío TLS) · Manejo de Extintores (lección 1 y video en Mindsmith) · Cumplimiento Regulatorio Sanitario (unidades 1 y 2 en Mindsmith) · Informes Técnicos (lecciones 1.1 y 1.2, publicadas en Mindsmith) · Servicio al Cliente (lección 1.1 en Mindsmith y actividad práctica 1.1).

## Muestras que faltan
Los proyectos que ya estaban en el portafolio apuntan a carpetas que no están en ningún repositorio. Si las tienes, cópialas así y aparecerán solas:

```
scorm/liderazgo-efectivo/index.html
scorm/ley-manejo-datos/index.html
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
