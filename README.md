## CV Online – Lucas Ruiz

Este proyecto es una página web sencilla donde presento mi currículum en formato online.  
Está pensado para verse bien tanto en ordenador como en móvil y poder exportarse también a PDF (vista de impresión).

### Tecnologías utilizadas

- **HTML5**: estructura semántica del CV (header, main, aside, sections, footer).
- **CSS3**: diseño visual, maquetación con Grid, variables CSS y estilos responsive.
- **Recursos estáticos**: imágenes (`assets/`) y ficheros ZIP de prácticas/proyectos.

### Estructura del proyecto

- **`index.html`**: página principal del currículum.
  - Cabecera con nombre y título.
  - Barra lateral con:
    - Foto.
    - Datos de contacto (teléfono, email, ubicación, GitHub).
    - Soft skills.
    - Hard skills.
  - Contenido principal con:
    - Perfil.
    - Experiencia.
    - Proyectos (con enlaces de descarga a ZIP de prácticas).
    - Formación.
    - Idiomas.
- **`css/style.css`**: hoja de estilos con:
  - Reset básico.
  - Variables de color y tipografía.
  - Maquetación en grid (sidebar + contenido).
  - Estilos de tarjetas, listas de skills, proyectos e idiomas.
  - Efectos de hover y focus (accesibilidad).
  - Media queries para tablet y móvil.
  - Estilos específicos para impresión (modo PDF).
- **`assets/`**:
  - Iconos (teléfono, mail, ubicación, GitHub, favicon).
  - Foto de perfil.
  - Ficheros ZIP de prácticas:
    - `Practica Clonezilla.zip`
    - `practica01_php.zip`
    - `Practica multiboot.zip`

### Cómo ver el proyecto

- **Opción 1 (rápida)**:  
  Abrir el archivo `index.html` directamente en el navegador (doble clic o “Abrir con…”).

- **Opción 2 (servidor local)**:  
  Levantar un servidor estático (por ejemplo con la extensión Live Server de VS Code) en la carpeta del proyecto y acceder a `index.html` desde `http://localhost`.

### Versión responsive

El diseño se adapta a diferentes tamaños de pantalla:

- **Escritorio**: layout en dos columnas (sidebar + contenido).
- **Tablets**: se ajustan los paddings y tamaños de fuente.
- **Móvil**: todo el contenido se muestra en una sola columna, con tamaños más pequeños y mejor legibilidad.

### Versión para imprimir / PDF

El archivo `style.css` incluye una sección `@media print` para mejorar la impresión:

- Fondo blanco.
- Borde en cabecera y tarjetas.
- Conversión de enlaces a texto con la URL al lado.

Para generar un PDF del CV:

1. Abrir `index.html` en el navegador.
2. Ir a “Imprimir” (Ctrl+P).
3. Elegir “Guardar como PDF”.
4. Ajustar márgenes si es necesario y guardar.

### Objetivo del proyecto

Este CV online forma parte de mi formación en el CFGS ASIX.  
Con él demuestro:

- **Conocimientos básicos de HTML y CSS**.
- **Uso de maquetación responsive**.
- **Buenas prácticas de accesibilidad y semántica**.
- **Organización de un pequeño proyecto web** con recursos estáticos y enlaces a proyectos reales.

### Vercel

Adjunto el link de mi deploy en Vercel.
https://lucas-ashy.vercel.app/

