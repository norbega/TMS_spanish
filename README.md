# TMS_spanish
Tokyo Mirage Show Spanish Translation

Este proyecto tiene como objetivo la traducción colaborativa de, al menos por ahora, los textos del juego de Wii U Tokyo Mirage Sessions #FE.

## ¿Qué dinámica sigue la traducción?
Es un proyecto libre, colaborativo y sin ánimo de lucro, por lo que se realizará según el tiempo libre de los contribuyentes al proyecto.

## ¿Cómo se van a organizar los contribuyentes para traducir de forma simultánea?
Para cada uno de los ficheros .msbt se ha de crear una rama con el siguiente patrón:
  Subdir_(subdir_)(subdir_)..._file
  Ejemplo: Title_title
  
## ¿Cuál sera la rama principal?
Master será la rama principal. Está protegida y los mergeos contra esta deberán ser aprobados.

## Vale, soy nuevo en esto, ¿qué necesito para poder ayudar?
Para poder ayudar en este proyecto necesitas los conocimientos básicos de Git. Puedes consultarlos aquí http://rogerdudler.github.io/git-guide/

## ¿Qué software estás utilizando para la traducción?
Para llevar a cabo la traducción estoy utilizando solo dos herramientas:
  - MsbtEditor: editor de ficheros .msbt (https://github.com/IcySon55/3DLandMSBTeditor)
  - CpkFileBuilder: compilador de ficheros .cpk
  
## ¿Cuál es el procedimiento para traducir?
Para aportar a la traducción se están siguiendo los siguientes pasos:
  - Se abre una rama nueva con el formato indicado.
  - Se modifica los textos del fichero indicado en la rama mediante el software MsbtEditor.
  - Se genera un nuevo fichero .cpk con el software CpkFileBuilder y se sustitye en el directorio del juego.
  - Una vez testeados los cambios de la rama y validados, se sube la rama al repositorio y se realiza una petición de mergeo.
  
## ¿Cómo genero el fichero .cpk?
El fichero .cpk debe ser generado mediante el botón "Build CPK", una vez abierto con el software CpkFileBuilder mediante el fichero de proyecto "pack_031_message_trans.cpkproj".

## ¿Cuál es la ruta donde se debe dejar el fichero .cpk?
La ruta donde debe permanecer el fichero .cpk ya modificado es content\Pack.

## ¿Puedo subir el fichero .cpk al repositorio?
No, en este repositorio solo se alojan los textos tratducidos en formato .msbt.

## Comunidad Clan DLAN:
http://www.clandlan.net/foros/topic/80348-en-progresocolaborativa-traduccion-de-tokyo-mirage-sessions-fe-wii-u/

Ahora que eres conocedor de todo esto, siéntete libre de participar, aportar ideas, herramientas y algún que otro café!
