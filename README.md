# PMX · Pableymax

> *One idea, a thousand ways to see it.*

[![Instagram](https://img.shields.io/badge/Instagram-@pableymax-0a2cff?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/pableymax)
[![YouTube](https://img.shields.io/badge/YouTube-@pableymax-0a2cff?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@pableymax)
[![Email](https://img.shields.io/badge/Email-contacto@pableymax.com-0a2cff?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contacto@pableymax.com)

-----

## Sobre el proyecto

**PMX** es un sitio web para estudio audiovisual independiente con sede en Colombia. El sitio presenta los proyectos del estudio, gestiona una convocatoria abierta de talento y conecta al equipo con colaboradores y audiencia.

-----

## Páginas

|Archivo          |Descripción                                 |
|-----------------|--------------------------------------------|
|`index.html`     |Página principal — hero, proyectos, contacto|
|`produccion.html`|Producción Visual — proyecto *18 Reverse*   |
|`filmmaking.html`|Filmmaking — proyecto *Lo que nadie ve*     |
|`contenido.html` |Contenido Creativo — proyecto *This is PMX* |

-----

## Estructura del repositorio

```
pmx-web/
├── index.html
├── produccion.html
├── filmmaking.html
├── contenido.html
├── img/
│   ├── logo.png.PNG
│   ├── instagram.png.PNG
│   ├── youtube.png.PNG
│   ├── gmail.png.PNG
│   ├── portada.PNG
│   ├── portada-filmm.PNG
│   ├── portada-contenido.PNG
│   ├── portada-film.PNG
│   ├── Portadatrailer.JPG.jpeg
│   └── pmx-reel.PNG
└── video/
    ├── produccion.mp4.mov
    ├── filmmaking.mp4.mp4
    └── contenido.mp4.mp4
```

-----

## Tecnologías

![HTML5](https://img.shields.io/badge/HTML5-0a2cff?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-0a2cff?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0a2cff?style=for-the-badge&logo=javascript&logoColor=white)
![Formspree](https://img.shields.io/badge/Formspree-0a2cff?style=for-the-badge&logo=mailchimp&logoColor=white)

Sin frameworks ni dependencias. HTML, CSS y JavaScript vanilla puro.

-----

## Funcionalidades

**Navegación**

- Navbar fija con backdrop blur
- Dropdown “Más” con animación de escala y opacidad
- Menú overlay móvil con animación circular `clip-path`
- Hamburger animado con transición a X

**Hero**

- Logo animado con efecto de flotación (`@keyframes flotar`)
- Transición de color de fondo al hacer scroll — de `#020d3a` a `#000` con easing cúbico

**Proyectos**

- Grid de cards con hover animado
- Secciones de video de fondo con `autoplay muted loop`
- Botón “Saber más” con aparición al hacer hover sobre la sección

**Modales**

- Modal *Productos* — aviso “próximamente” con animación de entrada
- Modal *Únete como Talento* — convocatoria con 5 roles, área de upload y formulario
- Cierre con botón, clic fuera o tecla `Escape`

**Formulario**

- Conectado a [Formspree](https://formspree.io)
- Feedback visual de envío, error y conexión
- Reset automático tras envío exitoso

**Animaciones**

- Reveal al hacer scroll con `IntersectionObserver`
- Todas las animaciones y transiciones en CSS puro

-----

## Convocatoria abierta

PMX busca talento para sus producciones audiovisuales:

|Rol        |Perfil                                     |
|-----------|-------------------------------------------|
|Actor      |Ficción, cortometrajes y contenido de marca|
|Camarógrafo|Operación de cámara en set y locación      |
|Guionista  |Historia, diálogos y estructura narrativa  |
|Editor     |Montaje, color y postproducción            |
|Director   |Visión creativa y coordinación en set      |

Postulaciones a través del formulario en el sitio o directo a **contacto@pableymax.com**

-----

## Proyectos activos

**18 Reverse** `Próximamente`
Producción Visual · 2026 · Tráiler en YouTube

**Lo que nadie ve**
Filmmaking · 2026 · Reel en Instagram

**This is PMX**
Contenido Creativo · 2026 · Reel en Instagram

-----

## Despliegue

El sitio es estático — puede alojarse en cualquier servidor o plataforma:

```
GitHub Pages · Netlify · Vercel · cualquier hosting estático
```

No requiere build, bundler ni instalación de dependencias.

-----

<sub>Colombia · © 2026 PMX | Pableymax — Todos los derechos reservados</sub>
