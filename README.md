#  Pequeños Pasos - E-commerce de Ropa Infantil

**Módulo:** DIU (Diseño de Interfaces de Usuario) - Tarea 1 / Reto 4
**Alumno:** José Luis Mba

##  Descripción del Proyecto
"Pequeños Pasos" es un prototipo interactivo de alta fidelidad para una aplicación móvil de comercio electrónico centrada en moda infantil. El proyecto se ha desarrollado siguiendo las directrices de **Material Design 3** para asegurar una experiencia de usuario (UX) coherente, accesible y moderna.

##  Enlace al Prototipo en Figma
> **Nota:** El archivo cuenta con permisos de edición habilitados para la docente, permitiendo revisar el historial de versiones, los estilos y las conexiones del prototipo interactivo.

* **[Haz clic aquí para acceder al archivo completo de Figma] https://www.figma.com/design/9qpi5mgnLxceKHJhACfaNo/T1-%C2%B7-Peque%C3%B1os-Pasos-%C2%B7-Jose-Luis-Mba?node-id=63-296&t=PnnyYt6wkpIPejZL-1**

##  Características y Funcionalidades
El prototipo abarca un flujo de compra completo, incluyendo las siguientes pantallas interactivas:
1. **Inicio:** Pantalla de bienvenida con acceso a novedades y barra de navegación.
2. **Catálogo:** Listado de productos (`TarjetaProducto`) con sistema de filtrado.
3. **Detalle de Producto:** Vista ampliada de la prenda, con selección de componentes personalizados (`SelectorTalla`) y un overlay emergente (*Bottom Sheet*) para la "Guía de tallas".
4. **Carrito:** Resumen de la compra antes del pago.
5. **Checkout:** Formulario de datos de envío que incluye un **estado de error** validado visualmente.
6. **Confirmación:** Pantalla de éxito del pedido.
7. **Perfil:** Zona de usuario que integra la característica de fidelización "Palabra del día" (Sostenibilidad).

###  Modo Oscuro (Dark Theme)
Se han diseñado las variantes en modo oscuro para las pantallas de **Inicio** y **Detalle**, aplicando correctamente la inversión de tonos de la paleta *surface* y *on-surface* para garantizar la legibilidad nocturna.

##  Sistema de Diseño (Material Theme Builder)
Todo el aspecto visual está guiado por un sistema de variables generadas a través del plugin *Material Theme Builder*:
* **Color Principal (Primary):** Azul `#36618E` (aplicado en botones de acción principal y navegación activa).
* **Superficies (Surface):** Fondos claros y tarjetas contrastadas para el modo claro.
* **Estado de Error:** Rojo característico aplicado en los campos obligatorios del proceso de Checkout.
