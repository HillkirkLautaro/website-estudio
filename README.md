# Estudio Jurídico Alejandro Hillkirk - Sitio Web

Este proyecto es el sitio web oficial del Estudio Jurídico Alejandro Hillkirk, desarrollado para ofrecer información clara y profesional sobre sus servicios legales, áreas de práctica y datos de contacto.

El sitio está construido con Astro, un framework moderno para crear sitios web estáticos rápidos y eficientes. Se utilizaron tecnologías web estándar como HTML, CSS y JavaScript integradas en Astro.

Además, el formulario de contacto está integrado con FormSubmit, facilitando la recepción segura y sencilla de mensajes sin necesidad de backend propio.

## 🚀 Tecnologías

- [Astro](https://astro.build/) - Framework web para sitios estáticos rápidos
- HTML, CSS y JavaScript - Tecnologías web estándar
- [FormSubmit](https://formsubmit.co/) - Para el manejo de formularios de contacto

## 📁 Estructura del Proyecto

```
website-estudio/       
├── .vscode/          # Configuración de VS Code
├── node_modules/     # Dependencias (no incluido en control de versiones)
├── src/
│   ├── assets/       # Recursos estáticos (imágenes, iconos, etc.)
│   ├── components/   # Componentes reutilizables de Astro/React/Vue
│   ├── layouts/      # Plantillas de diseño para las páginas
│   ├── pages/        # Rutas de la aplicación
│   └── styles/       # Hojas de estilo globales
├── .gitignore
├── .node-version
├── astro.config.mjs   # Configuración de Astro
├── netlify.toml      # Configuración de despliegue en Netlify
├── package.json      # Dependencias y scripts
└── tsconfig.json    # Configuración de TypeScript
```

## 🛠️ Instalación

1. Clona el repositorio:
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd website-estudio
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

4. Abre tu navegador en [http://localhost:4321](http://localhost:4321)

## 🚀 Despliegue

El sitio está configurado para desplegarse en Netlify. Los cambios en la rama `main` se despliegan automáticamente.

## 🌐 En Vivo

Visita el sitio en: https://estudiowebsite.netlify.app/
