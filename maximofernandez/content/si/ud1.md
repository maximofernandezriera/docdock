+++
title = "Sistemas informáticos"
date = "2017-04-24T18:36:24+02:00"
type="slide"
hidden=true

theme = "black"
[revealOptions]
transition= 'concave'
controls= true
controlsTutorial= true
progress= true
history= true
center= true
+++

## Unidad didáctica 1

## Los sistemas informáticos y los sistemas operativos

___

## Índice

* Introducción.
* Composición.
* Funciones y objetivos. 
* Tipo. 
* Servicios.
* Introducción a los sistemas operativos DOS y UNIX.


---

## La informática

* Nace para evitar tareas repetitivas de cálculo y gestión.
* El término informática apareció en Francia en 1962:

**INFOR**  mationauto **MATIQUE**

---

## La informática es la ciencia que estudia el tratamiento automático y racional de la información.

---

## Función y objetivos

* Desarrollo y mejora de máquinas

* Desarrollo y mejora de nuevos sistemas automáticos de trabajo.

* Construcción de aplicaciones informáticas.

---

## El sistema binario

* Para los ordenadores todos los datos son números acaban siendo conjuntos de 0 s y 1 s.
* Debido a esto último, el ordenador no utiliza el sistema decimal si no el sistema binario.

---

* El ordenador utiliza mecanismos que traducen los datos a:

1. Sistemas numéricos
1. Códigos alfanuméricos

---

## Medida de la información

---

## Como en la mayoría de ámbitos [distancia (Km), peso (Kg), tiempo (ml)], en la informática se utiliza una unidad base y sus múltiplos → el bit (b).

---

## Permiten dos valores: 0 y 1

* ¿Cuántas combinaciones podemos representar con un único bit?
* ¿Cuántas combinaciones tenemos con 2 bits? con 3?con 4?

---

## La información que da un bit es mínima, por lo tanto hay que buscar sus múltiplos:

* Llamamos byte (B) los conjuntos de 8 bits.

## Múltiplos en el Sistema Internacional

## DANGER ZONE: en el Sistema Internacional (SI) utilizan prefijos para designar los múltiplos de una unidad determinada:

---

## Veamos la siguiente tabla con las siguientes características:

## nombre  | unidad | símbolo | valor en el SI

---

|<p>**nombre** </p><p>unidad </p>|**símbolo** |<p>**valor en el SI** </p><p>20 = 1</p>|
| :-: | :-: | :-: |
|kilo |k |10<sup>3</sup> = 1.000|
|mega |M |10<sup>6</sup> = 1.000. 000|
|giga |G |10<sup>9</sup> = 1.000.000.000|
|tera |T |10<sup>12</sup> = 1.000.000.000.000|
|peta |P |10<sup>15</sup> = 1.000.000.000.000.000|
|exa |E |10<sup>18</sup> = 1.000.000.000.000.000.000|
|zetta |Z |10<sup>21</sup> = 1.000.000.000. 000.000.000.000|
|yotta |Y |10<sup>24</sup> = 1.000.000.000.000.000.000.000.000|

---

## Múltiplos en binario

## Cuando se crearon los múltiplos de las unidades en binario se adaptaron a su sistema de numeración.

---

## Veamos la siguiente tabla con las siguientes características:

## nombre  | unidad | símbolo | valor en el SI

---

|<p>**nombre** </p><p>unidad </p>|**símbolo** |<p>**valor en el SI** </p><p>20 = 1</p>|
| :-: | :-: | :-: |
|kilo |k |2<sup>10</sup> = 1.024|
|mega |M |2<sup>20</sup> = 1.024 · k|
|giga |G |2<sup>30</sup> = 1.024 · M|
|tera |T |2<sup>40</sup> = 1.024 · G|
|peta |P |2<sup>50</sup> = 1.024 · T|
|exa |E |2<sup>60</sup> = 1.024 · P|
|zetta |Z |2<sup>70</sup> = 1.024 · e|
|yotta |y |2<sup>80</sup> = 1.024 · Z|
|bronto |B |2<sup>90</sup> = 1.024 · y|

---

## Sistema Internacional vs Binario

## ¿Qué posible **confusión** encuentra entre el Sistema Internacional y el binario?

---

## Fíjaos en la siguiente tabla: 

## **Podemos observar los siguientes porcentajes de desfase**

---

![](https://revista.jovenclub.cu/wp-content/uploads/2016/03/Tabla-5.jpg) 

---

## Los prefijos del **Sistema binario** utilizan **potencias de 2**,mientras que **el SI** utiliza **potencias de 10**.

## Los fabricantes de discos duros utilizan el sistema decimal, pero el ordenador calcula la capacidad mediante el Sistema Binario. 

---

## Usamos la  siguiente fórmula para calcular la capacidad en binario:

---

 <img src="/home/maximo/Slides/Markdown-Templates/images/image2.png"/>

---

* *N* es la capacidad del fabricante  
* *y* es el prefijo equivalente en decimal  
* *x* es el prefijo equivalente en binario

---

## ¿Qué capacidad, en Sistema Binario, tiene un disco duro de 120 GB según su fabricante?

Vamos.

---

## Sistema Internacional vs Binario (III)

## SOLUCIÓN a la confusión: se introducen nuevos prefijos.

---

<img src="/home/maximo/Slides/Markdown-Templates/images/tabla.png"/>

---

## Introducción a los sistemas operativos

Empiezan las curvas.

---

## Ordenador: máquina compleja

* Uno o más procesadores  
* Discos y dispositivos de almacenamiento  
* Tarjetas de comunicaciones  
* Periféricos  
* ...

---

## El usuario, los dispositivos y el sistema operativo

 * Un usuario debería de conocer los detalles técnicos para controlar a la perfección los dispositivos → solución imposible.

 * Hay que buscar una solución a este problema de manera que un usuario cualquiera pueda utilizar fácilmente la máquina.

---

## El sistema operativo es una capa más

* Capa de software que aísla el hardware de los usuarios.

1. Hardware

2. Sistema Operativo

3. Software

---

## El sistema operativo tiene 3 objetivos principales:

1. **Comodidad:** hace que el ordenador sea más fácil de utilizar.
1. **Eficiencia:** permite que los recursos del sistema se utilicen de forma más eficiente.
1. **Capacidad de evolución:** está construido de forma que permita un desarrollo continuo (actualizaciones, correcciones, nuevos  servicios,...)

---

## Funciones del sistema operativo

* Las funciones principales que debe realizar un sistema operativo son las siguientes:

1. Gestión de usuarios  
1. Gestión de procesos  
1. gestión de memoria  
1. Gestión de archivos
1. Gestión de los dispositivos de entrada y salida

---

## El kernel

### El núcleo o **kernel** del sistema operativo administra todas las funciones antes mencionadas.

---

## Perspectiva histórica de los sistemas operativos

 1. Las causas principales de la evolución de los sistemas operativos han sido:
 1. Las actualizaciones y los nuevos tipos de hardware
 1. Las demandas de nuevos servicios
 1. La necesidad de resolver varios tipos de errores
 1. Los sistemas operativos, igual que el hardware, han sufrido cambios a través del tiempo.
 
---

## Tendencias actuales

 1. Multiproceso:

 Sistemas con varios procesadores → el sistema operativo se encarga de administrar los procesadores para repartir el trabajo de
 forma equilibrada

 1. Sistemas más tolerantes a fallos

 Sistemas de envío de errores para facilitar la tarea de corrección.

---

## Más tendencias actuales

 1. Sistemas abiertos

Con estandarización en las comunicaciones, interfaces de usuario y aplicaciones.

---

1. Interfaces de usuario más amigables

1. Sistemas operativos ligeros

---

## Tipos de sistemas operativos

* Podemos clasificar los sistemas operativos según varios criterios:

1. Según la utilización de recursos
1. Según la interactividad  
1. Según el número de usuarios  
1. Según el número de procesadores  
1. Según la distribución de tareas del sistema  
1. Según su estructura

---
