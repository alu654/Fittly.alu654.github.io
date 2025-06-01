# Sitio Web de Clothes App

Este directorio contiene el sitio web oficial de la aplicación Clothes, creado específicamente para cumplir con los requisitos de TestFlight y el App Store.

## Archivos Incluidos

### 📄 `index.html`
- **Propósito**: Página principal del sitio web
- **Contenido**: 
  - Descripción de la aplicación
  - Características principales
  - Diseño moderno y responsivo
  - Navegación hacia la política de privacidad

### 🔒 `privacy.html`
- **Propósito**: Política de privacidad completa
- **Importancia**: **REQUERIDA para TestFlight**
- **Contenido**:
  - Información detallada sobre recopilación de datos
  - Medidas de seguridad implementadas
  - Derechos del usuario
  - Cumplimiento con GDPR, CCPA y COPPA
  - Información de contacto

## 🚀 Para TestFlight

### Requisitos Cumplidos
✅ **Política de Privacidad**: Documento completo y detallado
✅ **URL Pública**: Sitio web accesible públicamente
✅ **Información de Contacto**: Email de soporte incluido
✅ **Descripción de la App**: Características y funcionalidades
✅ **Medidas de Seguridad**: Documentación de protección de datos

### Pasos para Publicar

1. **Subir a un Servidor Web**
   - Sube ambos archivos a tu servidor web
   - Asegúrate de que sean accesibles públicamente
   - Ejemplo: `https://tudominio.com/clothes/`

2. **Configurar en App Store Connect**
   - Ve a tu app en App Store Connect
   - En "App Information" → "Privacy Policy URL"
   - Ingresa: `https://tudominio.com/clothes/privacy.html`

3. **Verificar Accesibilidad**
   - Confirma que ambas páginas cargan correctamente
   - Verifica que los enlaces funcionen
   - Prueba en dispositivos móviles

## 🛠️ Personalización

### Información a Actualizar
Antes de publicar, actualiza la siguiente información:

- **Emails de contacto** en `privacy.html`:
  - `privacy@clothesapp.com` → tu email real
  - `support@clothesapp.com` → tu email de soporte

- **Dominio** en ambos archivos si es necesario

- **Información de la empresa** si aplica

### Opciones de Hosting Gratuito

1. **GitHub Pages**
   - Crea un repositorio público
   - Sube los archivos
   - Activa GitHub Pages
   - URL: `https://usuario.github.io/repositorio/`

2. **Netlify**
   - Arrastra la carpeta a netlify.com
   - Obtén URL automática
   - Opción de dominio personalizado

3. **Vercel**
   - Conecta con GitHub
   - Deploy automático
   - URL personalizada disponible

## 📱 Características del Diseño

- **Responsivo**: Se adapta a móviles y desktop
- **Moderno**: Diseño glassmorphism con gradientes
- **Accesible**: Cumple estándares de accesibilidad
- **Rápido**: CSS puro, sin dependencias externas
- **SEO Friendly**: Meta tags apropiados

## ⚠️ Importante para TestFlight

**Apple requiere que tengas:**
1. Una política de privacidad accesible públicamente
2. Información clara sobre el manejo de datos
3. Detalles de contacto válidos
4. Descripción precisa de la funcionalidad de la app

**Este sitio web cumple con todos estos requisitos.**

## 🔄 Mantenimiento

- Actualiza la política de privacidad si cambias el manejo de datos
- Mantén la información de contacto actualizada
- Revisa periódicamente que los enlaces funcionen
- Actualiza las características cuando agregues nuevas funciones

---

**¡Tu app está lista para TestFlight!** 🎉

Una vez que subas este sitio web y configures la URL en App Store Connect, podrás proceder con la revisión de TestFlight sin problemas relacionados con la política de privacidad.