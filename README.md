# 🎯 Ipora Futbol Club - Landing Page

Landing page profesional para **Ipora Futbol Club** con sistema de reservas integrado.

## 📋 Características

✅ Diseño moderno y responsive  
✅ Sistema de reservas con Calendly  
✅ Sección de historia con timeline animado  
✅ Galería de fotos con lightbox  
✅ Integración con WhatsApp  
✅ Optimizado para SEO  
✅ Animaciones y efectos visuales  
✅ 100% HTML, CSS y JavaScript (sin backend)

## 📁 Estructura del Proyecto

```
NicoReservas/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos
├── js/
│   └── main.js         # Funcionalidades JavaScript
├── imagenes/
│   ├── logo ipora.jpg
│   ├── cancha1.jpg
│   ├── cancha2.jpg
│   ├── ipora historia.jpg
│   ├── iporta historia 2.jpg
│   ├── ipora historia 3.jpg
│   ├── ipora historia 4.jpg
│   └── iporta historia 5.jpg
└── README.md
```

## 🚀 Sistema de Reservas - Google Calendar

### ✅ Ya Configurado

El sistema de reservas con **Google Calendar Appointment Scheduling** ya está integrado y funcionando.

### 📅 Gestionar Reservas

Para ver y gestionar las reservas:

1. Ir a [calendar.google.com](https://calendar.google.com)
2. En el menú izquierdo buscar **"Reserva Cancha Nico"**
3. Ver todas las reservas confirmadas
4. Recibir notificaciones automáticas por email

### ⚙️ Configurar Horarios y Disponibilidad

1. En Google Calendar → clic en tu **Appointment Schedule**
2. Clic en **"Configuración de reservas"**
3. Ajustar:
   - **Horarios disponibles** (días y horas)
   - **Duración de turnos**
   - **Tiempo de preparación** entre turnos
   - **Límite de reservas adelantadas**
   - **Preguntas personalizadas** para los clientes

### 🔄 Cambiar el Código (si es necesario)

Si necesitás cambiar el iframe en el futuro:

1. Abrir `index.html`
2. Buscar línea **177** (comentario Google Calendar)
3. Reemplazar el `<iframe>` completo

## 🌐 Subir a Namecheap Hosting

### 1. Conectar por FTP

- **Host:** `ftp.tudominio.com`
- **Usuario:** Tu usuario de cPanel
- **Contraseña:** Tu contraseña
- **Puerto:** 21

### 2. Subir archivos

1. Conectar con FileZilla o el File Manager de cPanel
2. Ir a la carpeta `public_html`
3. Subir todos los archivos:
   - `index.html`
   - Carpeta `css/`
   - Carpeta `js/`
   - Carpeta `imagenes/`

### 3. Configurar dominio

Si querés usar un dominio personalizado:
1. En Namecheap, ir a "Domain List"
2. Clic en "Manage" tu dominio
3. En "Advanced DNS" agregar registros:
   - **Type:** A Record
   - **Host:** @
   - **Value:** IP de tu hosting

## 📱 Funcionalidades Implementadas

### 1. Sistema de Navegación
- Menú fijo en scroll
- Navegación suave entre secciones
- Menú responsive para móviles

### 2. Hero Section
- Logo animado
- Título y slogan
- Botón de llamado a la acción
- Indicador de scroll

### 3. Historia del Club
- Timeline animado
- Galería de fotos con efecto hover
- Estadísticas animadas (contadores)
- Lightbox en imágenes (clic para ampliar)

### 4. Sistema de Reservas
- Integración con Calendly
- Cards informativas
- Diseño responsive

### 5. Servicios Adicionales
- Cards para Fútbol Funcional
- Cards para Salón de Fiestas
- Botones directos a WhatsApp

### 6. WhatsApp Integration
- Botón flotante permanente
- Links directos con mensaje pre-cargado
- Animación de pulso

## 🎨 Colores del Proyecto

- **Verde Principal:** `#00A651`
- **Verde Oscuro:** `#008741`
- **Verde Claro:** `#4CBB7C`
- **Amarillo:** `#FFD700`
- **Fondo Oscuro:** `#0D1B2A`
- **Fondo Secundario:** `#1B263B`

## 📱 Responsive Design

La web está optimizada para:
- 📱 **Móviles:** 320px - 480px
- 📱 **Tablets:** 481px - 768px
- 💻 **Laptops:** 769px - 1024px
- 🖥️ **Desktop:** 1025px+

## 🔧 Personalización

### Cambiar colores

Editar en `css/style.css` las variables CSS (línea 2-16):

```css
:root {
    --primary-color: #00A651;  /* Tu color principal */
    --primary-dark: #008741;   /* Versión oscura */
    --primary-light: #4CBB7C;  /* Versión clara */
}
```

### Cambiar textos

Editar directamente en `index.html` las secciones correspondientes.

### Agregar más fotos

1. Subir fotos a la carpeta `imagenes/`
2. Agregar en la galería (`index.html` línea ~125):

```html
<div class="gallery-item">
    <img src="imagenes/tu-foto.jpg" alt="Descripción">
</div>
```

## 📈 SEO Optimizado

- Meta tags configurados
- Descripciones alt en imágenes
- Estructura semántica HTML5
- Carga rápida (lazy loading)
- URLs amigables

## ✅ Checklist de Implementación

- [x] Estructura HTML creada
- [x] Estilos CSS implementados
- [x] JavaScript funcional
- [x] Imágenes optimizadas
- [ ] Configurar Calendly
- [ ] Subir a hosting
- [ ] Configurar dominio
- [ ] Probar en móviles
- [ ] Configurar Google Analytics (opcional)

## 📞 Contacto WhatsApp

Número configurado: **+598 97 128 095**

Los enlaces de WhatsApp incluyen mensajes pre-cargados:
- Fútbol Funcional
- Salón de Fiestas
- Consulta general

## 🚀 Próximos Pasos Recomendados

1. **Configurar Calendly** (siguiendo los pasos arriba)
2. **Subir a Namecheap** usando FTP
3. **Probar en diferentes dispositivos**
4. **Agregar Google Analytics** (opcional pero recomendado)
5. **Configurar dominio personalizado**
6. **Agregar más fotos** si tenés
7. **Optimizar imágenes** con TinyPNG antes de subir

## 💡 Tips Adicionales

- Las imágenes pesadas pueden hacer lenta la web. Comprimilas antes de subir.
- Calendly tiene app móvil para gestionar reservas fácilmente
- Podés agregar Google Maps embed en la sección de contacto
- Considerá agregar testimonios de clientes en el futuro

## 📄 Licencia

Proyecto desarrollado para Ipora Futbol Club - 2025

---

**Desarrollado con 💚 para la familia Ipora**
