___IGNORE__

![[Pasted image 20240227141331.png]]

![[Pasted image 20240227141419.png]]

la evolucion de los sistemas de 4 elementos a solo 3
surgio por el hecho de que se empezo a utilizar
metodologias agiles lo cual hace que podamos tener
una interaccion con el cliente, se debe de imponer un limite
hasta de donde el cliente sera capaz de realizar cambios


<hr>

___posiblemente no viene___

## sistema de informacion

![[Pasted image 20240227141738.png]]

## variedad de sistemas de informacion

![[Pasted image 20240227142006.png]]

## dise;o de la arq del sistema

es la parte visual o forma en la cual le damos el desarrollo al sistema

![[Pasted image 20240227142253.png|center]]

se elaboran todos los tipos de diagramas **muchos de ellos de uml** 

tambien se hace una serie de actividades de que se debe de hacer
para el dise;o del sistema


## lenguajes de definicion de arquitecturas de sistema

 

estos lenguajes ADL se usan para saber que tipo de arquitectura se trabajara o interactuara y se sabra que flujo de informacion se sseguira
estos diagramas tienen en general todo o toda la perspectiva del sistema
y pertenece a la fase del dise;o y le da una vista a los datos

![[Pasted image 20240227142954.png]]

### ESTANDAR 1471
se usa para revisar la arquitectura del software

>[!recite]+ IEEE 1471 definicion de arq de software
 >la arquitectura de un sistema de software es la estructura o estructuras del sistema que incluye elementos de sofftware las propiedades externamente visibles de estos elementos y la relacion entre ellos


en otras palabras se le da una vista a los componetntes del sistema
se ven capas metodos componentes de acceso al sistema etc


### esquema de arquitectura del sistema

toda arquitectura de software tiene 3 vistas
o hay 3 modelos de arquitectura que cubren diversos aspectos del software


y por vistas nos referimos a la forma visual que le daremos a los datos


>- Estatica: describe que componentes tiene la arquitectura
>- Functional: describe que hace cada componente
>- Dinamica: descriube como se comportan los cmponentes a lo largo del tiempo y como interactuan entre si

![[Pasted image 20240227144135.png]]

<hr>

## etapas del proceso de dise;o del esquema de arquitectura
.
en las fases anteriores se definen los requerimientos y se entrega el SRS
apartir de ello construimos la arquitectura del sistema

![[Pasted image 20240227144715.png]]

![[Pasted image 20240227144924.png]]

## metodos principales para dise;ar la arquitectura

hay 3 metodos principales para diuse;ar una arquitectura

![[Pasted image 20240227144956.png]]


## ADD (DISE;O GUIADO POR ATRIBUTOS)

**DIVIDE Y VENCERAS/** mienteas mas dividamos los proceso ya actividades que realziara el sistema es mas macil indentificar
como el isstema hara cada proceso o actividad ademas es mas facil de si identificamos un riesgo como lo vamos a  mitigar

EL ADD ES el mas ocupado
![[Pasted image 20240227150806.png]]

entre ams detallado o mas esten divididas las tareas es mas facil
ademas esta arquitectura erws iterativa y enc ada iteracion un elemento se decompone en elementos
este tipo de dise;o divide que tareas se tendran


## ACDM  (METODO DE DISE;O CENT5ADO EN LA ARQUITECTURA)

tambien conocido como *ACDM3* permite o define un proceso  para poder realizar
diversas tareas en las etapas del ciclo de desarollo arquitectonico
no solo toma en cuenta los requerimientos tiene ams etapas para poder ver el proceso y ver
los requerimientos que se tendran

los requerimientos caracteristicas elementos y atributos  que se tienen toman el nombre de drivers

ayudan a configurar el sistema que se esta dise;ando

>[!important] palabra clave
**drivers => elementos caracteristicas atributos y tareas de manera detallada (se usa en la etapa de diseño de la arquitectura)** 
>- tareas peque;as del dise;o de la arquitectura




ESTA METODOLOGIA TAMBIEN MANEJA UN CICLO QUE PERMITE DESAROLLAR CADA TAREA PARA SABER SI LA ARQ
QUE SE IMPLEMENTA ES LA ADECTUADA




## METODO  DE DEFINICION DE ARQUITECTURAS DE ROZANSKY WOODS

![[Pasted image 20240227151213.png]]

DESCRIBEN PRACTICAMENTE ACTIVIDADES QUE VAN MAS ALLA DELA ETAPA DE DISE;O
Y ABARCAN TODO EL CICLO DE DISE;O ARQUITECTONICO

en cada etapa del metodo se enfoca a la toma de decisiones 




<hr>

>[!important]
> ESTOS METODOS INDICAN COMO LA INFORMACION SE MANIPULARA MEDIANTE DIAGRAMAS QUE AYUIDARAN A
> DESAROLLAR EL SISTEMA


## evaluacion de la arquitectura de software

![[Pasted image 20240227144715.png]]


una vez establecida la arquyitectura de software como se establece en el ciclo de la arquitectura de oftware
se procede a la evaluacion o validacion de la misma

![[Pasted image 20240227172128.png]]
estos metodos se usan para identificar si hay o no riesgos en resumen\

## revisiones e inspecciones

el producto o el proceso o tarea se pasa por una revisión
a grandes rasgos se tiene una lista de tareas y actividades que el sistema deben cumplir y en base a eso los inspectores que
son gente experta en el diseño de arquitecturas  evaluara si los procesos se hagan de forma adecuada ya que se van a identificar defectos que se tomaran como riesgos
si bien no siempre se tienen riesgos se pueden revelar mediante este metodo algunos riesgos

ejemplo:
dar un proceso de alta y ver tipos de datos que vamos a definir
al momento de hacer la prueba para validar el alta puede que nos falto un dato o que empleados extrangeros no tienen un curp

por que es un riesgo ? por que algunos campos no puyeden nunca quedar en blanco
forzosamente deben tener un dato

otro ejemplo son con los numeros flotantes
es decir en que o a cuantos decimales se van a redondear para que los resultados sean correctos ?





![[Pasted image 20240227174513.png]]


## recorridos informales del dise;o

se va revisando que cada etapa definida en la arquitectura cumplan con el objetivo con el cual se dise;o para ver si realmente se cumple
con alguna caracteroistica que se esta ise;ando

si bien no es muy usado puede servir para evaluar cuantos defectos se puede tener

![[Pasted image 20240227174845.png]]

## ANALISIS DE EQUILIBRIO DE LA ESTRUCTURA (ATAM)

![[Pasted image 20240227180403.png]]

es uno de los mas conocidos para la evaluacion de la arquitectura de software 
fue desarollado por los investigadores del SEI y ==tiene como objetivo evaluar las consecuencias de las decisiones arquitectonicas respecto de los requerimientos de drivers (caracteristicas) del sistema==

**drivers de negocio -> que nos dice el negocio que debe tener el sistema de informacion en otras palabras son las reglas de negocio o que nos dice el neogicio que debe tener para desarollar el SISTEMA DE INFORMACION**

![[Pasted image 20240227181217.png]]

ATAM no solo contempla la parte del proceso de los datos
sino que tambien toca los requerimientos de negocio que nos dice el neogio para desarollar
el sistema de informacion



### ACDM (etapa 4)

para evaluar una arquitectura
se debe de tener un proceso ya definido
![[Pasted image 20240227183000.png]]

en esta eapa es todo lo que podemos identificar como issues

esta etapa permite ver todos los elemtnos que tengo para dise;ar mi sistema
como se hara un analisis funcional y estructural 

en este punto aun se pueden agregar y corregir errores
## REVISIONES ACTIVAS PARA DISE;OS INTERMEDIOS (ARAID)

![[Pasted image 20240228020137.png]]

>- es un metodo de especializacion 


este metodo consiste en identificar el dieño de la arquitectura
escenarios inicialesdiseñador de arquitectura programas facilitadores de revisiones de diseños intermedios
como resultados escupe faltantes de documentacion y probenas que evitaran que el diseño de la arquitectura pueda ser utilizado por los desarolladores

**identifica que no checa o que no se genera a nivel diagramas y diseño**


revisiones activas

## prototipos o experimentos
es otro metodo utilizado para evaluar la arquitectura (que cumpla con los requerimientos de negocio o drivers)
es utilizando prototipos
pero en este caso estos prototipos no se programan ni se meten con plataformas
solo se simula un prototipo con base al proceso (se usan daigramas uml para suponer riesgos hipotesis y escenarios principales para pues un proceso por ejemplo `cual es mi proceso de alta?`)


![[Pasted image 20240228135627.png]]


al final se tendran una lista de riesgos actualizada
mostrara problemas que evitaran que el dise;o de la arquitectura pueda ser utiulizado por los desarolladores para un escenario dado

al final todo esto es para saber si la arquitectura elegida funcionara o no


# documentacion de la arquitectura de software

para ello existen 4 metodos

![[Pasted image 20240228135918.png]]

>[!important] Diferencia entre metodos y marcos conceptuales
>- los metodos describen de manera mas explicita tanto las entradas requeridas como la secuencia deacciones que comprenden las salidas generadas
>- los marcos conceptuales proveen un conjunto de conceptos que deben considerarse al documentar la arquitectura

algunos de los metodos forman parte de los metodos para validar la arquitectura como es el caso de ==ACDM==

## vistas y mas alla (**VIEWS AND BEYOND**)

una vista conciste en un dise;o de diagramas diferentes como de flujos de datos
esto nos muestra como visualizaremos la infomracion de forma esquematica
en otras palabras le damos forma a la informacion


este metodo consiste en generar una **lista de vistas candidatas**
combinar las vistas y priorizar las vistas.



![[Pasted image 20240228141102.png]]


## 4+1 Vistas

es un marco conceptual para la documentaciond e arquitectura, este marco considera la nocion
de vista como concepto principal

se representan 5 vistas
1) vista logica
2) vista de procesos
3) vista de desarollo
4) vista fisica
5) vista "+1" o de casos de uso

es un metodo para documentar que consiste en el siguiente documento

![[Pasted image 20240228141518.png]]

es te documento se le llama **guia sobre el dise;p de la arquitectura y contiene informacion para entender el porque de las decisiones de deise;o tomadas por el arquitecto**

>- este documento es el DDF en este se colocan las cosas que se desarollan en el sistema la parte logica es el software ( el como se conforma cada componente y interaccionan ntre ellos)
>- la parte de procesos son que tareas debe realizar el sistema (*por ejemplo consultas*)
>- la parte de desarollo es como se va a dar una vista 
>- la parte fisica es a nivel de dispositivos de hardware

![[Pasted image 20240228141704.png]]

## ACDM (ETAPAS 3 Y 4)
estas etapas contemplan la etapa de documentacion

![[Pasted image 20240228150049.png]]
0por requerimientos se define lo que es la parte del sistema

en la parte de nivel de descomposicion del sistema se toca la parte de que tanto se divide el sistema pare vencer

## punto de vista y perspectivas

![[Pasted image 20240228150311.png]]

este metodo coinside con el metodo de rosawnsky woods

en este se contempla el que pasara cuando ya se esta implantando



# dise;o de modulos de software

## modelos estructurales

estos son diagramas de clases que muestran la organizacion de un sistema en terminos de los componentes que constituyen dicho sistema y sus relaciones

![[Pasted image 20240228180833.png]]

## diagramas de contexto

muestran las fronteras del sistema asi como tambien relacione existentes entre los sistemas

## modelos de comportamiento

**dentro de ellos entran los diagramas de estad on maquinas de estoado**

son modelos dinamicos del sistema conforme se ejecutan. en ellos se muestra lo que sucede o lo que supone que pasa cuando un sistema responde ante un estimulo de su entorno{}

![[Pasted image 20240228181654.png]]
se ve un dinamismo de que tenemos que hacer, es otra forma de despliegue de la informacion sin programar, se ve
de forma mas visual que flujo o procesos eguira la informacion


## Modelos de interacción

el modelo de interacción ayuda a identificar los requerimientos del usuario
enfatiza la busqueda de problemas de comunicacion entre sistemas para su resolucion

![[Pasted image 20240228181947.png]]

un ejemplo de estos diagramas son los diagramas de casos de uso 
si se quiere describir un caso de uso pues se hace uso de las **descripciones de casos de uso**

## Modelos uml () 
![[Pasted image 20240228200249.png]]

estod diagramas muestran el diseño de modulos mientras mas diagramas mas se entiende el sistema


# diseño de componentes y de datos de software

![[Pasted image 20240228200328.png]]



aqui se identifican datos crudos o daos sin procesar que seran manipulados y representan la materia prima dels sitema


![[Pasted image 20240228200448.png]]

>[!important] 
>en equipos agiles los modelos conceptuales de alto nivel a menudo se crean como parte de los esfuerzos iniciales de visualizacion de requisitos ya que se utilizan para rxplorar las estructuras y conceptos empresariales estaticos de alto nivel ]


![[Pasted image 20240228201512.png]]
es el siguiente nivel de los diagramas ER en estos se especifca mas las dimensiones o trblas que tendra la abe de deatos


![[Pasted image 20240228201620.png]]


**recuerda que raravez se utilizan en proyectos agile**

por que raravez se usan en proyectos agile ?![[Pasted image 20240228202443.png]]

en estos diagramas se aplica la normalizacion y el algebra relacional


>[!important]+ Que operaciones se realizan en los diagramas fisicos?
>- la normalizacion
>- se especifican claves foraneas
>- todos los atributos para cada entidad estan especificados
>- resuelve las relaciones de miuchos a muchos


en este punto se busca que no haya redundancia y haya integridad en los datos

## modelo de datos fisicos (MDF)
![[Pasted image 20240228202723.png]]

el modelo de datos fisicos

nota  no todos los diagramas se deben de dise;ar solo algunos es posible dise;arlos

diagrama relacional -> solo se ven que atributos tenemos cuales son mis llaves primarias y llaves foraneas (**NO LLEVAN CARDINALIDAD**)
diagrama ER -> a diferencia del relacional estos **SI LLEVAN CARDINALIDAD**




> [!recite] **tabla maestra**
>  son las tablas en las cuales se conectan todas las tablas 
> la gran mayoría de sus campos son llaves foraneas, incluso pueden conectar alguna otra base de datos


# diccionario de datos

los diaccionarios de datos

es una lista que contiene todas las caracteristicas de todos los elementos que forman parte del flujo de datos
de todo el sistema. de forma general
un diccionario de datos contiene los siguientes elementos
>- flujo de datos
>- entidades externas
>- procesos
>- archivos

![[Pasted image 20240228205037.png]]


>[!important] DEFINICION  DICCIONARIO DE DATOS
>- los diaccionarios de datos son la informacion que se va a tener de cada una de las tablas (aunque tambien se tienen de mas datos como los datos de los diagramas de casos de uso)

![[Pasted image 20240228205517.png]]

aqui solo no se incluye la cardinalidad 


>[!recite]+ por que es imporante hacer un diccionario de datos?
 **estos diagramas son importantes por que gracias a ellos podemos saber cual es el significado de un campo y que tipo de dato almacena**

### descripcion de las especificaciones de procesos y desiciones estructuradas

![[Pasted image 20240228210112.png]]
![[Pasted image 20240228211913.png]]![[Pasted image 20240228212001.png]]