<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


># Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

### 1. Crea el esqueleto de una página web simple con la siguiente estructura:

-  Encabezado ```<header>```
-  Tres párrafos ```<p>```
-  Una imagen ```<img>```
-  Un pie de página ```<footer>```

### 2.   Aplica los siguientes estilos usando selectores de etiqueta:

-  Color rojo a los encabezados ```<h1>```
-  Color azul a los párrafos ```<p>```
-  Borde grueso negro a la imagen ```<img>```

### 3.  Aplica los siguientes estilos usando seleccionadores de clase:

-  Color verde a los elementos con la clase ".destacado"
-  Tamaño de fuente grande a los elementos con la clase ".grande"

### 4. Aplica los siguientes estilos usando seleccionadores de ID:

-  Color amarillo al elemento con ID "#principal"
-  Sombra al elemento con ID "#sombras"

### 5. Aplica los siguientes estilos usando seleccionadores descendientes:

-  Color gris a los párrafos dentro de un ```<div>```
- Centrar el contenido de la sección ```<section>```

># Solucion

>### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <header id="sombras">
        <h1>Yo digo que las estrellas.</h1>
    </header>
    <div class="contenedor-tarjeta">
        <img src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/Evidencias%20Introduccion%20a%20la%20programacion%2Fpexels-aleksandr-firstov-18306592.jpg?alt=media&token=b77b2b5d-70d4-4680-8eec-679266d2fd29" alt="">
    </div>
    <section>
        <p class="destacado">Yo digo que las estrellas le dan gracias a la noche.</p>
        <p id="color">Por que encima de otro coche, no pueden lucir tan bellas.</p>
        <p id="principal">Y digo que es culpa de ellas, la noche y el universo, cual son culpables los versos de que hayan noches y estrellas.</p>
    </section>
    <div>
        <p>Yo digo que no hay quin crezca más allá de lo que vale.</p>
        <p id="principal">Y el tonto que no lo sabe es el que en zancos se arresta.</p>
        <p>Y digo que el que se presta para peon del veneno, es doble tonto y no quiero, ser bailarin de su fiesta.</p>
    </div>
    <footer>
        <p class="grande">
             Sebastian Castaño Restrepo.
        </p>
        <p class="grande">
             Introduccion a la programacion.
        </p>
        <p class="grande">
             zsebax.1994@gmail.com
        </p>
    </footer>
</body>
</html>
```
>### CSS
```css
header {
    background: #e0e0e0;
    border-radius: 5px;
    margin-bottom: 10px;
    display: flex;
}
header h1 {
    margin-left: 20px;
    color: red;
    border-radius: 5px;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 3);
}
.contenedor-tarjeta{
    display: flex;
    justify-content: center;
}
.contenedor-tarjeta img{
    width: 800px;
    justify-content: center;
    border: solid #e0e0e0 10px;
}
.destacado{
    color: rgb(71, 222, 71);
}
#color{
    color: gray;
}
.grande{
    font-size: 20px;
}
#principal{
    color: yellow;
}
#sombras{
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 3);
}
section{
    display: flex;
    flex-direction: column;
    align-items: center;
}
section p{
    color: blue;
}
footer{
    display: flex;
    justify-content: space-around;
    background: #e0e0e0;
    border-radius: 5px;
    color: blue;
}
div p{
    color: gray;
}
div{
    display: flex;
    flex-direction: column;
    align-items: center;
}
```