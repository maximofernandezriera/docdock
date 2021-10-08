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

# 1.2. Introducción a los sistemas operativos

---

# sistema operativo
Aunque una de las funciones del sistema operativo permite el acceso del software al hardware, no es imprescindible. Hay sistemas informáticos que no tienen sistema operativo. Por tanto, el sistema informático no es imprescindible.

---

Sistema operativo - Objetivos
El sistema operativo tiene tres objetivos principales:
Comodidad: hace que el ordenador sea más fácil de utilizar
Eficiencia: permite que los recursos del sistema se utilicen de forma más eficiente
Capacidad de evolución: está construido de manera que permita un desarrollo continuo (actualizaciones, correcciones, nuevos servicios, ...)
 
---

Sistema operativo - Funciones principales
Las funciones principales que debe realizar un sistema operativo son las siguientes:
Administración de procesos
Administración de recursos
Administración de memoria
Proporcionar una interfaz para comunicarse con el usuario
Gestión de usuarios y permisos
El núcleo (kernel) del sistema operativo administra todas estas funciones.
 
---

Sistema operativo - Funciones principales
Administración de procesos:
Los sistemas informáticos están preparados para ejecutar diferentes procesos a la vez. El sistema operativo se encarga de decidir el orden de procesamiento de los diferentes programas que se están ejecutando.
Administración de recursosç
El S.O. tiene la capacidad de distribuir los diferentes recursos (p.e. memoria y dispositivos) entre los procesos. El SO tiene un registro que le permite conocer qué recursos están disponibles y cuáles se están utilizando, durante cuánto tiempo, por qué proceso, etc.

---

Sistema operativo - Funciones principales
Administración de la memoria:
Supervisa qué áreas de la memoria están en uso y cuáles están libres. Además, determina cuánta memoria asignará a un proceso y en qué momento. También libera la memoria cuando un proceso ya no es requerida para un proceso.
Algunos sistemas de almacenamiento: ext4, NTFS y exFAT.
Gestión de usuarios y permisos:
Aplica una serie de permisos a los usuarios que les permiten acceder al sistema y así poder evitar acciones que afectan al trabajo que están realizando otros usuarios.

---

Sistema operativo - Funciones principales
Proporcionar una interfaz para comunicarse con el usuario:
Esta puede ser tanto una interfaz gráfica (GUI) o como una interfaz donde se pueda introducir y recibir información en forma de texto (línea de comandos).

---

Sistema operativo - Clasificación
Existen diferentes formas por las que se pueden clasificar los sistemas operativos:
Según la cantidad de procesos que pueden gestionar de forma simultánea:

---

MONOTAREA
Sólo admiten un programa al sistema. El programa es cargado en memoria y es allí hasta que acaba de ser ejecutado. Durante este periodo no se puede ejecutar ningún otro programa.
Realiza tareas secuencialmente.
MULTITAREA
Pueden admitir uno o más programas de uno o más usuarios simultáneamente.

---

Sistema operativo - Clasificación
Según el número de usuarios del sistema:
monousuario
Sólo permiten en un determinado momento la conexión de un único usuario a la vez en el sistema. Utilizan técnicas de monoprogramació ejecutando un único programa o pueden ser sistemas multiprogramados, que facilitan al usuario la ejecución de varios programas a la vez.
Por ejemplo, el sistema operativo DOS ..
MULTIUSUARIO
Varios usuarios pueden trabajar simultáneamente.
Por ejemplo, UNIX.

---

Sistema operativo - Clasificación
Según el número de procesadores:
MONOPROCESO
El sistema informático sólo dispone de un procesador. Por tanto, sólo permite realizar un proceso a la vez.
multiproceso
El sistema informático dispone de varios procesadores. Por lo tanto, permite ejecutar diferentes tareas al mismo tiempo, debido a que ofrecen realizar varios procesos de forma simultánea.

---

Sistema operativo - Clasificación
Según los servicios que ofrecen:
CENTRALIZADOS
Todos los recursos se encuentran en una misma máquina (mainframe).
DISTRIBUIDOS
Los recursos utilizados pueden estar en diferentes máquinas que deben estar conectadas en red.

---

No se debe confundir el sistema distribuido con el sistema en red:
En un sistema operativo en red los diversos sistemas informáticos están interconectados (por ejemplo, red local de ordenadores). Cada uno tiene su propio software y hardware.
En un sistema operativo distribuido, el software distribuye las tareas en la red y los usuarios no saben donde se realizan las tareas.

---

Sistema operativo - Clasificación
Según el tipo de licencia:
PROPIETARIOS
Aquellas que tienen limitaciones de uso.
Son propiedad de alguna empresa.
LIBRES
Permiten utilizar el programa libremente.
La licencia es el contrato entre los desarrolladores de software y el usuario. Se definen con precisión los derechos y deberes de cada parte.

---

Sistema operativo - Clasificación
Hay varios tipos de licencias. Estas especifican las acciones que puedes realizar sobre el software adquirido.
Por ejemplo:
Licencia GPL (sistema operativo Linux): permite la copia modificación y redistribución del software. la licencia y no deja de ser válida si se efectúan cambios en el hardware. No ofrece garantía.
Licencia EULA (sistema operativo Windows XP): se prohíbe la copia. La licencia puede dejar de ser válida si se efectúan cambios en el hardware. Garantía los primeros 90 días.

---

Sistema operativo - Inicios
El concepto de "Sistema Operativo" aparece en los años 50 cuando IBM desarrolló el primer sistema operativo.
En los años 60 se produce una revolución en este campo. Aparecen conceptos como multitarea, multiusuario y multiproceso. Durante las primeras décadas, los sistemas operativos eran monotasca, monousuario y monoprocés.
A finales de los 60 aparece UNIX, es la base de la gran mayoría de los sistemas operativos actuales (solaris, Mac OS, ...).
En los años 80, se lanzó el sistema operativo MS-DOS, el primer sistema operativo de Microsoft, con la idea de que todo el mundo pudiera tener un ordenador en su casa.

---

Sistema operativo -
Inicios - MS-DOS
Este sistema operativo dejaba que el proceso que se estaba ejecutando pudiera tener acceso a todos los recursos que quisiera. En consecuencia, había muchos problemas de seguridad.
No era multiusuario.
No era multitarea.
En primeras versiones no podía trabajar con más de 64KB de RAM. A partir de la versión 7.1 ya soportaba sistemas de ficheros FAT32 con 4GiB de limitación.

---

Sistema operativo - Tendencias
Multiproceso: administrar los procesadores para repartir el trabajo de forma equilibrada.
Sistemas más tolerantes a fallos: sistemas de errores para facilitar la tarea de corrección.
Sistemas abiertos: estandarización en las comunicaciones, interfaces de usuario y aplicaciones.
Interfaces de usuario (GUI) más amigables.
Sistemas operativos ligeros. Por ejemplo, Windows 10 ocupa unos 10 GB en disco.
