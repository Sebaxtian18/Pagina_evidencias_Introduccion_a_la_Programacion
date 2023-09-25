<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 
 
# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

## Solucion

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: firebrick;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: firebrick;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Los cuatro mejores Skateparks en Medellín</h1>
        <h3>Skate Or Die</h3>
    </header>

    <section>
        <h2>Skatepark Madre Laura.</h2>
        <p>El <i>Skatepark de La Madre Laura,</i> es el <u>spot</u> perfecto para comerzar a entrenar bowl, ya que este por su diseño con curvas, jotas y decensos se convierte en uno de los dos mejores spots para aprender a bombear y perderle el miedo a la velocidad.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/skaterpark-Madre-laura-2016-4-scaled.webp?alt=media&token=e2e53229-d0f2-4519-ae5d-0b08e2eb64cb" alt="Skatepark Madre Laura" width="700">
        <p>Mayor informacion <a href="https://progresoskateboarding.com/skateparks-colombia/" target="_blank">progreso skateboarding</a></p>
    </section>

    <section>
        <h2>Skatepark Niquia-Skate-Plaza.</h2>
        <p>El <i>Skatepark Niquia-Skate-Plaza,</i> es el <u>spot</u> es el la pista mas amplia y plana del <i>valle de aburra.</i> Cuenta con una piramide, varios <u>spots</u> de tubos, tanto altos, como bajos, un cajon, un transfer un y pequeño bowl.</p>
        <br>
        <p>Esta pista se caracteriza por la autogestion de la comunidad skater, ya que estos se han encargado de hacer varios de los <u>spots</u> que tiene.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/skateparkNiquia.jpg?alt=media&token=bcc4270f-ec9c-4af6-ae57-bbf49dae8a11" width="700">
        <p>Mayor informacion <a href="https://progresoskateboarding.com/skateparks-colombia/" target="_blank">progreso skateboarding</a></p>
    </section>

    <section>
        <h2>Skatepark 4 Sur.</h2>
        <p>El <i>Skatepark de La 4 Sur,</i> en lo personal es el <u>spot</u>, mas completo y amplio del <i>valle de aburra</i>. Su diseño mas al estilo <u>Bowl</u>, hace que este sea el Skatepark con mas visitantes no solo del valle de aburra, sino, de los distintos lugares del pais.</p>
        <br>
        <p>Este Skatepark cuenta con las jotas mas altas en el <i>valle de aburra.</i></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/panoramicas-skatepark-4sur-2-scaled.webp?alt=media&token=ba0056f6-7617-424b-8f7c-f28a930ab9a7" alt="Skatepark 4 Sur" width="700">
        <p>Mayor informacion <a href="https://progresoskateboarding.com/skateparks-colombia/" target="_blank">progreso skateboarding</a></p>
    </section>

    <section>
        <h2>Viga Skatepark.</h2>
        <p>El <i>Viga Skatepark,</i> es el <u>spot</u> del sur. Ubicado en envigado, cerca de la estacion del metro, se convierte en el Skatepark mas iconico de la ciudad, con su perfecto diseño, su pista es de alto nivel.</p>
        <br>
        <p>Aunque cuenta con poco espacio, supista tiene lo necesario para convertirse en un profecional de este deporte.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/skatepark-envigado-medelli-2016-4.webp?alt=media&token=7fc6d411-71b6-4b6c-90d8-a33c84cd4d25" alt="Skatepark envigado" width="700">
        <p>Mayor informacion <a href="https://progresoskateboarding.com/skateparks-colombia/" target="_blank">progreso skateboarding</a></p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Aqui les comparto unos videos con un par de trucos.</p>
        <video src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/139633%20(360p).mp4?alt=media&token=95aeb1e0-e9ab-455e-bf59-5d0f86f78da5" controls></video>
        <video src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/skate_-_40384%20(360p).mp4?alt=media&token=803cc568-77c6-4db1-af81-14aefe0dc3b7" controls></video>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Un poco de musica para ambientar la pagina</p>
        <audio src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/fashion-hip-hop-rock-stylish-boy-111449.mp3?alt=media&token=e1cab90e-c089-4a12-b247-913c35573254" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/guitar-electro-sport-trailer-115571.mp3?alt=media&token=26ab45de-42dc-45d4-92cf-854f6f1e9efa" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/intro-music-black-box-trap-beat-13221.mp3?alt=media&token=bae9b884-e069-479d-adaf-06e38246d729" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/github-pages-7777b.appspot.com/o/powerful-stylish-stomp-rock-lets-go-114255.mp3?alt=media&token=be444ed5-cc50-4c73-8f9d-8ef173f60d00" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Les comparto un par de articulos para que conozcan este maravilloso deporte y se animen a patinar</p>
        <iframe src="https://www.24-horas.mx/2023/08/16/el-es-yuto-horigome-el-atleta-que-consiguio-el-primer-oro-olimpico-en-skateboarding/" width="700" height="500" frameborder="0"></iframe>
        <iframe src="https://www.bing.com/videos/search?q=yuto+horigome&&view=detail&mid=B43E80FF850A73AA8F62B43E80FF850A73AA8F62&&FORM=VRDGAR&ru=%2Fvideos%2Fsearch%3Fq%3Dyuto%2Bhorigome%26FORM%3DHDRSC6" width="700" height="500" frameborder="0"></iframe>
    </section>

    <footer>
        Sebastian Castaño Restrepo.
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```