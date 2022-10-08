
<h1>Lab 1: Definición de casos de uso y requisitos de información</h1>

$~$

Especificación de los Actores

$-$

<table>

   <tr>
     <td colspan="4" class="t_title"><h1>Template for information requirement definition</h1></td>
  </tr>

  <tr>
    <td>IR 01</td>
    <td>Estudiante</td>
  </tr>

  <tr>
    <td>Versión</td>
    <td>07/10/2022<td>
  </tr>

  <tr>
    <td>Autores</td>
    <td>Alejandro Manzano</td>
  </tr>

  <tr>
    <td>Fuentes</td>
    <td></td>
  </tr>

  <tr>
    <td>Referencias</td>
    <td>Consultar horario</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td></td>
  </tr>

  <tr>
    <td>Datos específicos</td>
    <td></td>
  </tr>

  <tr>
    <td>Importancia</td>
    <td></td>
  </tr>

  <tr>
    <td>Estado</td>
    <td></td>
  </tr>
  
  <tr>
    <td>Comentarios</td>
    <td></td>
  </tr>
</table>

$~$

<table>

  <tr>
    <td>IR 02</td>
    <td>PDI</td>
  </tr>

  <tr>
    <td>Versión</td>
    <td>1.0 (08/10/2022)<td>
  </tr>

  <tr>
    <td>Autores</td>
    <td>Cristina García</td>
  </tr>

  <tr>
    <td>Fuentes</td>
    <td></td>
  </tr>

  <tr>
    <td>Referencias</td>
    <td> <li type="disc">Proponer cambio de horario, UC-02.</li>
		 <li type="disc">Dar de alta estudiante vista PDI, UC-07.</li>
		 <li type="disc">Buscar listas de clase, UC-04.</li>
	</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td>El sistema deberá permitir al PDI proponer cambios en el horario
		y dar de alta a estudiantes.</td>
  </tr>

  <tr>
    <td>Datos específicos</td>
    <td></td>
  </tr>

  <tr>
    <td>Importancia</td>
    <td>Muy importante</td>
  </tr>

  <tr>
    <td>Estado</td>
    <td>Aceptado</td>
  </tr>
  
  <tr>
    <td>Comentarios</td>
    <td></td>
  </tr>
</table>


$~$


| IR 02                         |PAS                            |
| :---                          | :---                          |
| Versión                       |1.0 (08/10/2022)               |
| Autores                       | Cristina García               |
| Fuentes                       |                               |
| Referencias                   | - Modificar horario  <br> - Dar de alta estudiante  <br> - Verificar datos estudiante  <br> |
| Descripción                   | El sistema deberá permitir al PAS modificar los horarios y dar de alta a los estudiantes. |
| Datos específicos             |                                |
| Importancia                   | Muy importante                 |
| Estado                        | Aceptado                       |
| Comentarios                   |                                |

$~$

Especificiación de los Casos de Uso

$~$

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
| Flujo normal                  | 	1.- El PDI solicita abrir un ticket. <br> 2.- El sistema pide la introducción del asunto y cuerpo del mensaje. <br> El PDI rellena los datos. <br> El estudiante envía el ticket.       |
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

<table>

  <tr>
    <td>Identificador</td>
    <td>UC-05</td>
  </tr>
  
  <tr>
    <td>Nombre</td>
    <td>Verificar datos estudiantes</td>
  </tr>

  <tr>
    <td>Autor</td>
    <td>Cristina García<td>
  </tr>

  <tr>
    <td>Fecha </td>
    <td>07/10/2022</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td>Permite verificar los datos del estudiantes</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>PAS</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>PAS debe estar auntenticado en el sistema</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- PAS introduce los datos del Estudiante a dar de alta.<br>
          2.- El sistema verifica los datos del Estudiante.
	    </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>2.A.- El sistema comprueba que los datos del Estudiante sean correctos. Si no lo son, 
			    PAS podrá volver a introducir los datos (paso 1) finalizar el proceso.
			</td>
  </tr>

  <tr>
    <td>Poscondiciones</td>
    <td>Ninguna.</td>
  </tr>
</table>

$~$

<table>

  <tr>
    <td>Identificador</td>
    <td>UC-06</td>
  </tr>
  
  <tr>
    <td>Nombre</td>
    <td>Modificar horario</td>
  </tr>

  <tr>
    <td>Autor</td>
    <td>Cristina García<td>
  </tr>

  <tr>
    <td>Fecha </td>
    <td>07/10/2022</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td>Permite modificar el horario</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>PAS</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>PAS debe estar auntenticado en el sistema</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- PAS hace uso de la herramienta que tiene el sistema para modificar el horario<br>
		  2.- PAS guarda los cambios realizados<br>
		  3.- El sistema actualiza los horarios modificados
	 </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>2.A.- El sistema no guarda los cambios realizados debido a que PAS cierra el programa sin guardar.
	  </td>
  </tr>

  <tr>
    <td>Poscondiciones</td>
    <td>Los cambios en el horario han sido actualizados.</td>
  </tr>
</table>

$~$


<table>

  <tr>
    <td>Identificador</td>
    <td>UC-07</td>
  </tr>
  
  <tr>
    <td>Nombre</td>
    <td>Dar de alta estudiante vista PDI</td>
  </tr>

  <tr>
    <td>Autor</td>
    <td>Cristina García<td>
  </tr>

  <tr>
    <td>Fecha </td>
    <td>08/10/2022</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td>Permite a PDI dar de alta a un estudiante determinado</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>PID</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>PID debe estar auntenticado en el sistema</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- PID solicita dar de alta al Estudiante.<br>
      2.- El sistema solicita los datos del Estudiante.<br>
      3.- PID introduce los datos del Estudiante.<br>
      4.- El sistema verifica los datos del Estudiante.<br>
	  </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>4.A.- El sistema comprueba que los datos del Estudiante sean correctos. Si no lo son, 
          PID podrá volver a introducir los datos del Estudiante (paso 3) o finalizar el proceso.
		  4.B.- El sistema, de forma excepcional, busca las listas de clase de las asignaturas del Estudiante.
	  </td>
  </tr>

  <tr>
    <td>Poscondiciones</td>
    <td>El Estudiante está dado de alta.</td>
  </tr>
</table>

$~$

$~$