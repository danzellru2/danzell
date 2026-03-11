# 📁 Estructura de tu Portafolio Web

## Archivos incluidos

```
portafolio/
├── index.html     ← Página principal (toda la estructura)
├── styles.css     ← Todos los estilos y diseño
├── script.js      ← Interactividad (menú, animaciones, formulario)
└── README.md      ← Esta guía
```

---

## 🚀 Cómo usarlo

1. Descarga los 3 archivos: `index.html`, `styles.css`, `script.js`
2. Ponlos todos en la **misma carpeta**
3. Abre `index.html` en tu navegador — ¡listo!

---

## ✏️ Cómo personalizar

### Tu foto
En `index.html`, busca este bloque y reemplázalo:
```html
<!-- ANTES (placeholder) -->
<div class="photo-icon">📷</div>
<p class="photo-hint">Sube tu foto aquí</p>

<!-- DESPUÉS (tu foto real) -->
<img src="mi-foto.jpg" alt="Tu Nombre">
```
Asegúrate de que `mi-foto.jpg` esté en la misma carpeta.

### Tu nombre y título
Busca "Tu Nombre" y "Desarrollador / Diseñador" en `index.html` y cámbialos.

### Proyectos
Cada tarjeta de proyecto tiene esta estructura — edita el título, descripción y enlaces:
```html
<h3>Nombre del Proyecto</h3>
<p>Descripción breve...</p>
<a href="URL_DE_TU_DEMO">Ver demo →</a>
<a href="URL_DE_TU_GITHUB">GitHub</a>
```

### Habilidades
Ajusta los porcentajes de las barras en `index.html`:
```html
<div class="fill" style="width:85%; --c:#F4A261"></div>
<!--                            ↑ cambia este número -->
```

### Redes sociales
En la sección de contacto, cambia los `href="#"` por tus URLs reales:
```html
<a href="https://linkedin.com/in/tu-usuario" class="social-pill">LinkedIn</a>
```

### Colores
En `styles.css`, líneas al inicio, cambia los colores principales:
```css
--accent-green:  #7EC8A4;   /* botón "Sobre mí" */
--accent-orange: #F4A261;   /* botón "Proyectos" y acentos */
--accent-blue:   #6BBFD4;   /* botón "Habilidades" y punto del nav */
```

---

## 🌐 Publicar gratis en internet

Opciones recomendadas:
- **GitHub Pages** — gratis, sube tus archivos a un repositorio público
- **Netlify** — arrastra tu carpeta en netlify.com/drop
- **Vercel** — conecta con GitHub en vercel.com

---

## 📱 Responsive
El diseño ya es responsive (se adapta a móvil automáticamente).
