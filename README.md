# 📚 Sistema de Biblioteca Digital - CRA
## Colegio Nacional E.M.D "Gral. Pablo L. Ávila"

### 🌐 Catálogo Online para Estudiantes

Este proyecto incluye un sistema completo de gestión de biblioteca escolar con una página de consulta pública para estudiantes.

## 📁 Archivos del Proyecto

- `biblioCRAvila.html` - Sistema de administración (solo para encargados)
- `catalogo-estudiantes.html` - Catálogo local para estudiantes
- `catalogo-estudiantes-github.html` - **Catálogo optimizado para GitHub Pages**
- `mectrans.png` - Imagen del encabezado izquierdo
- `pablologo.png` - Logo institucional

## 🚀 Configuración para GitHub Pages

### Paso 1: Subir archivos al repositorio
Asegúrate de subir estos archivos a tu repositorio de GitHub:
- `catalogo-estudiantes-github.html`
- `mectrans.png`
- `pablologo.png`
- `README.md` (este archivo)

### Paso 2: Configurar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Click en "Settings" (Configuración)
3. Busca la sección "Pages" 
4. En "Source", selecciona "Deploy from a branch"
5. Selecciona la rama `main` (o `master`)
6. Selecciona `/root` como carpeta
7. Click "Save"

### Paso 3: Editar la configuración
Abre `catalogo-estudiantes-github.html` y modifica las líneas 245-249:

```javascript
const GITHUB_CONFIG = {
    username: 'tu-usuario-github',     // ← Cambia esto por tu usuario
    repository: 'tu-repositorio',      // ← Cambia esto por el nombre de tu repo
    branch: 'main'                     // ← 'main' o 'master' según tu rama
};
```

**Ejemplo:**
```javascript
const GITHUB_CONFIG = {
    username: 'juanperez',
    repository: 'biblioteca-avila',
    branch: 'main'
};
```

### Paso 4: Acceder al catálogo
Una vez configurado, podrás acceder al catálogo en:
```
https://TU_USUARIO.github.io/TU_REPOSITORIO/catalogo-estudiantes-github.html
```

**Ejemplo:**
```
https://juanperez.github.io/biblioteca-avila/catalogo-estudiantes-github.html
```

## 📱 Características del Catálogo Online

### ✅ **Para Estudiantes:**
- ✨ **Búsqueda avanzada** por título, autor o editorial
- 📂 **Filtrado por categorías**
- 📊 **Estadísticas en tiempo real**
- 📱 **Diseño responsive** (móviles y tablets)
- 🌐 **Funciona online y offline**
- 🔄 **Sincronización automática** con el sistema de administración

### 🎨 **Interfaz Moderna:**
- 🎯 Estados visuales de disponibilidad:
  - ✅ **Disponible** (más de 2 unidades)
  - ⚠️ **Pocas unidades** (1-2 unidades)  
  - ❌ **Agotado** (sin stock)
- 📚 **Organización por categorías**
- 🖼️ **Soporte para imágenes de libros**
- 🎨 **Colores institucionales**

### 🔧 **Funciones Técnicas:**
- 🌐 **Detección de conexión online/offline**
- 📡 **Carga de imágenes desde GitHub**
- 💾 **Datos locales de respaldo**
- 🔄 **Sincronización periódica**

## 🔐 Sistema de Administración

El archivo `biblioCRAvila.html` incluye:
- 🔑 **Sistema de login** (admin/encargado)
- ➕ **Agregar/eliminar libros**
- 📂 **Categorías personalizables**
- 📊 **Gestión de inventario**
- 📤 **Importar/exportar Excel**
- 🖼️ **Subida de imágenes**

### Usuarios por defecto:
- **Usuario:** `admin` - **Contraseña:** `CRAvila`
- **Usuario:** `encargado` - **Contraseña:** `clave2024`

## 🔧 Instalación Local

1. Descarga todos los archivos
2. Abre `biblioCRAvila.html` para administración
3. Abre `catalogo-estudiantes.html` para consulta local

## 📞 Soporte

Si necesitas ayuda con la configuración o tienes algún problema, no dudes en:
1. Revisar que los nombres de archivos coincidan exactamente
2. Verificar que las imágenes estén en la raíz del repositorio
3. Comprobar que GitHub Pages esté activado correctamente

## 📝 Notas Importantes

- ⚠️ Las imágenes `mectrans.png` y `pablologo.png` deben estar en la raíz del repositorio
- 🔄 Los datos se sincronizan entre el sistema de administración y el catálogo
- 📱 El catálogo funciona perfectamente en móviles
- 🌐 No requiere servidor - funciona con GitHub Pages gratuito

---

**🏫 Colegio Nacional E.M.D "Gral. Pablo L. Ávila"**  
📚 Sistema Digital CRA - Biblioteca Escolar
