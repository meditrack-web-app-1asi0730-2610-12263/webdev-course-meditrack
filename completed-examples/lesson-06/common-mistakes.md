# Errores comunes para principiantes

## 1. No cerrar etiquetas

Incorrecto:

```html
<p>Hola mundo
```

Correcto:

```html
<p>Hola mundo</p>
```

## 2. Escribir mal el nombre del archivo CSS

Si el archivo se llama `styles.css`, el enlace debe ser:

```html
<link rel="stylesheet" href="styles.css">
```

## 3. Olvidar el atributo `alt` en imágenes

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

## 4. Usar colores con poco contraste

Evita colocar texto claro sobre fondos claros o texto oscuro sobre fondos oscuros.

## 5. No probar la página en el navegador

Cada cambio debe revisarse abriendo el archivo `index.html` en el navegador.
