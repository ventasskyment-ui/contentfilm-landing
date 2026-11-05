# Content Film - Landing Page Web

Landing page interactiva de alto impacto para **Content Film** (Grabación y edición de contenido para marcas y creadores en sesiones de 4 horas).

## 🚀 Vista Previa Local (Localhost)

Para iniciar el servidor local en la raíz del proyecto:

### Con Python:
```bash
python -m http.server 8000
```
Y abre en tu navegador: [http://localhost:8000](http://localhost:8000)

### Con Node.js / npx:
```bash
npx serve
```

---

## 📁 Estructura del Proyecto

El proyecto sigue una estructura limpia, desacoplada y lista para producción o despliegue en la nube (GitHub Pages, Vercel, Netlify o Cloudflare Pages):

```text
├── index.html         # Página principal estructurada y optimizada
├── support.js         # Runtime y controladores reactivos del DOM
├── vendor/            # Librerías cliente (React, ReactDOM)
│   ├── react.js
│   └── react-dom.js
├── assets/            # Archivos multimedia optimizados para la web (videos, imágenes, pósters)
├── raw_materials/     # Material original, tomas en bruto y revisiones de filmación (ignorado en Git)
├── package.json       # Configuración y scripts para despliegue web
├── .gitignore         # Exclusión de archivos pesados y temporales
└── README.md          # Documentación del proyecto
```

---

## 🌐 Despliegue en GitHub Pages / Vercel / Netlify

1. **Subir a GitHub:**
   ```bash
   git init
   git add .
   git commit -m "feat: landing page lista para producción"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   git push -u origin main
   ```

2. **GitHub Pages:**
   - Ve a **Settings** > **Pages** en tu repositorio de GitHub.
   - En **Branch**, selecciona `main` y carpeta `/ (root)`.
   - Guarda los cambios y en 1 minuto estará en línea.
