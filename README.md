# Portafolio — Anderson Ortiz
 
Portafolio personal de **Anderson Ortiz**, desarrollador de software, con una estética inspirada en el **Evangelion Unit-01 (Eva-01)**: paleta morado, verde neón y naranja, paneles angulares y detalles tipo HUD de NERV.
 
🔗 **Demo en vivo:** [mi-portafolio-two-beta.vercel.app](https://mi-portafolio-two-beta.vercel.app/)
 
---
 
## Descripción del proyecto
 
Este sitio web presenta mi perfil, mis habilidades y los proyectos que he construido. Está hecho con **HTML y CSS puros**, sin frameworks ni dependencias, para que sea ligero, rápido y fácil de mantener. Está pensado para verse bien tanto en escritorio como en móvil.
 
### Secciones
 
| Sección | Descripción |
|---|---|
| **Hero** | Presentación principal con mi nombre, rol y botones de acción. |
| **Perfil del piloto** | Sobre mí, datos rápidos y una foto de perfil con marco estilo visor. |
| **Sync rate** | Habilidades técnicas representadas con barras de progreso. |
| **Misiones** | Proyectos destacados, con descripción, tecnologías y enlace. |
| **Canal de comunicación** | Enlaces de contacto: correo, GitHub y LinkedIn. |
 
### Proyectos destacados
 
- **Blackjack** — Juego de cartas hecho con Vite y JavaScript. [Ver proyecto](https://blackjack-by-anderortiz.netlify.app/)
- **Game Hub** — Arcade personal de minijuegos que empezó con el juego de memoria Simon.
- **GIFs App** — Buscador de GIFs que consume la API de GIPHY. [Ver proyecto](https://gifs-app-ander-ortiz.netlify.app/)
- **Blobatar** — Generador de avatares con Blobatar. [Ver proyecto](https://ander-ortiz-blobatar.netlify.app/)
---
 
## Características
 
- Diseño temático Eva-01 con paleta de colores definida mediante variables CSS.
- Diseño responsive con CSS Grid y Flexbox.
- Navegación fija con desplazamiento suave entre secciones.
- Barras de habilidades y tarjetas con formas angulares (`clip-path`).
- Respeta la preferencia de movimiento reducido (`prefers-reduced-motion`).
- Sin JavaScript ni librerías externas; solo se cargan las fuentes de Google Fonts.
## Tecnologías
 
- **HTML5**
- **CSS3** (variables, Grid, Flexbox, `clip-path`, gradientes)
- **Google Fonts**: Orbitron y Share Tech Mono
- **Vercel** para el despliegue
## Estructura del proyecto
 
```
mi-portafolio/
├── index.html
├── css/
│   └── styles.css
├── img/
│   └── anderson.jpg
└── README.md
```
 
> Ajusta los nombres de carpetas y archivos si tu estructura es distinta.
 
## Cómo ejecutarlo localmente
 
1. Clona el repositorio:
```bash
   git clone https://github.com/<tu-usuario>/<tu-repositorio>.git
   cd <tu-repositorio>
```
 
2. Abre `index.html` en tu navegador, o usa un servidor local (por ejemplo, la extensión **Live Server** de VS Code).
## Despliegue
 
El proyecto está desplegado en **Vercel**. Cada `push` a la rama principal actualiza el sitio automáticamente cuando el repositorio está conectado a Vercel.
 
## Personalización
 
- **Colores:** edita las variables en `:root` al inicio del archivo CSS.
- **Foto:** reemplaza `img/anderson.jpg` por tu imagen (se recomienda proporción 4:5).
- **Proyectos y contacto:** actualiza los enlaces en las secciones correspondientes del HTML.
## Autor
 
**Anderson Ortiz** — Desarrollador de software
 
- Portafolio: [mi-portafolio-two-beta.vercel.app](https://mi-portafolio-two-beta.vercel.app/)
- GitHub: [github.com/<tu-usuario>](https://github.com/)
- LinkedIn: [linkedin.com/in/<tu-usuario>](https://www.linkedin.com/)