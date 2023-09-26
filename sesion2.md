<!-- No borrar o modificar -->
[Inicio](./index.md)


# ACTIVIDAD 2: MI PRIMER SITIO WEB


Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

## INDEX.HTML

```HTML
<!DOCTYPE html>
 <html>
    <head>
        <title>MI PRIMER PROYECTO</title>

    </head>
    <body>
        <header>
            <nav>
                <Ul>
                    <li><a href="index.html">INICIO</a></li>
                    <li><a href="tecnica.html">TECNICA</a></li>
                    <li><a href="contacto.html">CONTACTO</a></li>
                </Ul>
            </nav>
        </header>
        <main>
            <h1>BIENVENIDOS MI BLOG</h1>
            <P>por: ANDREA VARGAS</P>
        
        <section>
            <h2>QUIEN SOY?</h2>
            <p>Me llamo Lady Andrea Vargas, mi primer nombre no me gusta, tengo 24 años, vivo en el doce de octubre, mis hobby es leer, programar, ver series y observar la naturaleza, actualmente trabajo para una compañia de cobranzas</p>
            <article>
                <h2>MIS PROYECTOS</h2>
                <P>Mi proyecto mas importante es ejercer como programadora, es un sueño al cual no estoy dispuesta a renunciar, tengo una meta conmigo misma para obtener mi casa propia, entre otros proyectos tengo visualizado algunos viajes de los cuales pueda disfrutar de su naturaleza, seguir aprendiendo cada dia mas de programación y otros temas.</P>
            </article>
        </section>
        </main>
        <footer>
            <p>Cpyrigth 2023 - LandreaV</p>
            <a href="https://www.instagram.com/andreavargas02c/">INSTAGRAM</a>
            <a href="https://web.facebook.com/profile.php?id=100015788945269">FACEBOOK</a>
        </footer>
    </body>
 </html>
```

about.html
``` HTML
<!DOCTYPE html>
 <html>
    <head>
        <title>TECNICA</title>

    </head>
    <body>
        <header>
            <nav>
                <ol>
                    <li><a href="index.html">INICIO</a></li>
                    <li><a href="tecnica.html">TECNICA</a></li>
                    <li><a href="contacto.html">CONTACTO</a></li>
                </ol>
            </nav>
        </header>
        <main>
        <section> 
            <h2>DESARROLLO DE SOFTWARE</h2>

            <h3>¿Qué es el desarrollo de un software?</h3>

            <p>El desarrollo de software se refiere a un conjunto de actividades informáticas dedicadas al proceso de creación, diseño, despliegue y compatibilidad de software. El software en sí es el conjunto de instrucciones o programas que le dicen a una computadora qué hacer.</p>
        </section>
        <section>
            <h3>OBTIENE EL CURSO HOY AQUI</h3>
            <p>suscribete para obtener mas informacion sobre el curso, dejanos tus datos para ponernos en contacto.</p>
        </section>
            
        </main>

        <footer>
            <p>Cpyrigth 2023 - LandreaV</p>
            <a href="https://www.instagram.com/andreavargas02c/">INSTAGRAM</a>
            <a href="https://web.facebook.com/profile.php?id=100015788945269">FACEBOOK</a>
        </footer>
    </body>
 </html>
```

contact.html

``` HTML 
<!DOCTYPE html>
<html>

<head>
    <title>CONTACTO</title>

</head>

<body>
    <header>
        <nav>
            <ol>
                <li><a href="index.html">INICIO</a></li>
                <li><a href="tecnica.html">TECNICA</a></li>
                <li><a href="contacto.html">CONTACTO</a></li>
            </ol>
        </nav>
    </header>
    <main>
        <form>
            <label for="nombre">Nombre</label>
            <input type="text" id="nombre"><br>

            <label for="email">E-mail</label>
            <input type="email" id="email"><br>

            <label for="mensaje">Mensaje</label>
            <textarea id="mensaje">escribe tu comentario</textarea>

            <input type="submit" value="ENVIAR">
        </form>
     </main>

     <footer>
        <p>Cpyrigth 2023 - LandreaV</p>
        <a href="https://www.instagram.com/andreavargas02c/">INSTAGRAM</a>
        <a href="https://web.facebook.com/profile.php?id=100015788945269">FACEBOOK</a>
    </footer>
</body>

</html>








