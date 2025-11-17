# mi-portfolio

Plantilla base con Astro + Tailwind, lista para desplegar en GitHub Pages.

## Comandos

```bash
npm install
npm run dev      # Ejecuta localmente
npm run build    # Compila para producción
npm run deploy   # Sube a GitHub Pages


Para Reels de Instagram:
const reels = [  {    id: "reel-1",    url: "https://www.instagram.com/reel/TU_CODIGO_DE_REEL/embed/",    title: "Título del Reel"  },  // Agrega más reels aquí...];
Para obtener la URL de embed de un reel de Instagram:
Abre el reel en Instagram
Haz clic en los tres puntos (...)
Selecciona "Copiar enlace"
El código del reel está en la URL: instagram.com/reel/CODIGO_AQUI/
Para Videos de YouTube:
const youtubeVideos = [  {    id: "video-1",    videoId: "TU_VIDEO_ID", // Solo el ID, no la URL completa    title: "Título del Video"  },  // Agrega más videos aquí...];
Para obtener el ID de un video de YouTube:
Si la URL es: https://www.youtube.com/watch?v=dQw4w9WgXcQ
El ID es: dQw4w9WgXcQ
La página está lista para usar. Solo necesitas reemplazar los datos de ejemplo con tus propios videos. ¿Quieres que agregue alguna funcionalidad adicional o ajuste el diseño?