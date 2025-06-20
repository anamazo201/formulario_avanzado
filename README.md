# Formulario Avanzado

Este proyecto es un formulario web avanzado con validaciones en tiempo real, barra de progreso, indicador de fortaleza de contraseña y resumen de datos enviados.

## Características

- Validación en tiempo real de nombres, apellidos, correo, teléfono y fecha de nacimiento.
- Confirmación de correo y contraseña.
- Indicador visual de fortaleza de contraseña.
- Barra de progreso que muestra el avance del llenado del formulario.
- Contador de caracteres para comentarios.
- Botón de envío habilitado solo cuando todos los campos son válidos.
- Resumen de los datos ingresados al enviar el formulario.
- Restricción de copiar y pegar en campos sensibles (correo y contraseña).

## Estructura de archivos

```
FORMULARIO AVANZADO/
│
├── index.html
├── css/
│   └── styles.css
```

## Cómo usar

1. Abre el archivo `index.html` en tu navegador.
2. Llena los campos del formulario siguiendo las indicaciones y validaciones.
3. El botón "Enviar Formulario" se habilitará cuando todos los campos sean válidos.
4. Al enviar, verás un resumen de los datos ingresados.

## Personalización

- Puedes modificar los estilos en `css/styles.css`.
- Puedes agregar o quitar validaciones en el script dentro de `index.html`.
