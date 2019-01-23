# imageInverter

En chrome no funciona:
```
Uncaught DOMException: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': The canvas has been tainted by cross-origin data.
```
Pero lo he provado en firefox y va bien !

### Para cambiar la imagen solo hay que modifica el src:
```html
<img id="image" src="cualquierImagen.jpg">
```
