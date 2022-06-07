# Informe de Laboratorio 2
## Análisis de Mallas
### 1.	OBJETIVOS

**Principales**

 - Experimentar con el análisis de mallas 
 - Comprobar los datos arrojados por el análisis de mallas

**Específicos**

- Distinguir entre lo que es corriente y voltaje
- Investigar lo que es las leyes de Kirchoff
- Diferenciar las partes de una herramienta eléctrica
- Conocer cómo funciona el multímetro
- Consultar la nomenclatura de colores y valores parar las resistencias.

### 2.	MARCO TEÓRICO 

#### 2.1.	 Análisis de Mallas:
En el análisis de mallas se parte de la aplicación de LTK a un conjunto mínimo de lazos para encontrar al final todas las corrientes de lazo. A partir   de   las   corrientes   de   lazo   es   posible encontrar   todas   las   corrientes   de   rama.   El número de lazos que se pueden plantear en un circuito   puede   ser   muy   grande, pero   lo importante   es   que   el   sistema   de   ecuaciones represente   un   conjunto   mínimo   de   lazos independientes.
Este conjunto mínimo es cualquiera en el cual todos los elementos (ramas) hayan sido tenidos en cuenta   en   al menos   una   malla.   Las otras posibles   mallas   serán   entonces   redundantes.
Aquí   también   el   número   de   incógnitas (corrientes de lazo) debe ser igual al número de ecuaciones (una   por   malla   del   conjunto mínimo). 
De acuerdo con el tipo de circuito y la forma en que se   seleccionen   las   mallas   se   pueden   tener distintas   posibilidades   de   conexión   de   las fuentes: 
- Fuentes de corriente controladas.
-  Fuentes de voltaje independientes.
-  Fuentes de voltaje controladas.
-  Fuentes de corriente independientes no compartidas por varias mallas.
- Fuentes   de   corriente   independientes compartidas por varias mallas.
Según   lo   anterior   hay   varias   maneras   de resolver un circuito por el método de mallas.
El método que llamaremos general aplica a los casos   de   circuitos   con   fuentes   de   voltaje independientes   y   fuentes   de   corriente independientes   no   compartidas   por   varias mallas.

Este método NO aplica a los circuitos que tienen: 
1. Fuentes de corriente independientes compartidas por varias mallas (se usa el método de supermalia).
2. Fuentes controladas de corriente o voltaje (se deben escribir las ecuaciones de   dependencia de la variable controlada y controladora).

Si   el   circuito   solo   tiene   fuentes   de   voltaje independientes   entonces   se   aplica   el   método general por el sistema llamado de inspección.
El número mínimo de lazos independientes que hay   que   definir   para   tener   un   sistema   de ecuaciones linealmente independientes que   se deben tener está dado por la siguiente relación:

 # Lazos independiente = # ramas – # nodos +1
 
Para   que   un   conjunto   de   lazos   sea independiente se requiere que en cada uno de ellos   exista   al menos   un elemento   que haga parte de los otros lazos.

    Divisor de tensión:
Un divisor de tensión es una configuración del circuito eléctrico que reparte la tensión de una fuente entre una o más resistencias conectadas en serie, así: 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/tree/main/Fotos/8.png)


###### _FIGURA 1_

### 3.	DIAGRAMAS
- Diagrama de bloques

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/9.png)


###### _FIGURA 2_

- Diagramas UML

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/10.png)


###### _FIGURA 3_

- Diagramas eléctricos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/11.png)


###### _FIGURA 4_

 - Diagramas esquemáticos.


![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/1.png)


###### _FIGURA 5_

### 4.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Protoboard | 
| 1 |Fuente de voltaje de C.D. | 
| 1 |Multímetro Digital| 
| 1 |Resistencia 820 Ω | 
| 2 |Resistencia 390 Ω | 
| 1 |Resistencia 1 kΩ | 
| 1 |Resistencia 1,2 kΩ | 
| 1 |Resistencia 2,2 kΩ |
 
> (Herramientas utilizadas en simulación) 
> Simulador thinkercad


### 5.	EXPLICACIÓN

Armar el circuito
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/1.png)

__5.1__ Cálculos de forma teórica

- Calcular la corriente en las mallas
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/2.png)

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/3.png)

- Calcular el error porcentual

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/17.png) 

- Calcular la corriente

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/4.png)

__5.2__ Tabulación de los datos

__5.2.1__ Resultados obtenidos de la medición de la corriente tanto teórico como simulado

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/5.png)

__5.2.2__ Calculo del error

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio-2/blob/main/Fotos/6.png)
### 6.  MANUAL DE USUARIO
### 7.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 8.	APORTACIONES

 - No hay paso de corriente si se invierten la tomas positivas y negativas de un circuito.
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo.
 - La fuente de corriente directa mide cuantos amperios tiene el circuito.
 
### 9.	CONCLUSIONES
- Para el cálculo de la corriente de una malla solo se pude usar el uso de un resistor que no comparta malla con otros.
- Para la medición de las mallas se puede dar la dirección que se quiera

### 10.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. Mexico: Pearson Educacion. Serway,

R. (2001). Fisica II. Mexico: Pearson Educacion.

### 11.	 ANEXOS



###### _FIGURA 7_
