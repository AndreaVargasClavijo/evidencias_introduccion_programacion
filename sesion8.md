<!-- No borrar o modificar -->
[Inicio](./index.md)

# ACTIVIDAD 8

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>


Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>


Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"


Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"


Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un <div>
Centrar el contenido de la sección <section>

### SOLUCION

INDEX

``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIND GO</title>
    <link rel="stylesheet" href="style.css">

    <style>
        .grande {
            font-size: 40px;
            color: red;
            text-align: end;
            margin: 15px;
        }
        .destacado {
            background-image: linear-gradient(to bottom, #fff, #696565);
        }
        .footer1{
            background-color: #dfdede;
            padding-top: 0%;
        }

    </style>

</head>

<body>
    <header>
        <nav>
            <h1 class="grande">FIND GO</h1>
            <p id="link1"><a href="navegar.com">COMIENZA A NAVEGAR</a></p>
            <p id="link2"><a href="login administrador">LOGIN</a></a></p>
        </nav>
    </header>

    <div class="texto1">
        <h2
            style="color: red;  text-align: center; font-size: 20px; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
            NAVEGA EN INTERIORES DE CENTROS COMERCIALES
        </h2>

        <div id="identificador1">
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus obcaecati, eligendi laudantium modi
                deleniti illo? Necessitatibus sequi soluta est similique, numquam voluptate facere nobis deleniti ut, vero
                unde placeat vitae.</p>
        </div>
     
    </div>

    <div>
        <p id="texto2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex, minima. Dolorem asperiores, minus aliquam ipsam
            magni quas vitae quidem reprehenderit id eaque repellat pariatur sunt officiis consectetur, commodi tenetur
            iste! Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veritatis ad repellat accusantium rem? Vel
            voluptate explicabo corporis possimus, sed consequuntur rem quia aperiam atque, excepturi neque hic,
            provident quaerat voluptates.</p>
    </div>
    <div class="destacado">
        <p
            style="color: blue; text-align: center; border: solid 3px #ee82ee; padding: 20px; width: 700px; display: block; margin: 0 auto;">
            con nuestro sistema revolucionario puedes navegar dentro de un centro comercial con mas confianza,
            disfrutando de un confort que se siente desde que ingresas a la plataforma web, aprovechando descuentos
            imperdibles de tus marcas favoritas.
        </p>

        <div style="padding: 20px;">
            <img style="border: solid 10px #000; font-size: 50px; width: 600px; display: block; margin: 0 auto;"
                src="https://firebasestorage.googleapis.com/v0/b/cesde1-6ed08.appspot.com/o/CC.jpg?alt=media&token=257c6f4c-a851-49f6-9bf7-bc6d62a16cfd" alt="centro comercial-interior">
        </div>
    </div>


    <footer class="footer1">
        <p> <a href="contacto.com">comuniquese con nosotros</a></p>
        <p><a href="facebook.com">visitanos en facebook</a></p>
        <p>Copyrigth</p>
    </footer>




</body>

</html>
```

CSS

``` CSS
#identificador1, p {
    color: violet;
}

#texto2 {
    color: red;
}


#link1 a{
    text-decoration: none;
}

#link2 a{
    text-decoration: none;
}


#link1, #link2 {
    text-align:left;
    margin: 10px;
    font-size: 16px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
```




