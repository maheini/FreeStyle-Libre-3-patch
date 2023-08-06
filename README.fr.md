
# FreeStyle Libre 3 patch

Ce texte est traduit automatiquement. Vous devriez lire la version anglaise ou allemande pour les dernières mises à jour.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme en anglais</a>

Dépôt public pour piloter le développement d'interfaces Libre 3 pour des applications comme xDrip+ ou AndroidAPS. Ce référentiel est destiné à l'échange d'informations sur les solutions actuelles ainsi que sur Libre 3.

## Clause de non-responsabilité

L'utilisation des informations et de l'application de github.com est à vos propres risques et sans aucune garantie ou assistance. Ce projet n'est ni affilié ni approuvé par Abbott.

## Juggluco solution

Un grand merci à [jkaltes](https://www.juggluco.nl/) pour tout le travail. Avec l'application Juggluco, il est possible d'envoyer les lectures de glycémie du capteur Libre 3 vers xDrip+, AndroidAPS etc. hors ligne et sans racine. Vous pouvez trouver des instructions détaillées ici : [Instructions Libre 3 connexion avec Juggluco](./Juggluco-solution/juggluco-direct-instructions/en/instructions.md). Ou vous pouvez utiliser le [Lien de téléchargement](./Juggluco-solution/versions/latest/Juggluco.apk?raw=1). Veuillez noter : Ce projet est à vos propres risques et sans aucune sorte de garantie ou de soutien. Ce projet n'est ni affilié ni approuvé par Abbott.

## Autres solutions pour FSL 3 (nécessite une racine ou une connexion Internet)

- Free Three : Une solution hors ligne -> nécessite root et un certain savoir-faire, et seule l'application Libre 3 jusqu'à la version 3.3.1 est prise en charge [Lien (allemand)](https://insulinclub.de/index.php?thread /33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
       -> Dernier téléchargement : [Lien](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink vers Nightscout sideloading : [dépôt Github](https://github.com/timoschlueter/nightscout-librelink-up)
- App (Client LLU) pour télécharger les données de liaison et les partager avec Xdrip (source de sucre dans le sang : Libre 2) : [Lien (allemand)](https://insulinclub.de/index.php?thread/33987-llu- client/&postID=654144 #post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect) : une alternative pour LLU Client, qui est capable d'afficher la glycémie sous forme de notification (sans Xdrip+).
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/) : fonction dans la version Nightly de Xdrip+ (les étalonnages ne sont pas possibles)
- En développement pour iOS : DiABLE -> Essaie d'étendre les possibilités de FSTL3. [dépôt Github](https://github.com/gui-dos/DiaBLE)

## Statut actuel

Le déchiffrement a été cracké avec succès :smiley:. Il existe maintenant une solution finale pour les appareils non rootés fonctionnant avec Android et Xdrip.

## Comment contribuer

Si vous avez des informations utiles sur le Libre 3, merci de les partager dans l'[onglet discussions](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

### #WeAreNotWaiting