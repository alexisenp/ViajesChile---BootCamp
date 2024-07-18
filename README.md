# Documentación del Proyecto "Viajes Chile" 

Este proyecto es una prueba realizada para el BootCamp de [Talento Digital para Chile](https://talentodigitalparachile.cl/). En el cual se pedia realizar una página web de muestra para "Viajes Chile", una agencia de viajes ficticia. La página incluye una navegación fija, un carrusel de imágenes, secciones de contenido y un formulario de contacto. A continuación se detallan las librerías y componentes utilizados en este proyecto.
Los detalles completos de los requerimientos los pueden encontrar en el archivo requerimientos.pdf.

## Tecnologías Utilizadas

- **HTML5**: Estructura básica del sitio web.
- **CSS3**: Estilos personalizados.
- **Bootstrap 5.3.3**: Framework CSS para diseño responsive y componentes predefinidos.
- **Font Awesome**: Librería de iconos.
- **Google Fonts**: Fuente personalizada "Roboto".

## Librerías y Recursos

### Bootstrap

**CDN Bootstrap CSS:**
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```

**CDN Bootstrap JS:**
```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```


### Font Awesome
**CDN Font Awesome:**
```
<script src="https://kit.fontawesome.com/845ca18d34.js" crossorigin="anonymous"></script>
```

### Google Fonts
**CDN Google Fonts:**
```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
```

### Componentes Bootstrap Utilizados

El proyecto "Viajes Chile" utiliza los siguientes componentes de Bootstrap:

Componentes bootstrap que no usan javascript
- **Navbar**: Para la barra de navegación fija.
- **Button**: En el formulario de contacto y los controles del carrusel.
- **Card**: Para mostrar los destinos destacados.
- **Forms**: En el formulario de contacto.

- **Carousel**: Para el carrusel de imágenes.
- **Toast**: Para la notificación de confirmación.
- **Tooltip**: Para mostrar mensajes de ayuda.


### Estructura del Proyecto
**Encabezado (Header)**
El encabezado incluye una barra de navegación fija con enlaces a las diferentes secciones de la página y un carrusel de imágenes.

**Sección "¿Quiénes Somos?"**
Una sección informativa con iconos y texto descriptivo sobre la agencia de viajes.

**Sección "Destacados"**
Una sección que muestra los destinos destacados en tarjetas con imágenes y descripciones.

**Sección "Contacto"**
Un formulario de contacto con campos para nombre, asunto y mensaje, y un botón para enviar el formulario. También incluye una notificación de toast para confirmar el envío del mensaje.

**Footer**
Un pie de página con el nombre de la agencia y enlaces a redes sociales.

## Archivos CSS y JS Personalizados
**Archivo CSS**
El archivo CSS personalizado se encuentra en ./assets/css/style.css.

**Archivo JS**
El archivo JS personalizado se encuentra en ./assets/js/script.js.

## Instalación y Uso
**Clonar el repositorio:**


git clone https://github.com/tu-usuario/viajes-chile.git

Abrir el archivo index.html en tu navegador para ver la página web.

## Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para cualquier mejora o corrección.

