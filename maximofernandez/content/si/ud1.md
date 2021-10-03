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

# 1.1. Introducción a los sistemas informáticos

Máximo Fernández Riera 2021-2022

___

# Índice

<span style="color:#000000">la informática</span>

<span style="color:#000000">sistemas Informáticos</span>

<span style="color:#000000">El sistema binario</span>

---

# La informática

<span style="color:#000000"> __¿Qué es la informática?__ </span>

Nace para evitar tareas repetitivas de cálculo y gestión

El término informática apareció en Francia en 1962

__information automatique__

---

La informática es la ciencia que estudia el tratamiento automático y racional de la información\.

Desarrollo y mejora de máquinas

Desarrollo y mejora de nuevos sistemas automáticos de trabajo\.

Desarrollo de aplicaciones informáticas

---

# El ordenador

Hoy en día todos llevamos un ordenador a encima \-> el móvil

Pero en lugar de hablar de ordenadores \.\.\. mejor hablaremos de sistemas informáticos

---

# Partes del sistema informático

<span style="color:#000000"> __¿Cuáles son las partes fundamentales de un sistema informático?__ </span>

---

Un sistema informático tiene dos partes únicas y fundamentales:

El hardware \(hardware\)

El software \(software\)

Son totalmente dependientes entre sí\.

---

## Partes del sistema informático - Hardware

  * Tipo de componentes hardware:
  * procesador
  * memoria
  * placa base
  * Buses \(datos\, direcciones y control\)
  * Periféricos \(entrada\, salida\, comunicación y almacenamiento\)

---

## Partes del sistema informático - Software

El software se puede dividir en dos partes:

### SISTEMA OPERATIVO

\(Es el que controla el acceso de las aplicaciones al hardware\)

### APLICACIONES

---

![](https://gist.githubusercontent.com/maximofernandezriera/cccde28ddc3de00c5282f62faab3cc96/raw/92443235f8abf817ec63fee929e151a86d0d24eb/01.png)

---

# El sistema binario

Para los ordenadores todos los datos son conjuntos de 0 y 1\.

Debido a esto\, el ordenador no utiliza el sistema decimal si no el sistema binario\.

![](https://gist.githubusercontent.com/maximofernandezriera/6eb04f9409c051cd74fdead930595da5/raw/226cf14be0f5f3d29b50ed987c528313881ae0c7/02.png)

---

# El sistema binario - Medida de la información

un bit \(b\) es la unidad mínima de información \-> puede tener el valor 0 y 1

8 bits = 1 Byte

---

¿Cuántas combinaciones podemos representar con 1 bit?

¿Y con 2? ¿Y con 3? ¿Y con 4?

Un bit \(b\) \-> puede tener el valor 0 y 1

---

¿Cuántas combinaciones podemos representar con \.\.\.?

---

__1 bit:__

__0__

__1__

__total:__

__2__

---

__2 bits:__

__00__

__01__

__10__

__11__

__total:__

__4__

---

__3 bits:__

__000 100__

__001 101__

__010 110__

__011 111__

__total:__

__8__

---

__4 bits:__

__0000 0100 1000 1100__

__0001 0101 1001 1101__

__0010 0110 1010 1110__

__0011 0111 1011 1111__

__total:__

__16__

---

Un bit \(b\) \-> puede tener el valor 0 y 1

¿Cuántas combinaciones podemos representar con \.\.\.?

<span style="color:#0000FF"> __Son potencias de 2\!__ </span>

<span style="color:#0000FF"> __n bits \-> 2 ^ n combinaciones\!__ </span>

__1 bits:__

__0__

__1__

__total:__

__2__

---

__2 bits:__

__00__

__01__

__10__

__11__

__total:__

__4__

---

__3 bits:__

__000 100__

__001 101__

__010 110__

__011 111__

__total:__

__8__

---

__4 bits:__

__0000 0100 1000 1100__

__0001 0101 1001 1101__

__0010 0110 1010 1110__

__0011 0111 1011 1111__

__total:__

__16__

---

# El sistema binario - Múltiples en el Sistema Internacional

En el sistema internacional se utilizan prefijos para designar los múltiplos de una unidad determinada:

---

![](/03.png)

---

# El sistema binario - Múltiples en el Sistema Binario

Cuando se creó los múltiplos de las unidades en binario se adaptaron a su sistema de numeración:

---

![](/04.png)

---

# El sistema binario - SI vs SB

1 Kg de patatas son 1\.000 gramos de patatas

1 Km son 1000 metros

pero \.\.\.

1 KB son 1024 Bytes

---

![](/12.png)

---

![](https://gist.githubusercontent.com/maximofernandezriera/f2280d50520acf84c4912b38a20d8f80/raw/d60ddc403f94af75790ab3093230bcce46856234/04.png)

---

## El uso del Sistema binario creó confusión 1024 no es 1000

Los prefijos del Sistema Binario utilizan potencias de 2 y múltiplos de 1024\, mientras que el SI utiliza potencias de 10 y múltiplos de 1000\.

En la informática utilizar potencias de 2 es PERFECTO porque utilizamos el sistema binario como representación de datos\.

---

Los fabricantes de SSD \(Solid State Disk\) utilizan el sistema internacional para especificar su capacidad\. Mientras que los sistemas operativos muestran la capacidad siguiendo el sistema binario\.

---

Si tenemosun disco duro de 2 TB

Pasamos 2 TB a Bytes siguiendo el sistema internacional \(x1000\)

2 TB \-> 2000 GB \-> 2\.000\.000 MB \-> 2000000000 KB \-> 2 000 000 000 000 B

Pasamos el resultado a TB siguiendo el sistema binario \(/ 1024\):

2 000 000 000 000 B \-> \.\.\. \-> 1\,818 TB

Compras un disco duro de 2 TB

__pero según tu sistema operativo es de 1\,81 TB\!__

---

# El sistema binario - Solución

Se crearon unos estándares para poder solucionar el problema para que no haya confusión\.
