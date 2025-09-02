# 🚀 Guía de Deploy - Pietrafina Mobile Demo

## Opciones de Deploy en Vercel

### 1. 📁 Deploy por Drag & Drop (Más Fácil)

1. Ve a [vercel.com](https://vercel.com) y haz login
2. En el dashboard, busca el botón **"New Project"**
3. Arrastra la carpeta `pietrafina-mobile-demo` completa al área de drop
4. Vercel detectará automáticamente que es un sitio estático
5. Haz clic en **"Deploy"**
6. ¡Listo! Tu demo estará disponible en una URL como `https://pietrafina-mobile-demo.vercel.app`

### 2. 🔧 Deploy con Vercel CLI

```bash
# Instalar Vercel CLI globalmente
npm install -g vercel

# Navegar a la carpeta del proyecto
cd pietrafina-mobile-demo

# Login en Vercel (solo la primera vez)
vercel login

# Deploy
vercel

# Para deploy de producción
vercel --prod
```

### 3. 📂 Deploy desde GitHub

1. Crea un nuevo repositorio en GitHub
2. Sube todos los archivos de la carpeta `pietrafina-mobile-demo`
3. Ve a [vercel.com](https://vercel.com)
4. Haz clic en **"New Project"**
5. Conecta tu cuenta de GitHub
6. Selecciona el repositorio que acabas de crear
7. Vercel detectará automáticamente la configuración
8. Haz clic en **"Deploy"**

## ⚙️ Configuración Automática

El proyecto incluye:
- ✅ `vercel.json` - Configuración optimizada para Vercel
- ✅ `package.json` - Metadatos del proyecto
- ✅ Headers de cache optimizados
- ✅ Rutas configuradas para SPA

## 🌐 URLs de Ejemplo

Después del deploy, tendrás URLs como:
- **Desarrollo**: `https://pietrafina-mobile-demo-git-main-tu-usuario.vercel.app`
- **Producción**: `https://pietrafina-mobile-demo.vercel.app`

## 📱 Características del Demo

- **Mobile-First**: Optimizado para móviles
- **Parallax**: Efectos de scroll suaves
- **Glassmorphism**: Diseño moderno
- **Responsive**: Funciona en todos los dispositivos
- **Performance**: Carga rápida y optimizada

## 🔄 Actualizaciones

Para actualizar el demo:
1. Modifica los archivos localmente
2. Vuelve a hacer deploy con cualquiera de los métodos anteriores
3. Vercel actualizará automáticamente el sitio

## 📞 Soporte

Si tienes problemas con el deploy:
- Revisa la [documentación de Vercel](https://vercel.com/docs)
- Verifica que todos los archivos estén en la carpeta
- Asegúrate de que el logo esté incluido

---

**¡Tu demo móvil de Pietrafina estará listo en minutos!** 🎉
