<!-- No borrar o modificar -->
[Inicio](./index.md)

# ACTIVIDAD 3 

Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
Utiliza encabezados para títulos en cada elemento 

``` HTML
(<h1>...<h6>).
```


Crea una descripción para cada elemento utilizando párrafos  

```html 
(<p>). 
    
```

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:


``` html
- Usa <strong> para resaltar texto importante.
- Utiliza <br> para insertar saltos de línea si es necesario.
- Agrega <span> para aplicar estilos específicos a porciones de texto.
- Emplea <i> para enfatizar o dar énfasis a palabras o frases.
- Utiliza <u> para subrayar texto cuando sea necesario.
- Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.
```

### SOLUCIÓN 

``` HTML
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: sans-serif;
        }

        header {
            background-color: #3a086a;
            color: rgb(141, 100, 100);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: black;
        }

        footer {
            background-color: rgb(141, 100, 100);
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>IMÁGENES</h2>
        <p>GALERIA</p>

        <h3>imagenes locales</h3>

        <div>
            <h3>DIA</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <strong>Quisquam dignissimos saepe delectus
                    quae</strong> aliquam nisi voluptatibus voluptatum sint! Inventore totam consequatur veritatis
                ullam. Sapiente
                exercitationem eaque quisquam labore eveniet. Eveniet!</p>
            <img src="imagenes/dia.jpg" width="300">
        </div>
        <br>
        <br>

        <div>
            <h3>NOCHE</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis optio doloribus pariatur, repudiandae
                officia at doloremque minus nemo aliquam quis! Incidunt voluptatem.</p>
            <img src="imagenes/noche.jpg" alt="noche" width="300">
        </div>
        <br>
        <br>
        <br>
        <div>
            <h3>VERANO</h3>
            <p>Lorem ipsum dolor sit amet consectetur <b>adipisicing</b> elit. Voluptates laboriosam maiores hic dolorem
                praesentium corporis quidem.</p>
            <img src="https://media.istockphoto.com/id/1396453626/es/foto/cintur%C3%B3n-inflable-de-flamenco-rosa-con-accesorios-de-verano-sobre-fondo-azul-turquesa.webp?b=1&s=170667a&w=0&k=20&c=JLmgaeCGr0PzjuUQVIqlNZAhey2Mz15CTQ0EgFwkK1I="
                alt="verano" width="300">
        </div>
        <br>
        <br>
        <br>
        <div>
            <h3>INVIERNO</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Placeat quod numquam velit ut esse. Corporis,
                velit</p>
            <img src="https://media.istockphoto.com/id/1370726577/es/foto/magias-de-invierno.webp?b=1&s=170667a&w=0&k=20&c=dB9eBspsCQGIlvU6Z_J22lmFBR4dv6TCillNN1lup2Y="
                alt="invierno" width="300">
        </div>

    </section>

    <section>

        <div>
            <h2>VIDEOS</h2>
            <p>galeria de <i>videos</i></p>
        </div>

        <div>
            <h3>lluvia</h3>
            <p>este video está almacenado <u>LOCALMENTE</u></p>
            <video src="videos/lluvia.mp4" controls width="400"></video>
        </div>
        <div>
            <h3>tranvía</h3>
            <p>este video está <u>EN LA NUBE</u></p>
            <video
                src="https://cdn.pixabay.com/vimeo/138678094/ciudad-730.mp4?width=480&hash=715acfcfa5df78beb89478c782b633090d0aaf5a"
                controls width="400"></video>
        </div>
    </section>

    <section>
        <div>
            <h2>SECCION DE <i>AUDIOS</i></h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quas inventore libero rerum quidem accusamus
                facere eaque repudiandae neque blanditiis. Vero non ipsa, molestiae distinctio aperiam sequi aliquid
                harum soluta accusamus. </p>

        </div>
        <div>
            <h3><span>NUMERO 1</span></h3>
            <p>este audio es <strong>INTENSO</strong></p>
            <audio src="audios/braam-subdown-intense-drop-with-distortion-and-reverb-162383.mp3" controls></audio>
        </div>
        <div>
            <h3><span>NUMERO 2</span></h3>
            <p>este audio es <strong>RELAJANTE</strong></p>
            <audio src="audios/calm-river-ambience-loop-125071.mp3" controls></audio>
        </div>

        <div>
            <h3><span>NUMERO 3</span></h3>
            <p>este audio es <strong>CINEMATOGRAFICO</strong></p>
            <audio src="audios/cinematic-music-sketches-11-cinematic-percussion-sketch-116186.mp3" controls></audio>
        </div>

        <div>
            <h3><span>NUMERO 4</span></h3>
            <p>este audio es para <strong>MEDITAR</strong></p>
            <audio src="audios/leap-motiv-113893.mp3" controls></audio>
        </div>

    </section>

    <section>
        <div>
            <h2>SECCION DE INLINE FRAME</h2>
            <p> Lorem ipsum, dolor sit <strong>consectetur adipisicing elit.</strong> Aperiam, sequi. Iure expedita
                assumenda vero, harum fuga explicabo aut soluta quod quo corpori.</p>
        </div>
        <div>
            <h3><I>IFRAME 1</I></h3>
            <iframe src="https://es.wikipedia.org/wiki/Wikipedia:Portada" frameborder="40"></iframe></h3>
            <p>este iframe es de wikipedia para poder navegar rapidamente!!</p>
        </div>
        <div>
            <h4><i>IFRAME 2</i></h4>
            <iframe src="https://economipedia.com/definiciones/empleado.html" frameborder="50"></iframe>
            <p>este es un iframe de una pagina de estudio economico para navegar facilmente.</p>
        </div>
    </section>

    <footer>
        Lady Andrea Vargas Clavijo
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





