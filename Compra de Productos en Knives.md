# Compra de Productos en Knives

## Historia de Usuario

Como usuario del sitio web, quiero visualizar y comprar cuchillos desde la página de compra, para realizar una transacción rápida y segura.

---

## Visualización de Productos

### Observación 3

- La página debe mostrar una lista de cuchillos con imágenes, nombre, descripción y precio.

### Solución para Observación 3

- Se agregaron más imágenes con nombre, descripción y precio.

### Observación 2

- Los productos deben organizarse en tarjetas (cards) con un diseño atractivo.

### Solución para Observación 2

- Las imágenes fueron organizadas utilizando `grid` de Bootstrap para que sean atractivas.

---

## Interacción y Experiencia del Usuario

### Observación 4

- El usuario debe poder ver información sobre métodos de pago y cálculo de envío en la barra lateral.

### Solución para Observación 4

- Hay un menú de "Opciones" en la barra lateral que muestra enlaces de contacto, envío y métodos de pago. Cada enlace te lleva a una página funcional.

---

## Accesibilidad y Responsividad

### Observación 1

- La página debe ser completamente responsive y adaptable a dispositivos móviles.

### Solución

- Se utilizaron varios códigos de Bootstrap, como:
  - `container-fluid`: Hace que el contenido ocupe todo el ancho de la pantalla y se adapte automáticamente.
  - `row` y `col-md-3`, `col-md-9`, `col`: Definen un diseño flexible basado en columnas que cambia según el tamaño del dispositivo.
