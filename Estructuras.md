# Estructuras de datos

En ciencias de la computación, una estructura de datos es una forma particular de organizar datos en una computadora para que puedan ser utilizados 
de manera eficiente. Diferentes tipos de estructuras de datos son adecuados para diferentes tipos de aplicaciones y algunos son altamente especializados 
para tareas específicas. 

Las estructuras de datos son un medio para manejar grandes cantidades de datos de manera eficiente para usos tales como grandes bases de datos y servicios 
de indización de Internet. Por lo general, las estructuras de datos eficientes son clave para diseñar algoritmos eficientes. Algunos métodos formales de 
diseño y lenguajes de programación destacan las estructuras de datos, en lugar de los algoritmos, como el factor clave de organización en el diseño de software.

[Wikipedia](https://es.wikipedia.org/wiki/Estructura_de_datos)

Clasificación:

   Las estructuras de datos se clasifican en dos tipos: **INTERNAS Y EXTERNAS**
            
   En el ámbito de la Impresión de Data Variable se utilizan las **ESTRUCTURAS DE DATOS EXTERNA** las cuales son de 2 tipos:

      • Archivo o Fichero 
  
      • Base de datos
  
**Archivo o Fichero** 

  Un archivo o fichero es un sistema real o virtual de organización de datos mediante una clasificación y formato determinado. Se le
  llama asi a un conjunto de datos clasificados y almacenados de diversas formas para facilitar su persistencia y acceso en cualquier 
  momento mediante sistemas automatizados o software. Veamos algunos tipos:
     
  - **Ficheros Excel o Libros** 
        
     Están formados por *Hojas* en las cuales podemos organizar los datos en Filas y Columnas (tablas). 
     A cada hoja se le puede asignar un nombre espcifico. 

     Una hoja puede contener solo información de una entidad dada, ejemplo: Clientes, Productos, Estados, Cabeceras, Detalles, etc
     
     Personalmente recomiendo este formato.
     
     ![Fichero Excel](https://github.com/mmhgarcia/impresion_data_variable/blob/master/images/fichero_excel.jpg)
     
  - **Fichero TXT o Archivo Plano**
           
       Los archivos TXT sirven como almacenes de datos a la vez que evitan las complicaciones propias de otros formatos de archivo.
         
       La extensión TXT representa "textfile" (archivo de texto), que sustituyó a su antiguo nombre "flatfile" (archivo sin formato).

       Ejemplo de *Fichero TXT* con **CAMPOS DE LONGITUD FIJA** - NO LLEVA CABECERA
              
       ![Fichero TXT](https://github.com/mmhgarcia/impresion_data_variable/blob/master/images/fichero_txt.JPG)
      
       
  - **Fichero tipo CSV**
    
       Son archivos sin formatos especiales, son archivos planos.

       Las siglas CSV vienen del inglés **"Comma Separated Values"** y significan valores separados por comas. Dicho esto, un archivo CSV 
       es cualquier archivo de texto en el cual los datos están separados por **\, ; |** haciendo una especie de tabla en filas y columnas. 

       Las columnas quedan delimitadas por el caracter escogido mientras que cada fila se define mediante una línea adicional en el fichero. 
        
       Se pueden importar facilmente desde menejadores de bases de datos

       ![Fichero TXT](https://github.com/mmhgarcia/impresion_data_variable/blob/master/images/fichero_txt.JPG)

**Base de datos** 

   Para definirla aplica perfectamente la similitud con un *Libro de Excel*
   
      - Un Libro de Excel es un Contenedor de Hojas con Información
      - Una Base de datos es un Contenedor de Tablas con información

   Una base de datos es una colección de información organizada de forma que un software pueda seleccionar rápidamente los fragmentos de datos que 
   necesite. 
   
      Las bases de datos tradicionales o **RELACIONALES** se organizan en **TABLAS** 
      
      Las **TABLAS** están definidas por los **CAMPOS**
   
      Las **TABLAS son el Almacen de los DATOS**

   Existen distintos manejadores de bases de datos relacionales:
   
      - MySQL
      
      - POSTGRE
      
      - MS-SQL SERVER
      
      - SQLITE
      
   Veamos la siguiente relacion:
   
      BASE DE DATOS      
         TABLA 1         
            CAMPOS
         TABLA 2
            CAMPOS
         TABLA 3
            CAMPOS
            
         *Puede tener tantas tablas como requiera*
      
   Ahora apliquemos la definicion a un modelo ficticio:
   
   **BASE DE DATOS --> DEMO** (contenedor)  
      
   **PRODUCTO**  (tabla)
   - ID           (numerico y clave primaria)  
   - CODIGO       (sting)  
   - NOMBRE       (string)  
   - PRECIO       (numerico)    
   - EXISTENCIA   (numerico)          
      
   **CLIENTE**  (tabla)
   - ID  
   - CODIGO  
   - NOMBRE  
   - DIRECCION  
   - TELEFONO  
           
   **ESTADO**  (tabla)
   - ID  
   - CODIGO  
   - NOMBRE  

<hr />

Estos son los 02 elementos *FUNDAMENTALES* que se utilizan para el manejo de datos en ordenes de **Impresión de Data Variable**

Los **CLIENTES** generan **LA DATA** en *FICHEROS* para cuando van a ser enviados a **ENTIDADES EXTERNAS** para su manejo.

Eso es todo en lo referente a **ESTRUCTURAS DE DATOS**.
  
