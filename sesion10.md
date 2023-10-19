<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


# Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.
Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```
Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

## Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

# Solucion

1. ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

**R//** La diferencia entre `position: absoluta;` y `pisition: retalitive;` esta es el flujo del codigo, ya que la `position: absoluta;` puede posicionarse sobre cualquier elemento que tenga una posicion diferente a `statik` y se ubica en ralacion a su ancestro acaparando esta posicion e ignorando el flujo del codigo, **ya que su posicion original quedaria libre para un futuro elemento**, mientras que la posicion relativa sigue su flujo de codigo normal y aunque tambien se puede superponer, **el espacio que ocuparía en el flujo normal del documento se mantiene reservado**.

Un ejemplo de esto se muestra acontinuacion.
## HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="elemento-1">
    <img src="./img/8633682.png" alt="">
  </div>
  <div class="elemento-2">
    <img src="./img/8611714.png" alt="">
  </div>
</body>
</html>
```
##CSS
```css
.elemento-1 {
    position: absolute;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background: red;
  }

  .elemento-2 {
    position: relative;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background-color: green;
  }
```
Si observamos el `elemento-1` al tener la propiedad `position: absolute;` pierde el flujo de codigo y el `èlemento-2` que a su vez tiene una `position: relative;` se superpone a él.

Seria diferente si el `elemento-1` tuviese la propiedad `position: relative;`.  ya que este no deja su espacio libre en el flujo de codigo como se puede ver acontinuacion.

```css
.elemento-1 {
    position: relative;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background: red;
  }

  .elemento-2 {
    position: absolute;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background-color: green;
  }
```

2.  ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

**R//** La propiedad `z-index` se utiliza para controlar la visualizacion de los elementos cuando se superponen.

Con el ejemplo anterior podemos hacer que el `elemento-1` con `position: absolute;` pase a estar soble el `elemento-2` aunque este tenga una `position: relative;`.

```css
.elemento-1 {
    position: absolute;
    z-index: 2;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background: red;
  }

  .elemento-2 {
    position: relative;
    z-index: 1;
    width: 500px;
    height: 500px;
    top: 100px;
    left: 100px;
    background-color: green;
  }
```
3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

**R//**  La propiedad `display` nos permite determinar como se mostrara nuestro contenido en pantalla, ya sea 
- vertical ( `block` ) 
- horizontal ( `inline` o `inline-block` )

Estas propiedades nos ayudan a darle una mejor vista y distribucion del contenido a nuestros proyectos.

```css
.elemento-1 {
    position: absolute;
    display: inline-block;
    z-index: 2;
    width: 500px;
    height: 500px;
    top: 400px;
    left: 500px;
    background: red;
  }

  .elemento-2 {
    position: relative;
    z-index: 1;
    width: 500px;
    height: 500px;
    top: 0px;
    left: 900px;
    background-color: green;
  }
  
  .elemento-2 div{
    display: inline-block;
    width: 100px;
    height: 100px;
    background: papayawhip;
  }
  .elemento-2 :nth-child(2){
    display: inline-block;
    width: 100px;
    height: 50px;
    background: papayawhip;
  }

  .elemento-1 div{
    display: block;
    width: 100px;
    height: 100px;
    background: papayawhip;
  }
```
