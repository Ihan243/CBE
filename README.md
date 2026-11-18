# CBE — UCHS Program Website

Sitio web interactivo oficial para el programa educativo **CBE (UCHS Program)**, diseñado según el sistema de diseño editorial y tecnológico de Stitch.

---

## 🚀 Cómo abrir y visualizar la página

1. **Directamente en tu navegador:**
   - Haz doble clic sobre el archivo `index.html` en tu carpeta de escritorio:
     `c:\Users\galin\OneDrive\Escritorio\CBE\index.html`
   - Se abrirá inmediatamente en Google Chrome, Microsoft Edge o tu navegador preferido.

2. **Con VS Code Live Server (opcional):**
   - Si usas Visual Studio Code, abre la carpeta `CBE` y presiona **"Go Live"** con la extensión Live Server.

3. **Para publicar en internet:**
   - Puedes subir esta carpeta directamente a servicios gratuitos como **GitHub Pages**, **Vercel**, **Netlify**, o **Cloudflare Pages**. Al contener `index.html` en la raíz, se despliega automáticamente sin pasos adicionales de compilación.

---

## 📂 Estructura del proyecto

```
CBE/
├── index.html                   # Página web principal interactiva y lista para producción
├── cbe_design_system.md         # Documentación completa del sistema de diseño (tokens, colores, tipografía)
├── cbe_official_website/
│   └── code.html                # Archivo fuente original exportado desde Stitch
└── README.md                    # Documentación del proyecto
```

---

## 🎨 Sistema de diseño implementado

- **Paleta de Colores:**
  - `Midnight Navy (#0B1020)`: Fondo oscuro principal.
  - `Lime Green (#C9F36B)`: Acento vibrante para llamadas a la acción (CTAs) y badges.
  - `Deep Navy (#121B30)`: Superficies elevadas de tarjetas.
  - `Soft Indigo (#7584FF)`: Acento editorial para titulares y categorías.
  - `Off-white (#F5F6F2)` & `White (#FFFFFF)`: Fondos y contrastes de contenido.

- **Tipografía:**
  - **Space Grotesk**: Titulares de display, botones y números gigantes.
  - **DM Sans**: Textos descriptivos, navegación y cuerpo legible.

- **Componentes y Funcionalidades Interactivas:**
  - Barra de progreso de scroll superior en color verde lima.
  - Barra de navegación fija con efecto cristal (*backdrop blur*) y menú responsive para móviles.
  - Sección Hero con iluminación radial violeta y composición editorial fotográfica.
  - Marquesina ticker animada continua (*LEARN ✳ EARN ✳ EXPERIENCE ✳ NETWORK*).
  - Bento Grid interactivo con las 4 tarjetas principales (Learn, Earn, Experience, Network) con elevación hover 3D.
  - Sección editorial "About the Program" con rotaciones sutiles estilo revista digital.
  - Línea de recorrido del estudiante en 3 pasos ("The Journey").
  - Acordeón interactivo accesible para Preguntas Frecuentes (FAQ).
  - Sección CTA con marca de agua tipográfica gigante CBE en SVG.
  - **Modal interactivo de registro / postulación para estudiantes** al hacer clic en "Get Started" o en cualquier tarjeta Bento.
  - Animaciones de revelado al hacer scroll (*Intersection Observer*).

---

© 2026 CBE (UCHS Program). Todos los derechos reservados.
