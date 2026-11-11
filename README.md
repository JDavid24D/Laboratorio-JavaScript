# Laboratorio JavaScript
Práctica de Ingeniería Web sobre JavaScript, DOM, eventos y validación de formularios.
## Cambios realizados

### 1. Nuevo saludo con la fecha actual
- Se modificó la función `construirSaludo` en `js/app.js`.
- Al pulsar **Mostrar saludo** ahora aparece un mensaje nuevo que incluye la fecha de hoy, obtenida con `new Date().toLocaleDateString("es-EC", ...)`.
- Ejemplo: *¡Hola! Qué gusto verte en Ingeniería Web. Saludo n.º 1 · Hoy es miércoles, 11 de noviembre de 2026.*

### 4. Nombre del participante con mínimo 5 caracteres
- Se modificó la función `validarRegistro` en `js/app.js`.
- Antes se exigían 3 caracteres; ahora el nombre debe tener al menos 5.
- Si no los tiene, se muestra el error "Ingresa al menos 5 caracteres." y el participante no se registra.
