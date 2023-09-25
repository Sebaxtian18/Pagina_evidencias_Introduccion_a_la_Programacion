<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

## Solucion 

```html 
<table border="1px" align="center" cellpadding="2px" cellspacing="4px" valing="center">
    <thead>
        <tr>
            <th>Codigo</th>
            <th>Nombre</th>
            <th>Description</th>
            <th>Precio</th>
            <th>Stock</th>
            <th>Fecha de fabricacion</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">001</td>
            <td rowspan="2">OPPO Reno 6 Lite</td>
            <td>Reno 6 Lite combina una poderosa configuración técnica dentro de un diseño ligero, delgado y resistente. Ofrece un novedoso sistema de cámaras con IA 2.0 que te permitirá disfrutar de fotografías y videos con el más alto nivel de detalle. Además, es uno de los pocos equipos en el mundo que brinda una increíble batería de 5000 mAh con super carga rápida y permanece con un diseño delgado y estético.</td>
            <td>996.750</td>
            <td>5</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Su procesador Snapdragon y la función de ampliación de RAM te asegurarán potencia y fluidez. Personalízalo a tu gusto y disfruta de una de las marcas con mayor nivel de calidad en el mundo.</td>
            <td>Ref</td>
            <td colspan="2">Blanco y Azul</td>
        </tr>
        <tr>
            <td rowspan="3">002</td>
            <td rowspan="3">Iphone Pro Max</td>
            <td>El iPhone 14 Pro Max te permite captar detalles increíbles gracias a su cámara gran angular de 48 MP.</td>
            <td>6.099.000</td>
            <td>12</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Además, trae la Dynamic Island y una pantalla siempre activa, para que puedas interactuar con tu iPhone de una forma completamente nueva. Y viene con Detección de Choques, una funcionalidad de seguridad que pide ayuda cuando no estás en condiciones de hacerlo.</td>
            <td>Ref</td>
            <td colspan="2">Negro y Azul plateado</td>
        </tr>
        <tr>
            <td>Resistencia a las salpicaduras, al agua y al polvo: El iPhone 14 Pro y el iPhone 14 Pro Max son resistentes a las salpicaduras, al agua y al polvo, y fueron probados en condiciones de laboratorio controladas, con una clasificación IP68 según la norma IEC 60529 (hasta 30 minutos a una profundidad máxima de 6 metros). La resistencia a las salpicaduras, al agua y al polvo no es una condición permanente, y podría disminuir como consecuencia del uso normal. No intentes cargar un iPhone mojado; consulta el manual del usuario para ver las instrucciones de limpieza y secado. La garantía no cubre daños producidos por líquidos.</td>
        </tr>
        <tr>
            <td rowspan="2">003</td>
            <td rowspan="2">Consola PS5 Estándar 825GB + 1 Control Dualsense</td>
            <td>La consola PS5™ hace posibles nuevas formas de juego que jamás habías imaginado. Experimenta una velocidad sorprendente con una SSD de velocidad ultrarrápida, una inmersión más profunda con soporte para respuesta háptica además de una generación completamente nueva de juegos de PlayStation®.</td>
            <td>2.999.900</td>
            <td>32</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Velocidad sorprendente: Disfruta de la potencia de una CPU, una GPU y una SSD personalizadas con E/S integradas que redefinirán lo que una consola PlayStation puede hacer.</td>
            <td>Ref</td>
            <td colspan="2">Blanco</td>
        </tr>
        <tr>
            <td rowspan="3">004</td>
            <td rowspan="3">XBOX Series S 512 GB + 1 Control Inalámbrico</td>
            <td rowspan="2">Solo digital , Todo de nueva generación: Pásate a lo digital con la Xbox Series S y crea una biblioteca de juegos digitales. Tus juegos, partidas guardadas y copias de seguridad están a salvo en la nube. Además, disfruta de la capacidad de reservar y preinstalar los juegos disponibles próximamente para que puedas jugar a ellos en el momento de su lanzamiento.</td>
            <td>1.649.900</td>
            <td>23</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Ref</td>
            <td colspan="2">Blanco y Negro</td>
        </tr>
        <tr><td>La consola Xbox Series S, totalmente digital.
            Miles de juegos de 4 generaciones, con retrocompatibilidad
            Velocidad y el rendimiento con la Xbox Velocity Arquitechture
            Tecnología de aceleración de DirectX Raytracingle da a tus juegos un mayor nivel de realismo
            Con Xbox Entrega inteligente juega la mejor versión disponible de tu juego</td>
            <td colspan="3">9 Juegos incorporados en el disco duro.</td>
        </tr>
        <tr>
            <td rowspan="2">005</td>
            <td rowspan="2">Cámara Fotográfica SONY ILCE-6100L</td>
            <td>La cámara SONY de lentes intercambiables ILCE 6100L color negro te brinda una experiencia de alta calidad gracias a su sensor APS-C de 24 mm, logra que los detalles y calidad de fotografía y video sean a nivel profesional. Graba video en 4K, ideal para hacer video clips.</td>
            <td>3.829.900</td>
            <td>12</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Su modo ráfaga de 11 fotos por segundo captura todos los detalles en escenarios de movimiento, cuenta con conexión Wifi y uso de aplicación de Imagen Edge para teléfonos inteligentes, controlando la cámara de manera remota y también funciona como web cam para PC. ¡Adquiera la tuya aquí!</td>
            <td>Ref</td>
            <td colspan="2">Negro</td>
        </tr>
        <tr>
            <td rowspan="2">006</td>
            <td rowspan="2">Cámara Canon EOS RP con lente 24-105mm f/4-7.1 IS STM</td>
            <td>La Canon EOS RP incorpora toda la potencia de una cámara mirrorless de cuadro completo en un cuerpo pequeño y ligero, lo que te abre un mundo de posibilidades emocionantes y creativas.</td>
            <td>7.999.000</td>
            <td>5</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>El lente RF24-105mm F4-7.1 IS STM es compacto y ligero, ofrece un rango de zoom versátil al capturar diferentes sujetos con facilidad. Trae incorporado un estabilizador Óptico de Imagen que mantiene tus fotos y vídeos nitidos. Adquiere la tuya aquí!</td>
            <td>Ref</td>
            <td colspan="2">Negro</td>
        </tr>
        <tr>
            <td rowspan="3">007</td>
            <td rowspan="3">PANASONIC UA90 2000 Watts</td>
            <td>UA90 Panasonic, un paso adelante en cuanto a música y estilo de vida Un audio dinámico e impresionante. Diseño hexagonal: ofrece campo sonido increíblemente amplio. Cuenta con 10 parlantes: hace un perfecto balance de sonido. Controla el equipo desde tu celular: Max Juke App Panasonic. Memoria Interna de 4GB: puedes grabar hasta 1000 canciones, 2 entradas para micrófono: Disfruta del Karaoke en familia</td>
            <td>1.749.900</td>
            <td>20</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Un elegante diseño que luce bien en cualquier ambiente en tu hogar. La calidad incomparable y el potente desempeño del UA90, permite conectarte con tus seres queridos, con un toque de elegancia y un sonido impresionante. </td>
            <td>Ref</td>
            <td colspan="2">Negro</td>
        </tr>
        <tr>
            <td>Es tiempo de sentir cada onda de emoción de cada una de las notas musicales. Ahora puede llevar la música a un nivel totalmente nuevo, en su vida y en la vida de sus seres queridos. Una sofisticada y exclusiva experiencia musical, que le permite al sistema URBAN AUDIO proporcionarle a su vida, una sensación auditiva nueva y con una estupenda gama de sonido</td>
        </tr>
        <tr>
            <td rowspan="2">008</td>
            <td rowspan="2">Escritorio MADERKIT Baptistine</td>
            <td>Trabaja o estudia cómodamente en el Escritorio MADERKIT Baptistine que cuenta con compartimientos laterales con una óptima distribución de espacio para que puedas ubicar fácilmente donde quieras.</td>
            <td>219.900</td>
            <td>12</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td> Diseño moderno y elegante que combina perfecto con los demás muebles del hogar. ¡Anímate y cómpralo ya!</td>
            <td>Ref</td>
            <td colspan="2">Ceniza</td>
        </tr>
        <tr>
            <td rowspan="3">009</td>
            <td rowspan="3">Armario INVAL Granada 200 cm</td>
            <td rowspan="2">Armario INVAL es un closet de 200 cm con ocho puertas abatibles, dos tubos colgaderos metálicos, cuatro cajones y manijas metálicas. Ideal para organizar tu alcoba y almacenar toda tu ropa, zapatos y accesorios. Su estilo le brinda elegancia y modernidad a tu habitación. ¡Anímate y cómpralo ya!</td>
            <td>1.199.900</td>
            <td>333</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>Ref</td>
            <td colspan="2">Arena</td>
        </tr>
        <tr><td>Ideal para que organices todas tus prendas y pertenencias. Gran capacidad de almacenamiento. Diseño moderno sin manijas</td>
        </tr>
        <tr>
            <td rowspan="2">010</td>
            <td rowspan="2">Poltrona TUKASA Pekin Lona</td>
            <td>Complementa tus espacios con la silla Pekín TUKASA, especial para decorar tu hogar y un puesto adicional para tus visitas, su estructura está fabricada con madera pino seco reforestado, espuma de alta densidad y espuma penta gris lo cual genera estupendo confort, tapizada en tela eco cuero de fácil limpieza, y con terminado con puntos de costura en cuadros, patas metálicas cilíndricas de fácil armado, sin duda una silla hermosa, funcional y decorativa.</td>
            <td>399.900 </td>
            <td>17</td>
            <td>23/05/12</td>
        </tr>
        <tr>
            <td>¡Pídela en línea y déjanos inspirarte con una sala de ensueño!</td>
            <td>Ref</td>
            <td colspan="2">Petroleo</td>
        </tr>   
    </tbody>
</table>
```