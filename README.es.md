# FreeStyle Libre 3 patch

Este texto está auto traducido. debes leer la versión en inglés o en alemán para conocer las últimas actualizaciones.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Léame en inglés</a>

Repo público para impulsar el desarrollo de Libre 3. Este repo debe ser utilizado para intercambiar información sobre Libre 3. Los posibles objetivos son el descifrado y la creación de una interfaz para Xdrip.

## Descargo de responsabilidad

El uso de la información y la aplicación de github.com es a su propio riesgo y sin garantía o apoyo formal de ningún tipo. este proyecto no tiene ninguna asociación con y no está respaldado por Abbott.

## Solución Juggluco

Un enorme agradecimiento a [jkaltes](http://jkaltes.byethost16.com/) por todo el trabajo. Con la [new FSTL3 patch](http://jkaltes.byethost16.com/Juggluco/libre3/), 
por fin hay una solución offline que no requiere acceso root y está totalmente integrada con Xdrip. puedes encontrar las instrucciones aquí: [Instrucciones para el parche de Libre3 con Juggluco](./Juggluco-solution/instructions/en/instructions.md). O puede utilizar el [enlace de descarga](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1).Tenga en cuenta: Esta solución es bajo su propio riesgo y sin garantía o apoyo formal de ningún tipo. Este proyecto no tiene ninguna asociación con Abbott ni está respaldado por ella.

Por favor, tenga en cuenta: No estuve involucrado en el desarrollo de Juggluco y el parche final de Libre 3, pero me encanta compartir todo el trabajo de desarrollo que se está llevando a cabo.

## Otras soluciones para FSL 3 (requieren root o conexión online)

- Libre 3: Una solución offline -> requiere root y algunos conocimientos, también sólo soporta la aplicación Libre 3 hasta la versión 3.3.1. [Enlace (alemán)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Última descarga: [Enlace](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink to Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) para descargar datos de Linkup y compartir con Xdrip (fuente: Libre 2): [Link (alemán)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): una alternativa al cliente LLU que puede mostrar BG como notificaciones en Xdrip+.
- Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): función en la versión nocturna de Xdrip+ (la calibración no es posible)
- En desarrollo para iOS: DiaBLE -> tratando de aprovechar las capacidades de FSTL3. [Github repo](https://github.com/gui-dos/DiaBLE)

## Estado actual

El descifrado se acaba de romper :smiley:. Por fin hay una solución para teléfonos no rooteados, que funciona con Android y Xdrip.

## Cómo contribuir

Si tienes alguna información útil sobre Libre 3, compártela en la pestaña [discusiones](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Información de encriptación

Las siguientes cosas son conocidas sobre la aplicación Libre 3: Después de iniciar, la aplicación se comprueba si hay alguna modificación. Allí se utiliza la protección de código WhiteCryption.

### #WeAreNotWaiting