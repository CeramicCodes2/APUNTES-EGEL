# levantamiento de requerimientos

es una de las etapas mas relavantes
el lavantar el requerimiento de forma correcta 
es una de las necesidades apra que el clente
realize

## etapas del levantamiento de requerimientos

1) CONCEPCION
2) INDAGACION
3) ELABORACION
4) NEGOCIACION
5) ESPECIFICACION
6) VALIDACION
7) ADMINISTRACION

# concepcion

establece el entendimiento basico del problema

que es lo que deseas, cual es el objetivo final

es la naturalesa de la solucion que se desea
es una de las primeras taras a desarollar


# indagacion

definir claramente el alcance del proyecto o de lo que deseas realizar


>- problemas de alcance
>- problemas de entendimiento
>- problemas de volatilidad

ejemplo:

el sistema podra contactar con una plataforma del gobierno para ver los creditos sociales
etc

# elaboracion o modelado

aqui se empiezan a definir los modelos

esta tarea se centra en desarollar un modelo refinado de los requerimientos que identifique distintos
aspectos de la funcion del software

se identifican todas las relaciones y colaboracion entre clases y se producen varios diagramas adicionales
**componentes y dependencias **

# negociación

se pide a clientes usuarios y otros participantes
que ordenen sus requerimientos según su prioridad y que después analicen los conflictos
con el empleo de un enfoque iterativo que da prioridad a los requerimientos, se evalúa su costo y riesgo 
y se enfrentan los conflictos internos, algunos requerimientos se eliminan se combinan o se modifican de modo que cada parte logo
cierto grado de satisfaccion

> dialogo con el cliente y sponsor y stackholder para ver que requerimiento es prioritario osea las prioridades





## estandar BPMI
es un estandar para la diagramacion de procesos

> leer 3 veces
> 1) baja lectura
> 2) moderada
> 3) rapida

## wbs (work breakdown structure)

work breakdown structure
es una tecnica de administracion de un plan de trabajo
permite definir paquetes de taras o informacion para llegar a un fin comun una tarea 

los paquetes se clasifican 

se hace una matriz de dependencias

despues de eso se meten las dependencias en un canvas y despues ya el spriint

# especificacion

historias de usuario

una especificación puede ser un documento escrito 
un conjunto de modelos graficos un modelo matematico formal un conjunto de escenarios de uso
un prototipo o cualquier combinacion de estos.

>- es documentar lo que dice el cliente y traducirlo a un lenguaje tecnico


>[!important]
>debe desarrollarse y utilizarse utilizando una plantilla estandar

ejemplos de ellos son:

> historias de usuario
> diafragmas uml 

## EJEMPLO de especificacion


## ERS
es un documento que se crea cuando debe de especificarse una descripcion derallada de todos los aspectos de software que se va a elaborar antes de que el proyecto comienze.

aqui se debe de aclarar que es el dise;o y que no es.

ejemplo, se puede componer por:
>- manuales de usuario
>- suposicione sy dependencias
>- caracteristicas del sistema
>- requerimientos
>- interfaces de hw
>- interfaces de sf
>- comunicaciones ( por ejemplo si no se tienen los puertos adecuados abiertos)

## reverse proxy
![[Pasted image 20240122204917.png]]

se usa para establecer un esquema de seguridad para las aplicaciones

el proxi puede funcionar como un contexto
por ejemplo si se apunta a la direccion
192.168.1.3 puede funcionar bajo el contexto de /logging


tambien tene cosas como balanceo de cargas

pero hay un problema si el desarollador programa direcciones ip de forma estatica
para que funcione su sistema entonces fallara el reverse proxy se llama harcorear el codigo

# validacion
la validacion de los requerimientos analiza la especificacion a fin de ganrantizar
que todos los requerimientos han sido enunciados sin ambiguedades

ademas tratar de detectar inconsistencias y omisiones y errores ademas que los requermientos se hagan conforme a los estandares


ejemplo de validacion:
>- los requerimientos estan enunciados con claridad ? pordian interpretars emal
>- esta identificada la fuente del requerimiento(por ejemplo una persona o reglamento o documento)
>- el requerimiento esta acotado en terminos cuantitativos ?
>- el requerimiento viola algunas restricciones del dominio
>- se identifica la fuente del requerimiento (por ejemplo una persona reglamento o documento) (de donde viene la informacion fuentes estructuradas o no estructuradas)

## kpi

forma de medir el rendimiento o el cumplimiento de los objetivos
una formula

# administracion de los requerimientos

es el conjunto de actividades que van a ayudarle al equipo a identificar
controlar
priorizar
todos los requerimiento
y dar seguimiento 

cumple con las tareas
## analisis de requisitos del software

es una tarea de ingenieria de software que cubre el hueco entre la definicon del software a nivel sistema y el dise;o del software
permite especificar las caracteristicas operacionales del software
(funcion datos y rendimiento)

indica la interfaz del software con otros eleentos del sistema y 
establece las resticciones que debe cumplir el software


### tareas de analisis de requisitos
se divide en cinco areas de esfuerzo

1) reconocimiento del problema
2) evaluacion y sintesis
3) modelado
4) especificacion
5) revision



### todos los modelos de analisis se relacionan por un conjunto de principios operativos

>- debe representarse y enenderse el dominio de la informacion de un problema
>- deben definirse las funciones que debe realizar el software
>- debe representarse el comportamiento del software
>- debe dividirse los modelos que representan informacion funcion y comportamiento de manera que se descubran los detalles por capas 
>- ek oricesid e analisis debera ir desde la informacion esencial hasta ...


### directrices para ingenieria de requerimientos
1) entender el problema andes de empezar a crear el modelo de analisis
2) desarollar los prototipos que permitan al ususario entender como sera la interaciion con el humano maquina
3) registrar el orden y al razi de cada req
4) priorizar req
5) trabajar para eliminar 

## funciones de un analista

lleva a cabo las necesidades para cumplir con las cinco areas de esfuerzo 
se aplican las tecnicas discretas y interactivas definidas por kentall

levantar informacion
se hace por medio de 2 tecnicas


1) entrevistas
2) talleres
3) obsrvacion
4) encuestas
5) revision documental
6) uso de especificaciones formales para requerimientos 
# proceso de la ingenieria de requerimientos

## ACTIVIDADES DEL PROCESO

# ESPECIFICACION DE REQUERIMIENTOS

## requerimientos
describen 

se clasifican en 2 tipos

requerimeintos de ususario y requerimientos del sistema



## requerimientos funcionales

aquellos que se debe dedicar el software


## requerimiensos no funcionales
describen atributos solo del sistema
restricciones de operacion cuantitativas tipo de plataforma 

son restricciones de operacion del software son necesarios pero no directos al software


## especificacion de req en lenguaje natural
los requerimientos se deben de especificar en lenguaje natural

>- suelen especificar en lenguaje natural
>- se expresan de forma individual ( pj esquematicamente )
>- se organizan de forma jerarquica
>- a distintos niveles de detalle
>- a menudo se numeran (para facilitar su gestion)



deben de ser claros
concretos
consicos
completos y consistentes


### forma correcta de levanar req

1) correcta
2) no ambigua
3) completa
4) consistenta
5) calificada deacuerdo a imp
6) verificable
7) modificable


### preguntas basicas paara levantar req

que -> lo que espera que haga el sys
por que ha de ser asi quien lo propuso -> su justificacion
como se verifica su cumplimiento -> en su caso los criteros de aceptacion que sean aplicables



### req no funcionales

han de especificarse cuantitativamente siempre que sea posible
para poder verificar su cumplimiento


#### requerimientos mal planteados ejemplo
>- el sistema sera lo mas facil de usar posible ( que es facil de usar)

### bien planreado
>- un ususario experimentado debe ser capaz de utilizar todas las funciones del sistema tras un entrenamiento de 2 horas tras el cual no cmeteramas de 3 errores
>- 
>- cuando haya hasta 100 usuario accediendo simultaneamente al sistema su tiempo de respuesta no sera en ningun momento superior a 2 segundos
>- 




## casos de uso

## documento

# SABADO 23 DE MARZO DURACION 9 HORAS 8 AM ENTRADA 8(1/2) 
# INFORMACION DE REGISTRO DE PAGINA SENEVAL Y SE ENVIARA UN FOLIO QUE SE IMPRIMIRA EL DIA DEL EXAMEN TRAER INE Y FOLIO INFORMACION IGUAL QUE EN EL INE
# con acentos los nombres como venga en el ine

[[cuarta clase]]