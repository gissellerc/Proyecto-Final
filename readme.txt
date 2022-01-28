>----- Universidad Nacional Autónoma de México -----<
>----- Facultad de Ciencias -----<
>----- Manejo de Datos -----<
>----- Proyecto Final -----

----- Hecho por: -----
>-Hernández Sánchez María José
>-Quiñones Ramírez Marlene Casandra
>-Ramirez Coria Sandra Gisselle
>-Torres Nuñez Diego

----- Explicación del proyecto -----
Nos basamos en el tema de ropa, por lo que las tiendas que decidimos usar para esta gran proyecto fueron Calvin Klein, H&M, Julio, Zara y Forever 21, ya que consideramos que son marcas que se han logrado posicionar como las mejores en el mercado. Además, los productos con los cuales decidimos desarrollar nuestra base de datos, que también estará almacenada en un archivo de tipo .xlsx, fueron blusas, chamarras, jeans de mezclilla, tacones y zapatos.

----- Instrucciones para ejecutar el proyecto -----
Es un archivo elaborado en Jupyter Notebook, realizamos 5 web scrapers (en el código real sólo se utilizan 3) y a través de Chromedriver extrajimos lo más importante de estas tiendas de ropa como los productos con sus costos, su costo con descuento, si existe, y por supuesto el link para adquirir dicha prenda. Por lo que, si se desea ejecutar el archivo de preferencia realizarlo en Jupyter Notebook o en su defecto en Google Colab, ahí abriremos el archivo con nombre “Web Scraper proyecto final final.ipynb” y dentro de él vienen bastantes partes del código, cada una de ellas con sus pertinentes comentarios. Antes de comenzar a ejecutarlo, es necesario verificar que las librerías que se requieren están instaladas en sus computadoras (específicamente para las dos librerías que se encuentran al principio del código), después de esto, podemos proseguir con la ejecución. En el trabajo encontraremos distintas secciones:
-En la parte 0 del archivo, podemos encontrar una función que nos ayudará a convertir las columnas de nuestra base de datos de tipo str a numeric.
-Para el 1 y 2 Encontraremos todas las funciones correspondientes a los web scrapers.
-En el número 3 se puede decir que nos sirve como MAIN del proyecto, ya que ahí se realiza la ejecución de todas las funciones creadas en las secciones anteriores, además de que nos realiza el archivo en el que se guardará la base de datos, el cual se podrá consultar al termino de esta ejecución, pues quedará almacenado en la carpeta de archivos desde donde usted esté consultando este proyecto.
-Para las consultas, fragmento 4, decidimos llevar a cabo aquellas que tengan que ver con los promedios de precios originales y con descuento entre productos, tiendas, etc. Puesto que ellos fueron las que nos parecieron más interesantes para así tomar la decisión más sabia al momento de realizar una compra de ropa.
-El último apartado, las gráficas, nos muestra 4 tipos de gráficas distintas en las que se puede apreciar la diferencia de precios y productos entre cada marca de ropa.
Para comenzar a ejecutar sólo es necesario correr las partes de código que así lo digan, explícitamente con el siguiente comentario de código: “#### --- Este código se debe ejecutar para obtener las consultas y las gráficas ---“.
Realizando todo esto, podemos notar en los sitios 4 y 5 todas las comparaciones entre marcas y productos para así saber en que tienda será mejor comprar los 5 productos elegidos. Además, tendremos nuestro archivo con la base de datos creada.
