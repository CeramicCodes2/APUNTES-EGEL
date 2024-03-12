# etapas del desarollo del ciclo de vida (metodo tradicinal)

>- analisis
>- dise;o
>- construccion
>- implementacion
>- mantenimiento


# fase de analisis
etapa de construccion de un sistema informatico
consiste en relevar la informacion
y proponer los riesgos generales de la solucion

>[!important] stackeholders
>usuarios del sistema
# tipo de requerimiento

un req es una lista de funcinoes y capacidades necesarias para poder crear planes

requerimientos indican funciones y cointenidos que se espera que se tenga y como deben los usuarios interactuar con el


# tipos de requerimientos

>- de negocio
>- de usuario
>- funcionales y no funcinoales
>- transiccion
>- calidad 
>- implementacion

## requerimientos de negocio

definen los objetivos y problemas que la empresa quiere resolver con el producto

que tipos de requerimientos son los primeros que se definen en un proyecto ?
>- los requerimientos de negocio 

### ejemplos

> automatizar la gestion de relaciones con el cliente a objeto de reducir el tiempo de respuesta promedio en 70% en los proximos 6 meses

>optimizar la toma de pedidos del cliente a objeto de duplicar la cantidad de pedidos que se pueden procesar en un mes

>desarollar un proceso automatizado para emitri ye vitar por medios en linea directamente al entre regular un listado de transacciones de intercambio comercial 


## requerimientos de los ususarios

>[!info]
>describe lo que los usuarios  (stakeholders) esperan que el sistema haga
>ademas de como estos interactuaran con el sistema,
>**deben ser similares a los requerimientos del negocio**

>[!info]
>describen cuales son las necesidades de los interesados para ayudarles a lograr los objetivos y requermimientos
>de sus areas de negocio
>**pueden servir de puente para vincular losreq de negocio con los de la solucion**


### ejemplos
>- mecanismo para monitoriar los tiempos de respuesta

>[!info]
>El Customer Journey es el proceso que atraviesa un consumidor desde el momento en que se da cuenta de que necesita un producto hasta el momento en que lo adquiere y hace uso de él


>- necesitamos un mecanismo para monitorear diariamente los tiempos de respuesta sobre cada solicitud de soporte de clientes, con la finalidad de mejorar los tiempos de respuesta este reporte debera generarse de forma diaria, mensual o bajodemanda
>- nesesitamos un mecanismo que reciba los pedidos de los clientes por un medio en linea

## requerimientos funcionales
*como debe comportarse un producto*
o *lo que se espera que haga el sistema*

**incluyen funciones desempeladas por pantallas especificas descripciones de flujo de trabajo y otros requrimientos de negocio **


### ejemplos req funcionales

>- la solucion enviara un correo electronico cuando se registew un pedido de venta de cliente

## requerimientos no funcionales

describen condiciones bajo las cuales la solucion debe operar


se pueden subdividir enc ategorias como seguridad eticos legislativos etc

>- las solución debe poder manejar hasta 100k ususarios concurrentes sin
degradacion de desempe;o

>- los datos deben actualizarse en la base de datos para todos los ususarios en menos de 2 segundos

## requerimientos de transicion

describen las capacidades y condiciones que debe cumplir la solucion para
facilitar la transicion entre la situacion actual y la nueva

la diferencia entre otros tipos de req es que estos son temporales
abarcan topicos omo *conversion de datos entrenamiento y continuidad del negocio

### ejemplos

>- los usuarios deben ser entrenados en los modulos del sistema que correspondan con su departament o funcion
>- se debe trasladar los datos historicos transaccionales de almenos 5 a;os para poder emitir reportes compartivos en el nuevo sistema

## requerimientos de calidad

detallan las caracteristicas que un producto debe poseer para mantener su
efectividad y prevenit posibles problemas y limitaciones

![[Pasted image 20240131201940.png]]

# forma de escribir requerimientos

>[!IMPORTANT]
>- UNICO: EL REQUERIMIENTO SOLO PUEDE INTERPRETARSE DE UNA MANERA
>- ESPECIFICO NO DEBEN MEZCLAR 2 REQUISITOS DIFERENTES
>- CLAROS, COMPLETOS Y BIEN DEFINIDOS
>- VIABLES (REALISTICO Y  POSIBLE) DEBE SER FACTIBLE SEGUN LAS RESTRICCIONES
>- CONSISTENTES Y PRIORIZADOS EN BASE A LOS OBJETIVOS DE NEGOCIO
>- CAPACES DE VERIFICAR DURANTE PRUEBAS Y TEST
>- NECESARIO


### TRAZABILIDAD

DEBE MANTENERSE LA TRAZABILIDAD DE UN REQUERIMIENTO EN EL TIEMPO
ES DECIR SE DEBE REGISTRAR CADA CAMBIO REALIZADO


JIRA -> HERRAMIENTA PARA GENERAR DOCUMENTACION (TRAZABILIDAD DE MANERA FLUIDA)

En pocas palabras es el seguimientos de los requerimientos a lo largo del desarrollo de software 

![[Pasted image 20240131211337.png]]

EJEMPLO DE MATRIZ DE TRASABILIDAD

![[Pasted image 20240131211515.png]]