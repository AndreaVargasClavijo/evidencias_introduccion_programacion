<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

### ESPACIADOS

```HTML

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
</body>

</html>

<!-- 
¿que es margin?

R: La propiedad CSS margin establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top (en-US), margin-right , margin-bottom y margin-left (en-US). También se permiten valores negativos.

¿que es padding?

R: El padding en CSS es una propiedad o relleno que se crea alrededor del contenido de un elemento dentro de los bordes definidos y sirve para dar formato y diseño a una página web.

¿que es border?

R: Resumen. La propiedad border permite definir en una única regla todos los bordes de los elementos seleccionados. Se puede utilizar border para definir el o los valores siguientes: border-width , border-style , border-color .

¿que es border radius? 

R: La propiedad CSS border-top-left-radius establece el redondeo de la esquina superior izquierda del elemento. El redondeo puede ser un círculo o una elipse, o si uno de los valores es 0 , no se redondeará la esquina, dejándola cuadrada.

¿cuales medidas de css se pueden utilizar para espaciado?

R: rem, % y px


 -->
```

```CSS
.contenedor {
    background-color: beige;
    width: 200px;
    height: 200px;
  }
  
  .elemento {
    border-radius: 10px;
    border: 5px solid red;
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }

  .contenedor1 {
    background-color: antiquewhite;
    width: 200px;
    height: 200px;
  }
  
  .elemento1 {
    border-radius: 10px;
    border: 5px solid red;
    padding: 50%;
    margin: 50%;
    width: 100px;
    height: 100px;
  }
```



