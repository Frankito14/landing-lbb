# Learn Beyond Borders - Landing Page

## Descripción

Learn Beyond Borders es una página de aterrizaje para LBB English, una plataforma educativa dedicada a enseñar habilidades en el idioma inglés de manera accesible y efectiva. El sitio promueve el aprendizaje del inglés más allá de las fronteras, ofreciendo recursos y oportunidades para estudiantes de todo el mundo.

## Configuración de Tailwind CSS

Este proyecto utiliza Tailwind CSS a través de su CDN para un desarrollo rápido y sin configuración compleja. La configuración personalizada se incluye directamente en el archivo `index.html` mediante un script inline.

### Uso del CDN
- **URL del CDN**: `https://cdn.tailwindcss.com?plugins=forms,container-queries`
- **Plugins incluidos**: `forms` y `container-queries` para funcionalidades adicionales.

### Configuración Personalizada
La configuración de Tailwind se define en un script con ID `tailwind-config` en `index.html`. Incluye:
- **Modo oscuro**: Habilitado con `darkMode: "class"`.
- **Colores extendidos**: Un conjunto personalizado de colores para mantener la coherencia visual del sitio, incluyendo tonos para superficies, contenedores y elementos interactivos.

Para modificar la configuración, edita el objeto `tailwind.config` en el script correspondiente.

### Instalación Local (Opcional)
Si deseas migrar a una instalación local de Tailwind:
1. Instala Tailwind CSS: `npm install -D tailwindcss`
2. Inicializa la configuración: `npx tailwindcss init`
3. Copia la configuración personalizada al archivo `tailwind.config.js`.
4. Incluye Tailwind en tu CSS: `@tailwind base; @tailwind components; @tailwind utilities;`

Para más información, consulta la [documentación oficial de Tailwind CSS](https://tailwindcss.com/docs).