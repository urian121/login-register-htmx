# Sistema de Autenticación con HTMX

Este es un sistema de autenticación moderno que utiliza HTMX para crear una experiencia de usuario fluida sin necesidad de recargar la página. El proyecto incluye formularios de inicio de sesión y registro con validación del lado del cliente y transiciones suaves.

## Características

- **Interfaz de usuario moderna y responsiva** con Bootstrap 5
- **Validación de formularios** en tiempo real
- **Transiciones suaves** entre formularios
- **Sin recargas de página** gracias a HTMX
- **Formulario de ejemplo** incluido para pruebas

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── login-form.html     # Formulario de inicio de sesión
├── register-form.html  # Formulario de registro
└── assets/
    └── style.css       # Estilos personalizados
```

## Tecnologías Utilizadas

- [HTMX](https://htmx.org/) - Para interacciones AJAX sin JavaScript
- [Bootstrap 5](https://getbootstrap.com/) - Para estilos y componentes UI
- [Font Awesome](https://fontawesome.com/) - Para iconos (si se incluyen)

## Cómo Usar

1. Clona este repositorio
2. Abre `index.html` en tu navegador
3. Explora los formularios de login y registro

## Validación de Formularios

El proyecto incluye validación del lado del cliente:

- Campos requeridos
- Validación de formato de correo electrónico
- Validación antes del envío

## Personalización

Puedes personalizar los estilos editando el archivo `assets/style.css` o modificando las clases de Bootstrap en los archivos HTML.

## Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, pero recomendado para probar las peticiones AJAX)

## Notas

- Este es un proyecto de frontend. Para funcionalidad completa, necesitarás implementar el backend correspondiente (archivos PHP como `login.php` y `register.php`).
- Las credenciales no se validan en este ejemplo, solo se muestra la funcionalidad del frontend.
