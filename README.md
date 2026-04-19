# Portafolio — Alisha Ibarra Bello
 
> Portafolio personal con estética editorial. Instructora de robótica, formadora STEAM y desarrolladora multiplataforma.
 
Un sitio de una sola página construido con React y TypeScript, inspirado en la maquetación de revistas impresas: tipografía serif variable, numeración romana por secciones, capitulares, *pull quotes* y una paleta cream/ink con acento sienna.
 
🔗 **Demo en vivo:** _[añade aquí la URL cuando lo despliegues]_
 
---
 
## ✦ Secciones
 
- **Hero** — Portada con masthead de revista y hora de Madrid en vivo.
- **I. Ensayo** — Sobre mí, con ficha rápida, *pull quote* y estadísticas.
- **II. Archivo** — Trayectoria profesional en formato índice expandible.
- **III. Taller** — Habilidades técnicas agrupadas por categoría + idiomas.
- **IV. Colofón** — Contacto y enlaces con tema oscuro.
---
 
## ✦ Stack
 
| Categoría | Tecnología |
|---|---|
| Framework | React 18 + TypeScript |
| Build | Vite |
| Estilos | Tailwind CSS 3.4 |
| Componentes | shadcn/ui |
| Tipografía | Fraunces · Inria Serif · JetBrains Mono |
| Bundle final | Parcel + html-inline (artefacto HTML único) |
 
---
 
## ✦ Estructura del proyecto
 
```
portfolio/
├── src/
│   ├── components/
│   │   ├── Hero.tsx          # Portada con masthead y marquee
│   │   ├── About.tsx         # Ensayo personal + ficha
│   │   ├── Experience.tsx    # Lista expandible de experiencia
│   │   ├── Skills.tsx        # Habilidades e idiomas
│   │   ├── Contact.tsx       # Contacto con tema oscuro
│   │   └── SideNav.tsx       # Navegación lateral fija
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css             # Variables de tema y utilidades
├── index.html
├── tailwind.config.js
└── package.json
```
 
---
 
## ✦ Desarrollo local
 
### Requisitos
 
- Node.js 18 o superior
- pnpm (recomendado) o npm
### Instalación
 
```bash
# Clonar el repositorio
git clone https://github.com/<tu-usuario>/<nombre-del-repo>.git
cd <nombre-del-repo>
 
# Instalar dependencias
pnpm install
 
# Levantar el servidor de desarrollo
pnpm dev
```
 
El sitio quedará disponible en `http://localhost:5173`.
 
### Build para producción
 
```bash
pnpm build
```
 
Los archivos optimizados se generan en la carpeta `dist/`.
 
---
 
## ✦ Personalización
 
Toda la paleta y tipografía viven en `src/index.css` como variables CSS. Los colores principales:
 
```css
--ink:        #1c1917;   /* Texto y bordes */
--cream:      #f2ebdd;   /* Fondo principal */
--cream-deep: #e8dfcb;   /* Fondo de sección alterna */
--sienna:     #b04a26;   /* Acento */
```
 
Para editar el contenido de cada sección, modifica directamente el componente correspondiente en `src/components/`.
 
---
 
## ✦ Contacto
 
**Alisha Ibarra Bello**
Madrid, España
 
- 📧 ibarrabelloalisha@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/alisha-ibarra-bello-4526561b6)
- 📱 +34 692 61 60 05
---
 
## ✦ Licencia
 
El código está disponible bajo licencia MIT. Los contenidos personales (textos, biografía, experiencia) son © Alisha Ibarra Bello y se reservan todos los derechos.
 
---
 
<sub>Hecho a mano en Madrid. Vol. I.</sub>
