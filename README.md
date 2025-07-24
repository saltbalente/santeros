# Santeros - Sitio Web Espiritual

Sitio web profesional para servicios espirituales y consultas de santería, completamente optimizado y listo para despliegue en Vercel.

## 🚀 Despliegue en Vercel

Este repositorio está configurado para desplegarse automáticamente en Vercel:

1. **Conectar con GitHub**: Sube este repositorio a GitHub
2. **Importar en Vercel**: Ve a [vercel.com](https://vercel.com) e importa el repositorio
3. **Despliegue automático**: Vercel detectará automáticamente que es un sitio estático
4. **Configuración incluida**: El archivo `vercel.json` ya está configurado

### Comandos para GitHub

```bash
# Crear repositorio en GitHub y conectarlo
git remote add origin https://github.com/tu-usuario/santeros.git
git branch -M main
git push -u origin main
```

## 📋 Características del Sitio

- ✅ **100% Independiente**: Sin dependencias externas problemáticas
- ✅ **Optimizado para Vercel**: Configuración incluida
- ✅ **Responsive**: Compatible con todos los dispositivos
- ✅ **WhatsApp Integration**: Enlaces directos configurados
- ✅ **Video Autoplay**: Video promocional incluido
- ✅ **SEO Optimizado**: Meta tags y estructura correcta

## 🛠️ Cambios Realizados

### Limpieza de HTTrack
- ✅ Eliminados todos los comentarios de HTTrack
- ✅ Removidos archivos HTML innecesarios generados por HTTrack:
  - `img/banner/banner-2.html`
  - `img/banner/banner.html` 
  - `vendors/owl-carousel/owl.video.play.html`

### Independencia del Dominio
- ✅ Actualizadas todas las referencias de WhatsApp para usar texto genérico
- ✅ Corregidas las meta tags de Open Graph para usar rutas relativas
- ✅ Eliminadas referencias específicas al dominio en políticas de privacidad

### Eliminación de Dependencias Externas
- ✅ Removido Google Tag Manager (scripts de tracking)
- ✅ Eliminado widget GetButton.io 
- ✅ Removido timer.js no utilizado que causaba errores
- ✅ Eliminado directorio flipclock innecesario

### Optimización para Vercel
- ✅ Mantenidas solo las dependencias necesarias (Google Fonts)
- ✅ Conservados todos los archivos estáticos esenciales
- ✅ Verificado funcionamiento sin errores en navegador

## 📁 Archivos Incluidos

- `index.html` - Página principal limpia y optimizada
- `css/` - Archivos de estilos CSS
- `js/` - Archivos JavaScript necesarios
- `img/` - Imágenes y recursos gráficos
- `fonts/` - Fuentes web FontAwesome
- `vendors/` - Librerías de terceros (Bootstrap, jQuery, etc.)
- `favicon.ico` - Icono del sitio

## 🚀 Instrucciones de Instalación

1. **Sube todos los archivos** a la raíz de tu nuevo dominio
2. **Mantén la estructura de carpetas** exactamente como está
3. **Asegúrate** de que `index.html` esté en la raíz del servidor
4. **El sitio funcionará inmediatamente** sin configuración adicional

## ✨ Características

- ✅ **100% Independiente** - No depende del dominio original
- ✅ **Sin errores** - Funciona perfectamente en cualquier servidor
- ✅ **Optimizado** - Solo archivos necesarios incluidos
- ✅ **Responsive** - Funciona en móviles y escritorio
- ✅ **Enlaces funcionales** - Todos los botones de WhatsApp operativos

## 📱 Funcionalidades Preservadas

- Enlaces de WhatsApp funcionando correctamente
- Galería de imágenes con lightbox
- Diseño responsive completo
- Animaciones y efectos CSS
- Formularios de contacto
- Navegación suave

## 🔧 Tecnologías Utilizadas

- HTML5 estático
- CSS3 con Bootstrap 4
- JavaScript (jQuery, plugins)
- FontAwesome para iconos
- Google Fonts (Playfair Display, Roboto)

## 📝 Notas Importantes

- El sitio es completamente estático y no requiere base de datos
- Funciona en cualquier servidor web (Apache, Nginx, etc.)
- Compatible con hosting compartido básico
- Los enlaces de WhatsApp usan el número +1 (904) 870-1005
- Todas las imágenes están optimizadas y son locales

¡El sitio está listo para ser subido a tu nuevo dominio!