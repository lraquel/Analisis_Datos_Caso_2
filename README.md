# Análisis de Ventas de una tienda de ropa 📊
# Introducción

Uno de nuestro clientes es una tienda de ropa que desea que analicemos sus datos de ventas. Nosotros analizaremos sus datos y dejaremos todo preparado para futuros análisis porque estamos seguros de que nos seguirán contratando en meses venideros.     

# Problema a resolver 📅

En concreto, nos piden lo siguiente:
1.- Calcula y muestra el total facturado por las ventas realizadas

2.- Crea un diccionario que contenga la cantidad de productos vendidos por cada tipo de producto.

3.- Muestra el tipo de producto con mayor cantidad de ventas y el tipo de producto con menor cantidad de ventas.

4.- Muestra el total de ventas realizadas por cada mes del período de tiempo representado por los datos.

5.- Transforma el cálculo de ventas por mes en una función que podamos reutilizar cuando lleguen los nuevos datos de Abril y Mayo.

# Descripción de Datos

Los datos vienen en forma de una lista de diccionarios, donde cada diccionario represente una venta y tenga las siguientes claves:

- 'fecha': fecha de la venta en formato 'YYYY-MM-DD'.
- 'producto': nombre del producto vendido.
- 'precio': precio del producto vendido.
- 'cantidad': cantidad de productos vendidos.
- 'total': total de la venta (precio x cantidad).

# Práctica

### 0. Toma de datos:

- Copia y pega el contenido del archivo Datos_Ventas_Caso_Uso_Modulo_2.txt
- Cárgalo en una variable

### 1. Calcula y muestra el total facturado por las ventas realizadas

- Explora y entiende los datos
- Realiza un bucle que nos recorra las ventas y vaya sumando los totales

### 2. Crea un diccionario que contenga la cantidad de productos vendidos por cada tipo de producto.

- Crea un bucle que cree un diccionario y que sea capaz de discriminar, en cada vuelta, lo que debe hacer con los nuevos datos en función de si están o no en el diccionario.

### 3. Muestra el tipo de producto con mayor cantidad de ventas y el tipo de producto con menor cantidad de ventas.

- Crea un bucle capaz de calcular lo que se pide.
- Para ello necesitarás discriminar si el dato que llega es mayor o menor que el anterior.

### 4. Muestra el total de ventas realizadas por cada mes del período de tiempo representado por los datos.

- Realiza el sumatorio de los totales de ventas discriminando por el mes de la fecha de compra.
- Para ello deberás tener en cuenta que debes extraer el mes de la fecha.

### 5. Transforma el cálculo de ventas por mes en una función que podamos reutilizar cuando lleguen los nuevos datos de Abril y Mayo.

- Transforma lo anterior en una función capaz de tomar datos en el formato de lista de diccionarios.
- Añade a la función control de excepciones.
