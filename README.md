RELOJ EN TIEMPO REAL
=====================
Este proyecto muestra un reloj calendario en tiempo real utilizando 
la tarjeta Arduino UNO y el integrado DS3231. Los parametros son visualizados
a partir de dos botones en una pantalla LCD

Nivel de desarrollo del proyecto:
"alpha"

Créditos:
https://simple-circuit.com/arduino-ds1307-lcd-set-button/


Últimas adiciones
=================
El sensor DS3231 es un integrado de bajo costo y fácil configuración/uso, alta presción en tiempo
real del reloj. La cuenta la realiza en segundos, minutos, horas, día de la semana,
día, mes y año.
Una batería puede ser conectada para que el DS3231 retenga la cuenta en caso de un fallo o 
apagado en la alimentación de un sistema. Igualmente el DS3231 no necesita oscilador ya que la placa
cuenta con uno empotrado.

Cambios en la última versión 0.1alpha:

* Agregado ejemplo original
* Agregado números de versión
* Agregado comentarios adaptados y variables en contexto 

Correcciones:

* Corregidos errores de ortografía

Lista de Materiales
=========================

Arduino board
DS3231 RTC board
1602 LCD screen
2 x push button
10K ohm variable resistor (or potentiometer)
330 ohm resistor
3V coin cell battery
Breadboard
Jumper wires

Pre-requisitos/Requerimientos
=============================

Requerimientos de software:

* IDE Arduino.

Herramientas requeridas:

* Pinza cortadora de cable.


Uso
==================

In the circuit there are 2 push buttons (B1 & B2) connected to pins 8 and 9 respectively,
the two push buttons are used to set time date parameters (minutes, hours, date, month and year).
Button B1 selects the parameter and B2 increments the selected parameter.

Carpetas
========
La estructura de carpetas es muy importante en un proyecto, te permitirá tener
tus proyectos organizados y permitirá a otros compartir fácilmente cambios o 
mejoras. Esta estructura no está escrita en piedra y puedes modificarla según
se adopte mejor a tus necesidades.

Recuerda que dentro de cada carpeta es muy recomendable que incluyas un archivo
llamado "readme.txt" donde detalles los contenidos de la misma.

En la estruuctura de directorios se recomienda incluir por al menos las
siguientes carpetas:

* *doc*: Utiliza esta carpeta para ingresar toda la documentación que consideres
necesaria para tu proyecto. De preferencia utiliza formatos libres como "ODF"
o simples archivos de texto, si puedes crear una página web en HTML recuerda
renombrar el archivo principal como "index.html" para que pueda ser accedido
fácilmente en caso de que alguien copie esta carpeta en un servidor web.
* *src*: Coloca en esta carpeta todos los archivos de código fuente del software
de control de tu proyecto Open Hardware. Si utilizas un IDE como Eclipse o Arduino
copia dentro de src la carpeta del proyecto.
* *dsn* / *diseño*: En esta carpeta coloca todos los archivos para el diseño de tu
proyecto.
  +  *main*: Coloca en esta carpeta los archivos de diseño original que pueden
incluir, pero no limitarse a: Dibujos 2D, diseños 3D, archivos CAD, bibliotecas
de componentes, dibujos técnicos adicionales.
  +  *aux*: Coloca en esta carpeta los archivos de diseño auxiliares que ayuden
a construir tu proyecto. Los archivos de diseño secundario pueden incluír diseños
2D o 3D en formato de intercambio, dibujos técnicos adicionales, formatos listos
para manufactura, artes gráficos adicionales.
* *extra*: Esta carpeta es libre, aquí puedes colocar otros archivos que se
puedan requerir para hacer funcionar o construir tu proyecto. Un ejemplo de ello
puede ser un driver controlador de un dispositivo específico o vínculos a software
relevante, fotografías o videos.

Excepción de responsabilidades (Disclaimer)
==============================

> El presente proyecto se comparte "tal cual" con el único objetivo de que sea útil.
El/los creadores del presente hardware y su software asociado no pueden garantizar su
correcto funcionamiento bajo ninguna circunstancia. El/Los autor/es de este proyecto
no podrá/n hacerse responsable/s de cualquier pérdida de carácter material, personal o
económico a su persona o terceros derivados de la utilización del mismo. Este proyecto
no deberá ser utilizado bajo ninguna circustancia en sistemas de carácter crítico
o sistemas de los cuales dependan vidas de personas de manera directa o indirecta.


Licenciamiento
==============

> La plantilla de este README.md ha sido desarrollada por la visión openhardware.sv
con el objetivo de facilitar la documentación de proyectos. Esta plantilla está protegida
bajo la licencia CC BY, puedes modificarla y redistribuirla manteniendo esta nota de
atribución del autor.
