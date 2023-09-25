<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

# Solucion

## Distribuidora Anduri
```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Distribuidora Anduri</title>
</head>
<body>
    <header>
        <h1><strong>Distribuidora Anduri</strong></h1>
    </header>
    <main>
        <p>Bienvenidos a la empresa Distribuidora anduri tenemos una gama de productos dirigidos a la confeccion como

            son: las maquinas de cocer, repuestos y accesorios</p>
        <p>
        <h3><u>Aqui encontraran informacion sobre nuestros servicios y productos</u></h3>
        </p>
        <nav>
            <a href="about.html" target="_blank" rel="noopener noreferrer">Acerca</a>
        </nav>
        <p>
        <h3><u>Aqui estaran las formas con las cuales nos pueden contactar</u></h3>
        </p>
        <nav>
            <a href="contact.html" target="_blank" rel="noopener noreferrer">contacto</a>
        </nav>
    </main>
    <footer>
        <p><span style="color: red;">Sebastian Castaño Restrepo</span></p>
    </footer>
</body>
</html>
```

## Informacion

```html 

<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head>
<body>
    <header>
        <h1><strong>Nosotros</strong></h1>
    </header>
    <section>
        <h2><u>Historia</u></h2>
        <p>Esta empresa fue fundada en el año 1996 se empezo vendiendo unas promociones de agujas e hilos con tres

            vendedores y luego se empezo la venta con catalogo puerta a puerta mas adelante la empresa empezo a crecer y

            saco al negocio maquinas de cocer familiares e industriales y venta de muebles para maquinas ya asi la

            empresa empezo a crecer y se acoplo con las demandas de la actualidad </p>
    </section>
    <article>
        <h3><u>Mision y vision</u></h3>
        <p>
        <ul>
            <li>La mision de la compañia es mejorar la calidad de vida de las personas en cuanto a elaborar sus prendas,
                corte y confeccion.</li>
            <li>La vision es que queremos ser la compañia con mejor enfoque a la expectativa del cliente</li>
        </ul>
        </p>
    </article>
    <p>
    <h3><u>Aqui estaran las formas con las cuales nos pueden contactar</u></h3>
    </p>
    <nav>
        <a href="contact.html" target="_blank" rel="noopener noreferrer">contacto</a>
    </nav>
    <p>
    <h3><u>Aqui volveras al Inicio</u></h3>
    </p>
    <nav>
        <a href="intex.html" target="_blank" rel="noopener noreferrer">Inicio</a>
    </nav>
    <footer>
        <p><span style="color: red;">Sebastian Castaño Restrepo</span></p>
    </footer>
</body>
</html>
```
## Contacto

```html

<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>
<body>
    <header>
        <h1><strong>Contacto</strong></h1>
    </header>
    <main>
        <p>Aqui puedes dejar tus datos para luego contactarte</p>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="tex" id="nombre"><br>
            <p>
            </p>
            <label for="email">Email</label>
            <input type="email" id="email"><br>
            <p>
            </p>
            <label for="whatsapp">Whatsapp</label>
            <input type="whatsapp" id="whatsapp"><br>
            <p>
            </p>
            <label for="mensaje">Mensaje</label><br>
            <textarea id="mensaje"></textarea><br>
            <p>
            </p>
            <input type="submit" value="Enviar">
        </form>
        <aside>
            <h3><u>Ubicacion</u></h3>
            <p>Entre calle 58, Cra. 55 #34-89, Medellín, Antioquia</p>
        </aside>
        <p>
        <h3><u>Aqui encontraran informacion sobre nuestros servicios y productos</u></h3>
        </p>
        <nav>
            <a href="about.html" target="_blank" rel="noopener noreferrer">Acerca</a>
        </nav>
        <p>
        <h3><u>Aqui volveras al Inicio</u></h3>
        </p>
        <nav>
            <a href="intex.html" target="_blank" rel="noopener noreferrer">Inicio</a>
        </nav>
    </main>
    <footer>
        <p><span style="color: red;">Sebastian Castaño Restrepo</span></p>
    </footer>
</body>
</html>
```