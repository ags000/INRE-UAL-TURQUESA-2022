
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

Especificiación de los Casos de Uso

$~$

<table>
  <tr>
     <td colspan="4" class="t_title"><h1>Template for use case definition</h1></td>
  </tr>

  <tr>
    <td>Identificador</td>
    <td>UC-01</td>
  </tr>

  <tr>
    <td>Nombre</td>
    <td>Consultar horarios</td>
  </tr>

  <tr>
    <td>Autor</td>
    <td>Alejandro Manzano<td>
  </tr>

  <tr>
    <td>Fecha </td>
    <td>07/10/2022</td>
  </tr>

  <tr>
    <td>Descripción</td>
    <td>Permite al usuario ver el horario que le corresponde.</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>Estudiante</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>El Estudiante está identificado en el Sistema.</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- El Estudiante selecciona la opción de la aplicación para ver el horario.<br>
          2.- El sistema busca el correspondiente horario del Estudiante y se lo muestra.
      </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>2A.- Si el sistema no encuentra el horario del Estudiante devolverá un mensaje de error.</td>
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
    <td>UC-02</td>
  </tr>

  <tr>
    <td>Nombre</td>
    <td>Proponer cambio de horario</td>
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
    <td>Permite proponer un cambio en el horario.</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>PDI</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>El estudiante ha de estar autenticado en el sistema</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- El estudiante solicita abir un ticket.<br>
      2.- El sistema pide la introducción del asunto y cuerpo del mensaje.<br>
      3.- El estudiante rellena los datos.<br>
      4.- El estudiante envía el ticket.
      </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>4.A.- El sistema comprueba que los campos hayan sido rellenados. Si no lo son,
        PDI podrá volver a introducir los datos (paso 3) finalizar el proceso.
      </td>
  </tr>

  <tr>
    <td>Poscondiciones</td>
    <td>No hay</td>
  </tr>
</table>

$~$

<table>

  <tr>
    <td>Identificador</td>
    <td>UC-03</td>
  </tr>
  
  <tr>
    <td>Nombre</td>
    <td>Dar de alta estudiante</td>
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
    <td>Permite dar de alta a un determinado estudiante</td>
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
      <td>1.- PAS solicita dar de alta al estudiante.<br>
      2.- El sistema solicita los datos del estudiante.<br>
      3.- PAS introduce los datos del estudiante.<br>
      4.- El sistema verifica los datos del estudiante.
      </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>4.A.- El sistema comprueba que los datos del estudiante sean correctos. Si no lo son, 
          PAS podrá volver a introducir los datos del estudiante (paso 3) o finalizar el proceso.
      </td>
  </tr>

  <tr>
    <td>Poscondiciones</td>
    <td>El estudiante está dado de alta</td>
  </tr>
</table>

$~$


<table>

  <tr>
    <td>Identificador</td>
    <td>UC-04</td>
  </tr>
  
  <tr>
    <td>Nombre</td>
    <td>Buscar listas de clase</td>
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
    <td>Buscar al estudiante en las listas de clase</td>
  </tr>

  <tr>
      <td>Actores</td>
      <td>PDI</td>
  </tr>

  <tr>
      <td>Precondiciones</td>
      <td>PDI debe estar auntenticado en el sistema</td>
  </tr>

  <tr>
      <td>Flujo normal</td>
      <td>1.- PDI solicita buscar al estudiante en las listas de clase.<br>   
      2.- El sistema solicita los datos de la clase del estudiante al que se va a dar de alta.<br>
      3.- PDI introduce los datos de la clase.<br>
      4.- El sistema verifica los datos.<br>
      5.- El sistema muestra la lista de la clase.
	   </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>4.A.- El sistema comprueba que los datos de la clase sean correctos. Si no lo son, 
			    PDI podrá volver a introducir los datos (paso 2) o finalizar el proceso.
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
      <td>1.- PAS introduce los datos del estudiante a dar de alta.<br>
          2.- El sistema verifica los datos del estudiante.
	    </td>
  </tr>

  <tr>
      <td>Flujo alternativo</td>
      <td>2.A.- El sistema comprueba que los datos del estudiante sean correctos. Si no lo son, 
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

$~$