<!-- No borrar o modificar -->
[Inicio](./index.md)

# ACTIVIDAD 5

Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
- Utilizar las etiquetas HTML apropiados para cada campo.

### SOLUCIÓN 

``` HTML COPY
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORMULARIOS ANDREA VARGAS</title>
</head>

<body>
    <form action="">
        <h1>REALIZA TU COMPRA</h1>
        <div>
            <label for="idProducto">SELECCIONA EL PRODUCTO</label>
            <input type="text" id="idProducto">
        </div>
        <br>
        <div>
            <label for="idCantidad">Cantidad</label>
            <select name="cantidad" id="idCantidad">
                <option value="1">1</option>
                <option value="2">2</option>
            </select>
        </div>
        <br>
        <div>
            <label for="idPrecioUnitario">Valor de cada unidad</label>
            <input type="number" id="idPrecioUnitario" value="400000">
        </div>
        <br>
        <div>
            <label for="idPrecioTotal">Total a cancelar</label>
            <input type="number" id="idPrecioTotal" value="800000" minlength="400000">
        </div>
        <br>
        <div>
            <h2>detalles de envío</h2>
            <label for="idDireccion">ingrese su direccion</label>
            <input type="text" id="idDireccion" required>
        </div>
        <br>
        <br>
        <div>
            <h2>INFORMACION DE CONTACTO</h2>
            <label for="idNombre">Nombre completo</label>
            <input type="text" id="idNombre" required>

            <label for="idEmail">Ingrese su correo</label>
            <input type="email" id="idEmail" required>

            <label for="idNumCelular">Numero de contacto</label>
            <input type="text" id="idNumCelular">
        </div>
        <div>
            <h2>METODO DE PAGO</h2>
            <select name="metodoDePago" id="">
                <option value="1" selected>pse</option>
                <option value="2">efecty</option>
                <option value="1">banco</option>
            </select>

            <h2>fecha de entrega del producto</h2>
            <input type="date" name="fecha">
            <label for="fecha">FECHA DE ENTREGA DEL PRODUCTO</label>

            <h2>descripción para la entrega del producto en su domicilio</h2>
            <textarea name="comentarios" id="comentarios" placeholder="descripciones para la entrega del producto" rows="10" cols="50"></textarea>

        </div>

    </form>
</body>

</html>
```