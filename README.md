# Maybelline Cosmesticos

## Descripción
>Una empresa proveedora de cosmesticos para mujer, desea desarrollar su portal de productos, actualmente solo cuentan con el Endpoint que le devuelve los datos (Deben poder identificarse oportunidades de mejora en la data), desean que el programador que obtenga el trabajo pueda analizarlo y adaptar la información a una correcta interacción con el usuario. Son requeridas buenas prácticas de UI/UX y los colores deben reflejar los valores de la marca, los cuales son: Confianza y elegancia.

## Endpoint
> https://makeup-api.herokuapp.com/


## Fase 1: Prototipado y maquetación


### **Análisis de datos**

Los parámetros de búsqueda para los datos que se muestran en la documentación de la API se muestran en la siguiente imagen:

![search parameters](https://github.com/IntiDev/MaybelineCorp/blob/main/Images/API_Search_Parameters.png)

Al hacer un análisis de la estrucutra que tienen los datos y tomando en cuenta los parametrós de búsqueda se encontrarón 2 hallazgos importantes, para los parámetros de búsqueda **product_category** y **product_tags** en la estructura del JSON de datos se encuentran como **category** y **tag_list**, como se muestra en la siguiente imagen:

![data analysis](https://github.com/IntiDev/MaybelineCorp/blob/main/Images/API_data_analysis.png)

Una vez realizado el análisis anterior se leyeron los datos para establecer los parámetros principales que se tomarán en cuenta para realizar los prototipos de la UI.

Dentro de estos datos se encontraron que se cuenta con un total de:

- **10 tipos de producto**
- **16 categorias**
- **23 tipos de tags**
- **58 marcas**

Con esta información se clasificaron los tipos de productos en **5 categorías principales**:

- **Polvos**
- **Ojos**
- **Base**
- **Labios**
- **Uñas**

En la siguiente imagen se muestra la distribución de la clasificación de los tipos de producto:

![analysis data result](https://github.com/IntiDev/MaybelineCorp/blob/main/Images/API_analysis_result.png)

La clasificación anterior se hizo para obtener las categorías principales que se mostrarán en la página principal del sitio.

### **Prototipos**

**_Bajo nivel_**

Con el análisis de los datos se hicieron 5 prototipos de la UI que incluyen las siguientes vistas:

1.  [Home](https://github.com/IntiDev/MaybelineCorp/blob/main/Mockups/1.%20Home.jpeg) : vista principoal del sitio donde se muestra un carrusel con los 4 productos mejor calificados y las 5 categorías principales para navegar entre los tipos de producto.

2. [Filtros](https://github.com/IntiDev/MaybelineCorp/blob/main/Mockups/2.%20Filtros.jpeg) : en esta vista se muestran todos los productos relacionados con la categoría seleccionada con una pequeña descripción, además de una barra de búsqueda y un filtro por precio y rating.

3. [Producto](https://github.com/IntiDev/MaybelineCorp/blob/main/Mockups/3.Producto.jpeg) : para esta vista se muestra el producto seleccionado a detalle, con su imagen, nombre, precio, marca y descripción. En esta vista el usuario puede seleccionar la cantidad de producto que quiere comprar y agregarlo a su bolsa.

4. [Carrito de compra](https://github.com/IntiDev/MaybelineCorp/blob/main/Mockups/4.Carrito.jpeg) : aquí se muestra el despligue a detalle de la compra como, número de productos, descripción del producto, precio por unidad, cantidad por unidad, subtotal y total.

**Nota:** en cada pantalla se muestra un header con el logo y link al carrito de compra, una barra de navegación con las 5 categorías principales y un footer con texto y links a las redes sociales de la empresa.

