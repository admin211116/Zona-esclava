# Zona esclava o secundaria

**¿Qué es un servidor de nombre secundario?**

Es un servidor, el cual, tiene autoridad sobre una zona pero la información de esa zona la obtiene de un servidor primario y esto lo hace mediante un proceso llamado tranferencia de zona. Por lo tanto, si el servidor primario fallara el secundario podría resolver las peticiones.

**¿En qué consiste la tranferencia de zona?**

Esta consiste en que para que el servidor secundario permanezca sincronizado le consulta al primario de forma frecuente y si el servidor primario ha sido actualizado el secundario realiza la tranferencia de zona y asi obtiene los datos del primero.

A continuación, realiza la siguente actividad siguendo los pasos que se te dan:

[Actividad zona esclava.](Configuracion-zona-esclava.md)

