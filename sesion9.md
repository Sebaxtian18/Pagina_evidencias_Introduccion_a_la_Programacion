<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


# Actividad: Propiedades de espaciado y unidades de medida

Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código.

```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
3. En el archivo CSS, agrega el siguiente código:

```
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
- Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles. Antes de hacerlo debes agregar un `background-color` para poder visualizar los contenedores.

-  Practicar el uso de las propiedades de espaciado.

4. Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
5. Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

```
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
6.  Border: Agrega un borde de 5 píxeles de color rojo.

```
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
7. Border-radius: Agrega un radio de esquina de 10 píxeles.

```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
8. Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
# Preguntas:
- ¿Qué es la propiedad margin?
- ¿Qué es la propiedad padding?
- ¿Qué es la propiedad border?
- ¿Qué es la propiedad border-radius?
- ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

# Solucion

### HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
  <div class="contenedor1">
    <div class="elemento1"></div>
  </div>
  <div class="contenedor2">
    <div class="elemento2"></div>
  </div>
  <div class="contenedor3">
    <div class="elemento3"></div>
  </div>
  <div class="contenedor4">
    <div class="elemento4"></div>
  </div>
  <div class="contenedor5">
    <div class="elemento5"></div>
  </div>
</body>
</html>
```
### CSS

```css
.contenedor {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento {
    width: 100px;
    height: 100px;
    background: teal;
  }    

  .contenedor1 {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento1 {
    position: relative;
    top: 10px;
    margin: 10px;
    width: 100px;
    height: 100px;
    background: teal;
  }    

  .contenedor2 {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento2 {
    position: relative;
    top: 10px;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
    background: teal;
  }    

  .contenedor3 {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento3 {
    position: relative;
    top: 10px;
    border: solid 5px red;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
    background: teal;
  }    

  .contenedor4 {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento4 {
    position: relative;
    top: 10px;
    border-radius: 10px;
    border: solid 5px red;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
    background: teal;
  }    
  
  .contenedor5 {
    width: 200px;
    height: 200px;
    background: orange;
  }
  
  .elemento5 {
    position: relative;
    top: 50%;
    border-radius: 10px;
    border: solid 5px red;
    padding: 50%;
    margin: 50%;
    width: 100px;
    height: 100px;
    background: teal;
  }    
  ```

  ### Preguntas
  1. ¿Qué es la propiedad `margin`?
  - La propiedad `margin` nos permite desplazar contenido al interior de un contenedor o el contenedor mismo haciendo uso de los cuatro margenes: margen izquierdo `margin-left`, margen derecho `margin-right`, margen superior `margin-top`, o margen inferior `margin-bottom`.
  2. ¿Qué es la propiedad `padding`?
  - La propiedad `padding` nos permite incrementar el tamaño del contenido de un contenedor o el contenedor mismo.
  3. ¿Qué es la propiedad `border`?
  - Esta propiedad nos permite darle un borde visible al contenedor, un de tamaño especifico, y un color haciendolo mas vistoso.
  4. ¿Qué es la propiedad `border-radius`?
  - Esta Propiedad nos permite suavisar las esquinas de los contenedores o redondearlas por completo hasta lograr un circulo o un ovalo.
  5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?
  - Son varias, pero las mas comunes son los pixeles `Px` que seria un pixel en pantalla. 
  - Los Ems `em` que se basa en el tamaño de fuente utilizado en el contenedor. 
  - El porcentaje `%` que se basa en el tamaño del elemento padre. (contenedor).
  - El Rem `rem` que se basa en el tamaño de fuente, pero del documento `HTML`. 
  - El Vw `vw`, que se basa en el ancho de la ventana. Este es muy bueno para trabajar los contenidos en diferentes dispositivos.
  - El Vh `vh`, este sebasa en el alto de la ventana. 