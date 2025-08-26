# PM_Laboratorio4

# Tomate Tu Tiempo
La aplicación Tomate tu Tiempo es un programa que satisface la necesidad de organizar las actividades diarias de las personas, programando el tiempo que el usuario usará para realizar las actividades y evitando aplicaciones que lo distrayan.


# CONFLICTO
Al no haber código y solo archivos .txt, el conflicto no es tan grave y solo se necesita de un fetch.

Contexto:
El archivo equipo.txt fue editado por otro usuario, y sin haber realizado _pull_ se edito el mismo archivo en mi dispositivo.
Se realizan los pull, fetch y push en Github Desktop, para Git en consola sigue la misma dinámica pero con líneas de código en la terminal.

Al querer subir los cambios a una versión anterior del repositorio nos lo indica como en la siguiente imagen, explicándonos que no es posible hacer _push_ nuestro commit porque debemos hacer fetch de los cambios más recientes subidos en el repositorio para reconciliar los problemas en la versión local:
<img width="1484" height="911" alt="image" src="https://github.com/user-attachments/assets/0342f43c-a30f-4422-af0a-0141cfee6e97" />

Luego de hacer _fetch_, Github Desktop nos pide realizar un _pull_ de los cambios del repositorio origen:
<img width="1462" height="927" alt="image" src="https://github.com/user-attachments/assets/ee453099-ed3e-4051-9630-35b44532433b" />

Al finalizar se resuelven todos los conflictos y se sube el código, reescribiendo lo que ya había en el repositorio origen:
<img width="1498" height="928" alt="image" src="https://github.com/user-attachments/assets/a68998ce-69fe-4385-98ad-9ebb28ba94a8" />

Si el conflicto habría sido con código, nos abre el IDE que utilicemos (Visual Studio Code) y se ven todos los conflictos que existen obligándonos a elegir entre una de las versiones de código para hacer _merge_ ( _merge_ es el código que se quedará y sobreescribirá al otro).
