<!-- No borrar o modificar -->
[Inicio](./index.md)


# ACTIVIDAD 4 TABLAS


 rear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

![TABLA] (tabla.jpeg)

### SOLUCIÓN 

``` HTML COPY
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TABLAS</title>
</head>
<body>
    <header>
        <h1>TABLAS EJERCICIO 4</h1>
    </header>
    <main>
        <table border="1">
            <thead>
              <tr>
                <th>codigo</th>
                <th>nombre</th>
                <th colspan="3">descripcion</th>
                <th>precio</th>
                <th>stock</th>
                <th>fecha de creacion</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td rowspan="2">001</td>
                <td rowspan="2">rubor</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae mollitia quae soluta perferendis, modi repellendus quibusdam laborum veniam vel perspiciatis itaque nesciunt. </td>
                <td>20.000 cop</td>
                <td>100</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>30.000 cop</td>
                <td>200</td>
              </tr>
              <tr>
                <td rowspan="2">002</td>
                <td rowspan="2">agua micelar de rosas</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae mollitia quae soluta perferendis, modi repellendus quibusdam laborum veniam vel perspiciatis itaque nesciunt. </td>
                <td>35.000 cop</td>
                <td>45</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>40.000 cop</td>
              </tr>
              <tr>
                <td rowspan="2">003</td>
                <td rowspan="2">brochas de maquillaje</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae mollitia quae soluta perferendis, modi repellendus quibusdam laborum veniam vel perspiciatis itaque nesciunt. </td>
                <td>15.000 cop</td>
                <td>500</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>20.000</td>
                <td>200</td>
              </tr>
              <tr>
                <td rowspan="2">004</td>
                <td rowspan="2">locion</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae mollitia quae soluta perferendis, modi repellendus quibusdam laborum veniam vel perspiciatis itaque nesciunt. </td>
                <td>45.000 cop</td>
                <td>10</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>30.000 cop</td>
                <td>100</td>
              </tr>
              
              <tr>
                <td rowspan="2">005</td>
                <td rowspan="2">crema</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae. </td>
                <td>60.000 cop</td>
                <td>40</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>30.000 cop</td>
                <td>100</td>
              </tr>
              <tr>
                <td rowspan="2">006</td>
                <td rowspan="2">bloqueador solar</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit maxime recusandae mollitia quae soluta perferendis </td>
                <td>45.000 cop</td>
                <td>30</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>30.000 cop</td>
                <td>10</td>
              </tr>

              <tr>
                <td rowspan="2">007</td>
                <td rowspan="2">labiales</td>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi reprehenderit. </td>
                <td>7.000 cop</td>
                <td>200</td>
                <td>12-12-2023</td>
              </tr>
              <tr>
                <td colspan="3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quos id, labore dicta voluptatum magnam dolore commodi. Debitis provident tempore repellendus id rem in optio.</td>
                <td>9.000 cop</td>
                <td>250</td>
              </tr>
            </tbody>
          </table>
    </main>
</body>
</html>
```





