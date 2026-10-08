[README.md](https://github.com/user-attachments/files/33210000/README.md)
# 🎺 Sonus Divinus

**Sonus Divinus - Instrumentos de Banda** es un sitio web desarrollado en HTML, CSS y JavaScript para presentar y facilitar la compra de instrumentos musicales destinados a bandas escolares, universitarias y profesionales.

El proyecto muestra un catálogo organizado por categorías, presenta diferentes niveles de calidad y precios en bolivianos, y permite iniciar un pedido mediante un formulario conectado a **Formspree** y solicitar información de pago mediante **WhatsApp**.

## 📌 Características principales

- Catálogo de **instrumentos de viento**.
- Catálogo de **instrumentos de percusión**.
- Organización de productos por tipo de instrumento.
- Clasificación de productos:
  - Económica
  - Semiprofesional
  - Profesional
- Precios expresados en **bolivianos (Bs)**.
- Tarjetas de productos con:
  - Imagen
  - Nombre
  - Descripción
  - Nivel
  - Precio
  - Botón de compra
- Diseño adaptable y moderno.
- Navegación mediante pestañas entre viento y percusión.
- Ventana modal para finalizar pedidos.
- Formulario de compra con datos del cliente.
- Envío del formulario mediante **Formspree**.
- Solicitud del código QR de pago mediante **WhatsApp**.
- Información de dirección y contacto.
- Diseño con identidad visual de **Sonus Divinus**.

## 🎷 Instrumentos disponibles

### Instrumentos de viento

El catálogo incluye:

- Trompetas
- Barítonos / Eufonios
- Saxofones
- Clarinetes

Cada grupo cuenta con opciones económicas, semiprofesionales y profesionales.

### Instrumentos de percusión

El catálogo incluye:

- Bombos de marcha
- Tambores militares / cajas de marcha
- Platillos de banda

También se ofrecen diferentes opciones según el nivel del instrumento.

## 💰 Precios

Los precios del catálogo están expresados en **Bs (bolivianos)** y son utilizados como valores de referencia dentro del proyecto.

Algunos ejemplos incluidos en el catálogo:

| Instrumento | Precio |
|---|---:|
| Trompeta Estudiante Sib | 1.250 Bs |
| Trompeta Intermedia Sib | 2.800 Bs |
| Trompeta Custom Sib Pro | 4.500 Bs |
| Barítono Estudiante Sib | 2.400 Bs |
| Saxofón Alto Eb Estudiante | 2.100 Bs |
| Clarinete Bb Estudiante ABS | 1.200 Bs |
| Bombo Estudiante 20" | 980 Bs |
| Tambor Escolar 14"x3.5" | 580 Bs |
| Platillos de Marcha 14" | 650 Bs |

## 🛒 Sistema de compra

Cuando el usuario selecciona **Comprar Ahora**, se abre una ventana para finalizar el pedido.

El formulario solicita:

- Nombre completo
- Correo electrónico
- Teléfono de contacto
- Ciudad / dirección
- Producto seleccionado
- Precio del producto

El producto y el precio se cargan automáticamente en el formulario.

### Formspree

El formulario utiliza Formspree para recibir los datos enviados por el cliente.

Actualmente está configurado con:

```html
<form action="https://formspree.io/f/mppadjzo" method="POST">
```

Si deseas utilizar otro formulario de Formspree, debes reemplazar la dirección de `action` por la correspondiente a tu cuenta.

## 📱 WhatsApp

El sitio incorpora contacto mediante WhatsApp utilizando el número configurado en el código:

```text
+591 75436615
```

El botón permite solicitar el código QR para realizar el pago.

El sistema también genera automáticamente un mensaje con el nombre y precio del producto seleccionado.

## 🎨 Diseño

El diseño utiliza una combinación de colores oscuros y dorados, buscando transmitir una imagen elegante y relacionada con instrumentos musicales.

Entre los elementos visuales se encuentran:

- Logo circular con las iniciales **JP**
- Nombre **Sonus Divinus**
- Subtítulo **Instrumentos de Banda**
- Tarjetas de productos
- Botones de compra
- Ventanas modales
- Iconos de Font Awesome
- Efectos de desplazamiento y transición

## 🧰 Tecnologías utilizadas

- **HTML5** — estructura de la página.
- **CSS3** — diseño, colores, tarjetas, botones y adaptación visual.
- **JavaScript** — navegación entre categorías, apertura del formulario y generación del enlace de WhatsApp.
- **Font Awesome 6.4.0** — iconos.
- **Formspree** — recepción de formularios.
- **WhatsApp** — comunicación y solicitud del código QR de pago.

## 📁 Estructura del proyecto

El proyecto principal está desarrollado en un único archivo:

```text
Sonus Divinus-8.html
```

La estructura general del archivo es:

```text
Sonus Divinus-8.html
│
├── HTML
│   ├── Encabezado
│   ├── Navegación
│   ├── Catálogo de instrumentos de viento
│   ├── Catálogo de instrumentos de percusión
│   ├── Pie de página
│   └── Formulario de compra
│
├── CSS
│   ├── Colores
│   ├── Tarjetas
│   ├── Botones
│   ├── Navegación
│   ├── Modal
│   └── Pie de página
│
└── JavaScript
    ├── Cambio de categorías
    ├── Apertura del formulario
    ├── Carga del producto y precio
    ├── Generación del enlace de WhatsApp
    └── Cierre del formulario
```

## ▶️ Cómo ejecutar el proyecto

No es necesario instalar programas adicionales para visualizar la página.

### Opción 1: Navegador

1. Descarga o guarda el archivo `Sonus Divinus-8.html`.
2. Haz doble clic sobre el archivo.
3. Se abrirá automáticamente en el navegador.

### Opción 2: Visual Studio Code

1. Abre **Visual Studio Code**.
2. Selecciona **Abrir archivo**.
3. Abre `Sonus Divinus-8.html`.
4. Puedes utilizar una extensión como **Live Server** para visualizar los cambios en tiempo real.

## ⚙️ Personalización

Puedes modificar fácilmente:

- Nombre de los instrumentos.
- Descripciones.
- Precios.
- Imágenes.
- Colores.
- Número de teléfono.
- Dirección.
- Datos del formulario.
- Información del pie de página.

### Cambiar el número de WhatsApp

Busca en JavaScript:

```javascript
var myPhoneNumber = "59175436615";
```

y reemplaza el número por el correspondiente, utilizando el código de país y sin el signo `+`.

También debes actualizar el enlace de WhatsApp ubicado en el pie de página si cambias el número de contacto.

## 📍 Información de contacto

**Dirección:** Azari

**Celular / WhatsApp:** +591 75436615

## 🎯 Objetivo del proyecto

El objetivo de **Sonus Divinus** es ofrecer una plataforma web sencilla y organizada para mostrar instrumentos de banda, facilitar la consulta de productos y permitir que los posibles compradores puedan iniciar un proceso de pedido y comunicación de manera digital.

## 📚 Uso académico

Este sitio web forma parte de un proyecto educativo de desarrollo de un emprendimiento digital relacionado con la comercialización de instrumentos de banda.

El proyecto permite aplicar conocimientos de:

- Desarrollo web.
- Diseño de interfaces.
- HTML.
- CSS.
- JavaScript.
- Formularios web.
- Comunicación digital.
- Organización de productos.
- Emprendimiento y comercio electrónico.

## 👨‍💻 Autor

**Proyecto:** Sonus Divinus  
**Área:** Desarrollo web / Emprendimiento  
**Año:** 2026

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de presentación de un emprendimiento web.

© 2026 JP Sonus Divinus. Todos los derechos reservados.
