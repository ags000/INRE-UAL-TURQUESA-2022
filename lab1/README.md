
# ***Lab 1: Definición de casos de uso y requisitos de información***

$~$

## ***Índice de contenidos***

- Supuesto 1: Horarios
- Supuesto 2: Sistema de Compras

$~$

### **Supuesto 1: Horarios**

<br>

<div align="justify">
En una universidad, el personal del PDI, el personal del PAS y los estudiantes pueden consultar horarios. Por su parte, el personal del PAS puede modificar horarios y dar de alta estudiantes. El personal de PDI puede proponer cambios en los horarios y dar de alta estudiantes. La funcionalidad de dar de alta estudiantes del PAS realiza una verificación de los datos del estudiante. Sin embargo, la funcionalidad de dar de alta estudiantes del PDI, además de verificar los datos también permite de forma excepcional realizar la búsqueda en las listas de clase de sus asignaturas.
</div">

<br>

#### **Especificación de los Actores**

<br>

| IR 01                         | Estudiante                     |
| :---                          | :---                          |
| Versión                       | 2.0 (08/10/2022)               |
| Autores                       | Alejandro Manzano             |
| Fuentes                       |                               |
| Referencias                   | - Consultar horarios, UC-01.   |
| Descripción                   | El Estudiante deberá estar dado de alta en el sistema. |
| Datos específicos             |                               |
| Importancia                   | Muy importante.               |
| Estado                        | Aceptado.                     |
| Comentarios                   |                               |

$~$

| IR 02                         | PDI                            |
| :---                          | :---                          |
| Versión                       | 1.0 (08/10/2022)               |
| Autores                       | Cristina García               |
| Fuentes                       |                               |
| Referencias                   | - Proponer cambio de horario, UC-02.  <br> - Dar de alta estudiante vista PDI, UC-07.  <br> - Buscar listas de clase, UC-04.  <br> |
| Descripción                   | El sistema deberá permitir al PDI proponer cambios en el horario y dar de alta a estudiantes. |
| Datos específicos             |                                |
| Importancia                   | Muy importante.                |
| Estado                        | Aceptado.                      |
| Comentarios                   |                                |

$~$

| IR 03                         | PAS                            |
| :---                          | :---                          |
| Versión                       | 1.0 (08/10/2022)               |
| Autores                       | Cristina García               |
| Fuentes                       |                               |
| Referencias                   | - Modificar horario, UC-06. <br> - Dar de alta estudiante, UC-03.  <br> - Verificar datos estudiante, Uc-05. <br> |
| Descripción                   | El sistema deberá permitir al PAS modificar los horarios y dar de alta a los estudiantes. |
| Datos específicos             |                                |
| Importancia                   | Muy importante.                |
| Estado                        | Aceptado.                      |
| Comentarios                   |                                |

$~$

#### **Especificación de los Casos de Uso**

<br>

| Identificador                 | UC-01                         |
| :---                          |    :----                      |
| Nombre                        | Consultar horarios            |
| Autor                         | Alejandro Manzano             |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite al usuario ver el horario que le corresponde.       |
| Actores                       | Estudiante                    |
| Precondiciones                | El Estudiante está autenticado en el sistema.       |
| Flujo normal                  | 	1.- El Estudiante selecciona la opción de la aplicación para ver el horario. <br> 2.- El sistema busca el correspondiente horario del Estudiante y se lo muestra.        |
| Flujo alternativo             | 2A.- Si el sistema no encuentra el horario del Estudiante devolverá un mensaje de error.                       |
| Poscondiciones                | Ninguna.                      |

$~$

| Identificador                 | UC-02                         |
| :---                          |    :----                      |
| Nombre                        | Proponer cambio de horario    |
| Autor                         | Cristina García               |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite proponer un cambio en el horario.       |
| Actores                       | PDI        |
| Precondiciones                | El PDI está autenticado en el sistema.       |
| Flujo normal                  | 	1.- El PDI solicita abrir un ticket. <br> 2.- El sistema pide la introducción del asunto y cuerpo del mensaje. <br> 3.- El PDI rellena los datos. <br> 4.- El estudiante envía el ticket.       |
| Flujo alternativo             | 4.A.- El sistema comprueba que los campos hayan sido rellenados. Si no lo son, PDI podrá volver a introducir los datos (paso 3) finalizar el proceso.        |
| Poscondiciones                | Ninguna.        |

$~$

| Identificador                 | UC-03                         |
| :---                          |    :----                      |
| Nombre                        | Dar de alta estudiante        |
| Autor                         | Cristina García               |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite dar de alta a un determinado Estudiante.       |
| Actores                       | PAS                           |
| Precondiciones                | PAS debe estar auntenticado en el sistema.       |
| Flujo normal                  | 1.- PAS solicita dar de alta al Estudiante. <br> 2.- El sistema solicita los datos del Estudiante. <br> 3.- PAS introduce los datos del Estudiante. <br> 4.- El sistema verifica los datos del Estudiante.      |
| Flujo alternativo             | 4.A.- El sistema comprueba que los datos del Estudiante sean correctos. Si no lo son, PAS podrá volver a introducir los datos del Estudiante (paso 3) o finalizar el proceso.                       |
| Poscondiciones                | El Estudiante está dado de alta.                      |

$~$

| Identificador                 | UC-04                         |
| :---                          |    :----                      |
| Nombre                        | Buscar listas de clase        |
| Autor                         | Cristina García               |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite buscar al Estudiante en las listas de clase.       |
| Actores                       | PDI                           |
| Precondiciones                | PDI debe estar auntenticado en el sistema.       |
| Flujo normal                  | 1.- PDI solicita buscar al Estudiante en las listas de clase. <br> 2.- El sistema solicita los datos de la clase del Estudiante al que se va a dar de alta. <br> 3.- PDI introduce los datos de la clase. <br> 4.- El sistema verifica los datos. <br> 5.- El sistema muestra la lista de la clase.      |
| Flujo alternativo             | 4.A.- El sistema comprueba que los datos de la clase sean correctos. Si no lo son, PDI podrá volver a introducir los datos (paso 2) o finalizar el proceso.                    |
| Poscondiciones                | Ninguna.                      |

$~$

| Identificador                 | UC-05                         |
| :---                          |    :----                      |
| Nombre                        | Verificar datos estudiantes        |
| Autor                         | Cristina García               |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite verificar los datos del estudiantes.       |
| Actores                       | PAS                           |
| Precondiciones                | PAS debe estar auntenticado en el sistema.       |
| Flujo normal                  | 1.- PAS introduce los datos del Estudiante a dar de alta. <br> 2.- El sistema verifica los datos del Estudiante.                 |
| Flujo alternativo             | 2.A.- El sistema comprueba que los datos del Estudiante sean correctos. Si no lo son, PAS podrá volver a introducir los datos (paso 1) finalizar el proceso.          |
| Poscondiciones                | Ninguna.                      |

$~$

| Identificador                 | UC-06                         |
| :---                          |    :----                      |
| Nombre                        | Modificar horario             |
| Autor                         | Cristina García               |
| Fecha                         | 07/10/2022                    |
| Descripción                   | Permite modificar el horario. |
| Actores                       | PAS                           |
| Precondiciones                | PAS debe estar auntenticado en el sistema.       |
| Flujo normal                  | 1.- PAS hace uso de la herramienta que tiene el sistema para modificar el horario. <br> 2.- PAS guarda los cambios realizados. <br> 3.- El sistema actualiza los horarios modificados.                 |
| Flujo alternativo             | 2.A.- El sistema no guarda los cambios realizados debido a que PAS cierra el programa sin guardar.            |
| Poscondiciones                | Los cambios en el horario han sido actualizados.                      |

$~$

| Identificador                 | UC-07                         |
| :---                          |    :----                      |
| Nombre                        | Dar de alta estudiante vista PDI        |
| Autor                         | Cristina García               |
| Fecha                         | 08/10/2022                    |
| Descripción                   | Permite a PDI dar de alta a un estudiante determinado.       |
| Actores                       | PID                           |
| Precondiciones                | PID debe estar auntenticado en el sistema.       |
| Flujo normal                  | 1.- PID solicita dar de alta al Estudiante. <br> 2.- El sistema solicita los datos del Estudiante. <br> 3.- PID introduce los datos del Estudiante. <br> 4.- El sistema verifica los datos del Estudiante.               |
| Flujo alternativo				| 4.A.- El sistema comprueba que los datos del Estudiante sean correctos. Si no lo son, PID podrá volver a introducir los datos del Estudiante (paso 3) o finalizar el proceso. <br> 4.B.- El sistema, de forma excepcional, busca las listas de clase de las asignaturas del Estudiante.   |
| Poscondiciones                | El Estudiante está dado de alta.                      |

$~$

### **Supuesto 2: Sistema de Compras**

<br>

<div align="justify">
En un sistema de compra, existen cuatro tipos de usuarios: comprador, vendedor, proveedor y administrador. Los compradores pueden agregar productos, consultar precios, finalizar la compra y consultar ofertas. Agregar productos implica marcar esos productos como bloqueados. Los vendedores también pueden consultar ofertas y consultar precios. Los proveedores pueden consultar precios, avisar de nuevos productos y consultar ofertas. Avisar de nuevos productos, de forma excepcional, realiza la incorporación de una oferta. Los proveedores también tienen una funcionalidad para avisar del fin de una oferta. Cuando se avisa del fin de una oferta, se ejecuta la funcionalidad de eliminar la oferta. Ambas funcionalidades de avisar del proveedor tienen en común que se encarga de enviar una notificación. Los administradores pueden consultar precios, consultar ofertas y eliminar productos. La funcionalidad de consultar precios incluye una funcionalidad de buscar productos que es similar a la funcionalidad de consultar productos de los compradores. Sin embargo, la funcionalidad de consultar productos añade una funcionalidad para verificar la disponibilidad. Para realizar una venta, un comprador y un vendedor participan de forma conjunta. En dicha operación, se lleva a cabo el acuerdo de un precio; excepcionalmente, durante la realización de la venta, se consultará el histórico de ventas.
</div">

<br>

#### **Especificación de los Actores**

<br>

$~$

#### **Especificación de los Casos de Uso**

<br>

| Identificador                 | UC-01                         |
| :---                          | :----                         |
| Nombre                        | Consultar ofertas             |
| Autor                         | Cristina García               |
| Fecha                         | 09/10/2022                    |
| Descripción                   | Permite consultar las ofertas.       |
| Actores                       | Comun, Proveedor, Vendedor, Comprador y Administrador                           |
| Precondiciones                | El usuario debe haber accedido al sistema de compra.       |
| Flujo normal                  | 1.- El usuario solicita entrar en la oferta deseada. <br> 2.- El sistema muestra la oferta escogida.             |
| Flujo alternativo             | 2.A.- Si el sistema no encuentra la oferta deseada devolverá un mensaje de error.     |
| Poscondiciones                | Ninguna.                      |

 <br>


| Identificador                 | UC-02                         |
| :---                          | :----                         |
| Nombre                        | Consultar precios             |
| Autor                         | Cristina García               |
| Fecha                         | 09/10/2022                    |
| Descripción                   | Permite consultar los precios.       |
| Actores                       | Comun, Proveedor, Vendedor, Comprador y Administrador                           |
| Precondiciones                | El usuario debe haber accedido al sistema de compra.       |
| Flujo normal                  | 1.- El usuario solicita ver el precio deseado. <br> 2.- El sistema busca los productos que entren en el rango de dicho precio <br> 3.- El sistema muestra la consulta del precio.             |
| Flujo alternativo             | 2.A.- Si el sistema no localiza ningún producto por el precio deseado, devolverá un mensaje de error.     |
| Poscondiciones                | Ninguna.                      |

 <br>

| Identificador                 | UC-03                         |
| :---                          | :----                         |
| Nombre                        | Finalizar compra              |
| Autor                         | Cristina García               |
| Fecha                         | 09/10/2022                    |
| Descripción                   | Permite que el Comprador finalice la compra.       |
| Actores                       | Comprador          |
| Precondiciones                | El Comprador debe haber accedido al sistema de compra.       |
| Flujo normal                  | 1.- El Comprador solicita finalizar la compra de los productos escogidos previamente. <br> 2.- El sistema solicita los datos del Comprador para poder realizar la compra. <br> 4.- El Comprador introduce todos los datos pertinentes. <br> 3.- El sistema comprueba que todos los datos hayan sido introducidos. <br> 4.- El sistema finaliza la compra. <br> 5.- El sistema confirma la compra realizada mediante un resguardo tanto en el propio sistema de compras como a través de un correo.            |
| Flujo alternativo             | 3.A.- El sistema comprueba que todos los los datos necesarios hayan sido introducidos. Si no lo han sido, el Comprador podrá volver a introducir los datos (paso 4) o finalizar el proceso. <br> 5.A.- El sistema no ha podido confirmar la compra a través del correo del Comprador debido a que ha sido introducido de manera incorrecta.   |
| Poscondiciones                | El Comprador ha realizado la compra.                      |

 <br>

| Identificador                 | UC-04                         |
| :---                          | :----                         |
| Nombre                        | Eliminar producto             |
| Autor                         | Cristina García               |
| Fecha                         | 09/10/2022                    |
| Descripción                   | Permite que el Administrador elimine un producto determinado.       |
| Actores                       | Administrador          |
| Precondiciones                | El Administrador debe haber accedido al sistema de compra.       |
| Flujo normal                  | 1.- El Adminsitrador selecciona un producto a eliminar. <br> 2.- El sistema elimina el producto seleccionado.          |
| Flujo alternativo             | 2.A.- Si el sistema no permite al Administrador eliminar el producto, mostrará un mensaje de error.   |
| Poscondiciones                | El producto será eliminado del sistema de compras.                      |

 <br>

| Identificador                 | UC-05                         |
| :---                          | :----                         |
| Nombre                        | Agregar producto             |
| Autor                         | Alejandro Manzano               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | Permite que el Comprador añada un producto a su carro de la compra para ser comprado.      |
| Actores                       | Comprador          |
| Precondiciones                | El producto no está marcado como bloqueado.       |
| Flujo normal                  | 1.- El Comprador selecciona un producto a añadir. <br> 2.- El sistema añade el producto seleccionado al carro de la compra del Comprador. <br> 3.- El producto se es marcado como bloqueado por el sistema.          |
| Flujo alternativo             | 2.A.- Si el sistema no puede añadir el producto mostrará un mensaje de error al Comprador y no se marcará como bloqueado.   |
| Poscondiciones                | El producto ha quedado marcado como bloqueado.                     |

 <br>


| Identificador                 | UC-06                         |
| :---                          | :----                         |
| Nombre                        | Marcar producto como bloqueado             |
| Autor                         | Alejandro Manzano               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | Permite que al sistema marcar un producto como bloqueado cuando este añadadido al carro del Comprador.       |
| Actores                       | Comprador          |
| Precondiciones                | El Comprador ha añadido seleccionado la opción de agregar un producto a su carro.      |
| Flujo normal                  | 1.- El sistema busca el producto y cambia el campo de disponibilidad, que determina si este está bloqueado o no. <br> 2.- La interfaz se actualiza y se muestra el producto como bloqueado.          |
| Flujo alternativo             | 1.A.- Si el sistema no encuentra el producto devuelve un mensaje de error.   |
| Poscondiciones                | El producto ha quedado marcado como bloqueado por el sistema de compras.                      |

 <br>

| Identificador                 | UC-07                         |
| :---                          | :----                         |
| Nombre                        | Consultar producto             |
| Autor                         | Alejandro Manzano               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | Permite al Comprador consultar los detalles de los productos en los que esté interesado.       |
| Actores                       | Comprador          |
| Precondiciones                | Ninguna. |
| Flujo normal                  | 1.- El Comprador selecciona un producto del cual quiere consultar sus características. <br> 2.- El sistema busca las características del producto y verifica la disponibilidad del mismo. <br> El sistema muestra en una nueva interfaz todas las características del producto, y si está disponible o no para ser comprado.          |
| Flujo alternativo             | 2.A.- Si el sistema no encuentra el producto devolverá un mensaje de error.   |
| Poscondiciones                | Ninguna.                      |

 <br>


| Identificador                 | UC-08                         |
| :---                          | :----                         |
| Nombre                        | Verificar disponibilidad             |
| Autor                         | Alejandro Manzano               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | El sistema comprueba la disponibilidad de un producto cuando el Comprador trata de consultar los detalles del mismo.       |
| Actores                       | Comprador          |
| Precondiciones                | El Comprador ha seleccionado la opción para consultar los detalles de un producto. |
| Flujo normal                  | 1.- El sistema busca el producto en la base de datos y comprueba sus campos <br> 2.- El sistema devuelve el campo de la disponiblidad.   |
| Flujo alternativo             | 1.A.- Si el sistema no encuentra el producto devolverá un mensaje de error.   |
| Poscondiciones                | El sistema ha retornado una variable booleana.                      |

 <br>

| Identificador                 | UC-09                         |
| :---                          | :----                         |
| Nombre                        | Buscar productos              |
| Autor                         | Cristina García               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | Permite buscar productos.     |
| Actores                       | Comun                         |
| Precondiciones                | El usuario debe haber accedido al sistema de compra.       |
| Flujo normal                  |  1.- El usuario solicita buscar los productos según los parámetros introducidos. <br> 2.- El sistema busca los productos que coincidan con las mismas características dadas por el usuario. <br> 3.- El sistema muestra en una nueva interfaz todos los productos que tengan las caracteristicas requeridas.        |
| Flujo alternativo             | 2.A.- Si el sistema no encuentra ningún producto, devolverá un mensaje de error, permitiendo al usuario volver a buscar un producto (paso 1) o finalizar el proceso.   |
| Poscondiciones                | Ninguna. 

<br>

| Identificador                 | UC-10                         |
| :---                          | :----                         |
| Nombre                        | Consultar histórico de ventas         |
| Autor                         | Cristina García               |
| Fecha                         | 11/10/2022                    |
| Descripción                   | Permite consultar el histórico de ventas de un producto.     |
| Actores                       | Comprador y Vendedor          |
| Precondiciones                | Los usuarios deben haber accedido al sistema de compra.       |
| Flujo normal                  |  1.- El usuario solicita consultar el histórico de ventas de un producto. <br> 2.- El sistema busca dicho histórico de ventas. <br> 3.- El sistema muestra el histórico de ventas del producto pedido.        |
| Flujo alternativo             | 2.A.- Si el sistema no encuentra ningún histórico del producto, devolverá un mensaje de error, permitiendo finalizar el proceso.   |
| Poscondiciones                | Ninguna. 

