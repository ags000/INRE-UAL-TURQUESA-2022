# ***Proyecto***
 
<br>

## ***Índice de contenidos***

Hoja de revisión. <br>
Contenidos.
1. Introducción.
2. Información del Dominio del problema. <br>
2.1. Organigrama. <br>
2.2. Glosario de términos.
3. Necesidades del negocio. <br>
3.1. Objetivos del negocio. <br>
3.2. Modelos de Proceso de Negocio. <br>
3.2.1. Sub-procesos. <br>
3.2.2. Tareas. <br>
4. Requisitos del sistema a desarrollar. <br>
4.1. Requisitos. <br>
4.2. Casos de uso. <br>
4.2.1. Lista de diagramas de casos de uso del modelo. <br>
4.2.2. Diagramas de casos de uso. <br>
4.2.3. Lista general de casos de uso y actores del proyecto. <br>
4.2.4. Detalle de los casos de uso. <br>
4.3. Diagramas de clases asociados a los requisitos de información. <br>

Apendices 

<br>

# Hoja de revisión 

| Fecha | Versión | Descripción | Autor |
| :--   | :--     | :--         | :--   |
| 29/10/2022  | 1.0        | Se ha recibido el pliego de condiciones técnicas el desarrollo del software de un sistema de información interactivo al viajero del transporte público regular de viajeros para la isla de Gran Canaria (portal web de servicios) mediante procedimiento abierto | Alejandro, Cristina y Adrián |
| 15/11/2022  | 1.0        | Se realiza la entrevista a un mecánico naval para aclarar y detallar más los diferentes apartados            | Alejandro, Cristina y Adrián       |
| 19/11/2022  | 1.0        | Se comienza el análisis de requisitos sobre el pliego de condidiciones, extrayendo los requisitos funcionales y no funcionales de cada apartado del documento.            | Alejandro, Cristina y Adrián      |
| 22/11/2022  | 1.1        | Se elabora la estructura del documento de plantilla de requisitos con sus correspondientes apartados y secciones.            | Alejandro, Cristina y Adrián      |
| 13/12/2022  | 1.2        | Se construyen los diagramas de casos de uso, BPMN y el organigrama.            | Alejandro, Cristina y Adrián      |
| 14/12/2022  | 1.3        | Se rellenan los campos de las tablas de cada requisito funcional, no funcional y de la información.            | Alejandro, Cristina y Adrián      |
| 15/12/2022  | 1.4        | Se construyen los diagramas entidad-relación y se continua rellenando los campos de las tablas que faltaban.            | Alejandro, Cristina y Adrián      |
| 16/12/2022  | 1.5        | Versión final del proyecto, plantilla de requisitos completa.            | Alejandro, Cristina y Adrián      |


# 1. Introducción.

Se ha elaborado una propuesta de implementación del desarrollo de un software para un sistema de información interactivo para el usuario del transporte público regular de la isla de Gran Canaria. Para ello se ha elaborado una plantilla de requisitos que se corresponden con las especificaciones técnicas proporcionadas por el pliego de condiciones entregado con anterioridad.

La propuesta recoge el trabajo realizado para el análisis, definición, diseño, desarrollo, puesta a punto e implementación del software necesario para poner en funcionamiento un Sistema Interactivo de Información (SIIT) y un Sistema de Información y Monitorización de la Explotación del Transporte (SMET), así como los servicios continuos para el mantenimiento de los mismos.

<br>

# 2. Información del Domino del problema.

## 2.1. Organigrama.

<div align="center">
    <img src="./../Proyecto/organigrama.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 1. Organigrama de la empresa AUTGC.</p></i>
</div>

<br>

## 2.2. Glosario de términos.

<br>

| Término                  | Descripción                     |
| :---                     | :---                            |
| WYSIWYG                  | Acrónimo de «Lo que ves obtienes», (What you see is what you get) es una frase aplicada a los procesadores de texto y otros editores de texto con formato (como los editores de HTML) que permiten escribir un documento mostrando directamente el resultado final, frecuentemente el resultado impreso.                                                     |
| Cloud tag                | Las nubes de etiquetas consisten en agrupar palabras (etiquetas, tags) y mostrarle al visitante de la web cuales son las etiquetas más usadas, usando también estilos que permiten visualizar mejor cual tiene mayor actividad y cual tiene menor actividad.
| CEN                      | Comité Europeo de Normalización         |
| SIIT                     | Sistema Interactivo de Información del Transporte |
| SMET                     | Sistema de la Mo5nitorización de la Explotación del Transporte |
| HelpDesk                 | Conjunto de recursos tecnológicos y humanos, para prestar servicios con la posibilidad de gestionar y solucionar todas las posibles incidencias de manera integral, junto con la atención de requerimientos relacionados con las Tecnologías de la Información y la Comunicación (TIC).  |
| PDA                      | Personal Digital Assistant, Ayudante personal digital. Es un dispositivo de pequeño tamaño que combina un ordenador, teléfono/fax, Internet y conexiones de red.  |
| LOPD                     |  Ley Orgánica 15/1999 de 13 de diciembre de Protección de Datos de Carácter Personal. Es una ley española que tiene por objeto la garantía y la protección de los datos personales, las libertades públicas y los derechos fundamentales de las personas físicas, en especial de su honor, intimidad y privacidad personal y familiar.   |
| AUT                      | Autoridad Única del Transporte |
| Entorno de colaboración       | Entorno enfocado a la facilitación de la comunicación e intercambio de información tanto entre los administradores como entre los usuarios del sistema. |

<br>

# 3. Necesidades del negocio.

<br>

## 3.1. Objetivos del negocio.

<br>

| OBJ-1                 		  | Gestión del Portal del SIIT   |
| :---                    		  | :---                          |
| Versión                         | 2.0                           |
| Descripción                     | El sistema deberá implementar un Portal Web que cuente tanto con las necesidades de los usuarios como el análisis técnico. Se deberá implementar la identificación de necesidades (contenidos, servicios, audiencias,…), definición de la estructura (arquitectura de la información, mapa web,…) y organización del portal, detallar componentes organizativos, funcionales y técnicos del mismo. |
| Comentarios                     |                               |

<br>

| OBJ-2                 		  | Gestión de los sistemas de la información del SIIT   |
| :---                    		  | :---                          |
| Versión                         | 2.0                           |
| Descripción                     | El sistema deberá implementar un sistema integrado de información de la red de transporte público de todos los municipios de Gran Canaria que proporcione herramientas de análisis, consulta, localización y gestión, con el objeto de que el usuario del transporte público pueda consultar de forma dinámica la información del servicio permitiéndole conocer y programar con antelación su viaje.                               |
| Comentarios                     |                               |

<br>

| OBJ-3                 		  | Gestión del SMET   |
| :---                    		  | :---                          |
| Versión                         | 2.0                           |
| Descripción                     | El sistema deberá implementar el análisis, diseño, implementación y la puesta en marcha de un sistema de información central sobre la explotación para la Autoridad Única del Transportes cuya misión fundamental sea la de monitorizar en tiempo real el estado de la red de transporte público por carretera en la Isla de Gran Canaria. |
| Comentarios                     |                               |

<br>

## 3.2. Modelos de Procesos de Negocio.

<br>

### 3.2.1. Sub-procesos.

<br>

<div align="center">
    <img src="./../Proyecto/BPMN-01.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 1. BPMN-01.</p></i>
</div>

<br>

<div align="center">
    <img src="./../Proyecto/BPMN-02.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 2. BPMN-02.</p></i>
</div>

<br>

<br>

<div align="center">
    <img src="./../Proyecto/BPMN-03.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 3. BPMN-03.</p></i>
</div>

<br>

### 3.2.2. Tareas.

<br>

| Nombre                   | BPMN-01                       |
| :---                     | :---                          |
| Descripción              | Un trabajador de la AUTGC establece contacto con un operador de transporte para obtener el acta de incidencias (medio magnético o soporte papel) para proporcionárselo al operador adjudicatario. El operador revisa la información y si considera que los datos no son correctos, contactará con los operadores de trabajo para que la corrijan y le envíen la nueva información.                                |

<br> 

| Nombre                   | BPMN-02                       |
| :---                     | :---                          |
| Descripción              | Para que un usuario pueda comprar un bono a través de la Web, debe especificar la fecha y lugar deseado para realizar el viaje y el sistema buscará todas las opciones disponibles. Si hay, las muestra, en caso contrario, le mostrará las alternativas disponibles. Si el usuario desea una de esas opciones, selecciona la deseada, introduce sus datos personales y la compra, de manera que el sistema guarda la información en la base de datos y envía un resguardo al usuario. Por el contrario, si no quiere ninguna, podrá elegir otra fecha distinta o finalizar la compra.                            |

<br>

| Nombre                   | BPMN-03                       |
| :---                     | :---                          |
| Descripción              | Para que un usuario realice una consulta origen-destino debe introducir en el sistema el origen y el destino del viaje que quiere realizar. Además, podrá filtrar la consulta por un criterio de búsqueda (tiempo de viaje, precio, número de transbordos, parada, intervalo horario de salida). El sistema comprobará que la solución más optima se encuentre disponible y la proporcionará, pudiendo el usuario imprimir la información obtenida, y simular el recorrido. Si el sistema no encuentra una solución, informará al usuario, y le permitirá imprimir la solución (en este caso al no haber, saldrá un texto informativo).                                              |

<br>

# 4. Requisitos del sistema a desarrollar.

<br>

## 4.1. Requisitos.

<br>

### 4.1.1 Portal.

<br>

| RF-01					| Gestor de contenido	|
| :---					| :----  	|
| Versión				| 1.0	|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	|		|
| Descripción			| El SIIT deberá poseer un sistema propio que pueda ser utilizado para administrar el contenido y la información del sistema interactivo. Así como, las herramientas necesarias para el mantenimiento del mismo.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 		|

<br>

| RF-02					| Acceso web con editor WYSIWYG		|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema deberá poseer  el acceso a web con un editor WYSIWYG para el gestor de contenido.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| WYSIWYG (What You See Is What You Get) implica que el editor deberá mostrar siempre la versión final del archivo que se está creando o editando.		|

<br>

| RF-03					| Creación de páginas de forma sencilla y coherente		|
| :---					| :---- 	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema deberá proporcionar las herramientas para la creación de páginas de forma sencilla y coherente con el resto de la Web a usuarios finales que no tengan conocimiento de programación ni de HTML.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-04					| Previsualización de la publicación de una página		|
| :---					| :---- 	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-01, RF-02		|
| Descripción			| El gestor de contenidos debe de poseer una función para previsualizar la versión final de la página previamente a que esta sea publicada de manera definitiva.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-05					| Modificación sencilla del diseño de una página	|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema deberá proporcionar las herramientas para la modificación sencilla del diseño común a varias páginas o de la Web entera.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-06					| Contenido flexible		|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-01		|
| Descripción			| Todo contenido de la web de cualquier tipo deberá de poder ser publicado, retirado y modificado por el gestor de contenido.		|
| Importancia			| Alta	|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-07					| Herramientas de seguimiento		|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| 		|
| Descripción			| El sistema deberá proporcionar estadísticas de acceso a las distintas Secciones y Servicios.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| Solo los gestores de contenido tendran acceso a las estadísticas		|

<br>

| RF-08					| Entorno de colaboración		|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| 		|
| Descripción			| El sistema tendrá un entorno de colaboración  enfocado a facilitar la comunicación e intercambio de información.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 		|

<br>

| RF-09					| Espacios para el trabajo compartido 		|
| :---					| :---- 	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-08		|
| Descripción			| El entorno de colaboración contará con espacios para el trabajo compartido y en colaboración en la AUT.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| Los espacios para el trabajo compartido serán solo para los gestores de contenido. 		|

<br>

| RF-10					| Herramientas web 2.0 	 |
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RF-08		|
| Descripción			| Herramientas web 2.0 para los usuarios del transporte público! Foro, Blog, y relación de cloud tag en la home del website.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 		|

<br>

| RF-11					| Buscador		|
| :---					| :----  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	|		|
| Descripción			| El buscador permitirá la localización de cualquier contenido mediante la introducción de términos clave. En las búsquedas no se diferenciarán las palabras con o sin acento, mayúsculas o minúsculas. Dispondrá de opciones que permitan la parametrización de las búsquedas considerado entre otras características: idioma, secciones del sitio, etc. 		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|


| RF-12					| Consultar estadísticas 	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El portal contará con un aplicativo de estadísticas que permita conocer como se utiliza el sistema por parte de los usuarios, con el fin de obtener información de interés desde el punto de vista del transporte (origen más solicitado, destino más solicitado, información más requerida, puntos de información más solicitados, etc.) y procurar su mejora continuada. 		|
| Comentarios			|		|

<br>

| RNF-01		    	| Análisis del portal		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	|		|
| Descripción			| Definir, a través de un análisis completo, tanto el enfoque del portal y necesidades de los usuarios como el análisis técnico.		|
| Comentarios			|		|

<br>

| RNF-02		    	| Recopilar información		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Identificación de necesidades (contenidos, servicios, audiencias,…), definición de la estructura (arquitectura de la información, mapa web,…) y organización del portal, detallar componentes organizativos, funcionales y técnicos del mismo.		|
| Comentarios			|		|

<br>

| RNF-03		    	| Propuesta de home e interior		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| La empresa adjudicataria deberá presentar dos propuestas de home e interior, que deberán reflejar menús, iconografía, colores, estilos, etc, de modo que quede determinada la línea de comunicación e imagen en Internet del Proyecto y de los servicios.		|
| Comentarios			|		|

<br>

| RNF-04		    	| Tareas del Proyecto		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01, RNF-03		|
| Descripción			| Las tareas, una vez asignado el proyecto serán: Diseño del interfaz, Diseño de páginas tipo, Definición del estilo gráfico de comunicación y promoción on-line, Creación del libro de estilo y de la marca en canales digitales.		|
| Comentarios			|		|

<br>

| RNF-05		    	| Requerimientos técnicos		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| En función de los análisis realizados, se establecerán los requerimientos técnicos con los que debe cumplir la plataforma que soporte el portal y sus servicios.		|
| Comentarios			|		|

<br>

| RNF-06		    	| Ciclo de vida del software		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Diseño, desarrollo, puesta en marcha, alojamiento y mantenimiento de la plataforma tecnológica para difusión, soporte y comunicación de contenidos referentes al transporte público.		|
| Comentarios			|		|

<br>

| RNF-07		    	| Diseño de la arquitectura		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Diseño de la arquitectura tanto física como lógica.		|
| Comentarios			|		|

<br>

| RNF-08		    	| Diseño del modelo de datos		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| El diseño del modelo de datos debe preferentemente corresponderse con alguno de los estándares europeos definidos por el CEN (comité europeo de normalización). 		|
| Comentarios			|		|

<br>

| RNF-10		    	| Desarrollo o adaptación de las aplicaciones		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Descripción general de la solución propuesta, arquitectura de hardware, arquitectura de software, descripción de cada uno de los componentes.		|
| Comentarios			|		|

<br>

| RNF-11		    	| Versión multidispositivo		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Desarrollo o adaptación de las aplicaciones necesarias para el correcto funcionamiento del portal.		|
| Comentarios			|		|

<br>

| RNF-12		    	| Detallar los lenguajes y navegadores soportados		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Versión multidispositivo.		|
| Comentarios			|		|

<br>

| RNF-13		    	| Propuesta inicial		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| RNF-01		|
| Descripción			| Elaborar una propuesta inicial de contenido recopilando todo lo disponible en diversas fuentes y sometiéndola al visto bueno de la AUTGC, la cual a su vez facilitará los medios que estén a su disposición para facilitar el trabajo.		|
| Comentarios			|		|

<br>

| RNF-14		    	| Carga inicial		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	|		|
| Descripción			| La carga inicial de los contenidos acordados en el gestor.		|
| Comentarios			|		|

<br>

| RNF-15		    	| Maquetación		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	| 		|
| Descripción			| Maquetación conforme a las pautas dadas y plantillas existentes en el gestor.		|
| Comentarios			|		|

<br>

| RNF-16		    	| Actualización		|
| :---					| :----  	|
| Objetivos asociados	| OBJ-1		|
| Requisitos asociados	|		|
| Descripción			| Actualización continúa durante todo el contrato de dichos contenidos, de acuerdo con el tipo de cada uno de ellos, y sobre todo vigilando que no se presenten contenidos obsoletos en ningún caso.		|
| Comentarios			|		|

<br>

| RI-01                    | Usuarios             |
| :---                     | :---                           |
| Requisitos asiciados     | [CU-01 / CU-11]                  |
| Descripción              | El sistema deberá almacenar información correspondiente a las personas autenticadas que usan el sistema (usuario logueado y administrador).          |
| Datos específicos        | idUsuario : String <br> contraseña : String <br> rol : Int <br> nombre_completo : String <br> email : String <br> idioma_deseado : String.  |
| Comentarios              | Un usuario normal tendrá como rol el valor '0' y un administrador el valor '1'.|

<br>

| RI-02                    | Estadísticas             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-06                |
| Descripción              | El sistema deberá almacenar información correspondiente a las estadísticas          |
| Datos específicos        | idEstadistica : Int <br> procedencia_geografica : String <br> consulta_realizada : String.  |
| Comentarios              | Ninguno. |

<br>

| RI-03                    | Administrador_visualiza_Estadisticas             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-06            |
| Descripción              | El sistema deberá almacenar información correspondiente a las estadísticas que ha visualizado cada administrador.         |
| Datos específicos        | idEstadistica : Int <br> idAdministrador : String |
| Comentarios              | Ninguno. |

<br>

| RI-04                    | Mensaje_Espacio_Compartido             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-05              |
| Descripción              | El sistema deberá almacenar todos los mensajes del chat del espacio compartido.       |
| Datos específicos        | id_Mensaje_Espacio_Compartido : Int <br> id_Administrador : String <br> fecha : Date <br> Mensaje : String |
| Comentarios              | Se considera el espacio compartido como un IRC. |

<br>

| RI-05                    | Administrador_Modifica_Paginas             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-02, CU-04                 |
| Descripción              | El sistema deberá almacenar información correspondiente a las páginas modificadas por un administrador        |
| Datos específicos        | idAdministrador : Int <br> idPagina : Int <br> idUsuario_creador : Int <br> fecha_modificacion : Date |
| Comentarios              | Tabla para trigger de consistencia de datos. |

<br>

| RI-06                    | Página             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-07, CU-08                 |
| Descripción              | El sistema deberá almacenar información correspondiente a las nuevas páginas creadas       |
| Datos específicos        | idPagina : Int <br> idUsuario : String <br> ruta_html : String <br> fecha_creacion : Strubg |
| Comentarios              | Ninguno. |


### 4.1.2 Sistemas de la información.

<br>

| RF-01					| Tratamiento de la información cartográfica		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| El sistema debe poseer toda la información integrada de la red de transporte público de todos los municipios de Gran Canaria.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| La información se representará tanto georeferenciada de acuerdo a la directiva INSPIRE como con información de texto asociada.		|

<br>

| RF-02					| Calcular distancias entre paradas		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema debe ser capaz de calcular la distancia entre dos paradas de cada transporte.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-03					| Definir transbordos		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema deberás ser capaz de crear transbordos entre los viajes para optimizar la eficiencia de las rutas de los vehículos.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-04					| Calcular tiempos de recorrido		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema deberá de ser capaz de calcular un tiempo estimado para el trayecto de un recorrido completo.		|
| Importancia			| Alta	 	|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-05					| Identificar zonas por las que no se puede transitar		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema de ser capaz de identificar zonas intransitables y elaborar una ruta alternativa para llegar al destino.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-06					| Definir barrios, zonas y municipios		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema debe poder definir tanto barrios como zonas y municipios de Gran Canaria		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-07					| Seleccionar origen desde el mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El usuario podrá introducir un lugar de origen en el mapa a partir del cual calcular las rutas.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-08					| Seleccionar destino desde el mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El usuario podrá introducir un lugar de destino en el mapa a partir del cual calcular las rutas.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-09					| Presentar recorrido de una línea		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema proporcionará la información de todo el recorrido que realiza una línea de un determinado transporte.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-10					| Presentar la solución de un itinerario recomendado		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02	 	|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema presentará un itinerario recomendado para cada ruta que se introduzca.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-11					| Mostrar las paradas y sus datos según selección previa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema mostrará las paradas y sus datos ç según una selección previa que ha de realizar el usuario.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| Se podrán seleccionar las paradas cercanas a un cierto sitio, de una línea, dentro de un municipio, zona o barrio, etc.		|

<br>

| RF-12					| Ubicar sitios de interés, eventos culturales y turísticos		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema remarcará en el mapa los lugares de interés turísticos y culturales.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-13					| Presentar información	adicional	|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| El sistama podrá presentar información adicional para cada acción realizada.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|


<br>

| RF-14					| Información adicional para paradas		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-13		|
| Descripción			| El sistema presentará información adicional de las paradas, indicando líneas que pasan por cada parada, su dirección postal, foto, etc.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-15					| Información adicional para una línea		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-13		|
| Descripción			| El sistema presentará información adicional de una línea concreta, presentando sus tarifas, horarios, empresa gestora, incidencias, etc		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-16					| Parada de inicio y fin para un itinerario recomendado		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-13		|
| Descripción			| El sistema presentará información adicional de la solución de un itinerario recomendado, por cada tramo se mostrará la parada de inicio y de fin.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-17					| Acercar sobre el mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema permitirá ampliar la visión en el mapa para mostrar más detalles sobre el mismo.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| Más detalles implica que se puedan leer los nombres de calles y avenidas más secundarias y de otro tipo. 		|

<br>

| RF-18					| Alejar sobre el mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		| 
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema permitirá alejar la visión en el mapa para mostrar una visión más general del mismo.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-19					| Desplazar sobre el mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema permitirá desplazar la visión sobre el mapa.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-20					| Ir a mapa base (en el mapa)		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema permitirá volver al mapa base mostrado inicialmente.|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-21					| Centrar mapa		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El sistema permitirá centrar la visión sobre el mapa en relación a la posición actual.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-22					| Cálculo de itinerarios recomendados		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| 		|
| Descripción			| El sistema calculará y proporcionará al usuario los itinerarios recomentados para una determinada ruta. 		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| El proceso debe encontrar la mejor solución en el menor tiempo (de itinerario) contemplando todas las alternativas del transporte público disponible.		|

<br>

| RF-23					| Modificar los parámetros utilizados en el cálculo del itinerario		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-22  		|
| Descripción			| Todos aquellos parámetros que se utilicen en el cálculo y puedan influir en el resultado del itinerario se podrán modificar y ajustar hasta lograr el mayor grado de exactitud en el modelo.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-24					| Mostrar tramos que componen un trayecto		|
| :---					| :--  	|
| Versión				| 1.0	 	|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-22		|
| Descripción			| Para cada tramo se especificará la línea implicada, el tiempo necesario para recorrerlo, el punto de inicio y el de fin, el coste por etapa y la hora estimada de comienzo.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-25					| Mostrar coste de un viaje		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-22		|
| Descripción			| El sistema deberá de mostrar el coste asociado al viaje que se realizará en el transporte público. 		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-26					| Definir parámetros de la consulta a realizar		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| El usuario debe: establecer punto de origen y destino del itinerario, fecha y hora del trayecto y el aspecto que le interesa potenciar de la solución (tiempo, coste, transbordos, etc).		|
| Importancia			| Alta		|
| Urgencia				| 		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-27					| Seleccionar origen y destino		|
| :---					| :--  	|
| Versión				| 1.0	 	|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El usuario podrá introducir de manera simultánea el origen y el destino de la ruta para calcular la solución del itinerario.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| El usuario podrá seleccionar el origen y destino a través de la calle y número de portal por municipio, el barrio, la zona, el municipio, las paradas (de una línea, de un barrio, de un municipio o de una zona), desde el mapa o a partir de un evento cultural o sitio de interés turístico.  		|

<br>

| RF-28					| Mostrar en el mapa el recorrido de la solución		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema deberá de mostrar el recorrido completo ilustrado sobre el mapa una vez calculada la solución del itinerario con los datos introducidos por el usuario.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-29					| Mostrar solución en forma esquemática		|
| :---					| :--  	|
| Versión				| 1.0	|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema también deberá ser capaz de mostrar la solución del rerorrido de forma esquemática; especificando cada parada y su ubicación.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-30					| Mostrar solución como texto para ser impreso		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema también deberá ser capaz de mostrar la solución en formato de texto para ser impreso en los tickets de cada viaje; mostrando el origen, el destino y el número de paradas.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-31					| Acceder a información de mayor detalle de las paradas y las líneas que forman parte de la respuesta desde la solución		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El usuario podrá acceder a una pestaña con información detallada tanto de las paradas como de las líneas que están relacionadas con la solución calculada por el sistema.			|
| Importancia			| Alta	|
| Urgencia				| 		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-32					| Indicar los diferentes tramos que debe recorrer un usuario		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema proporcionará al usuario la información relativa a los tramos que este debe realizar durante el trayecto, presentado en la solución del cálculo de mejor camino.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|		|

<br>

| RF-33					| Indicar el tiempo empleado en recorrer un tramo		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02	 	|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema proporcionará el tiempo asociado estimado para recorrer un tramo concreto presentado en la solución del cálculo de mejor camino. 		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|  		|

<br>

| RF-34					| Mostrar tiempo total del trayecto hasta alcanzar destino		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema proporcionará un computo del tiempo total para realizar el trayecto completo presentado en la solución del cálculo de mejor camino.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 		|

<br>

| RF-35					| Mostrar la línea		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema mostrará la línea a elegir para realizar el trayecto deseado, presentado en la solución del cálculo de mejor camino..	|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 	|

<br>

| RF-36					| Mostrar descripción de la línea		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 	 	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema dará información de la solución tanto sobre la línea, como el número de tramos, el tiempo estimado por tramo y total del trayecto.		|
| Importancia			| Alta	|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			| 		|

<br>

| RF-37					| Mostrar destino de la línea en la que viajará		|
| :---					| :--  	|
| Versión				| 1.0		|
| Autores				| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fuentes				| Pliego de condiciones 		|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-26		|
| Descripción			| El sistema mostrará cláramente el destino de la línea que se ha escogido para viajar, presentada en la solución.		|
| Importancia			| Alta		|
| Urgencia				|		|
| Estado				|		|
| Estabilidad			|		|
| Comentarios			|   	|

<br>

| RNF-01				| Desarrollar procesos de recogida de información de cada gestor		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se debe modelar una forma de recopilar la información de cada gestor del transporte. La información proporcionada por estos gestores se encuentra disponible en medio magnético o papel. 		|
| Comentarios			|		|

<br>

| RNF-02				| Desarrollar trabajo de campo para la obtención de la información		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se debe realizar un trabajo físico que permita la obtención de la información no recogida y necesaria para el correcto funcionamiento del sistema. 		|
| Comentarios			| La AUTGC facilitará los medios que estén a su alcance. <br> Se debe recoger la información física (discos magnéticos, papel) de los gestores de transporte. Además, se debe recoger información de otras fuentes. Por ejemplo, un informador que avise de obras en una ruta.	|

<br>

| RNF-03				| Datos que se deben obtener		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RF-01		|
| Descripción			| El usuario debe obtener las líneas de guaguas, sus recorridos, paradas, horarios planificados de los itinerarios según tipos de día y períodos definidos, las tarifas, restricciones de tráfico, incidencias notificadas, etc.  		|
| Comentarios			|		|

<br>

| RNF-04				| Modelo de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| El modelo de datos del sistema debe corresponderse con alguno de los estándares europeos definidos por el CEN.		|
| Comentarios			|		|

<br>

| RNF-05				| Definir la estructura de la base de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| La estructura de la base de datos debe de construirse acorde a los estándares correspondientes y manteniendo la eficiencia entre tablas y relaciones esenciales sin sobrecargarlas innecesariamente. 		|
| Comentarios			|		|

<br>

| RNF-06				| Desarrollo del proceso de carga inicial de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se deberán introducir una carga datos reales inicial para poner a prueba los sistemas.		|
| Comentarios			|		|

<br>

| RNF-07				| Mantenimiento de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se deberán de hacer revisiones periódicas para que los datos almacenados de los transportes y los mapas no se queden anticuados respecto a los cambios que se produzcan en los mismos.		|
| Comentarios			|		|

<br>

| RNF-08				| Proceso de verificación de consistencia y amplitud de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Los procesos de verificación de la consistencia y amplitud de los datos contemplarán, como mínimo, la modificación de datos, introducción manual de datos y listados de horarios y servicios.		|
| Comentarios			|		|

<br>

| RNF-09				| Base de datos corporativa de la AUTGC		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| 		|
| Descripción			| Se deberá elaborar una baste de datos que contengan todos los elementos necesarios que requieran las distintas funcionalidades que requieran almacenar información de manera permanente en la aplicación.		|
| Comentarios			|		|

<br>

| RNF-10				| Casos de prueba y validación		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se deberán elaborar pruebas funcionales para validar las funcionalidades del sistema (pruebas unitarias, componentes, integración, aceptación...)		|
| Comentarios			|		|

<br>

| RNF-11				| Se dispondrá de ayuda en línea para cada proceso		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| Existirán gerentes a los que se pueda acudir para requerir ayuda en línea con la aplicación.		|
| Descripción			|		|
| Comentarios			|		|

<br>

| RNF-12				| Lenguaje de programación		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Las tareas de programación se realizarán en lenguaje PL/SQL. 		|
| Comentarios			|		|

<br>

| RNF-13				| Tablas en la base de datos		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| La estructura de las diferentes tablas de la base de datos contendrá,como mínimo, las líneas, paradas, itinerarios de línea, empresas y tarifas.		|
| Comentarios			|		|

<br>

| RNF-14				| Datos relacionados con el transporte público		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Se deberán de recoger la respectiva información de los diferentes transportes públicos para que estos sean integrados en el sistema. 		|
| Comentarios			|		|

<br>

| RNF-15				| Integrar información del transporte público y su información cartográfica asociada		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	| RNF-14		|
| Descripción			| La aplicación deberá de contener toda la información de los diferentes transportes públicos, así como toda la información de los mapas urbanos para calcular las rutas de los mismos.		|
| Comentarios			|		|

<br>

| RNF-16				| Aspectos del cálculo del itinerario		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Los cálculos internos de la aplicación deberán de usar los métodos y algoritmos adecuados para obtener las rutas más óptimas y eficientes posibles.		|
| Comentarios			|		|

<br>

| RI-07                    | Paradas             |
| :---                     | :---                |
| Requisitos asiciados     |   CU-12, CU-13, CU-22                  |
| Descripción              | El sistema deberá almacenar información sobre las paradas.         |
| Datos específicos        | idParada : Int <br> direccion_postal : String <br> codigo_municipio : String <br> coordenadas : String <br> imagen : String |
| Comentarios              | Ninguno.            |

<br>

| RI-08                    | Lineas             |
| :---                     | :---               |
| Requisitos asiciados     |  CU-22                  |
| Descripción              | El sistema deberá almacenar información sobre las líneas.        |
| Datos específicos        | descripcion : String <br> idLinea : String <br> idParada_comienzo : Int <br> idParada_fin : Int <br> idEmpresa_encargada : Int |
| Comentarios              | Ninguno.           |

<br>

| RI-09                    | Itinerario_linea             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-20, CU-21, CU-22               |
| Descripción              |  El sistema deberá almacenar información sobre los itinerarios.  |
| Datos específicos        |  idLinea : String <br> idParada : Int <br> numero_orden : Int <br> tipo_parada : String <br> horas_de_paso : String |
| Comentarios              | Ninguno.    |

<br>

| RI-10                    | Tarifas             |
| :---                     | :---                           |
| Requisitos asiciados     | CU-21                |
| Descripción              | El sistema deberá almacenar información sobre las tarifas. |
| Datos específicos        | idTarifas: Int <br> precio : Float <br> idLinea : String |
| Comentarios              | Ninguno.           |

<br>

| RI-11                    | Empresas             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-20, CU-21                 |
| Descripción              | El sistema deberá almacenar información sobre las empresas.        |
| Datos específicos        | idEmpresa : Int <br> nombre : String |
| Comentarios              | Ninguno.           |

<br>

| RI-12                    | Incidencias             |
| :---                     | :---                           |
| Requisitos asiciados     |  CU-20, CU-21                 |
| Descripción              | El sistema deberá almacenar información sobre las incidencias. |
| Datos específicos        | idIncidencia : Int <br> idLinea : String <br> incidencia : String |
| Comentarios              | Ninguno.   |

<br>

| RI-13                    | Interes             |
| :---                     | :---                           |
| Requisitos asiciados     | CU-21                |
| Descripción              | El sistema deberá almacenar información sobre los puntos de interés. |
| Datos específicos        | idInteres : Int <br> descripcion : String <br> coordenadas : String <br> imagen : String |
| Comentarios              | Registra los puntos de interés culturales y eventos |



### C. Servicios continuos

| RNF-01				| Alojamiento y puesta en marcha de las aplicaciones		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	| RNF-06 - foro		|
| Descripción			| El alojamiento y puesta en  marcha de las aplicaciones se producirá en el servidor de publicación seleccionado, en la plataforma donde permanecerán alojadas hasta el fin del contrato		|
| Comentarios			| Se incluirá la instalación sobre la plataforma, HelpDesk para la atención de incidencias sobre la explotación de este entorno, operación de sistemas en modo remoto, y administración y mantenimiento del sistema en modo remoto	|

<br>

| RNF-02				| Disposición y mantenimiento de un dominio para su publicación		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	| RNF-06		|
| Descripción			| Todas las tareas de mantenimiento correctivo de las aplicaciones asegurarán su correcto mantenimiento durante el período del proyecto.		|
| Comentarios			|		|

<br>

| RNF-03				| Mantenimiento integral de las aplicaciones desarrolladas para la AUTGC		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Mantenimiento preventivo, correctivo y evolutivo aplicable al desarrollo de software objeto del contrato durante un perdio de años. El servicio de atención integral se proporcionará por vía telefónica, presencial y e-mail. El servicio de mantenimiento se atenderá, al menos, en horario local de 8 a 20 horas de lunes a jueves y en horario de 8 a 15 horas los viernes.|
| Comentarios			|		|

<br>

| RNF-04				| Las aplicaciones a desarrollar se alimentarán de otras herramientas software de la AUTGC		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Las aplicaciones a desarrollar se alimentarán de otras herramientas software de la AUTGC, por tanto, y con el objeto de facilitar esta cooperación, se deberán utilizar modelos, especificaciones, protocolos y herramientas compatibles las otras herramientas de la AUTGC existentes en el momento de la adjudicación y preferentemente empleando modelos de datos de acuerdo con los estándares definidos por el CEN.|
| Comentarios			|		|

<br>

| RNF-05				| Integrción de otros subsistemas de la AUTGC	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se integrarán otros subsistemas de la AUTGC como el módulo de gestión de la Tarjeta de Pago Única, la pasarela de pago (web), módulos de datos provenientes de los operadores de transportes (SAE, viajeros, ...), y otros software de gestión del transportes y coordinación de los servicios.		|
| Comentarios			|		|

<br>

| RNF-06				| Plataforma desarrollada proveerá de un cliente estándar de conexión a web services		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La plataforma desarrollada proveerá de un cliente estándar de conexión a web services que permitan conectarse con las aplicaciones que soportan ese mismo protocolo de conexión. |
| Comentarios			| Quedando fuera de este proyecto la adaptación de otras aplicaciones que existan en la AUTGC y que no cumplan dicho estándar.	|

<br>

| RNF-07				| Software permeable	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El software deberá ser permeable y permitir la integración en el Sistema General mediante servicios web o herramientas similares de tecnología avanzada y a ser posible abierta y no propietaria. 	|
| Comentarios			|		|

<br>

| RNF-08				| Funcionamiento de los sistemas de información		|
| :---					| :--  	|
| Objetivos asociados	| OBJ-02		|
| Requisitos asociados	|		|
| Descripción			| Los datos necesarios para el funcionamiento de los sistemas de información serán recogidos de las bases de datos de las empresas prestatarias de los servicios de transportes, y de la AUT, que son bases de datos relacionales. |
| Comentarios			|		|

<br>

| RNF-09				| Propiedades del software		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El software deberá tener una arquitectura modular y escalable, de manera que se puedan poner en marcha las distintas funcionalidades a medidas que vayan siendo comprobadas y validas, permitiendo además las futuras ampliaciones que fuesen necesarias. 	|
| Comentarios			|		|

<br>

| RNF-10				| Representación de la red de transporte	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La representación de la red de transporte deberá formar parte de un sistema de información geográfica. Esta información deberá incluir la posición geográfica (latitud, longitud y altura) de los nodos de dicha red, los recorridos de los vehículos, carreteras de la isla y planos de núcleos urbanos, fotografías de sitios de interés turístico, ocio, cultura, paradas y estaciones, etc.		|
| Comentarios			|		|

<br>

| RNF-11				| Integración en el SIIT	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La AUTGC colaborará con el licitador en la provisión de la información georeferenciada que el licitador debe integrar en el SIIT, siendo el licitador el responsable de recopilar, revisar y poner a punto la misma con el mayor grado de exactitud posible.		|
| Comentarios			|		|

<br>

| RNF-12				| Contenidos y servicios orientados al usuario final	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Los contenidos y servicios orientados al usuario final deberán ser accesibles desde distintos puntos de información habilitados para ello por la AUT en estaciones, intercambiadores, paradas preferentes, etc., dichos Puntos de información los proveerá debidamente configurados la AUTGC.	|
| Comentarios			|		|

<br>

| RNF-13				| Contenidos y servicios orientados al usuario final	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Los contenidos y servicios orientados al usuario final deberán ser accesibles desde cualquier punto en donde los usuarios dispongan de acceso a Internet haciendo uso tanto de dispositivos móviles (ordenadores portátiles, teléfonos móviles, PDAs, etc.) 	|
| Comentarios		   |		|

<br>

| RNF-14				| Las aplicaciones deberán ajustarse a las recomendaciones del W3C		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Todas las aplicaciones deberán ajustarse a las recomendaciones aportadas por el W3C, donde se recogen las pautas de accesibilidad al contenido WEB, versión 1.0		|
| Comentarios			|		|

<br>

| RNF-15				| Cumplimiento del nivel de conformidad AA	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se exige el cumplimiento del nivel de conformidad AA, desestimándose la opción de crear un sitio Web en paralelo con contenidos formateados en texto plano, al considerarse ésta una solución no inclusiva y no integradora.	|
| Comentarios			|		|ok

<br>

| RNF-16				| Sistema de monitorización visible		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá ser visible en cualquier plataforma, sistema operativo y navegador de Internet, sin necesidad de descargar ningún complemento externo. Si esto fuera necesario, deberá de confeccionarse un apartado de descargas actualizado, desde el cual proceder a realizar la descarga de dicho software. No se empleará flash, shockwave u otro formato gráfico propietario en el desarrollo y publicación de la web. 	|
| Comentarios			|		|

<br>

| RNF-17				| Navegación entre todos los componentes	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá tener navegación entre todos los componentes deberá de ser rápida, sencilla y estructurada temáticamente hablando.	|
| Comentarios			|		|

<br>

| RNF-18				| Herramientas o elementos de navegación	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá tener herramientas o elementos de navegación comunes fácilmente accesibles desde todas las pantallas.	|
| Comentarios			|		|

<br>

| RNF-19				| Elementos de navegación	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá incorporar elementos de navegación que permitan saber en cada momento en que nivel del árbol de información se encuentra el usuario. 	|
| Comentarios			|		|

<br>

| RNF-20				| Páginas del sistema de monitorización	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá tener páginas que podrán contener elementos multimedia y mostrar resultados de consultas a bases de Datos, para mostrar resultados de forma dinámica.	|
| Comentarios			|		|

<br>

| RNF-21				| Portal del sistema de monitorización	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación deberá tener el portal visible, con una velocidad de presentación razonable en aquellas páginas que sean dinámicas. 	|
| Comentarios			|		|

<br>

| RNF-22				| Software de desarrollo y administración multiplataforma	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| En la interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación el software de desarrollo y administración de la Web deberá de poder manejarse desde cualquier plataforma. 	|
| Comentarios			|		|

<br>

| RNF-23				| Software preparado para dispositivos Web 	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| En la interfaz del sitio y de las partes accesibles del sistema de monitorización de la explotación el software estará preparado para permitir el uso de cualquier dispositivo Web especialmente para el uso de pantalla táctil, sin modificar el código.	 	|
| Comentarios			|		|

<br>

| RNF-24				| Normativa LOPD	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se deberá cumplir lo dispuesto por la LOPD, en cuanto a normas de protección de datos de carácter personal, así como la legislación aplicable en materia de publicación y comunicación de información en Internet.	 	|
| Comentarios			|		|

<br>

| RNF-25				| Mecanismos y medidas de seguridad		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se deberán incorporar mecanismos y medidas de seguridad con el objeto de garantizar la seguridad de las transacciones que se puedan realizar y para dar una imagen de seguridad y tecnología avanzada al sitio. 	|
| Comentarios			| El pago de los certificados u otros medios de protección privados correrá por cuenta del desarrollador durante el período de desarrollo del contrato. A partir del fin del proyecto, se negociará el mantenimiento de este punto.		|

<br>

| RNF-26				| Posicionamiento en buscadores	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La página Web resultante deberá estar preparada para facilitar el posicionamiento natural en los principales buscadores de ámbito nacional e internacional para ello se deberán emplear las técnicas apropiadas. |
| Comentarios			|		|

<br>

| RNF-27				| Idiomas	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El portal deberá contener al menos ediciones en inglés, alemán, francés y español. La edición en español debe de ofrecer la posibilidad de clonar de forma sencilla la página para la traducción a otros de los idiomas contemplados en el sitio. Todas las ediciones en los distintos idiomas deberán tener las mismas funcionalidades y gestionarse del mismo modo. El sistema resultante de este proyecto deberá permitir la fácil creación, adaptación y gestión de ediciones adicionales en otros idiomas. 	|
| Comentarios			|		|

<br>

| RNF-28				| Comercio electrónico	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema deberá permitir la ejecución de programas de autentificación de usuarios, sistemas de pago y de comercio electrónico, en particular deberá contemplar todos los subsistemas, interfaces, desarrollos e implementaciones necesarias para permitir la recarga, consulta, y cualquier operación relativa al titulo único del transporte de Gran Canaria. 		|
| Comentarios			|		|

<br>

| RNF-29				| Contenidos publicitarios 	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La propuesta deberá contemplar la posibilidad de incluir espacios publicitarios, como banners u otros soportes publicitarios de promoción. 		|
| Comentarios			|		|

<br>

| RNF-30				| Información general sobre el servicio público de transporte de viajeros	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se mostrará la información básica en el ámbito del transporte regular, es decir, operadores que prestan el servicio, líneas, horarios, recorridos, paradas, tarifas, tipos de bonos y descuentos, etc. Existirá la posibilidad de mostrar una foto de cualquiera de las paradas que integran el recorrido y que sea seleccionada por el usuario, incluso debe poderse simular el recorrido mediante la visualización de las paradas o puntos de interés por los que discurra el recorrido, indicando la hora prevista de paso así como los posibles lugares de interés o transbordos que se deban realizar. La consulta de información se realizará por distintos criterios (municipios, barrio o zona, paradas, empresa, etc.)	|
| Comentarios			|		|

<br>

| RNF-31				| Consultas origen-destino 	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema deberá informar de cómo ir de un punto origen de la red de transporte a otro destino de la red de transporte. Para ello, el usuario introducirá en el sistema el origen y el destino del viaje que quiere realizar, pudiendo para ello seleccionarlos a través de distintas búsquedas (por municipios, barrio o zona, paradas, etc.). El usuario tendrá la opción de plantear la consulta seleccionando el criterio de búsqueda que desee (tiempo de viaje, precio, número de transbordos, parada, intervalo horario de salida). Como resultado el sistema proporcionará la información de la mejor óptima a la búsqueda planteada.	|
| Comentarios			|		|

<br>

| RNF-32				| Información proporcionada por las consultas		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La solución de las consultas deben proporcionar el identificador de la solución, precio, número de estapas con la información de cada una (línea, parada, código, hora estimada de llegada, ...)	|
| Comentarios			|		|

<br>

| RNF-33				| Opcionalidades de la consulta	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema ofrecerá la opción de imprimir toda la información obtenida como resultado, y también de simular el recorrido, en cuanto a los eventos que lo componen y las operaciones a realizar presentando a su vez las fotos que correspondan a las paradas y lugares de interés relacionados con el recorrido de manera similar a la simulación que ofrecen los navegadores basados en GPS. 	|
| Comentarios			|		|

<br>

| RNF-34				| Información de horarios de paso de vehículos por puntos de la red de transporte 	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Dada un punto de la red de transporte (una parada o punto relevante de la red de transporte) se deberá mostrar información relativa a la planificación de los vehículos que pueden pasar por este punto. La información a mostrar debe contemplar la línea, parada inicial, hora de inicio de la expedición, parada final, hora estimada de llegada a la parada final y observaciones.	|
| Comentarios			|		|

<br>

| RNF-35				| Información de interés turístico	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se mostrará la información de interés turístico, como por ejemplo, información sobre los distintos municipios (localización, qué visitar, etc.), las principales playas, naturaleza (miradores, paisajes relevantes, etc.), fiestas populares (fechas, lugar de celebración), gastronomía, puntos de información turísticas y patrimonio artístico, arquitectónico y arqueológico. Además, se informará de rutas con interés turístico con posibilidad de ser realizadas en transporte regular de viajeros. 		|
| Comentarios			| La AUTGC facilitará el acuerdo de cesión de esta información por parte de otros organismos de la administración, siendo el licitante el responsable de recabarla coordinarla y adecuarla a la imagen y alcance del proyecto. 		|

<br>

| RNF-36				| Información de lugares de interés general		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema proporcionará información sobre lugares de interés general de toda la Isla, como por ejemplo: centros sanitarios, centros de seguridad y emergencias, centros de la administraciones públicas, centros culturales, lugares de ocio, etc. Además, se informará de los servicios de transporte público que pueden utilizarse para llegar a ellos. 	|
| Comentarios			| La AUTGC facilitará el acuerdo de cesión de esta información por parte de otros organismos de la administración, siendo el licitante el responsable de recabarla coordinarla y adecuarla a la imagen y alcance del proyecto. 		|

<br>

| RNF-37				| Agenda cultural y de ocio	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se mostrará información sobre la agenda cultural y de ocio de los principales teatros, auditorios, salas de exposiciones, así como de los eventos que se celebren en la Isla relacionados con la cultura y el ocio.	|
| Comentarios			| La AUTGC facilitará el acuerdo de cesión de esta información por parte de otros organismos de la administración, siendo el licitante el responsable de recabarla coordinarla y adecuarla a la imagen y alcance del proyecto. |

<br>

| RNF-38				| Información corporativa 		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se mostrará información sobre la Autoridad Única del Transporte de Gran Canaria y sobre el sistema de transporte público regular de viajeros en la isla. 		|
| Comentarios			| Esta información será facilitada por la AUTGC.		|

<br>

| RNF-39				| El sistema posibilitará de manera segura la recarga de la tarjeta única de pago de la AUTGC, mediante pasarela multibanco.		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema posibilitará de manera segura la recarga de la tarjeta única de pago de la AUTGC, mediante pasarela multibanco.	|
| Comentarios			|		|

<br>

| RNF-40				| Descarga de archivo		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El sistema deberá proporcionar la funcionalidad de descargar archivos que contengan aplicaciones y datos asociados a servicios que la AUT pudiera proporcionar.		|
| Comentarios			|		|

<br>

| RNF-41				| Actualización de contenidos	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El software se desarrollará de forma que permita una actualización o modificación sencilla y rápida de los datos del sistema, tanto de los relacionados con la prestación del servicio de transporte como de los vinculados a turismo y cultura.	|
| Comentarios			|		|

<br>

| RNF-42				| Información geográfica	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La información sobre puntos de la red de transporte será ubicada sobre cartografía utilizandolas coordenadas que para ello suministren las empresas prestatarias de los servicios de transporte y que deberá ser revisada unificada y depurada por el licitador. El software permitirá asociar a cada parada ubicada sobre la cartografía datos de interés para la AUT como para los usuarios, permitiendo consultar dichos datos "pinchando" sobre la cartografía o elaborando consultas con múltiples criterios pero acotados para optimizar el tiempo de respuesta (ejemplo: paradas de la línea 1, paradas de la línea 1 con marquesinas en el municipio de Mogán, horarios de paso de la línea 1 y 2, etc.). 	|
| Comentarios			|		|

<br>

| RNF-43				| Otras utilidades asociadas a la cartografía	|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| El software permitirá asociar a cada parada ubicada sobre la cartografía datos de interés para la AUT como para los usuarios, permitiendomostrar una foto de la parada seleccionada, seleccionar sobre la cartografía las paradas necesarias para la ejecución de las consultas de origen-destino, mostrar plano de recorrido del servicio consultado, y simular el recorrido consultado en estilo similar a los navegadores GPS. 	|
| Comentarios			|		|

<br>

| RNF-44				| Garantías Software		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se deberá garantizar por dos años el software, a contar desde la fecha de recepción del proyecto en su totalidad, obligándose a realizar durante dicho período los cambios necesarios para solventar las deficiencias detectadas imputables a la empresa desarrolladora si así lo solicita la AUT. Dicha garantía incluirá la subsanación de errores o fallos ocultos que se pongan de manifiesto en el funcionamiento de las aplicaciones, o que se descubran mediante pruebas o cualesquiera otros medios, así como la conclusión de la documentación incompleta y subsanación de la que contenga deficiencias. 	|
| Comentarios			| El tiempo de respuesta ante una solicitud de asistencia por fallo será como máximo de 24 horas. 		|

<br>

| RNF-45				|Software y licencias 		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| Se deberá entregar todas aquellas herramientas, licencias software y códigos fuente que sean necesarios para la generación y depuración de nuevas versiones de los distintos aplicativos, permitiendo la realización de modificaciones y mejoras por personal de la AUT hasta la finalización del contrato.		|
| Comentarios			|		|

<br>

| RNF-46				|Implantación del sistema 		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	|		|
| Descripción			| La instalación del software se realizará en los servidores que sean necesarios y en los equipos de los distintos puntos de información que la AUT decida instalar (hasta un máximo de 20 puntos), así corno la carga de todo tipo de datos (servicios de transporte, turísticos, culturales, etc.) que deban ser utilizados por el sistema.	|
| Comentarios			|		|

<br>

| RNF-47				|Mantenimiento del software		|
| :---					| :--  	|
| Objetivos asociados	|		|
| Requisitos asociados	| 		|
| Descripción			| Se desarrollará y ejecutará un plan de mantenimiento que garantice el perfecto direccionamiento del sistema de información (software, hardware, comunicaciones, etc.). 	|
| Comentarios			| Dentro del plan de mantenimiento se incluye las labores vinculadas a la renovación tecnológica (migraciones motivadas por la aparición de nuevas versiones, adaptación a nuevos lenguajes, utilización de nuevo hardware)|
 
<br>

| RI-14                    | Usuarios             |
| :---                     | :---                           |
| Requisitos asiciados     |               |
| Descripción              | El sistema deberá almacenar información correspondiente a las personas autenticadas que usan el sistema.         |
| Datos específicos        | idUsuario : String <br> contraseña : String <br> rol : Int <br> nombre_completo : String <br> email : String <br> idioma_deseado : String.  |
| Comentarios              | |

<br>

| RI-15                    | Paradas             |
| :---                     | :---                |
| Requisitos asiciados     |                     |
| Descripción              | El sistema deberá almacenar información sobre las paradas.         |
| Datos específicos        | idParada : Int <br> direccion_postal : String <br> codigo_municipio : String <br> coordenadas : String <br> imagen : String <br> incidencia_parada : String |
| Comentarios              | Ninguno.            |

<br>

| RI-16                    | Lineas             |
| :---                     | :---               |
| Requisitos asiciados     |                    |
| Descripción              | El sistema deberá almacenar información sobre las líneas.        |
| Datos específicos        | descripcion : String <br> idLinea : String <br> idParada_comienzo : Int <br> idParada_fin : Int <br> idEmpresa_encargada : Int <br> suspendida_cortada : Int |
| Comentarios              | Ninguno.           |

<br>

| RI-17                    | Itinerario_linea             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              |  El sistema deberá almacenar información sobre los itinerarios.  |
| Datos específicos        |  idLinea : String <br> idParada : Int <br> numero_orden : Int <br> tipo_parada : String <br> horas_de_paso : String |
| Comentarios              | Ninguno.    |

<br>

| RI-18                    | Tarifas             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              | El sistema deberá almacenar información sobre las tarifas. |
| Datos específicos        | idTarifas: Int <br> precio : Float <br> idLinea : String |
| Comentarios              | Ninguno.           |

<br>

| RI-19                    | Empresas             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              | El sistema deberá almacenar información sobre las empresas.        |
| Datos específicos        | idEmpresa : Int <br> nombre : String |
| Comentarios              | Ninguno.           |

<br>

| RI-20                    | Incidencias             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              | El sistema deberá almacenar información sobre las incidencias. |
| Datos específicos        | idIncidencia : Int <br> idLinea : String <br> incidencia : String <br> idUsuario : String <br> fecha_incidencia : String |
| Comentarios              | Ninguno.   |

<br>

| RI-21                    | Interes             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              | El sistema deberá almacenar información sobre los puntos de interés. |
| Datos específicos        | idInteres : Int <br> descripcion : String <br> coordenadas : String <br> imagen : String <br> titulo : String |
| Comentarios              | Registra los puntos de interés culturales y eventos |

<br>

| RI-22                    | Evento_visualizado_usuario             |
| :---                     | :---                           |
| Requisitos asiciados     |                  |
| Descripción              | El sistema deberá almacenar información sobre los eventos visualizados. |
| Datos específicos        | idInteres : Int <br> idUsuario : String |
| Comentarios              |  |

<br>

| RI-23                    | Bono             |
| :---                     | :---                           |
| Requisitos asiciados     | RNF-30                 |
| Descripción              | El sistema deberá almacenar información sobre los bonos comprados por cada usuario. |
| Datos específicos        | idBono : Int <br> descripcion : String <br> precio : Float <br> linea : Int <br> fecha : String <br> idUsuario : String |
| Comentarios              |  |


## 4.2. Casos de uso.

<br>

### 4.2.1. Lista de diagramas de casos de uso del modelo.

| Código    			| Nombre	|
| :---					| :--  	|
| DCU-01				| Diagrama del Portal del SIIT	|
| DCU-02				| Diagrama de Sistema de información del SIIT	|
| DCU-03				| Diagrama del SMET	|

<br>

### 4.2.2. Diagramas de casos de uso.

<br>

<div align="center">
    <img src="./../out/lab0/src/portal/Portal.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 4. DCU-01.</p></i>
</div>

<br>

<div align="center">
    <img src="./../out/lab0/src/SIIT/SIIT.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 5. DCU-02.</p></i>
</div>

<br>

<div align="center">
    <img src="./../out/lab0/src/SMET/SMET.svg" style="border: 3px solid #bbb">
    <i><p>Imagen 6. DCU-03.</p></i>
</div>

<br>

### 4.2.3. Lista general de casos de uso  y actores del proyecto.

<br>

Lista de casos de uso 

<br>

| Código			| Caso de uso 	| Descripción       |
| :---				| :--       	| :--               |
| CU-01				| Utilizar editor WYSIWYG	| El usuario podrá editar la Web haciendo uso del editor WYSIWYG            |
| CU-02             | Modificar Web   | El usuario puedrá modificar la Web   |
| CU-03             | Administrar contenido |El usuario accede a la sección de la administración del contenido|
| CU-04 | Modificar diseño de una página| El usuario puede alterar de forma sencilla el diseño común a varias páginas que se muestran o incluso de la Web entera|
| CU-05 | Utilizar espacio compartido | El usuario podrá hacer uso del entorno de colaboración de espacio compartido |
| CU-06| Visualizar estadísticas de acceso| El usuario podrá consultar las estadísticas de acceso a las distintas secciones y servicios|
| CU-07| Crear nueva página | El usuario podrá crear nuevas páginas de forma sencilla y coherente con el resto de la Web|
| CU-08 | Previsualizar página | El usuario podrá visualizar la versión final de los cambios realizados antes de ser publicados|
| CU-09| Buscar | El usuario podrá buscar distintos contenidos en la Web | 
| CU-10 | Elegir idioma | El usuario podrá cambiar el idioma del sistema entre los que estén permitidos|
| CU-11| Usar herramientas Web 2.0 | El usuario podrá hacer uso de las herramientas Web 2.0 desarrolladas |
| CU-12  | Ver horario y lineas| El usuario podrá consultar las líneas disponibles y el horario de cada línea |
| CU-13| Ver horario y lineas (vista Administrador) | El usuario podrá consultar las líneas disponibles y el horario de cada línea|
| CU-14|Modificar datos| El usuario podrá modificar los datos registrados en el sistema|
| CU-15| Introducir datos | El usuario podrá agregar nuevos registros al sistema	  |
| CU-16 | Introducir fecha y hora| El usuario podrá introducir la fecha y hora de viaje deseado |
| CU-17| Introducir potenciador| El usuario podrá filtrar una consulta en función de un potenciador|
| CU-18 | Seleccionar origen y destino | El usuario podrá seleccionar el origen y destino de la consulta |
| CU-19 | Usar mapa | El usuario podrá usar el mapa para registrar el punto de origen/destino |
| CU-20 | Ver resultado | El usuario podrá visualizar los datos de una solución de un itinerario |
| CU-21  | Realizar consulta   | El usuario podrá realizar una consulta del trayecto   |
| CU-22  | Ver información cartográfica   | El usuario podrá visualizar un mapa con todos los datos registrados    |
| CU-23  | Obtener ayuda en linea   | El usuario podrá recibir ayuda en líena adaptada  |
| CU-24  | Generar alarmas  | El sistema genera una alarma que será recibida por otro usuario para notificarlo de algo   |
| CU-25  | Ver advertencias   | El operador de transporte puede ver la lista de advertencias de las rutas  |
| CU-26  | Ver eventos  | El usuario puede ver la lista de eventos disponibles  |
| CU-27  | Ver alarma  | El usuario recibe una alarma informándole de un suceso o evento concreto relevante   |
| CU-28  | Ver alarmas (vista Usuario Logueado)  | El usuario recibe una alarma informándole de un suceso o evento concreto relevante  |
| CU-29  | Ver alarmas (vista Operador de transporte)  | El usuario recibe una alarma informándole de un suceso o evento concreto relevante  |
| CU-30  | Ver alarmas (vista Operador adjudicatario)  | El usuario recibe una alarma informándole de un suceso o evento concreto relevante.  |
| CU-31   | Registrar situaciones puntuales  | El usuario podrá registrar sitaciones puntuales  |
| CU-32  | Definir evento  | El usuario podrá definir nuevos eventos  |
| CU-33  | Proveer datos   | El usuario podrá introducir nuevos datos en el sistema  |
| CU-34  | Crear advertencia | El usuario podrá crear una advertencia dirigida a los operadores de transporte  |
| CU-35  | Registrar periodos continuos de tiempo  | El usuario podrá registrar un intervalo de tiempo  |
| CU-36  | Examinar el estado de la explotación en tiempo real  | El usuario podrá examinar el estado de la explotación en tiempo real para cada operador  |
| CU-37  | Examinar el estado de la explotación en tiempo real (vista Operador adjudicatorio)  | El usuario podrá examinar el estado la explotación en tiempo real  |
| CU-38  | Crear conjunto de operadores  | El usuario podrá crear un conjunto de operadores para examinar el estado de explotación en tiempo real  |

<br>

Lista de actores 

<br>

| Actor			        | Descripción	|
| :---					| :--  	|
| Administrador			| Usuario con todos los permisos disponibles para gestionar la aplicación. Debe identificarse en el sistema utilizando unas credenciales especiales proporcionadas por la autoridad correspondiente para poseer dichas funcionalidades 		|
| Usuario logueado      | Usuario con permisos de lectura y edición que puede alterar el contenido de la aplicación de manera controlada. Debe de identificarse utilizando las credenciales que previamente creó al registrarse en el sistema por primera vez                  |
| Usuario no logueado    | Usuario con permisos solo de lectura, vista como invitado de la aplicación pero sin poder añadir contenido a la misma. Puede identificarse en el sistema para acceder a los permisos de Administrador o de Usuario Logueado dependiendo de las credenciales que utilice. 
| Usuario | Actor abstracto que representa las funcionalidades tanto del usuario logueado como del usuario no logueado             |
| Sistema  | Sistema encargado de generar las alarmas que reciben los demás usuarios  | 
| Operador de transporte  | Usuario con permisos de operación en los  transportes de la AUGT, Autoridad Única de Transporte de Gran Canaria  | 
| Operador adjudicatario  | Usuario con permisos de administración del SMET, Sistema de Monitorización de la Explotación del Transporte  | 

<br>

### 4.2.4. Detalle de los casos de uso.

<br>

### Casos de uso del portal.

<br>

| Identificar			| CU-01	|
| :---					| :--  	|
| Nombre				| Utilizar editor WYSIWYG		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá editar la Web haciendo uso del editor WYSIWYG  		|
| Actores				| Administrador		|
| Precondiciones		| El usuario debe haber seleccionado la opción de editar la Web	|
| Flujo normal			| 1. El sistema muestra la interfaz y las opciones del editor WYSIWYG. <br> 2. El usuario utiliza el editor WYSIWYG para editar la Web.		|
| Flujo alternativo		| 2A. El usuario cancela la edición de la Web. 	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| WYSIWYG (What You See Is What You Get) quiere decir que el editor mostrará siempre la versión final del documento editado sin necesitar de previsualizar.		|

<br>

| Identificar			| CU-02	|
| :---					| :--  	|
| Nombre				| Modificar Web		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario puedrá modificar la Web  			|
| Actores				| Administrador		|
| Precondiciones		| El usuario debe estar identificado como Administrador en el sistema.		|
| Flujo normal			| 1. El usuario solicita la opción de editar la Web. <br> 2. El sistema permite al usuario la edición a través del editor WYSIWYG <br> 3. El usuario hace uso del editor WYSIWYG para modificar la Web. <br> 4. El usuario guarda los cambios realizados. |
| Flujo alternativo		| 3A. El usuario cancela la edición de la Web. <br> 4A. El usuario descarta los cambios realizados.		|
| Poscondiciones		| Los cambios realizados se guardan en la base de datos.	|
| Comentarios			| -		|

<br>

| Identificar			| CU-03	|
| :---					| :--  	|
| Nombre				| Administrar contenido		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario accede a la sección de la administración del contenido.		|
| Actores				| Administrador		|
| Precondiciones		| El usuario está identificado como Administrador.		|
| Flujo normal			| 1. El usuario selecciona la función de administrar el contenido de una página. <br> 2. El sistema muestra la interfaz y lista las opciones a realizar. <br> 3. El usuario selecciona la opción deseada. <br> 4. El usuario guarda los cambios realizados.                          	|
| Flujo alternativo		| 3A. El usuario selecciona la opción para publicar contenido. <br>  3B. El usuario selecciona la opción de eliminar contenido. <br> 3C. El usuario selecciona la opción para modificar el contenido. <br> 3D. El usuario cancela la administración de contenidos. <br> 4A. El usuario descarta los cambios realizados.	|
| Poscondiciones		| La base de datos es actualizada con los cambios realizados.  |
| Comentarios			| -		|

<br>

| Identificar			| CU-04	|
| :---					| :--  	|
| Nombre				| Modificar diseño de una página		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario puede alterar de forma sencilla el diseño común a varias páginas que se muestran o incluso de la Web entera.		|
| Actores				| Administrador		|
| Precondiciones		| El usuario está identificado como Administrador.		|
| Flujo normal			| 1. El usuario accede a la sección para modificar el diseño. <br> 2. El sistema muestra la interfaz de diseño con las respectivas herramientas para modificarlo. <br> 3. El usuario realiza los cambios en el diseño de las páginas. <br> 4. El usuario guarda los cambios. <br> 5. El sistema registra las páginas que han sido modificadas. El proceso termina. 	    |
| Flujo alternativo		| 4A. El usuario descarta los cambios realizados.  		|
| Poscondiciones		| El diseño común entre una o varias páginas ha sido alterado. Se registra qué administrador modificó las páginas, así como la hora.	|
| Comentarios			| El paso 5. garantiza el control de consistencia de los datos.		|

<br>

| Identificar			| CU-05	|
| :---					| :--  	|
| Nombre				| Utilizar espacio compartido		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá hacer uso del entorno de colaboración de espacio compartido.	|
| Actores				| Administrador		|
| Precondiciones		| El usuario está identificado como Administrador. 		|
| Flujo normal			| 1. El usuario accede a la opción para utilizar el espacio compartido. <br> 2. El sistema despliega la interfaz y muestra los demás usuarios que están conectados al espacio compartido. <br> 3. El usuario puede comunicarse con los usuarios mediante mensajes de texto.		|
| Flujo alternativo		| - 		|
| Poscondiciones		| Ninguna.		|
| Comentarios			| AUT significa Autoridad Única de Transporte.		|

<br>

| Identificar			| CU-06	|
| :---					| :--  	|
| Nombre				| Visualizar estadísticas de acceso		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá consultar las estadísticas de acceso a las distintas secciones y servicios.		|
| Actores				| Administrador		|
| Precondiciones		| El usuario debe de estar identificado como administrador.		|
| Flujo normal			| 1. El usuario seleccionará el apartado del portal para acceder a las estadísticas. <br> 2. El sistema consultará el número de visitas registrado, su procedencia geográfica y las consultas realizadas en la Web  <br> 3. El sistema mostrará por pantalla las estadísticas mediante dos gráficos de barras.		|
| Flujo alternativo		| 3. Si no hay visitas, el sistema mostrará un mensaje. |
| Poscondiciones		| Ninguna.		|
| Comentarios			| 	    |

<br>

| Identificar			| CU-07	|
| :---					| :--  	|
| Nombre				| Crear nueva página		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá crear nuevas páginas de forma sencilla y coherente con el resto de la Web.		|
| Actores				| Usuario Logueado, Administrador	    |
| Precondiciones		| El usuario está identificado.		|
| Flujo normal			| 1. El usuario seleccionará la sección para crear una nueva página. <br> 2. El sistema mostrará la interfaz con sus respectivas herramientas para la creación de la página web. <br> 3. El usuario utilizará las herramientas para crear la nueva página. <br> 4. El sistema mostrará una previsualización de la página antes de la publicación de la misma. <br> 5. El usuario publica la nueva página definitivamente.      |
| Flujo alternativo		| 5A. El usuario descarta la publicación de la nueva página.		|
| Poscondiciones		| La nueva página ha sido incorporada a la Web y se han almacenado sus datos asociados en la base de datos.	|
| Comentarios			| Las herramientas para la creación de la nueva página deben de ser sencillas para usuarios que no tengan conocimiento de programación ni de HTML.		|

<br>

| Identificar			| CU-08	|
| :---					| :--  	|
| Nombre				| Previsualizar página		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá visualizar la versión final de los cambios realizados antes de ser publicados.		|
| Actores				| Usuario Logueado, Administrador		|
| Precondiciones		| El usuario está usando la función de crear una nueva página.		|
| Flujo normal			| 1. El sistema muestra una previsualización de la página con los añadidos por parte del usuario. <br> 2. El usuario puede seleccionar la opción para publicar la nueva página de manera definitiva o descartar la publicación.
| Flujo alternativo		| -		|
| Poscondiciones		| Ninguna.		|
| Comentarios			| -		|

<br>

| Identificar			| CU-09	|
| :---					| :--  	|
| Nombre				| Buscar		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá buscar distintos contenidos en la Web.		|
| Actores				| Usuario No Logueado, Usuario Logueado, Administrador		|
| Precondiciones		| Ninguna.		|
| Flujo normal			| 1. El usuario accede al buscador. <br> 2. El usuario busca escribe en el buscador el elemento que desea encontrar. <br>  3. El sistema consulta en sus datos para encontrar el elemento. <br> 4. El usuario recibe el elemento buscado.		|
| Flujo alternativo		| 4A. El elemento buscado no es encontrado.		|
| Poscondiciones		| Ninguna.		|
| Comentarios			| 		|

<br>

| Identificar			| CU-10	|
| :---					| :--  	|
| Nombre				| Elegir idioma		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá cambiar el idioma del sistema entre los que estén permitidos.		|
| Actores				| Usuario No Logueado, Usuario Logueado, Administrador		|
| Precondiciones		| Ninguna. 		|
| Flujo normal			| 1. El usuario accede a la opción para cambiar el idioma. <br> 2. El usuario selecciona el idioma deseado y lo aplica. <br> 3. El sistema cambia todos los textos al lenguaje indicado.	|
| Flujo alternativo		| 		|
| Poscondiciones		| El idioma de la aplicación ha sido cambiado.		|
| Comentarios			|		|

<br>

| Identificar			| CU-11	|
| :---					| :--  	|
| Nombre				| Usar herramientas Web 2.0		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá hacer uso de las herramientas Web 2.0 desarrolladas.		|
| Actores				| Usuario No Logueado, Usuario Logueado, Administrador		|
| Precondiciones		| Acceder al portal.		|
| Flujo normal			| 1. El usuario solicita entrar al foro. <br> 2. El sistema le redirige al foro.	|
| Flujo alternativo		| 1.A. El usuario solicita entrar al blog. <br> 2.A. El sistema le redirige al blog. <br> 1.B. El usuario solicita visualizar el cloud tag. <br> 2.B. El sistema recopila las palabras clave. <br> 3.B El sistema muestra el cloud tag.		|
| Poscondiciones		| Ninguna	|
| Comentarios			| Ninguno		|

<br>

### Casos de uso del diagrama de Sistema de la información del SIIT

| Identificar			| CU-12	|
| :---					| :--  	|
| Nombre				| Ver horario y lineas	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá consultar las líneas disponibles y el horario de cada línea.		|
| Actores				| Usuario		|
| Precondiciones		| El usuario tiene que acceder al sistema.	|
| Flujo normal			| 1. El usuario solicita consultar una línea <br> 2. El sistema solicita la línea al usuario.<br> 3. El usuario escoge una línea a consultar <br> 4. El sistema muestra el recorrido de la línea en un mapa <br> 5. El sistema proporciona la opción de conocer más detalles. <br> 6. El usuario solicita conocer más detalles de la línea. <br> 7. El sistema proporciona: descripción de la línea, empresa gestora, incidencias, tarifas y horarios. <br> 8. El proceso finaliza.	|
| Flujo alternativo		| 6. El usuario no solicita conocer más detalles. El proceso finaliza.		|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-13	|
| :---					| :--  	|
| Nombre				| Ver horario y lineas (vista Administrador)		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá consultar las líneas disponibles y el horario de cada línea.		|
| Actores				| Administrador		|
| Precondiciones		| El administrador está autenticado. |
| Flujo normal			| 1. El usuario solicita consultar una línea <br> 2. El sistema solicita la línea al usuario.<br> 3. El usuario escoge una línea a consultar <br> 4. El sistema muestra el recorrido de la línea en un mapa <br> 5. El sistema proporciona la opción de conocer más detalles. <br> 6. El usuario solicita conocer más detalles de la línea. <br> 7. El sistema proporciona: descripción de la línea, empresa gestora, incidencias, tarifas y horarios. <br> 8. El proceso finaliza.	|
| Flujo alternativo		| 6. El usuario no solicita conocer más detalles. El proceso finaliza.		|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-14	|
| :---					| :--  	|
| Nombre				| Modificar datos		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá modificar los datos registrados en el sistema.		|
| Actores				| Administrador		|
| Precondiciones		| El administrador está autenticado.	|
| Flujo normal			| 1. El usuario solicita modificar datos. <br> 2. El sistema solicita el dato a modificar. <br> 3. El usuario selecciona el dato a modificar. <br> 4. El sistema demanda el nuevo contenido. <br> 5. El usuario proporciona el contenido. <br> 6. El sistema actualiza el contenido. El proceso finaliza. 	|
| Flujo alternativo		|6. Si el contenido proporcionado no cumple con el mismo formato que el contenido a sustituir, el proceso finaliza.		|
| Poscondiciones		| Se ha actualizado el registro del dato modificado en la base de datos.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-15	|
| :---					| :--  	|
| Nombre				| Introducir datos		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá agregar nuevos registros al sistema.		|
| Actores				| Administrador		|
| Precondiciones		| El administrador está autenticado.	|
| Flujo normal			| 1. El usuario solicita agregar datos. <br> 2. El sistema solicita el tipo de dato a agregar. <br> 3. El usuario selecciona el tipo de dato a agregar. <br> 4. El sistema proporciona campos de texto para agregar la información. <br> 5. El usuario rellena los campos. <br> 6. El sistema agrega el contenido. 	|
| Flujo alternativo		|6. Si el contenido proporcionado no cumple con el formato que debe tener, el proceso finaliza.		|
| Poscondiciones		| Se ha actualizado el registro del dato modificado en la base de datos.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-16	|
| :---					| :--  	|
| Nombre				| Introducir fecha y hora		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá introducir la fecha y hora de viaje deseado.		|
| Actores				| Usuario		|
| Precondiciones		| El usuario está en el sistema.	|
| Flujo normal			| 1. El sistema solicita la fecha y hora. <br> 2. El usuario proporciona la fecha y hora. <br> 3. El sistema almacena la fecha y hora de forma temporal.	|
| Flujo alternativo		|	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-17	|
| :---					| :--  	|
| Nombre				| Introducir potenciador		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá filtrar una consulta en función de un potenciador.		|
| Actores				| Usuario		|
| Precondiciones		| El usuario está en el sistema.	|
| Flujo normal			| 1. El sistema solicita un potenciador. <br> 2. El usuario solicita potenciar por coste. <br> 3. El sistema almacena de forma temporal el potenciador.	|
| Flujo alternativo		| 2.A El usuario solicita potenciar por número de transboros.|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-18	|
| :---					| :--  	|
| Nombre				| Seleccionar origen y destino		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá seleccionar el origen y destino de la consulta.		|
| Actores				| Usuario		|
| Precondiciones		| El usuario está en el sistema.	|
| Flujo normal			| 1. El sistema solicita un punto de origen y destino. <br> 2. El sistema proporciona dos cuadros de texto. <br> 3. El usuario escribe en el cuadro de texto [calle y número / barrio o municipio] <br> 3. El sistema hace una traducción de la dirección proporcionada a una dirección cartografiada. <br> 4. La traducción es exitosa, el sistema registra el punto de origen y destino de forma temporal.	|
| Flujo alternativo		| 3.A. El usuario (no usa el cuadro de texto), selecciona una parada y la marca como punto de origen / destino. <br> 4.A. El sistema registra la parada como punto de origen / destino. <br> 3.B. El usuario selecciona un evento en el mapa y lo marca como punto de origen / destino. <br> 4.B. El sistema registra el evento como punto de origen / destino. <br> 4.C. La traducción no es exitosa, el sistema indica al usuario que revise las direcciones proporcionadas.	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| El origen y destino se pueden proporcionar de diversas formas: desde el mapa, escribiendo la dirección y desde una parada o evento.|

<br>

| Identificar			| CU-19	|
| :---					| :--  	|
| Nombre				| Usar mapa		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá usar el mapa para registrar el punto de origen/destino.		|
| Actores				| Usuario		|
| Precondiciones		| El usuario está en el sistema.	|
| Flujo normal			| 1. El usuario se desplaza por el mapa <br> 2. El sistema actualiza el mapa en función del desplazamiento. <br> 3. El usuario selecciona una parada y la marca como punto de origen / destino. <br> 4. El sistema registra la parada como punto de origen / destino.	|
| Flujo alternativo		| 3. El usuario selecciona un evento y lo marca como punto de origen / destino. <br> 4. El sistema registra el evento como punto de origen / destino. 	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno. |

<br>

| Identificar			| CU-20	|
| :---					| :--  	|
| Nombre				| Ver resultado		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá visualizar los datos de una solución de un itinerario.		|
| Actores				| Usuario		|
| Precondiciones		| El sistema ha realizado todos los cálculos necesarios, el usuario está en el sistema.	|
| Flujo normal			| 1. El sistema muestra la distancia entre paradas, los transbordos necesarios, el tiempo del recorrido total, los tramos a recorrer por el usuario y las zonas por las que no transitar. <br> 2. El sistema muestra la solución en forma esquemática. <br> 3. El usuario solicita ver más detalles <br> 4. El sistema muestra información adicional de las líneas: descripción, empresa gestora, incidencias, tarifas y horarios.	|
| Flujo alternativo		|  3.A. El usuario no solicita más detalles, el proceso finaliza.	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno. |

<br>

| Identificar			| CU-21	|
| :---					| :--  	|
| Nombre				| Realizar consulta		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá realizar una consulta del trayecto	|
| Actores				| Usuario		|
| Precondiciones		| El usuario está en el sistema.	|
| Flujo normal			| 1. El usuario solicita realizar una consulta. <br> 2. El sistema muestra un mapa de Gran Canaria con todos los datos cartografiados (eventos, paradas...). <br> 3. El sistema solicita los datos para realizar la consulta (fecha, hora, potenciador, punto de origen, punto de destino). <br> 4. El usuario proporciona los datos pedidos. <br> 6. El sistema hace una traducción de la dirección proporcionada a una dirección cartografiada. <br> 7. El sistema calcula la distancia entre paradas, los tiempos de recorrido, los tramos a recorrer por el usuario y define transbordos necesarios. <br> 8. El sistema identifica zonas por las que no transitar. <br> 9. El sistema muestra la distancia entre paradas, los transbordos necesarios, el tiempo del recorrido total, los tramos a recorrer por el usuario (itinerario recomendado) y las zonas por las que no transitar. <br> 10. El sistema muestra la solución en forma esquemática. <br> 11. El usuario solicita ver más detalles. <br> 12. El sistema muestra información adicional de las líneas: descripción, empresa gestora, incidencias, tarifas y horarios.
| Flujo alternativo		| 4A. El usuario solicita potenciar por número de transboros. <br> 4B. El usuario (no usa el cuadro de texto), selecciona una parada y la marca como punto de origen / destino. <br> 4C. El usuario selecciona un evento en el mapa y lo marca como punto de origen / destino. <br> 5A. El sistema registra el evento como punto de origen / destino. <br> 5B. La traducción no es exitosa, el sistema indica al usuario que revise las direcciones proporcionadas. <br> 9A. El usuario se desplaza por el mapa <br> 9B. El sistema actualiza el mapa en función del desplazamiento. <br> 9C. El usuario selecciona una parada y la marca como punto de origen / destino. <br> 10A. El sistema registra la parada como punto de origen / destino. <br> 10B. El usuario selecciona un evento y lo marca como punto de origen / destino. <br> 10C. El sistema registra el evento como punto de origen / destino. <br> 11A. El usuario no solicita más detalles, el proceso finaliza.	|
| Poscondiciones		| La consulta realizada se almacena en la base de datos.		|
| Comentarios			| Ninguno.		|

<br>

| Identificar			| CU-22	|
| :---					| :--  	|
| Nombre				| Ver información cartográfica		|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá visualizar un mapa con todos los datos registrados. 		|
| Actores				| Usuario		|
| Precondiciones		| Ninguna	|
| Flujo normal			| 1. El sistema muestra un mapa de GC con todos los datos cartografiados (eventos, paradas...) y un cuadro de texto para introducir destino/origen. <br> 2. El proceso finaliza.	|
| Flujo alternativo		| 2.A. El usuario hace cualquier operación siguiente [Centrar, desplazarse, alejar, acercar, ir a mapa base] <br> 2.B El usuario selecciona una parada / evento como punto de origen / destino. <br> 3.B El sistema muestra un itinerario de ejemplo (calcula distancia entre paradas, transbordos, coste, tiempos, zonas por las que no transitar) entre las dos paradas y solicita al usuario que haga una consulta. <br> 4.B El sistema muestra los detalles anteriormente calculados. <br> 2.C El usuario solicita ver más detalles de [parada/evento] <br> 3.C El sistema muestra descripción, código postal, imagen, líneas cercanas o que pasan por la [parada/evento].     	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno. |

<br>

| Identificar			| CU-23	|
| :---					| :--  	|
| Nombre				| Obtener ayuda en linea	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá recibir ayuda en línea adaptada.		|
| Actores				| Usuario		|
| Precondiciones		| Ninguna	|
| Flujo normal			| 1. El usuario solicita ayuda en línea. <br> 2. El sistema muestra pregutnas frecuentes relacionadas con la sección en la que se encuentra el usuario.	|
| Flujo alternativo		|  	|
| Poscondiciones		| Ninguna.		|
| Comentarios			| Ninguno. |

<br>

### Casos de uso del diagrama del SMET

<br>

| Identificar			| CU-24	            |
| :---					| :--            	|
| Nombre				| Generar alarmas  	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El sistema genera una alarma que será recibida por otro usuario para notificarlo de algo.	            	|
| Actores				| Sistema      		|
| Precondiciones		| Se dan las condiciones para que el sistema cree una alarma.                	|
| Flujo normal			| 1. El sistema crea un mensaje con la información precisa para el usuario. <br> 2. El sistema envía la alarma al usuario. <br> 3. El usuario recibe la notificación de la alarma y confirma haber visto el mensaje.	                |
| Flujo alternativo		| 3A. Si el usuario no confirma haber visto la alarma, el sistema volverá a enviarla (paso 2).              	|
| Poscondiciones		| Ninguna.             		|
| Comentarios			| Una alarma es un mensaje (no necesariamente de texto, puede ser un simple sonido) que notifica al receptor de algo en concreto.                  |

<br>

| Identificar			| CU-25	            |
| :---					| :--            	|
| Nombre				| Ver advertencias              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El operador de transporte puede ver la lista de advertencias de las rutas.	            	|
| Actores				| Operador de Transporte             		|
| Precondiciones		| El operador de transporte se encuentra identificado en el sistema.               	|
| Flujo normal			| 1. El operador de transporte selecciona la función para ver las advertencias. <br> 2. El sistema muestra una lista con las advertencias de los posibles peligros que hay hay o las rutas cortadas.	                |
| Flujo alternativo		| 2A. En caso de que no haya advertencias, la lista se mostrará vacía y aparecerá un mensanje "No hay ninguna advertencia en este momento".               	|
| Poscondiciones		| Ninguna.             		|
| Comentarios			| -                   |

<br>

| Identificar			| CU-26	            |
| :---					| :--            	|
| Nombre				| Ver eventos              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario puede ver la lista de eventos disponibles.	            	|
| Actores				| Usuario logueado y Usuario no logueado            		|
| Precondiciones		|                	|
| Flujo normal			| 1. El usuario selecciona la sección para ver los eventos. <br> 2. El sistema muestra un listado con todos los eventos disponibles en el momento. <br> 3. El usuario selecciona un evento concreto <br> 4. El sistema muestra toda la información del evento seleccionado.               |
| Flujo alternativo		|                	|
| Poscondiciones		| Ninguna.             		|
| Comentarios			| -                   |

<br>

| Identificar			| CU-27	            |
| :---					| :--            	|
| Nombre				| Ver alarma              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario recibe una alarma informándole de un suceso o evento concreto relevante.	            	|
| Actores				| Usuario No Logueado             		|
| Precondiciones		| La alarma ha sido enviada por el sistema con el usuario como receptor previamente.               	|
| Flujo normal			| 1. El usuario recibe una notificación de la alarma. 2. El usuario abre el mensaje que contiene la alarma y examina su contenido. 3. El usuario confirma que ha leído el mensaje.	                |
| Flujo alternativo		| 3A. Si el usuario no confirma, volverá a recibir la alarma en un periodo corto de tiempo.               	|
| Poscondiciones		| El sistema recibe la confirmación de alarma recibida por parte del usuario.             		|
| Comentarios			| -                  |

<br>

| Identificar			| CU-28	            |
| :---					| :--            	|
| Nombre				| Ver alarmas (vista Usuario Logueado)              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario recibe una alarma informándole de un suceso o evento concreto relevante.	            	|
| Actores				| Usuario Logueado             		|
| Precondiciones		| La alarma ha sido enviada por el sistema con el usuario como receptor previamente.               	|
| Flujo normal			| 1. El usuario recibe una notificación de la alarma. 2. El usuario abre el mensaje que contiene la alarma y examina su contenido. 3. El usuario confirma que ha leído el mensaje.	                |
| Flujo alternativo		| 3A. Si el usuario no confirma, volverá a recibir la alarma en un periodo corto de tiempo.               	|
| Poscondiciones		| El sistema recibe la confirmación de alarma recibida por parte del usuario.             		|
| Comentarios			| -                  |

<br>

| Identificar			| CU-29	            |
| :---					| :--            	|
| Nombre				| Ver alarmas (vista Operador de transporte)              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario recibe una alarma informándole de un suceso o evento concreto relevante.	            	|
| Actores				| Operador de transporte             		|
| Precondiciones		| La alarma ha sido enviada por el sistema con el usuario como receptor previamente.               	|
| Flujo normal			| 1. El usuario recibe una notificación de la alarma. 2. El usuario abre el mensaje que contiene la alarma y examina su contenido. 3. El usuario confirma que ha leído el mensaje.	                |
| Flujo alternativo		| 3A. Si el usuario no confirma, volverá a recibir la alarma en un periodo corto de tiempo.               	|
| Poscondiciones		| El sistema recibe la confirmación de alarma recibida por parte del usuario.             		|
| Comentarios			| -                  |

<br>

| Identificar			| CU-30	            |
| :---					| :--            	|
| Nombre				| Ver alarmas (vista Operador adjudicatario)              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario recibe una alarma informándole de un suceso o evento concreto relevante.	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| La alarma ha sido enviada por el sistema con el usuario como receptor previamente.               	|
| Flujo normal			| 1. El usuario recibe una notificación de la alarma. 2. El usuario abre el mensaje que contiene la alarma y examina su contenido. 3. El usuario confirma que ha leído el mensaje.	                |
| Flujo alternativo		| 3A. Si el usuario no confirma, volverá a recibir la alarma en un periodo corto de tiempo.               	|
| Poscondiciones		| El sistema recibe la confirmación de alarma recibida por parte del usuario.             		|
| Comentarios			| -                  |

<br>

| Identificar			| CU-31	            |
| :---					| :--            	|
| Nombre				| Registrar situaciones puntuales              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá registrar sitaciones puntuales.	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe estar identificado como Operador adjudicatario en el sistema.                 	|
| Flujo normal			| 1. El usuario solicita registrar una situación puntual. <br> 2. El sistema lista los contenidos disponibles a registrar  <br> 3. El usuario selecciona un determinado momento. <br> 4. EL sistema guarda la sitación seleccionada.  	                |
| Flujo alternativo		|                	|
| Poscondiciones		| La nueva situación se ha añadido a la base de datos del sistema.              		|
| Comentarios			|             |

<br>

| Identificar			| CU-32	            |
| :---					| :--            	|
| Nombre				| Definir evento              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá definir nuevos eventos. 	            |
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe estar identificado como Operador adjudicatario en el sistema.                 	|
| Flujo normal			| 1. El usuario solicita definir un evento nuevo. <br> 2. El sistema solicita el título, información y destinatarios del nuevo evento <br> 3. El usuario introduce la informacion pedida. <br> 4. El sistema comprueba que la información introducida sea correcta <br> 5. El sistema publica y envía el evento los usuarios.                 |
| Flujo alternativo		| 2.A. El usuario puede poner como destinatarios solo a los operadores de transporte, de manera que se generen advertencias exclusivamente para ellos. C<br> 4.A. Si la información no es correcta, el sistema advertirá al usuario permitiéndole voler a introducir los datos (paso 3) o finalizar el proceso.     |
| Poscondiciones		| El nuevo evento creado se registrará en la base de datos.              		|
| Comentarios			| Tanto los usuarios logueados como los no logueados podrán ver los eventos creados.                   |

<br>

| Identificar			| CU-33	            |
| :---					| :--            	|
| Nombre				| Proveer datos              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá introducir nuevos datos en el sistema.	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe estar identificado como Operador adjudicatario en el sistema.                 	|
| Flujo normal			| 1. El usuario solicita la introducción de nuevos datos. <br> 2. El sistema solicita los datos a introducir. <br> 3. El usuario introduce los datos pedidos. <br> 4. El sistema comprueba que los datos sean correctos. <br> 5. El sistema guarda los datos en el sistema.	                |
| Flujo alternativo		| 4.A. Si los datos introducidos son incorrectos, el sistema permitirá al usuario volver a introducirlos (paso 3) o finalizar el proceso.                	|
| Poscondiciones		| Los nuevos datos agregados han de guardarse en la base de datos del sistema.            		|
| Comentarios			|                   |

<br>

| Identificar			| CU-34	            |
| :---					| :--            	|
| Nombre				| Crear advertencia              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá crear una advertencia dirigida a los operadores de transporte.	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe haber definido un evento previamente               	|
| Flujo normal			| 1. El sistema genera una advertencia con los datos introducidos en la definición del evento <br> 2. El sistema envía la advertencia a los operadores de transporte. 	                |
| Flujo alternativo		|                	|
| Poscondiciones		|              		|
| Comentarios			|                   |

<br>

| Identificar			| CU-35	            |
| :---					| :--            	|
| Nombre				| Registrar periodos continuos de tiempo              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá registrar un intervalo de tiempo. 	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe estar identificado como Operador adjudicatario en el sistema.                 	|
| Flujo normal			| 1. El usuario solicita registrar un periodo de tiempo. <br> 2. El sistema lista el contenido que se puede registrar <br> 3. El usuario selecciona el intervalo de tiempo deseado.	<br> 4. El sistema guarda el intervalo de tiempo.                |
| Flujo alternativo		|                	|
| Poscondiciones		| Se ha añadido en la base de datos el registro de tiempo realizado.             		|
| Comentarios			| El periodo registrado se guarda como películas de evolución temporal del estado.                  |

<br>

| Identificar			| CU-36	            |
| :---					| :--            	|
| Nombre				| Examinar el estado de la explotación en tiempo real              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá examinar el estado de la explotación en tiempo real para cada operador.	            	|
| Actores				| Usuario no logueado, Usuario logueado             		|
| Precondiciones		|                	|
| Flujo normal			| 1. El usuario solicita visualizar la explotación del transporte en tiempo real. <br>	2. El sistema solicita el operador que se quiere visualizar. <br> 3. El usuario selecciona el operador deseado. <br> 4. El sistema muestra el estado de la explotación del transporte en tiempo real seleccionado.                |
| Flujo alternativo		| 4.A. Si el sistema no encuentra niguna información disponible, informa al usuario y finaliza en proceso.                |
| Poscondiciones		|              		|
| Comentarios			|                   |

<br>

| Identificar			| CU-37	            |
| :---					| :--            	|
| Nombre				| Examinar el estado de la explotación en tiempo real (vista Operador adjudicatorio)              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá examinar el estado la explotación en tiempo real.	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe estar identificado como Operador adjudicatario en el sistema.              	|
| Flujo normal			| 1. El usuario solicita visualizar la explotación del transporte en tiempo real. <br>	2. El sistema solicita el operador que se quiere visualizar. <br> 3. El usuario selecciona el operador deseado. <br> 4. El sistema muestra el estado de la explotación del transporte en tiempo real seleccionado.   	                |
| Flujo alternativo		| 2.A. El usuario podrá crear un conjunto de operadores en vez de visualizar a un solo operador. <br> 4.A. Si el sistema no encuentra niguna información disponible, informa al usuario y finaliza en proceso.                	|
| Poscondiciones		|              		|
| Comentarios			|                   |

<br>

| Identificar			| CU-38	            |
| :---					| :--            	|
| Nombre				| Crear conjunto de operadores              	|
| Autor					| Cristina García, Adrián Galdeano, Alejandro Manzano		|
| Fecha					| 13/12/2022		|
| Descripción			| El usuario podrá crear un conjunto de operadores para examinar el estado de explotación en tiempo real. 	            	|
| Actores				| Operador adjudicatario             		|
| Precondiciones		| El usuario debe haber accedido a la sección de examinar el estado de la explotación en tiempo real               	|
| Flujo normal			| 1. El usuario selecciona varios operadores de trabajo a examinar.	                |
| Flujo alternativo		|                	|
| Poscondiciones		|              		|
| Comentarios			|                   |

<br>

## 4.3. Diagramas de clases asociados a los requisitos de información.


### 4.3.1 Portal

<div align="center">
    <img src="./../Proyecto/BD-portal.svg" style="border: 3px solid #000">
    <i><p>Imagen de la base de datos del Portal.</p></i>
</div>

<br>

### 4.3.2 SIIT


<div align="center">
    <img src="./../Proyecto/BD-siit.svg" style="border: 3px solid #000">
    <i><p>Imagen de la base de datos de SIIT.</p></i>
</div>

<br>

### 4.3.3 SMET

<div align="center">
    <img src="./../Proyecto/BD-smet.svg" style="border: 3px solid #000">
    <i><p>Imagen de la base de datos de SMET.</p></i>
</div>

<br>

# Apendices

<br>

| Modelo de Entrevista     |                               |
| :---                     | :---                          |
| Entrevistado             | Ulie Estilique                |
| Fecha                    | 15/11/2022                    |
| Hora                     | 09:55                         |
| Lugar                    | Gran Canaria                  |
| Asunto                   | Entrevista a un mecánico de barco                              |
| Desarrollo de la entrevista   |                          |
| Contexto                 | Pregunta / Tema tratado       |
|                          | P: ¿Se le ocurre alguna forma de proteger las herramientas de explotación para cada contenido de la web, tanto estático como dinámico que haya que tener sí o sí en cuenta? <br> R: (omitida)               |
|                          | P: ¿Las estadísticas de acceso son para los usuarios que acceden al  portal o para la empresa ? <br>R:  Simplemente por si hay mucha gente pidiendo la ruta específica. Que los mandamases vean que hay mucha gente pidiendo esa ruta.                           |
|                          | P: ¿Qué tipo de estadísticas quiere (tráfico de usuarios, horas en las que más se usa la aplicación, qué servicios son los que más se usan …? <br> R: Saber si hay que introducir un nuevo barco, un nuevo autobús en la ruta.                        |
|                         | P: ¿Qué secciones y servicios se tienen en cuenta en el portal? <br> R: Ni idea.                     |
|                         | P: Respecto al cloud tag en la home del website ¿se refiere a que la página de cada usuario cambia sus funcionalidades según el rol de este (cliente, administrador)? <br> R: Ni idea.          |
|                         | P: Para el buscador. ¿Qué se considera un término clave? <br> R: Selector de tipo de ruta que quiero hacer (ruta escénica, ruta más rápida…). Keywords, manuales y por proximidad                |
|                         | P: ¿Qué elementos se obtienen como resultado de una búsqueda? P.e.: eventos de ocio, paradas, rutas… <br> R: Ruta con elementos de ocio y paradas marcadas, pero solo se obtienen rutas         |
|                         | P: A la hora de realizar una búsqueda,¿ se permite aplicar distintos filtros con la finalidad de facilitar el contenido? P.e.: mostrar resultados del idioma buscado,... <br> R: Solo se obtienen rutas, se filtra el tipo de ruta. (ej de filtro. poner un monumento como fin)                      |
|                         | P: ¿Qué se puede modificar del listado de horarios y servicios? <br> R: (Omitida)                 |
|                         | ¿Hay algún dato que no se pueda modificar en el sistema? <br> R: Ni idea                      |
|                         | P: ¿De qué forma se mide la distancia entre paradas (tiempo, distancia, paradas, etc)? <br> R: Se muestra de las dos maneras (distancia y tiempo).                    |
|                         | P: ¿Calcular tiempos de recorrido hace referencia a lo que tarda una línea en dar una vuelta completa, o la distancia entre paradas? <br> R: Listado de paradas y la ruta completa. Barcos también.                 |
|                         | P: ¿Cuál es la distancia que se considera cercana? <br> R: El cliente marca la distancia que considera cercana, de la que se le mostrarán los elementos disponibles.              |
|                         | P: ¿Cuáles son los parámetros a potenciar en la solución? <br> R: (Omitida)                 |
|                         | P: ¿Qué se entiende exactamente por alarmas? (Notificaciones que se envían automáticamente cuando ocurre un evento?) <br> R: Barco roto, incidencias, calles cortadas, manifestación. Eventos en general.              |
|                         | P: ¿Qué otros mecanismos se podrían definir para las alarmas? ¿Se podrán configurar para activarlos o desactivarlos? <br> R: (Omitida)         |
|                         | P: ¿A qué se refiere con tiempo de salto?  <br> R: Tiempo de retraso que se produce por una incidencia.                  |
|                         | P: ¿Algún software de gestión del transporte y coordinación de los servicios a tener en cuenta? <br> R: (Omitida)  |
|                         |P: ¿Qué protocolo de conexión se debería aplicar y siguiendo qué principios? Por ejemplo, si buscamos la integración de la mayor parte de las aplicaciones de la AUTGC, deberíamos usar un protocolo que ya comparta la mayoría de estas aplicaciones. <br> R: Ni idea.                     |
|                         | P: Como empresa licitadora, ¿hemos de encargarnos de la adaptación del sistema para los distintos puntos de información habilitados por la Autoridad Única del Transporte (teniendo en cuenta la arquitectura y diseño de estos puntos) o todo este trabajo irá a cargo de la AUTGC ? Ya que se nos ha referido que la AUTGC los proveerá debidamente configurados. <br> R: (Omitida)                 |
|                         | P: ¿Qué se entiende por crear un sitio Web en paralelo con contenido formateado en texto plano? <br> R: (Omitida)    |
|                         | P:  ¿Qué otros soportes publicitarios de promoción se pueden realizar? <br> R: Ni idea.               |
|                         | P: ¿A cuantos usuarios está dirigida la aplicación? ¿Cuál es el tráfico promedio que se espera al día?<br>R: A todo el mundo.           |
| Conclusiones de la entrevista     | El cliente no estaba cualificado para responder a las preguntas técnicas.    |
| Resumen                 |                     |
| Puntos a aclarar        |                     |
| Observaciones           | Dado el resultado de la entrevista, más adelante, habrá que realizar otra entrevista con un responsable más cualificado.      |

