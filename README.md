# Eiser E-Commerce

## 📋 Descripción del Proyecto

Eiser es una plataforma de **comercio electrónico** moderna y responsiva desarrollada con tecnologías web estándar. Este proyecto proporciona una experiencia completa de compra en línea con funcionalidades intuitivas y un diseño atractivo.

---

## ✨ Características Principales

- 🛍️ **Catálogo de Productos** - Visualización y navegación de productos
- 📦 **Carrito de Compras** - Gestión de artículos seleccionados
- 💳 **Proceso de Pago** - Sistema de checkout completo
- 📝 **Blog** - Artículos y contenido relacionado con productos
- 👥 **Formulario de Contacto** - Comunicación con el equipo
- 📍 **Seguimiento de Pedidos** - Rastreo en tiempo real
- 📱 **Diseño Responsivo** - Compatible con dispositivos móviles y de escritorio
- 🎨 **Personalización** - Temas personalizables mediante SCSS

---

## 📁 Estructura del Proyecto

```
Sistema/
├── index.html                 # Página de inicio
├── blog.html                  # Página del blog
├── category.html              # Categorías de productos
├── single-product.html        # Detalle de producto individual
├── single-blog.html           # Detalle de artículo del blog
├── cart.html                  # Carrito de compras
├── checkout.html              # Proceso de pago
├── tracking.html              # Seguimiento de pedidos
├── contact.html               # Página de contacto
├── elements.html              # Elementos UI de demostración
├── contact_process.php        # Procesamiento de formularios
│
├── css/                       # Estilos compilados
│   ├── bootstrap.css          # Framework Bootstrap
│   ├── style.css              # Estilos personalizados
│   ├── responsive.css         # Estilos responsivos
│   ├── font-awesome.min.css   # Iconos Font Awesome
│   ├── flaticon.css           # Iconos Flaticon
│   └── themify-icons.css      # Iconos Themify
│
├── scss/                      # Archivos SCSS (fuente)
│   ├── style.scss             # Archivo principal
│   ├── _variables.scss        # Variables de colores y fuentes
│   ├── _predefine.scss        # Estilos predefinidos
│   ├── _header.scss           # Estilos del encabezado
│   ├── _footer.scss           # Estilos del pie de página
│   ├── _product.scss          # Estilos de productos
│   ├── _blog.scss             # Estilos del blog
│   ├── _button.scss           # Estilos de botones
│   ├── _contact.scss          # Estilos del formulario de contacto
│   └── _*.scss                # Otros módulos de estilos
│
├── js/                        # Archivos JavaScript
│   ├── jquery-3.2.1.min.js    # Librería jQuery
│   ├── bootstrap.min.js       # Bootstrap JavaScript
│   ├── custom.js              # Scripts personalizados
│   ├── contact.js             # Funcionalidad del formulario
│   ├── theme.js               # Scripts del tema
│   ├── mail-script.js         # Manejo de correos
│   └── *.js                   # Otras librerías
│
├── vendors/                   # Librerías externas
│   ├── bootstrap-datepicker/  # Selector de fechas
│   ├── owl-carousel/          # Carrusel de imágenes
│   ├── lightbox/              # Visor de imágenes
│   ├── counter-up/            # Contador animado
│   ├── isotope/               # Filtrado de elementos
│   ├── nice-select/           # Selector mejorado
│   ├── animate-css/           # Animaciones CSS
│   └── ...                    # Otras dependencias
│
├── img/                       # Imágenes del proyecto
│   ├── banner/                # Imágenes de banners
│   ├── product/               # Imágenes de productos
│   │   ├── feature-product/
│   │   ├── new-product/
│   │   ├── inspired-product/
│   │   └── most-product/
│   ├── blog/                  # Imágenes del blog
│   └── instagram/             # Imágenes de Instagram
│
├── fonts/                     # Fuentes personalizadas
└── prepros-6.config          # Configuración de Prepros
```

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica
- **CSS3 / SCSS** - Estilos y diseño responsivo
- **JavaScript (ES5)** - Interactividad
- **jQuery 3.2.1** - Manipulación del DOM
- **Bootstrap 4** - Framework CSS

### Librerías y Plugins
- **Owl Carousel** - Carruseles de imágenes
- **Isotope** - Filtrado y disposición de elementos
- **SimpleLightbox** - Galería de imágenes
- **jQuery UI** - Componentes interactivos
- **jQuery Validate** - Validación de formularios
- **Counter Up** - Animación de contadores
- **WOW.js** - Animaciones desencadenadas por desplazamiento
- **GMaps** - Mapas interactivos

### Backend
- **PHP** - Procesamiento del lado del servidor
- **jQuery AJAX** - Peticiones asincrónicas
- **Mail Script** - Envío de correos

---

## 📱 Páginas Principales

| Página | Archivo | Descripción |
|--------|---------|-------------|
| **Inicio** | `index.html` | Página principal con productos destacados |
| **Categorías** | `category.html` | Listado de productos por categoría |
| **Producto** | `single-product.html` | Detalle completo de un producto |
| **Carrito** | `cart.html` | Gestión del carrito de compras |
| **Checkout** | `checkout.html` | Proceso de pago |
| **Blog** | `blog.html` | Artículos y noticias |
| **Artículo** | `single-blog.html` | Detalle de artículo individual |
| **Contacto** | `contact.html` | Formulario de contacto |
| **Seguimiento** | `tracking.html` | Rastreo de pedidos |

---

## 🚀 Instalación y Configuración

### Requisitos Previos
- Servidor web con soporte PHP (Apache, Nginx, etc.)
- PHP 5.6 o superior
- Navegador web moderno

### Pasos de Instalación

1. **Clonar o descargar el proyecto**
   ```bash
   git clone <repository-url>
   cd Sistema
   ```

2. **Configurar el servidor**
   - Colocar los archivos en el directorio raíz del servidor web
   - Asegurar que PHP esté habilitado

3. **Configurar el correo electrónico**
   - Editar `contact_process.php`
   - Cambiar `demo@domain.com` por el correo de destino
   - Configurar las credenciales SMTP si es necesario

4. **Compilar SCSS (Opcional)**
   ```bash
   # Usando prepros o cualquier compilador SCSS
   sassc scss/style.scss css/style.css
   ```

---

## 📝 Configuración de Contacto

El archivo `contact_process.php` es responsable del envío de correos. Actualiza la siguiente información:

```php
$to = "tu-email@dominio.com";  // Email destino
$logo = 'img/logo.png';         // Logo del correo
$link = '#';                    // Link del correo
```

---

## 💬 Información de Contacto

- **Teléfono:** +01 256 25 235
- **Email:** info@eiser.com

---

## 📊 Estructura SCSS

El proyecto utiliza **SCSS** para mejor mantenimiento del CSS. Los estilos se organizan en módulos:

- `_variables.scss` - Colores, tipografía y tamaños
- `_predefine.scss` - Clases y estilos base
- `_header.scss` - Estilos del encabezado
- `_product.scss` - Estilos de la tienda
- `_blog.scss` - Estilos del blog
- `_contact.scss` - Estilos de formularios
- `_footer.scss` - Estilos del pie de página

**Compilar cambios SCSS:**
```bash
sassc scss/style.scss css/style.css
```

---

## 🎨 Personalización

### Cambiar Colores
1. Abrir `scss/_variables.scss`
2. Modificar los colores según necesidad
3. Compilar los cambios SCSS

### Agregar Fuentes Personalizadas
1. Colocar archivos de fuentes en `fonts/`
2. Importar en `scss/_variables.scss`
3. Recompilar CSS

---

## 🔒 Seguridad

### Recomendaciones
- ✅ Validar y sanitizar todas las entradas del usuario
- ✅ Usar HTTPS en producción
- ✅ Implementar CSRF tokens en formularios
- ✅ Usar prepared statements para consultas a BD
- ✅ Mantener las dependencias actualizadas

---

## 📄 Licencia

Este proyecto es de uso exclusivo. Para más información, contactar con el equipo de desarrollo.

---

## 👨‍💻 Soporte y Mantenimiento

Para reportar bugs, solicitar funcionalidades u obtener soporte:
- **Email:** info@eiser.com
- **Teléfono:** +01 256 25 235

---

## 🔄 Versionado

**Versión Actual:** 1.0  
**Última Actualización:** Abril 2026

---

## 📚 Recursos Útiles

- [Bootstrap Documentación](https://getbootstrap.com/)
- [jQuery Documentación](https://jquery.com/)
- [SCSS Documentación](https://sass-lang.com/)
- [HTML5 MDN](https://developer.mozilla.org/es/docs/Web/HTML)

---

**¡Gracias por usar Eiser E-Commerce!** 🎉
